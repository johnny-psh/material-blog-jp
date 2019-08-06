# material-blog-jp (Jekyll Theme) 
Material-blog-jp is a blog built following material design principles. This theme is built using the Material Design Lite web framework.  

This theme comprises four web pages, index, about, search and 404. Index will display all the blog posts, starting from the latest. Search will display a text field input and two of the latest blog posting. About will contain a description of the blog. 404 will display when someone tries to access a resource that cannot be found. This theme is optimized for mobile phones, iPads, etc 

Supports code highlights using Rogue (GitHub Theme) 

Because of some limitations, please have at least two posts to push the footers to the bottom of the page, the same goes for the “about” section. 

![GitHub Logo](/screenshot.PNG) 

## Installation 
Setup Jekyll in your environment https://jekyllrb.com/docs/installation/windows/ 

Clone or fork this repository 

`git clone https://github.com/johnnymythology/material-blog-jp.git`  

`gem install material-blog-jp` 

`bundle exec jekyll serve` 

A more detailed writeup [https://www.johnnypan.me/technical/2019/08/06/Material-Design-Blog-Theme.html](https://www.johnnypan.me/technical/2019/08/06/Material-Design-Blog-Theme.html) 

## Usage 
There are four default pages: 
- index.md  
- about.md 
- search.md 
- 404.md 

Each page has a different title. Edit the title in the Front Matter. 

The blog title needs to be edited in _config.yml. Fill in the options in _config.yml accordingly. This will be used for SEO (Search Engine Optimization). 

To create a new post, follow the naming format in the two example post. Since this blog uses images for each post, select an image and put it inside the assets folder. Follow the naming convention as the two sample images. (“yyyy-mm-dd.jpg”) 

For any photos used in the post, please put it inside the assets folder. To use an image in the post, follow this format:  

`![image](/assets/old-blog-screenshot.PNG)` 

## Technical 
Web Framework: Material Design Lite 

Static Site Generator: Jekyll 

Javascript Libraries: jQuery 

For search, I am using “simple jekyll search” by Chistian Fei 

Material Design Lite header I am using is not mobile optimized and requires some additional CSS. 

jQuery is used for the arrow button to scroll the screen back to the top. 

## Contributing 
Bug reports and pull requests are welcome on GitHub at https://github.com/johnnymythology/material-blog-jp. 

## License 
The theme is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT). 
