## Requirements
-Sprig

or

- Raspberry Pi (any model)
- Adafruit 16x2 LCD Pi Plate
- Morse code / telegraph key (optional)

This is a Python 3 project.

## Installation

To install all dependancies:

```bash
sudo apt update && sudo apt upgrade
sudo apt install python3-pip
sudo pip3 install adafruit-circuitpython-charlcd
sudo pip3 install python-twitter
```

Clone this repo:

```bash
cd
git clone Samarpan1122/morse_code-keyer-with-pi-pico.git
cd morse_code-keyer-with-pi-pico
```

## Starting

Morse code practice:

```
python3 lcd_morse.py
```

With Twitter capability:

```
python3 lcd_morse_twitter.py
```
