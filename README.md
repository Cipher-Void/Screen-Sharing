# Screensharing_Lib
Screenshare: Python module for sharing/casting your screen with others in realtime with
fast &amp; accurate casting. Works best when connected to same network  Copyright © 2024 Coder-wis
<vishalsharma659615@gmail.com>

## Coming updates :
<ol>
  <li> Mouse Controlling </li>
  <li> Voice Transfer features </li>
</ol>

## Installation of Library :
The pip command to install ttkinter videos library for use
<pre><code> pip install screensharing </code></pre>

## Usage :
Notes **only for 0.0.2 version**
### From Server-Side (sender) :
<pre lang='sh'>
import importlib
screenshare = importlib.import_module("screenshare-main")

import socket

host=socket.gethostname()
print("host : ",host)
screenshare.server(host).create()
</pre>

### From Client-Side (receiver) :
<pre lang='sh'>
import importlib
screenshare = importlib.import_module("screenshare-main")

ser=screenshare.server_receive(host="Dell",port=8080)
ser.connect()
</pre>

## Releases :
For the updated version <b><a href="https://pypi.org/project/screensharing/"> Latest </a></b> version.

## License :
Distributed under the MIT License. See <b><a href="https://github.com/Vishal24102002/screenshare_lib/blob/main/LICENSE"> LICENSE </a></b>for more information.
