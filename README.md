# Solar-Lunar Dates Converter
	Convert Gregorian date to/from Chinese lunar date (Windows & Linux)

Features:
1. Show two Gregorian dates for Lunar leap months.
2. Work for Year 1901 to Year 2099. Results for other years are not dependable!
3. Run on both Windows and Linux.

How to run:
- Double-click **SolarLunarConvert.exe** (complied on Windows 11)
(Your can import my digital certificate, **qLiu_Github_cert.pfx**. See [Windows11-self-signed-certificate](../../../Windows11-self-signed-certificate))
	
System requirements:
- Windows 11 (with **solarLunar.dll**)
- Linux (with **libSolarLunar.so**, complied on Ubuntu 24.04.2 LTS)

No installation needed! Download and Enjoy it for free.\
[Contact me](https://www.linkedin.com/in/qiangliu427/) *if you have questions.*

Note:
This App is an example of [Python calling C functions](../../../Python-calls-C-dll), which are defined in **solarLunar.dll** or **libSolarLunar.so** in qlcpp/.
