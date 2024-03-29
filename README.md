



[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=30&pause=1000&color=0FA400&width=435&lines=Setup+Mosquitto)](https://git.io/typing-svg)<img src="https://user-images.githubusercontent.com/91486755/185505116-05f9f700-7c20-40f0-b513-2895385133fd.png" width="35"   alt="deploy" align="left">

1. Setting up Mosquitto
   - Download from: [Mosquitto](https://mosquitto.org/download/)
     - Install
2. Configuring the ports will be used and websocks
* For Linux Users <img src="https://user-images.githubusercontent.com/91486755/185505274-146442df-69c2-46d9-a158-f3b8de448cf8.png" width="20"  alt="deploy" align="justify" >



  - sudo apt-add-repository ppa:mosquitto-dev/mosquitto-ppa
  - sudo apt-get update
  - sudo apt-get install mosquitto
  - sudo apt-get install mosquitto-clients
  - sudo apt clean
* Windows users :computer:
  - Just Install the .exe
3. Creating a configuration file .conf
  - replace the * with the name you want on the config file
* For Linux Users:
  - go to mosquitto default installation(YOURUSER/etc/mosquitto)
  - on mosquitto default run terminal commands
  ```
  nano *.conf
  ```
  - put this on *.conf
  ```
  listener 1883
  listener 9001
  allow_anonymous true
  ```
*  For Windows Users:
    - go to mosquitto default instalation folder(c:\mosquitto\)
    - create a new *.txt
    ```
    listener 1883
    listener 9001
    allow_anonymous true
    ```
    - save as *.conf
    
# Starting Mosquitto broker
  - In mosquitto default folder:
    - left click, Open Terminal Here // to windows users: shift + left click, Open power shell here
     - run the command
        ```
        ./mosquitto -v -c *.conf
        ```
[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=30&pause=1000&color=A513F7&width=435&lines=ARDUINO+IDE)](https://git.io/typing-svg)
1. Install Arduino IDE
   * [ARDUINO IDE Windows](https://downloads.arduino.cc/arduino-1.8.19-windows.exe)
   * [ARDUINO IDE LINUX](https://downloads.arduino.cc/arduino-1.8.19-linux64.tar.xz)
2. ESP8266 Library on Arduino IDE
   * In your Arduino IDE, go to File> Preferences
<img src="https://i0.wp.com/randomnerdtutorials.com/wp-content/uploads/2019/07/Install-ESP8266-Board-add-on-in-Arduino-IDE-open-preferences.png?w=197&quality=100&strip=all&ssl=1">

   *  Enter http://arduino.esp8266.com/stable/package_esp8266com_index.json into the “Additional Boards Manager URLs” field as shown in the figure below. Then, click the “OK”
<img src="https://i0.wp.com/randomnerdtutorials.com/wp-content/uploads/2019/07/Install-ESP8266-Board-add-on-in-Arduino-IDE-enter-URL.png?w=722&quality=100&strip=all&ssl=1">

3. Open the Boards Manager. Go to Tools > Board > Boards Manager…
<img src="https://i0.wp.com/randomnerdtutorials.com/wp-content/uploads/2019/07/Install-ESP8266-Board-add-on-in-Arduino-IDE-open-boards-manager.png?w=671&quality=100&strip=all&ssl=1">
4. Search for ESP8266 and press install button for the “ESP8266 by ESP8266 Community“
<img src="https://i0.wp.com/randomnerdtutorials.com/wp-content/uploads/2019/07/Install-ESP8266-Board-add-on-in-Arduino-IDE-search-ESP8266.png?w=786&quality=100&strip=all&ssl=1">


# PubSubClient Library

1. Go to Skectch
   * Library
      - Manage Library
         - Search for "PubSubClient" then click Install
<br>

# Installing the REACT Project


1. On CMD or TERMINAL run
   ```
   git clone https://github.com/Migeurfi/TCC3i3.git
   cd TCC3i3
   ```
2.1 Install Npm Packages
   * requires [nodejs](https://nodejs.org/en/)
   ```
   npm install 
   ```
2.2 start project:
   ```
   npm start
   ```
     
<br>
<h2>Code On<h2>
<p align="left">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=vscode,arduino,react,nodejs,css,js,git" />
  </a>
</p>
   


