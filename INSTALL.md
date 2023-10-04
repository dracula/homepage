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

3. Boom! It's working ✨
