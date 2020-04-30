## RobofeverIOTESP8266v1.0
> This is prepared for Robofever 
>> The board selected is Nodemcu 1.0 or ESP 12E i.e. CP2102.
>>> The file compiles with no errors
>>>> This is v1.0 and will be updated accordingly.
### Initial issue : No response from Nodemcu 1.0 
> The fix is that you need to specify <abbr>TCP_MSS 1460</abbr> as a macro. There is some issue within the libraries itself.<br>
Refer http://lwip.wikia.com/wiki/Tuning_TCP for more info.
<br>Also refer https://github.com/esp8266/Arduino/issues/4593 .
