### [Foobar](https://foobar.com)

#### Install using Git

If you are a git user, you can install the theme and keep up to date by cloning the repo:

```bash
git clone https://github.com/dracula/foobar.git
```

#### Install manually

Download using the [GitHub `.zip` download](https://github.com/dracula/foobar/archive/master.zip) option and unzip them.

#### Activating theme

1. Add following to ``config/settings.yaml``:
```yaml
color: slate
theme: dark

background:
  image: /images/dracula-background.png

cardBlur: sm
```
2. Copy ``custom.css`` to ``/app/config``:
3. Download ``dracula-background.png`` from Homer Dracula theme:
[Dracula Background PNG](https://github.com/dracula/homer/blob/437b67925299b57013e5d169167096ef2d99f604/dracula-background.png)
4. Copy ``dracula-background.png`` to ``/app/public/images``.
5. Boom! It's working ✨
