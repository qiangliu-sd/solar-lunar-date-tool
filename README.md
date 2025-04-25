# Solar-Lunar Dates Converter
	Convert Gregorian date to/from Chinese lunar date

Features:
1. Define your own format for displaying dates in Chinese characters in **qlcpp/datesChina.json**. By default, show Lunar dates in Chinese characters between 2020 and 2040.
2. Show two Gregorian dates for Lunar leap months.
3. Work for Year 1901 to Year 2099. Results for other years are not dependable!

How to run:
1. If you want, update json-file:
   - Add more keys for more years
   - Modify values of keys in **datesChina.json**\
(*keep the json file in the sub-dir*: **qlcpp**; 
*do NOT modify the names, qlcpp and datesChina.json*)

2. Double-click **SolarLunarConvert.exe**
(Your can import my digital certificate, **qLiu_Github_cert.pfx**. See [Windows11-self-signed-certificate](../../../Windows11-self-signed-certificate))
	
System requirements:
- Windows OS

No installation needed! Download and Enjoy it for free.\
[Contact me](https://www.linkedin.com/in/qiangliu427/) *if you have questions.*

Note:
This App is an example of [Python calling C functions](../../../Python-calls-C-dll), which are defined in **qlcpp/solarLunar.dll**.
