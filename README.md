*See [jquery/jquery](https://github.com/jquery/jquery) for the original Github project.*

This project contains an AJAX-only branch which generates a custom build of jQuery.

To generate the jQuery files,

1. Clone out the git repo

        git clone https://dtjm@github.com/dtjm/jquery.git

2. Check out the `ajaxonly` branch or one of the `x.x.x-ajaxonly` tags.

        git checkout ajaxonly

2. Run `make`

        make
    
3. The files will be in the `dist` folder.
