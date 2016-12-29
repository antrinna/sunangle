# sunangle
ruby script to calculate UTC time of various sun positions

To calculate time when sun is at certain zenith (90-sunangle) call sa_rise(day, latitude, longitude, zenith) and/or sa_set(day, latitude, longitude, zenith)
E.g.: SunTimes.new.sa_rise(Date.new(2012, 3, 8), 40, 110, 45)

Original methods to calculate sunrise and sunset times do not require zenith parameter, call rise(day, latitude, longitude) and/or set(day, latitude, longitude). 
E.g.: SunTimes.new.rise(Date.new(2012, 3, 8), 40, 110)