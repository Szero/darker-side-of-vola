![voladark](https://raw.githubusercontent.com/Szero/darker-side-of-vola/master/voladark.png)

Darker Side Of Vola
===================

High contrast theme for [Volafile](https://volafile.org).
I tried few bitsized True Type fonts but such fonts are
shit when antialiasing comes into play so I decided to leave it with default font.

Installation
------------

Install [Tampermonkey](https://tampermonkey.net/) extension first.

After installing it, just click this
[this.](https://github.com/szero/darker-side-of-vola/raw/master/extension/darker.user.js)

Contributing
------------

In order to contribute you need to install [this](https://github.com/Szero/stuff2str)
program first. You will want to modify only to the css and darker.js file.
After you are done with the changes, invoke the build_addon.sh script like so:

```sh
./build_addon.sh version <version_number_above_the_current_one>
```
This will build the addon and metadata file in extension folder. And you are ready to commit.

Thanks
------

- To [dad](https://github.com/voladad) for creating [css](https://userstyles.org/styles/103946/as-dark-as-my-soul) as
a base for it.
