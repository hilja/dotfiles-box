My Dotfiles for Ubuntu
========

NOTE: Still really beta.

<<<<<<< HEAD
This differs a bit from the [OSX dotfiles][3] that I have. These are meant for a remote Ubuntu box, works a bit differently.
=======
This differs a bit from the [OSX dotfiles][3] that I have. It's meant for a remote Ubuntu box.
>>>>>>> b603485fdb06055875f60337f762aab1f3e74733

## Install

Just run this:

<<<<<<< HEAD
```bash
git clone https://github.com/hilja/dotfiles-box.git && cd dotfiles-box && source bootstrap.sh
=======
```
    git clone https://github.com/hilja/dotfiles-ubuntu.git && cd dotfiles && source bootstrap.sh
>>>>>>> b603485fdb06055875f60337f762aab1f3e74733
```

It does:

- `git clone` the repo
<<<<<<< HEAD
- `cd` into the `dotfiles-box` dir
- Run the `bootstrap.sh` script, that will copy the files from the `dotfiles` dir and put them to `~/`

Pretty much ripped from [here][1] and [here][2].
=======
- `cd` into the `dotfiles` dir
- Run the `bootstrap.sh` script, that will copy the files from the `dotfiles` dir and put them to `~/`

Pretty much ripped from [here][1] and [here][2]
>>>>>>> b603485fdb06055875f60337f762aab1f3e74733

[1]: https://github.com/paulirish/dotfiles
[2]: https://github.com/mathiasbynens/dotfiles
[3]: https://github.com/hilja/dotfiles