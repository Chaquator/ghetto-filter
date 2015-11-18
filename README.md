# Turbo Meme Generator

A tool I made that uses templates and simages (short for "surrogate images") to generate abstract sh*tposts.

Runs on Python 3.4(.2)

## Usage
I'm literally gonna let [argparse](https://docs.python.org/3/library/argparse.html) write this for me because I don't want to waste the effort.
```
usage: turbomeme.py [-h] [-c file] [-sl dir] [-tl dir] [-uf dir] [-q int]
                    [-co count] [-tf file]
                    out

Churns memes at the speed of sound

positional arguments:
  out                   Output file (or directory if you're using count)

optional arguments:
  -h, --help            show this help message and exit
  -c file, --config file
                        Specify custom config. The default config is in the
                        same directory as the install.
  -sl dir, --simages-location dir
                        Location for simages
  -tl dir, --templates-location dir
                        Location for templates
  -uf dir, --unused-file dir
                        Location for unused files
  -q int, --quality int
                        Quality of image from 1 (worst) to 95 (best)
  -co count, --count count
                        Specify how many memes you intend to output
  -tf file, --template-file file
                        Override choosing random template and supply your own,
                        instead. Used for testing purposes
```

## Sample images
![WHAT ARE THOOOSE](samples/image0.jpg)
![WHAT ARE THOOOSE](samples/image1.jpg)
![WHAT ARE THOOOSE](samples/image2.jpg)
![WHAT ARE THOOOSE](samples/image3.jpg)
![WHAT ARE THOOOSE](samples/image4.jpg)
![WHAT ARE THOOOSE](samples/image5.jpg)
![WHAT ARE THOOOSE](samples/image6.jpg)
![WHAT ARE THOOOSE](samples/image7.jpg)

## Install
Check [releases](https://github.com/Chaquator/turbo-meme-generator/releases)

## Build
Run `setup.py` inside the directory to compile it into a single `.exe` file. 

Dependencies (that aren't included in a standard install of Python 3.4.2):
- [py2exe](http://www.py2exe.org/) (only if you plan to build with `setup.py` obviously)
- [Pillow](https://python-pillow.github.io/) (fork of old PIL, updated for Python 3.4)

## Licenses
what?


# Ghetto-filter

Ghetto-filter is a little Python CLI tool that "ghetto-ifies" an image.
It runs on Python 3.4(.2).

## Usage
Like [my last repo](https://github.com/Chaquator/turbo-meme-generator), I'm letting argparse make the usage for me.
```
usage: ghetto_filter.py [-h] -i file [-sh float] [-co float] [-cf float]
                        [-q int]
                        output

Ghetto Filter for image

positional arguments:
  output

optional arguments:
  -h, --help            show this help message and exit
  -i file, --input file
                        Input file (Required)
  -sh float, --sharpness float
                        Default: 5.0; Sharpness for the image
  -co float, --contrast float
                        Default: 3.0; Contrast for the image
  -cf float, --color-factor float
                        Default: 0.7; 0.0 represents black and white; 1.0
                        represents full, original color; and going further
                        increases the vibrance of the color.
  -q int, --quality int
                        Default: 15; Quality of output jpeg from 0 to 100
```
						
## Build
Run `setup.py` inside the directory to compile it into a single `.exe` file. 

If you are building from source, here are the dependencies (that aren't included in a standard install of Python 3.4.2):
- [py2exe](http://www.py2exe.org/) (only if you plan to build with `setup.py` obviously)
- [Pillow](https://python-pillow.github.io/) (fork of old PIL, updated for Python 3.4)

## Releases
one sec ill get that later


## Licenses
what?