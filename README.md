# Megasquirt-Microsquirt-digital-dashboard-for-under-50-DIY
Megasquirt/Microsquirt digital LCD dashboard for under 50$ DIY

Do you wish you had money to invest for all these nice and expensive LCD race dashboards out there? 
Do you need to monitor your ECU Data without bringing your laptop with you all the time?

There's a solution, and it's very cheap. I've been tinkering for years to develop this solution, wasted a lot of money on development boards all for having the BEST solution ever.

Check the following youtube video to see a demo: https://youtu.be/CQPU9dfFPQw

On this video, the dashboard is receiving simulated data over CanBus.

Here how you can do it, it's very simple, first you purchase this (if you want to buy me a beer, purchase it through my link):

Get a USB Type C data cable and hook it up into your device. 
Visit this website https://esptool.spacehuhn.com/ and connect to your device.

You need to select your board from available COM Ports. It's easily detectable as it says "ESP32".

If it doesn't connect, hold boot button, hold now reset button, keep for 2 seconds then release reset, wait 1 second and also release boot. It should work now.

After connection you will be prompted what to flash and where. You need to flash the firmware "LCD_DASH_5Inch_FREE.Bin" right at 0x0000 address.

After it's done, reboot the device using the reset button or unplug/plug back your USB.

Now onto the wiring of the unit to the microsquirt! Follow this:

https://github.com/somahex00-web/Megasquirt-Microsquirt-digital-dashboard-for-under-50-DIY/blob/main/Dashboard%20for%20microsquirt%20installation%20guide%20-%205%20inch%20dash%20ENG%20161025.pdf



I've kept the "premium" dashboard for licensed use, you can check my other youtube videos to see the paid version.
