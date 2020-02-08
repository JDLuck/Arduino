# JDLuck Arduino Boards

#### AVR Boards
* [Spark Mark 2]

### Installation & Setup Instructions 

Start Arduino and open the Preferences window (**File** > **Preferences**). <br>
Copy and paste the following URL into the 'Additional Boards Manager URLs' input field:

	https://raw.githubusercontent.com/JDLuck/Arduino/master/package_jdluck_arduino_index.json

![Boards Manager URL](images/install-url.png)

If a URL already exists in the above field, click the button at the right end of the field. This will open an editing window allowing you to paste the above URL onto a new line.

In the Arduino IDE, open the 'Boards Manager' dialog (**Tools** > **Board** > **Boards Manager...**)<br> 
Select a search type of 'All' and filter for 'JDLuck'. Click the 'JDLuck AVR Boards' package entry and then 'Install'.

![Boards Manager Package](images/install-manager.png)

In the Arduino IDE, select the appropriate board to target, an example for the Spark Mark 2; <br>
(**Tools** > **Board** > **JDLuck Spark Mark 2**)

In the Arduino IDE, ensure that you have selected the correct COM port to target, as an example for the Spark Mark 2; <br>
(**Tools** > **Port** > **COM4 (JDLuck Spark Mk. 2)**)<br>
<br>
You can find the COM port number in 'Device Manager' on windows if you are unsure.

![Device Manager COM Port](images/install-com.png)

You should now be ready to 'Verify' and 'Upload' your sketch.