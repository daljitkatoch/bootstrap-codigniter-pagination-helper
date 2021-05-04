# Bootstrap codigniter pagination helper

# Need of this helper
It would make easy to you call this helper and pass the required parameter instead of doing code again and again in each page.

# Helper file location in your project
create a helper file in your project folder. **path:** application\helpers\pagination_helper.php 

# How to call this helper
You can call this helper by placing this code in the construct of class (**$this->load->helper('pagination');**) or you can also call it on the autoloader file. 

You can call this helper's function like this in your class function
**pagination($url, $rowscount, $perpage, 2);**

Where **$url** is url of the current page
Where **$rowcount** is total number of records.
Where **$perpage** number of products you want to show on one page.
Where **2** is the segment of the url.
