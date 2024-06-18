# homebrew-ttork

Homebrew formula for the [TTORK](https://github.com/SwordOfDamocles/ttork) Multi-Tilt Tool.

If you have previously installed packages from this repository, you may need to run `brew update` to ensure that you have the latest versions of the formulas:

```bash
brew update;brew upgrade
```

## Installing ttork
[TTORK](https://github.com/SwordOfDamocles/ttork) allows you to manage multiple instances of the amazing [Tilt](https://tilt.dev) microservice development tool, across multiple repositories.

First, tap the repository:
```bash
$ brew tap SwordOfDamocles/ttork
```

Then install:
```bash
$ brew install swordofdamocles/ttork/ttork
```

Check installed version:
```bash
$ ttork version
ttork, version 0.3.1
```