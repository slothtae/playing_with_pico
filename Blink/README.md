# Blinking onboard led program

The raspberry pi pico has a surface mound led on the board and can be controled as a GPIO. Lets make a program to make the led blink.
<h4>Steps:</h4>
<ul>
<li>Open your editor</li>
<li>Open the code.py file from the editor</li>
<li>Copy and paste the code from the code file and save and run the file on pico</li>
</ul>

# Hardware 
<h4>Components : </h4>
  <h5>Pi pico</h5>
  
# Explanation
Lets see how the code works
</br><img src="https://raw.githubusercontent.com/slothtae/playing_with_pico/main/Blink/image.png"></br>
<ul> 
  <li><img src="https://github.com/slothtae/playing_with_pico/blob/main/Blink/image%201.png?raw=true"></br>
  The import statement imports modules which have the methods or function we need to use the pico board hardware and other abilities.
  Here we import 3 modules: board, digitalio and time.</br><h5>board :</h5>This module has all the pins we can use in pico.</br><h5>digitalio :</h5>Specifies if a pin is a digital input or output and other detail.</br><h5>time :</h5>We can use funcion like sleep</li></br>
  <li><img src="https://github.com/slothtae/playing_with_pico/blob/main/Blink/image%202.png?raw=true"></br>This line specifiy a variable led and assign the the led on the board as the led pin is saved as LED in board module. By using digitalio we specifies that the led is an Output device.</li></br> 
  <li><img src="https://github.com/slothtae/playing_with_pico/blob/main/Blink/image%203.png?raw=true"></br>We use a infinity loop with while loop and a always true condition. True is a boolean value in python. By using the .value we change the state of the led. The sleep function from time module is used to pause the state of the led for a certain time in our case 0.5 sec.</li> 
  
</ul>
