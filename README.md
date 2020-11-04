# template-2020
## How to use

Look at the above list of files closely. You will see that the pages are named with the .md file extension: index.md, page2.md … page5.md. 
.md stands for MarkDown. You don't need to use the markdown language, and we don't introduce it here. But, there are many features and advantages of these .md files:

* .md files are automatically converted to HTML files when you publish them.

* When you edit the .md files, you are only editing the content for the BODY part of your pages. The system will automatically insert the content of your md files into the HTML of your pages.

* You still need to use HTML tags in your .md files, but only the tags you use in the body of the document. E.G.: `<h1>`, `<h2>`, `<p>`, `<hr>`, `<img>`, `<video>` etc. Etc.

* The big advantage of .md files is that you won't affect the architecture and structure of your main HTML template.

The HTML template of your site is located in the layouts folder. You will only need to edit this slightly to name the labels of your navigation bar.  Apart from that, you won't need to edit the HTML template at all.

In the folder assets/css, you will find the style.scss. .scss is a varient of css and works in the same way. You can edit this file to create custom styles for your site. For example, you will be able to change the colours of your banner, and make any other style adjustments you choose.
Finally, the config.yml file is a configuration file, where you can insert settings for your site.
