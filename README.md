# Thumbnail_Showcase
HTML Thumbnail Showcase or image library [Preview](https://sharishth.github.io/Thumbnail_Showcase/)

# Version
v1.0.0

# Features
- Image Links are Hoverable, they scale-up on hover, and get brighter

# Feature thought to be implemented in next version
- javascript implementation
- Rating system
- page switching using JS

# Usage and Guide
- Your recommended image dimension should be **255x255** pixels
- Put your images/ thumbnails in **assets** folder
- Copy paste the below code with following changes below
  
  <code>
      
        <div class="thumber">
          <a href="#">
            <img src="assets/images.jpg"> <!--Your Thumbnail Image Directory-->
            <p>Robot</p> <!--Caption here-->
            <span class="fa fa-star checked"></span>
            <span class="fa fa-star checked"></span>
            <span class="fa fa-star checked"></span>
            <span class="fa fa-star"></span>
            <span class="fa fa-star"></span>
          </a>
        </div>
     </code>
- To add new pages, simply make copy of file **index.html** and rename it to something else, eg.index2.html
- link to new file like code below
   <code>
  
      <div style="text-align: center;">
        <a class="a-button" href="#">&#60;</a> <a href="index.html">1</a> <a href="index2.html">2</a> <a href="#">3</a> <a class="a-button" href="#">&#62;</a>
        </div>
      <br>
     </code>
