Pokémon Showdown Client for Battle Dome
========================================================================

Introduction
------------------------------------------------------------------------

This is the Pokemon Showdown Client for various Battle Dome utilities.
Will be updated periodically!

Testing
------------------------------------------------------------------------

In order to test, edit and use the client, extra software must be 
installed before it is ready:

[Python version 3.10.2 or later][4] (Windows Installer 64-bit at the bottom) |
[Node.js version 16.15.1 or later][5] (Windows Installer (.msi)) |
[Visual Studio Code][6]

[4]: https://www.python.org/downloads/release/python-3102/ 
[5]: https://nodejs.org/en/download/
[6]: https://code.visualstudio.com/

Python Installation:
![image](https://user-images.githubusercontent.com/36202270/172741278-b2503fa8-eaea-405b-8d3a-d6789d35ec9f.png)

Node.js Installation:
![image](https://user-images.githubusercontent.com/36202270/172741451-c94b3675-bb10-4f8e-8f1b-9ef4c0b80e1c.png)

Visual Studio Code Installation:
![image](https://user-images.githubusercontent.com/36202270/172741550-fac54f2f-d8e6-4c93-91e6-bd57b1547bee.png)

After you have installed the above, download the .zipped client and unzip
it in a folder of your choice.

### Running the client

Right-click the folder then click Open with Code, view below:
![image](https://user-images.githubusercontent.com/36202270/172741746-ee9606c3-7c7d-40c5-818a-5573c776f460.png)

Click New Terminal as shown below:
![image](https://user-images.githubusercontent.com/36202270/172741924-decf3cd7-70f9-4a8a-9cde-f9059dacb0f2.png)

A new terminal should be opened:
![image](https://user-images.githubusercontent.com/36202270/172741982-2842c9db-8bd6-43d1-a954-acedf696d555.png)

At this point type `py -m http.server` into the terminal.
![image](https://user-images.githubusercontent.com/36202270/172742167-7f7a079e-ad26-4a01-aa1c-e851418e5b85.png)

`localhost:8000/testclient.html` should then be typed into your brower of choice. (I used Opera as my browser)
![image](https://user-images.githubusercontent.com/36202270/172742689-a7fa890f-0078-4c8b-8fb0-9238eb20a1ac.png)

You should be good to log in from here!

License
------------------------------------------------------------------------

Pokémon Showdown's client is distributed under the terms of the [AGPLv3][6].

The reason is mostly because I don't want low-effort proprietary forks that add bad code that steals everyone's passwords, or something like that.

If you're doing _anything_ else other than forking, _especially_ if you want to some client code files in your own open-source project that you want to release under a more permissive license (like, if you want to make your own multiplayer open-source game client for a different game), please ask at `staff@pokemonshowdown.com`. I hold all the copyright to the AGPLv3 parts and can relicense them to MIT for you.

  [6]: http://www.gnu.org/licenses/agpl-3.0.html

**WARNING:** This is **NOT** the same license as Pokémon Showdown's server.
