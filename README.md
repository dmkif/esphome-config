# ESPHome Configuration

This project will share and save ESPhome.io configuration files. 

## Installation

1. Initialize a python3 venv

```bash
python -m venv venv
```
2. Install esphome latest bleeding edge version
```bash
pip install https://github.com/esphome/esphome/archive/dev.zip
```
3. Create secrets.yaml and add at least these lines
```bash
wifi_ssid: [[YOUR_SSID]]
wifi_password: [[YOUR_PASSWORD]]
```

## Usage

Activate virtual environment
```bash
source venv/bin/activate
```
Start ESPHome dashboard
```bash
esphome . dashboard
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
[MIT](https://choosealicense.com/licenses/mit/)
