

## Conky

**Conky** is a free, light-weight system monitor for X, that displays
any kind of information on your desktop.


### Features

Conky can display more than 300 built-in objects, including support for:

 * A plethora of OS stats (uname, uptime, **CPU usage**, **mem
   usage**, disk usage, **"top"** like process stats, and **network
   monitoring**, just to name a few).
 * Built-in **IMAP** and **POP3** support.
 * Built-in support for many popular music players ([MPD][],
   [XMMS2][], [BMPx][], [Audacious][]).
 * Can be extended using built-in [**Lua**](lua) support, or any of your
   own scripts and programs ([more](Lua Interface)).
 * Built-in [**Imlib2**][Imlib2] and [**Cairo**][cairo] bindings for arbitrary drawing
   with Lua ([more](wiki/Lua-API)).

... and much much more.

Conky can display information either as text, or using simple progress
bars and graph widgets, with different fonts and colours.

### Screenshots

![screenshot](./screenshot.png?raw=true "screenshot of conky")

### Installation

## Conky on Linux

### Arch

Conky is available in the Arch repositories, so you can install it the
normal way:

```bash
$ pacman -S conky
```

### Ubuntu
```bash
$ sudo apt install conky conky-all
```

###clone this conky
```bash
$ git clone https://github.com/emp3ror/mjt_conky .conky
```

###run conky
```bash
$ sh .conky/startup.sh 
```

### add to startup
In openbox, add 
```
(sleep 1s && sh ~/.conky/startup.sh) &
```
to .config/openbox/autostart


### License

Conky is licensed under the terms of the [GPLv3](LICENSE.GPL) and
[BSD](LICENSE.BSD) licenses.

### Contributing

To submit code changes, please open pull requests against [the GitHub repository](https://github.com/emp3ror/mjt_conky/edit/master/README.md). Patches submitted in issues, email, or elsewhere will likely be ignored. Here's some general guidelines when submitting PRs:

 * In your pull request, please:
   * Describe the changes, why they were necessary, etc
   * Describe how the changes affect existing behaviour
   * Describe how you tested and validated your changes
   * Include any relevant screenshots/evidence demonstrating that the changes work and have been tested
 * Any new source files should include a GPLv3 license header
 * Any contributed code must be GPLv3 licensed

[MPD]: http://musicpd.org/
[XMMS2]: http://wiki.xmms2.xmms.se/index.php/Main_Page
[BMPx]: http://bmpx.backtrace.info/site/BMPx_Homepage
[Audacious]: http://audacious-media-player.org/
[luawiki]: http://en.wikipedia.org/wiki/Lua_%28programming_language%29
[stable-src]: https://github.com/brndnmtthws/conky/archive/1.9.0.tar.gz
[devel-src]: https://github.com/brndnmtthws/conky/archive/master.tar.gz
[wiki]: https://github.com/brndnmtthws/conky/wiki
[lists]: http://sourceforge.net/mail/?group_id=143975
[ircconky]: irc://irc.freenode.net/conky
[Imlib2]: http://docs.enlightenment.org/api/imlib2/html/
[cairo]: http://www.cairographics.org/