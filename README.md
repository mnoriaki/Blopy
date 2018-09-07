# Blopy
Blopy: Blockly based programming environment for Micro Python

## Description
Blopy is an programming envrionment for Micro Python interpreters runnning on micro processors. Most of the Blopy code is based on Blockly and WebREPL. 

## Demo
If you want to try it now, visit http://b.mtng.org and connect to your Micro Python interpreter. 

## Usage
Prepare a micro controller with Micro Python and WebREPL enabled. If you have an ESP8266, take a look at
* https://docs.micropython.org/en/latest/esp8266/esp8266/tutorial/intro.html
* https://learn.adafruit.com/micropython-basics-esp8266-webrepl/access-webrepl

to see how to prepare them.

Open Blopy/index.html with your browser and connect to the WebREPL, make a program with Blocks and click `Run' button on right top of the page.

## Preparing your Blopy
First you need clone Blockly and WebREPL repositories by
```
make git-clone
```
Copy files from cloned repositories by
```
make copy
```
That's it.

## License
MIT license. Blockly is licensed under Apache License and WebREPL is licensed under MIT License.

## Author
Noriaki Mitsunaga
