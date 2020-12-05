# LED-Sports-Score-Ticker

Project consists of two parts:

*  Scores Scraper - This script will scrape ESPN APIs for the latest scores then writes the formated string to a text file in S3.

* Philly Scores API - API that consumes ESPN APIs and returns formatted strings for major philly sports teams. 

* Scores Ticker - This script runs on a Raspberry Pi. It grabs a string from a http endpoint and writes to LED panels using [Henner Zeller RPi RGB LED Matrix.](https://github.com/hzeller/rpi-rgb-led-matrix/)
