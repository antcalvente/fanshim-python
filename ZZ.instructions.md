https://learn.pimoroni.com/tutorial/sandyj/getting-started-with-fan-shim

git clone https://github.com/pimoroni/fanshim-python
cd fanshim-python
sudo ./install.sh

# Config used in the past
cd examples
sudo ./install-service.sh --on-threshold 60 --off-threshold 43 --delay 5

sudo systemctl stop pimoroni-fanshim.service