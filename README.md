# Playing with pico
I'm just playing with raspberry pi pico using <a href="https://circuitpython.org/" target="_blank">adafruit's circuit python</a>.

Raspberry Pi Pico is a microcontroller board released by raspberrypi foundation in the Q1 of 2021.
Raspberry Pi foundation has their own silicon chip RP2040 on this board.

# Pi Pico
You can get one from the raspberry pi site <a href="https://www.raspberrypi.org/products/raspberry-pi-pico/" target="_blank">here</a>.
I's a microcontroller board based on RP2040 chip made by rapberry foundation and check out the <a href="https://www.raspberrypi.org/documentation/rp2040/getting-started/" target="_blank">pi pico</a>, most of the detail of raspberry pi pico is given in the site.
You can check out pico's datasheet <a href="https://datasheets.raspberrypi.org/pico/pico-datasheet.pdf" target="_blank">here</a>.

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
<img src="https://github.com/slothtae/playing_with_pico/blob/main/image/pico.svg" target="_blank">
image source: <a href="https://www.raspberrypi.org/documentation/rp2040/getting-started/#board-specifications" target="_blank">Raspberry pi site</a>
</br>You can find all the specification and detail about raspberry pi pico <a href="https://www.raspberrypi.org/documentation/rp2040/getting-started/#board-specifications" target="_blank">here</a>.

# Pico With Circuit Python
<img src="https://github.com/slothtae/playing_with_pico/blob/main/image/circuitpython.png" target="_blank">
</br>image source:<a href="https://learn.adafruit.com/" target="_blank">Adafruit's Site</a></br>
<a href="https://circuitpython.org/" target="_blank">Circuit python</a> is Adafruit's fork of micropython used for microcontrollers.
</br>You can check out <a href="https://cdn-learn.adafruit.com/downloads/pdf/getting-started-with-raspberry-pi-pico-circuitpython.pdf?timestamp=1620201933" target="_blank">Getting started with Raspberry Pi Pico and Circuit Python</a> to know how to use circuit python on pi pico.</br>
We can install circuit python on pi pico using the uf2 file provide int he ada fruit site.
<h4>Steps to install circuit python in pi pico :</h4>
<ul> 
  <li>Download the adafruit's circuit python uf2 file from <a href="https://circuitpython.org/board/raspberry_pi_pico/" target="_blank">here</a>.</li> 
  <li>Press and hold the bootselect button and connect it to your host device and release the bootselect button.The pico will appear as a usb mount device</li> 
  <li>Now simply drag and drop the uf2 file downloaded earlier onto the pico.Now the pico will reboot and you will see a circuit python device</li>
  <li>Now you will need an <a href="https://en.wikipedia.org/wiki/Integrated_development_environment#:~:text=An%20integrated%20development%20environment%20(IDE,automation%20tools%20and%20a%20debugger." target="_blank">IDE</a>.You can download <a href="https://codewith.mu/" target="_blank">MuEditor</a> or <a href="https://thonny.org/" target="_blank">Thonny</a>. Use whatever you like download and install it in your host device.</li>
</ul>
The adafruit's <a href="https://cdn-learn.adafruit.com/downloads/pdf/getting-started-with-raspberry-pi-pico-circuitpython.pdf?timestamp=1620201933" target="_blank">Getting started with Raspberry Pi Pico and Circuit Python</a> has all the details you require in it.</br>
<h6>Note: I'm using Linux and thonny as my editor, but the steps works for windows and mac too.</h6>
