#Wire up the reader https://www.youtube.com/watch?v=IeuQNXSNzxA
sudo raspi-config #Enable the SPI Interface
sudo reboot
lsmod | grep spi
pip3 install RPi.GPIO
