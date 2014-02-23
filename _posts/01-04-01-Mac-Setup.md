---
title: Configuration Mac
isChild: true
---

## Configuration Mac {#mac_setup_title}

OSX contient PHP préinstallé, mais la version ets généralement un peu plus ancienne que la dernière version stable disponioble. Lion dispose de PHP 5.3.6, Moutain Lion de 5.3.10 et Mavericks de 5.4.17. 

Pour mettre à jour PHP sur OSX vous pouvez utiliser le [package managers][mac-package-managers], avec
[php-osx par Liip][php-osx-downloads] qui est recommendé.

L'autre option est de le [compiler vous même][mac-compile], et dans ce cas assurez vous d'avoir bien isntallé au préalable Xcode et le substitut Âpple ["Command Line Tools for Xcode"][apple-developer] téléchargeable depuis le "Mac Developer Center".

Pour un package "tout-en-un" incluant PHP, le serveru web Apache et la base de données MySQL ainsi qu'une interface d'administration conviviale, essayez [MAMP][mamp-downloads] ou [XAMPP][xampp].

[mac-package-managers]: http://www.php.net/manual/en/install.macosx.packages.php
[mac-compile]: http://www.php.net/manual/en/install.macosx.compile.php
[xcode-gcc-substitution]: https://github.com/kennethreitz/osx-gcc-installer
[apple-developer]: https://developer.apple.com/downloads
[mamp-downloads]: http://www.mamp.info/en/downloads/index.html
[php-osx-downloads]: http://php-osx.liip.ch/
[xampp]: http://www.apachefriends.org/en/xampp.html
