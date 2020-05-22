# Instruments Lab Jekyll Tutorial
### May 22 2020

I'll be giving an intro to Jekyll from 1400-1600. This repo contains everything you need. 

## Do I need coding experience?

If you have it that's great, but if you don't Jekyll is a really really good way to learn!

## Do I need to know the command line?

All you need to know is how to get to a command line (the terminal on a Mac)! Don't worry if you don't know much about the command line.

# Stuff to do beforehand if you'd like to follow along

If you'd like to follow along, install Jekyll and build the example site I've provided. (If you don't want to follow along that's cool too, you can just skip this):

## 1. Install Jekyll

Install Jekyll using the command line, with the instructions on [this page](https://jekyllrb.com/docs/installation/). (Questions? Ping me on slack `@astrid`!)

## 2. Clone this repo

[Go to the repo](https://github.com/disastrid/ail_jekyll), click `Clone or download` and copy the URL, then clone it locally on the command line or in the Github GUI. This will download all the working files you'll need.

## 3. Test it!

After installing, go to your terminal and go to the repo folder.

For example, on my machine I keep all repos in a folder called `GitHub` and I get to this repo like this:

```
$ cd ~/GitHub/ail_jekyll
```
### 3a. Go into the docs folder

Once you're in the folder, list the contents. Everything is in a folder called `docs/`:

```
$ ls
README.md     docs
```

Navigate to the docs folder:
```
$ cd docs/
```

### 3b. Build the site

Then, build and run the site:
```
$ bundle exec jekyll serve
```

When the site's ready these lines will print:
```
  Server address: http://127.0.0.1:4000/
  Server running... press ctrl-c to stop.
```

### 3c. Admire the site you built!

Open a web browser, and go to the URL `localhost:4000`. Voila!

As you make changes in a text editor and save them, Jekyll will automatically rebuild your site. Just refresh the page when it's finished to see your changes.
