My Dotfiles for Ubuntu
========

NOTE: Still really beta.

This differs a bit from the [OSX dotfiles][3] that I have. These are meant for a remote Ubuntu box, works a bit differently.

## Install

Just run this:

```bash
git clone https://github.com/hilja/dotfiles-box.git && cd dotfiles-box && source bootstrap.sh
```

It does:

- `git clone` the repo
- `cd` into the `dotfiles-box` dir
- Run the `bootstrap.sh` script, that will copy the files from the `dotfiles` dir and put them to `~/`

Pretty much ripped from [here][1] and [here][2].

To update:

- `cd` into the `dotfiles` dir
- Run the `bootstrap.sh` script, that will copy the files from the `dotfiles` dir and put them to `~/`

Pretty much ripped from [here][1] and [here][2]

[1]: https://github.com/paulirish/dotfiles
[2]: https://github.com/mathiasbynens/dotfiles
[3]: https://github.com/hilja/dotfiles