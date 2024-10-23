I2C LCD       Function      Pin No        Function/GPIO
GND            Ground          6              GND
VCC        Power Supply        4              +5V
SDA          Data bits         3          GPIO 2/ SDA
SCL        Serial clock        5          GPIO 3 / SCL

Install LCD: git clone  https://github.com/sterlingbeason/LCD-1602-I2C
Verify I2C ad: i2cdetect   -y   1  ---Open LCD.py--> change 12c_addr value
          Optional:$sudo apt-get install -y python3-smbus
                   $ sudo apt-get install -y  i2c tools
