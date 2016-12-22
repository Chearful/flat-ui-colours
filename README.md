# Flat UI Colours
A simple CSS library for each of the colours listed at http://flatuicolors.com/.

# Setup
Simply download the .css or .min.css files from the repo and upload to your web server - then attach to your pages. CDN coming Soon TM

# Usage
Each colour is done by its name available on http://flatuicolors.com/. If the name has a space; then simply drop the space.

If you want to style the text in a specific colour then use the class:
`.flatuic-text-NAME`
Alternatively, you can change the background colour using this class:
`.flatuic-bg-NAME`

# Examples
If I wanted to make my h1 the colour of `concrete` and the background of the div `peter river`, I would use this:
```html
<div class="flatuic-bg-peterriver"> <!-- Notice the dropping of the space in the colour name -->
   <h1 class="flatuic-text-concrete">Lorem Ipsum</h1>
   <p>Blah blah blah</p>
</div>
```
# License
This project is licensed under MIT. Here is a quick summary: https://tldrlegal.com/license/mit-license 
