### [Foobar](https://foobar.com)

#### Install using Git

If you are a git user, you can install the theme and keep up to date by cloning the repo:

```bash
git clone https://github.com/dracula/foobar.git
```

#### Install manually

Download using the [GitHub `.zip` download](https://github.com/dracula/foobar/archive/master.zip) option and unzip them.

#### Activating theme

1. Add following to config/settings.yaml:;
```yaml
color: slate
theme: dark

background:
  image: /images/dracula-background.png

cardBlur: sm
```

2. Add following to config/custom.css:;
```yaml
.theme-slate {
  --color-50: 0 0 0;
  --color-100: 0 0 0;
  --color-200: 248 248 242;
  --color-300: 189 147 249;
  --color-400: 241 250 140;
  --color-500: 0 0 0;
  --color-600: 0 0 0;
  --color-700: 0 0 0;
  --color-800: 40 42 54;
  --color-900: 68 71 90;

  --color-logo-start: 80 250 123;
  --color-logo-stop: 80 250 123;
}
```

3. Download dracula background image from Homer Dracula theme:
[Dracula Background PNG](https://github.com/dracula/homer/blob/437b67925299b57013e5d169167096ef2d99f604/dracula-background.png)

4. Copy dracula background image into your Homepage installation.  For Docker copy it into an ./images directory and mount it in your docker-compose.yaml:'
````yaml
    volumes:
      - ./images:/app/public/images
````
5. Boom! It's working ✨
