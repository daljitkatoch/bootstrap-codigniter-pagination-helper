# Bootstrap codigniter pagination helper
create a helper file in application\helpers with the name pagination_helper.php

# Need of this helper
It would make easy you to call just helper and pass the required parameter instead of doing code again and again in each page.


# How to call this helper
call the helper in by placing this code in your construct. **$this->load->helper('pagination');**

and call the function like this
**pagination($url, $rowscount, $perpage, 2);**

Where **$url** is url of the current page
Where **$rowcount** is total number of records.
Where **$perpage** number of products you want to show on one page.
Where **2** is the segment of the url.
