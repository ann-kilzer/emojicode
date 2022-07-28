# How to make sense of this

This looks like the fever dream of a PL grad student who found a -1 cursed keyboard in their windowless lab and now can only type specific Unicode codepoints...

Anyway, the good people of https://github.com/emojicode/emojicode gave this to us and I am
trying to make sense of it.





## START THE MAGIC

1. Install Emojicode 1.0 beta 2 here: https://www.emojicode.org/docs/guides/install.html

2. Compile it

```sh
emojicodec fun.emojic
```

3. Run it

```sh
./fun [Your name]
```

This program reads from STDIN (aka the film-rabbit-computer sequence) and therefore needs
a parameter. If you omit it, 🤯 happens!

