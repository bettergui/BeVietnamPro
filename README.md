# The Be Vietnam Pro font family

A while ago, [Be Vietnam](https://github.com/bettergui/BeVietnam) was made to compliment the essence of our beloved Tiếng Việt and was lucky enough to be [adopted](https://fonts.google.com/specimen/Be+Vietnam) by many millions of users around the globe. But we still want to push our limits further by challenging ourselves to craft an even better typeface that embraces Vietnamese beauty and excellent in functionality & usability, and we call it Be Vietnam Pro.

This new variant inherits the spirit of the original Be Vietnam and takes it to the next level. We refined Vietnamese letterforms with diacritics adaptive forms for specific use cases. We engineered them for better readability; and much more improvements.

We hope you will enjoy Be Vietnam Pro as much as we do, and we cannot wait to see what you can create with it!

![Sample 1](documentation/samples/1.png)
![Sample 2](documentation/samples/2.png)
![Sample 3](documentation/samples/3.png)
![Sample 4](documentation/samples/4.png)
![Sample 5](documentation/samples/5.png)
![Sample 6](documentation/samples/6.png)
![Sample 7](documentation/samples/7.png)
![Sample 8](documentation/samples/8.png)

## To build the font

First, install ttfautohint : `brew install ttfautohint`

Then, install gftools in a virtual environment:
1. go to the root of your local clone of this repository: `cd path/to/dir`
2. there, create a venv: `python3 -m venv env`
3. Activate the venv: `source env/bin/activate`
4. Install gftools: `pip install gftools`

Now you can build the fonts:
Before building the font, go to the sources directory of your local clone. 
Make sure you activated the virtual env. 
From there you can run: `gftools builder config.yaml`
