sudo raspi-config
#Enable the SPI Interface
sudo reboot
lsmod | grep spi
sudo apt-get install python2.7-dev
git clone https://github.com/lthiery/SPI-Py.git
cd SPI-Py
sudo python setup.py install
