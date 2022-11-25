ReadMe 

To switch the MagTag from bootloader to CircuitPY mode, double click the reset button (may have to try multiple times to get the timing right).  MagTag mounted drive will change names when switching between Bootloader Mode and CircuitPY mode. 

Additional Code File, secrets.py
There is an additional code file not found in GIT named secrets.py 

== Start Example secrets.py == 

secrets = {
    'ssid' : 'put network name here',
    'password' : 'put network password here',
    'aio_username' : 'my_adafruit_io_username',
    'aio_key' : 'my_adafruit_io_key',
    'timezone' : "America/Chicago", # http://worldtimeapi.org/timezones
    }

== End Example secrets.py ==

