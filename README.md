# EPEVER-Controller-remote
Wireless remote to switch charge controller output using MODBUS
Also switches daily using EPEVER RTC
Code has only been tested on an XTRA Series.
EPever MPPT Charge controller RS485 Interface
 *  Design brief:
 *   Use: Scottish Bothy with multiple occupants. Operation must be simple:  
 *      * 'Press Here' > 'Lights ON'  Press Again > 'Lights OFF'
 *      * Remote Load ON/OFF switching to eliminate trip in dark to Epever controller
 *       
 *   Lights have been left on for weeks battening the flattery:
 *        Daily Load OFF timed by EPever RTC - IF ON > OFF at Midday 12:00hrs
 *  
 *   Power consumption: <1mA@12Volts
 *    
 *  Big thankyou to Colin Hickey for permission to adapt his code
 *  https://github.com/chickey/RS485-WiFi-EPEver
 *  And also:
 *  https://github.com/glitterkitty/EpEverSolarMonitor 
 *
 *  Hardware:
 *    Development arduino nano  
 *    Production 5 Volt pro mini
 *    MAX485CSA Converter module  
 *
 *    Remote switching -  using cheap wireless doorbell 
 *    
 
 
![VerySmallBell](https://user-images.githubusercontent.com/30367667/211414502-df63461b-1d76-4c96-a9c1-698f55d002bc.png)
![smallCase Rear](https://user-images.githubusercontent.com/30367667/211414531-66b0d02b-7a34-4935-a7f1-2a94e6bc41b9.png)
