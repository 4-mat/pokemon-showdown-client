Pokémon Showdown Client
========================================================================

Navigation: [Website][1] | [Server repository][2] | **Client repository** | [Dex repository][3]

  [1]: http://pokemonshowdown.com/
  [2]: https://github.com/Zarel/Pokemon-Showdown
  [3]: https://github.com/Zarel/Pokemon-Showdown-Dex

Introduction
------------------------------------------------------------------------

This is the Pokemon Showdown Client for various Battle Dome utilities.
Will be updated periodically!

Testing
------------------------------------------------------------------------

In order to test, edit and use the client, extra software must be 
installed before it is ready:

[Python version 3.10.2 or later][4]
[Node.js version 16.15.1 or later][5]
[Visual Studio Code][6]

After you have installed the above, download the .zip..... {continue here}

**Client testing requires a build step! Run `node build` (on Windows) or `./build`
(on other OSes) to build.**

### Running the client

You can connect to an arbitrary server by navigating to
`testclient.html?~~host:port`. For example, to connect to a server running
locally on port 8000, you can navigate to `testclient.html?~~localhost:8000`.

**NOTE**: (run `py -m http-server` from the
directory this README is in, then navigate in your browser to
`http://localhost:8080/testclient.html`).


License
------------------------------------------------------------------------

Pokémon Showdown's client is distributed under the terms of the [AGPLv3][6].

The reason is mostly because I don't want low-effort proprietary forks that add bad code that steals everyone's passwords, or something like that.

If you're doing _anything_ else other than forking, _especially_ if you want to some client code files in your own open-source project that you want to release under a more permissive license (like, if you want to make your own multiplayer open-source game client for a different game), please ask at `staff@pokemonshowdown.com`. I hold all the copyright to the AGPLv3 parts and can relicense them to MIT for you.

  [6]: http://www.gnu.org/licenses/agpl-3.0.html

**WARNING:** This is **NOT** the same license as Pokémon Showdown's server.
