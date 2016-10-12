# How to install Ruby on Ubuntu

## Installing Rbenv

It may not seem, but the best way to install ruby in your computer is with a version manager. To do this, we'll use Rbenv just because it is very simple to use

Just follow the instructions! All this commands bellow has to be typed on your Console

- Check out rbenv into ~/.rbenv.
```bash
$ git clone https://github.com/rbenv/rbenv.git ~/.rbenv
```

- Add ~/.rbenv/bin to your $PATH for access to the rbenv command-line utility.
```bash
$ echo 'export PATH="$HOME/.rbenv/bin:$PATH"' >> ~/.bashrc
```
- Restart your shell so that PATH changes take effect
```bash
source ~/.bashrc
```
- Now check if rbenv was set up
```bash
$ type rbenv
#=> "rbenv is a function"
```

## Installing Ruby

Please, pay attention, very difficulty ahead!

- List all available Ruby versions:
```bash
$ rbenv install -l
```

- Install a Ruby version (in 10-11-2016 the currently ruby version is 2.3.1):
```bash
$ rbenv install 2.3.1
```

- Nice! and now, type `irb` (is for `interactive ruby shell`) on your console and FEEL THE MAGIC
```bash
$ irb
irb(main):001:0> _
```

And now you can go to your [first command]() on irb or [go back](../../README.md) to README!
