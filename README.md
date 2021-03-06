![retrosmart-preview](https://github.com/mdomlop/retrosmart-openbox-themes/blob/master/preview.png "Retrosmart look")

Retrosmart Openbox themes
=========================

Retrosmart openbox themes is a set of themes for Openbox with a retro look. It
is inspired in the simplicity of many systems like Haiku and old Windows.

A 12 size sans-serif font is recommended for optimum appearance. The font size
is changed by editing `~/.config/openbox/rc.xml`. If you do not know how to
edit your `rc.xml`, you can use the graphic programs `obconf` or `obconf-qt`.

An example of how the theme section should look in your `rc.xml`:

        <theme>
            <name>retrosmart-openbox-navy</name>
            <titleLayout>CIDMLN</titleLayout>
            <keepBorder>yes</keepBorder>
            <animateIconify>yes</animateIconify>
            <font place="ActiveWindow">
                <name>Noto Sans</name>
                <size>12</size>
                <weight>normal</weight>
                <slant>Normal</slant>
            </font>
            <font place="InactiveWindow">
                <name>Noto Sans</name>
                <size>12</size>
                <weight>normal</weight>
                <slant>Normal</slant>
            </font>
            <font place="MenuHeader">
                <name>Noto Sans</name>
                <size>12</size>
                <weight>Normal</weight>
                <weight>normal</weight>
                <slant>Normal</slant>
            </font>
            <font place="MenuItem">
                <name>Noto Sans</name>
                <size>12</size>
                <weight>Normal</weight>
                <slant>Normal</slant>
            </font>
                <font place="ActiveOnScreenDisplay">
                <name>Noto Sans</name>
                <size>12</size>
                <weight>Normal</weight>
                <slant>Normal</slant>
            </font>
            <font place="InactiveOnScreenDisplay">
                <name>Noto Sans</name>
                <size>12</size>
                <weight>Normal</weight>
                <slant>Normal</slant>
            </font>
        </theme>

INSTALLATION
------------

Execute:

        $ ./configure
        $ make
        # make install

For uninstall run:

        # make uninstall

Please read [INSTALL.md](https://github.com/mdomlop/retrosmart-openbox-themes/blob/master/INSTALL.md) for more information.
