# EPEVER-Controller-remote
This is a wireless remote to switch on and off a charge controller using MODBUS
the code has only been tested on an XTRA Series.
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
 *
 *    Remote switching - Wireless using cheap doorbell 
 */
