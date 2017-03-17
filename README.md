# budgie-applet-extra

Extra Budgie applets.

## Installation Example

To install the `caffeine` applet, for instance:

```shell
$ git clone https://github.com/jonathan-j-lee/budgie-applet-extra.git
$ cd budgie-applet-extra/
$ cp caffeine/Caffeine.plugin /usr/lib/budgie-desktop/plugins/
$ cp caffeine/caffeine.py /usr/lib/budgie-desktop/plugins/
$ chmod +x /usr/lib/budgie-desktop/plugins/caffeine.py
```

This may require `sudo`.

Then, simply reboot or run `budgie-panel --replace`, and add Caffeine to the panel from Raven. The installation process for the other applets is similar.

## Acknowledgements

Many thanks to the creators of [these applet examples](https://github.com/budgie-desktop/budgie-desktop-examples) for guidance.
