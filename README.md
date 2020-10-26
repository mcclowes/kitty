# kitty config

Config for the terminal emulator, [Kitty](https://sw.kovidgoyal.net/kitty/index.html).

## Setup

1. Install kitty

`brew install cask kitty`

2. Clone this in the correct dir

`cd ~/.config && rm -rf kitty && git clone https://github.com/mcclowes/kitty`

### Extending this config

If you want to extend this config with your own settings, the best way is to make an additional config file to add your new rules to. Where there are config conflicts, this new config file will take precedence.

1. Make a new config

`mkdir new.conf`

2. Include it in this config

`echo 'include new.conf' >> kitty.conf`

3. Modify it as you see fit

`subl new.conf`

## Useful links

- [Config documentation](https://sw.kovidgoyal.net/kitty/conf.html#conf-kitty-shortcuts-layout)