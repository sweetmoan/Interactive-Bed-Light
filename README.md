# Interactive-Bed-Light
<b>design for u to control ur bed lights anywhere!</b> <br>
u can modify the script to control various of lights in ur room and have someone to control it for fun.

<b>How:</b> <br>
<b>Requirements:</b> Python installed , flask and pyserial library.<br>
1.To setup , in led_strip.ino upload this code to arduino uno ,view the code and change the variable if you like. <br>
2.Complete the following curcuit in breadboard that connects led strips to arduino. <br>
the curcuit: <br>
3.Run the app.py <br>
<br>
<b>to Tunnel the server app [this is to access the web page anywhere]:</b> <br>
4.Download Clouldflare [u can use ngrok if u like]<br>
link: https://developers.cloudflare.com/cloudflare-one/connections/connect-apps/install-and-setup/installation<br>
5.Open Cmd > go to where ur cloudflare.exe place and enter "clouldflare.exe tunnel -url localhost:80" <br>
