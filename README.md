# Benthos-Learning
Benthos Learning Tutorial and Code Snippets

## Steps to run  bloblang in local by pulling benthos docker image

There are a few ways to execute Bloblang, below guide is to pull a Benthos docker image and run the command benthos blobl server, which opens up an interactive Bloblang editor:

- Step 1: Pull Image : 
 docker pull docker.repo1.uhc.com/jeffail/benthos:latest

- Step 2: Run Blobl Server : 
 docker run -p 4195:4195 --rm docker.repo1.uhc.com/jeffail/benthos blobl server --no-open --host 0.0.0.0

- Step 3: Open in Browser : 
 Next, open your browser at [localhost](http://localhost:4195) and you should see an app with three panels, the top-left is where you paste an input document, the bottom is your Bloblang mapping and on the top- 
 right is the  output.

