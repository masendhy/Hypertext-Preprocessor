Untuk Linux dan Mac tambahkan di .bashrc atau .profile .zshrc
Inti dari setting PATH adalah, agar kita bisa mengakses PHP dari command prompt / terminal

1. Buka zshrc :

```zsh
code ~/.zshrc
```

2. Tambahkan path:

```zsh
export PATH="/Applications/XAMPP/bin:$PATH"
```

3. Check PHP version :

```zsh
php --version
```

- jika berhasil maka akan keluar :
  PHP 8.1.9 (cli) (built: Aug 4 2022 15:11:08) (NTS)
  Copyright (c) The PHP Group
  Zend Engine v4.1.9, Copyright (c) Zend Technologies
  with Xdebug v3.1.5, Copyright (c) 2002-2022, by Derick Rethans
  with Zend OPcache v8.1.9, Copyright (c), by Zend Technologies
