# famly-fetch
Fetch your (kid's) images from famly.co

You need python3 installed and then it's as simple as running:

```
./fetch.py <email> <password>
```

Notice that this will make your password visible in the process list
while the program is running, so only run this on a personal computer.

Downloaded images will be stored in the current working directory,
usually the folder where you run this program from.

It will only download images where you have tagged your child. Images
will be saved in the order they are listed in Famly, which is usually
in chronological order, but dates unfortunately not easily available.

The images have been stripped for any metadata including EXIF
information by Famly.

[Hent-billeder-fra-Famly.co.pdf](Hent-billeder-fra-Famly.co.pdf)
contains instructions in Danish on how to make it work on a computer
running Windows.

There is now also a script (contributed by
[pay64k](https://github.com/pay64k)) to fetch images from messages in
Famly. That can be run as:

```
./fetch_from_messages.py <email> <password>
```
