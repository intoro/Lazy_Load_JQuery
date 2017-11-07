Lazy Load JQuery library delays the loading of images until the user scrolls to them.
This will reduce loading time on long pages with lots of images.

To get started the fastest, from a terminal:

git clone https://github.com/intoro/Lazy_Load_JQuery.git

This will create a folder titled Lazy_Load_JQuery. Inside that folder will be an index.html file and two folders: one titled js/ and the other img/. The index.html file references the 3 .js files in the /js folder. Two in the header and one right above the closing </body> tag. The 3 .js files are a version 2.2.4 of jQuery, a version 1.9.7 of the Lazy Load Library, and the custom jQuery code for this lazy load tutorial called customLazy.js . The /img folder contains the 7 images used in this example of Lazy Load. Open the index.html file in a browser. Chrome works great! Open the developer console (right click ---> inspect) and select the Network tab. Scroll down the page and notice the images appear as you scroll.




replacing the two <script> tags in the header with the cdn URLs also works:

<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/2.2.4/jquery.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery_lazyload/1.9.7/jquery.lazyload.js"></script>
