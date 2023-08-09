# [WeeWX](http://www.weewx.com)
*Open source software for your weather station*

## Modifications for Cotech weather station
[Trådlös väderstation med USB Cotech | Clas Ohlson](https://www.clasohlson.com/se/Tr%C3%A5dl%C3%B6s-v%C3%A4derstation-med-USB-Cotech/p/36-7959)

Using the WeeWx SDR integration and a RTL-SDR receiver dongle (v3) to connect the weather station to WeeWx.
[Köp RTL-SDR receiver dongle (v3) till rätt pris @ Electrokit](https://www.electrokit.com/produkt/rtl-sdr-receiver-dongle-v3/)

Install RTL_433 from [merbanan/rtl_433: Program to decode radio transmissions from devices on the ISM bands (and other frequencies)](https://github.com/merbanan/rtl_433)

May be installed with: sudo apt install rtl-433.

The SDR integration is from: [matthewwall/weewx-sdr: weewx driver for software-defined radio](https://github.com/matthewwall/weewx-sdr/) and modified for the Cotech weather station.

Install WeeWx as described in [http://weewx.com/docs.html/latest/setup.htm WeeWX&#58; Installation using setup.py]
download of the tar.gz file is not needed if this repository is cloned.https://github.com/matthewwall/weewx-sdr/

## Description

The WeeWX weather system is written in Python and runs on Linux, MacOSX,
Solaris, and *BSD.  It runs exceptionally well on a Raspberry Pi.  It generates
plots, HTML pages, and monthly and yearly summary reports, which can be
uploaded to a web server. Thousands of users worldwide!

See the WeeWX website for [examples](http://weewx.com/showcase.html) of web
sites generated by WeeWX, and a [map](http://weewx.com/stations.html) of
stations using WeeWX.

* Robust and hard-to-crash
* Designed with the enthusiast in mind
* Simple, easy to understand internal design that is easily extended (Python skills recommended)
* Python 2 or Python 3
* Growing ecosystem of 3rd party extensions
* Internationalized language support
* Localized date/time support
* Support for US and metric units
* Support for multiple skins
* Support sqlite and MySQL
* Extensive almanac information
* Uploads to your website via FTP, FTPS, or rsync
* Uploads to online weather services

Support for many online weather services, including:

* The Weather Underground
* CWOP
* PWSweather
* WOW
* AWEKAS
* Open Weathermap
* WeatherBug
* Weather Cloud
* Wetter
* Windfinder

Support for many data aggregation services, including:

* EmonCMS
* Graphite
* InfluxDB
* MQTT
* Smart Energy Groups
* Thingspeak
* Twitter
* Xively

Support for over 70 types of hardware including, but not limited to:

* Davis Vantage Pro, Pro2, Vue, Envoy;
* Oregon Scientific WMR100, WMR300, WMR9x8, and other variants;
* Oregon Scientific LW300/LW301/LW302;
* Fine Offset WH10xx, WH20xx, and WH30xx series (including Ambient, Elecsa, Maplin, Tycon, Watson, and others);
* Fine Offset WH23xx, WH4000 (including Tycon TP2700, MiSol WH2310);
* Fine Offset WH2600, HP1000 (including Ambient Observer, Aercus WeatherSleuth, XC0422);
* LaCrosse WS-23XX and WS-28XX (including TFA);
* LaCrosse GW1000U bridge;
* Hideki TE923, TE831, TE838, DV928 (including TFA, Cresta, Honeywell, and others);
* PeetBros Ultimeter;
* RainWise CC3000 and MKIII;
* AcuRite 5-in-1 via USB console or bridge;
* Argent Data Systems WS1;
* KlimaLogg Pro;
* New Mountain;
* AirMar 150WX;
* Texas Weather Instruments;
* Dyacon;
* Meteostick;
* Ventus W820;
* Si1000 radio receiver;
* Software Defined Radio (SDR);
* One-wire (including Inspeed, ADS, AAG, Hobby-Boards).

See the [hardware list](http://www.weewx.com/hardware.html) for a complete list
of supported stations, and for pictures to help identify your hardware!  The
[hardware comparison](http://www.weewx.com/hwcmp.html) shows specifications for
many different types of hardware, including some not yet supported by WeeWX.

## Downloads

For current and previous releases:

[http://weewx.com/downloads](http://weewx.com/downloads)

## Documentation and Support

Guides for installation, upgrading, and customization are in `docs/readme.htm`
or at:

[http://weewx.com/docs.html](http://weewx.com/docs.html)

The wiki includes user-contributed extensions and suggestions at:

[https://github.com/weewx/weewx/wiki](https://github.com/weewx/weewx/wiki)

Community support can be found at:

[https://groups.google.com/group/weewx-user](https://groups.google.com/group/weewx-user)

<h2>Licensing</h2>

WeeWX is licensed under the GNU Public License v3.
