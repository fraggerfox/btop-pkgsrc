btop-pkgsrc
===============

NetBSD [pkgsrc][4] script for `btop`.

You can find `btop` [here][1]

Installation
------------

Copy `www/btop` folder to `/usr/pkgsrc` directory.

NOTE: If your pkgsrc directory is different from above, copy to the respective
place.

Usage
-----

Once you have copied the folder, install it as you would do for any port.

`$ cd /usr/pkgsrc/www/btop`<br>
`$ make install clean`

For a list of dependencies for the build check [here][2]

NOTE: If you are using pkgsrc in a non NetBSD system, replace `make` with
`bmake` in the above btop example.

Credits
-------

* `btop` is developed and maintained by the [Jakob P. Liljenberg][3]
* Thanks to [0-wiz-0][5] for helping test the NetBSD specific changes.

License
-------

BSD 2-clause. See LICENSE.

[1]: https://github.com/aristocratos/btop
[2]: https://github.com/aristocratos/btop?tab=readme-ov-file#compilation-netbsd
[3]: https://github.com/aristocratos
[4]: http://pkgsrc.se/sysutils/btop
[5]: https://github.com/0-wiz-0
