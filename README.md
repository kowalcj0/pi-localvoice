pi-localvoice
=============

python based service for raspberry pi that plays audio files based on provided JSON schedule


# Raspberry Pi - Requirements:

* Python 2.7
* [RPi.GPIO](https://pypi.python.org/pypi/RPi.GPIO)
* [mpg321](http://mpg321.sourceforge.net/)

# Example JSON schedule:
```json
{"schedule":[{"priority":3,"suid":"S138009819520545","direction":"BOTH","maxbid":"32","pricetopay":"32","starttime":"2013-09-25 11:00:00","endtime":"2013-09-25 17:00:00","requestedplays":"3","filename":"http:\/\/www.ht0004.mobi\/audio_files\/A138009819547204.mp3","retrieveddatetime":null},{"priority":2,"suid":"S138011463681137","direction":"BOTH","maxbid":"32","pricetopay":"32","starttime":"2013-09-25 10:00:00","endtime":"2013-09-25 20:00:00","requestedplays":"20","filename":"http:\/\/www.ht0004.mobi\/audio_files\/A138011463662368.mp3","retrieveddatetime":null},{"priority":1,"suid":"S138009790363324","direction":"BOTH","maxbid":"34","pricetopay":"33","starttime":"2013-09-25 14:00:00","endtime":"2013-09-25 19:00:00","requestedplays":"10","filename":"http:\/\/www.ht0004.mobi\/audio_files\/A138009790345095.mp3","retrieveddatetime":null}]}
```
