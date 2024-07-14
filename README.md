# base16-vivid

A set of [tinted-theming](https://github.com/tinted-theming) scheme templates for
[vivid](https://github.com/sharkdp/vivid). These
templates can be used with any compliant [Base16
builder](https://github.com/tinted-theming/base16-builder-go).

## Usage

Depending on the usage, there are three ways on how to use this:

### 1. Manual copy

If you are fine with manually copying the data to `~/.config/vivid/themes`,
you can always clone the repo or download the code as a zip file!

### 2. No `filetypes.yml` databases

If no `filetypes.yml` database is being used,
one can just clone this repository into the `~/.config/` folder:

```sh
git clone <url> ~/.config/vivid
```

### 3. Symlink

If you want both themes using a repo and a `filetypes.yml` database,
the repo can be cloned inside `~/.config/vivid` and the themes folder symlinked:

```sh
git clone <url> ~/.config/vivid/repo
ln -s ~/.config/vivid/repo/themes ~/.config/vivid/themes
```

Both `2.` and `3.` utilize cloning the repo,
which makes it easier to keep the files up to date if any changes arise!
