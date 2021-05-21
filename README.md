# Playing with pico
I'm just playing with raspberry pi pico using <a href="https://circuitpython.org/">adafruit's circuit python</a>.

Raspberry Pi Pico is a microcontroller board released by raspberrypi foundation in the Q1 of 2021.
Raspberry Pi foundation has their own silicon chip RP2040 on this board.

# Pi Pico
You can get one from the raspberry pi site <a href="https://www.raspberrypi.org/products/raspberry-pi-pico/">here</a>.
I's a microcontroller board based on RP2040 chip made by rapberry foundation and check out the <a href="https://www.raspberrypi.org/documentation/rp2040/getting-started/">pi pico</a>, most of the detail of raspberry pi pico is given in the site.
You can check out pico's datasheet <a href="https://datasheets.raspberrypi.org/pico/pico-datasheet.pdf">here</a>.

<h3>Specs</h3>

Raspberry Pi Pico is a low-cost, high-performance microcontroller board with flexible digital interfaces. Key features include:
<ul>
  <li>RP2040 microcontroller chip designed by Raspberry Pi foundation in UK</li>
  <li>Dual-core Arm Cortex M0+ processor, flexible clock running up to 133 MHz</li>
  <li>264KB of SRAM, and 2MB of on-board Flash memory</li>
  <li>Castellated module allows soldering direct to carrier boards</li>
  <li>USB 1.1 with device and host support</li>
  <li>Low-power sleep and dormant modes</li>
  <li>Drag-and-drop programming using mass storage over USB</li>
  <li>26 × multi-function GPIO pins</li>
  <li>2 × SPI, 2 × I2C, 2 × UART, 3 × 12-bit ADC, 16 × controllable PWM channels</li>
  <li>Accurate clock and timer on-chip</li>
  <li>Temperature sensor</li>
  <li>Accelerated floating-point libraries on-chip</li>
  <li>8 × Programmable I/O (PIO) state machines for custom peripheral support</li>
</ul>
<img src="https://www.raspberrypi.org/documentation/rp2040/getting-started/static/64b50c4316a7aefef66290dcdecda8be/Pico-R3-SDK11-Pinout.svg">
image source: <a href="https://www.raspberrypi.org/documentation/rp2040/getting-started/#board-specifications">Raspberry pi site</a>
</br>You can find all the specification and detail about raspberry pi pico <a href="https://www.raspberrypi.org/documentation/rp2040/getting-started/#board-specifications">here</a>.

# Pico With Circuit Python
<img src="https://cdn-learn.adafruit.com/guides/cropped_images/000/001/954/medium640/Blinka_Computing_Grey.png?1520546961">
</br>image source:<a href="https://learn.adafruit.com/">Adafruit's Site</a>
<a href="https://circuitpython.org/">Circuit python</a> is Adafruit's branch of micropython use for microcontrollers.
</br>You can check out <a href="https://cdn-learn.adafruit.com/downloads/pdf/getting-started-with-raspberry-pi-pico-circuitpython.pdf?timestamp=1620201933">Getting started with Raspberry Pi Pico and Circuit Python</a> to know how to use circuit python on pi pico.</br>
We can install circuit python on pi pico using the uf2 file provide int he ada fruit site.
<h4>Steps to install circuit python in pi pico :</h4>
<ul> 
  <li>Download the adafruit's circuit python uf2 file from <a href="https://circuitpython.org/board/raspberry_pi_pico/">here</a>.</li> 
  <li>Press the bootselect button and connect it to your host device and it will apear as a usb mount device</li> 
  <li>Now simply drag and drop the uf2 file downloaded earlier onto the pico.</li> 
</ul>
Now the pico will reboot and you will se code.py and other files in it you can put your source code in the code.py file and program the pi pico using
circuit python.
