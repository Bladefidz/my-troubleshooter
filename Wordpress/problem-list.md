WP Troubleshooter List
======================

### Remove Unwanted <p> Tags
Quick steps:
* Go to wp-includes folder
* Seek and open default-filters.php
* comment this line:
~~~
add_filter( 'the_content', 'wpautop');
~~~
More Info: [wordpress.org](https://wordpress.org/support/topic/unwanted-ltpgt-tags-added-to-pages)