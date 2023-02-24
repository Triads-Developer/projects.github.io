{\rtf1\ansi\ansicpg1252\cocoartf2708
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\froman\fcharset0 Garamond;\f1\fswiss\fcharset0 Helvetica;}
{\colortbl;\red255\green255\blue255;\red0\green0\blue0;}
{\*\expandedcolortbl;;\cssrgb\c0\c0\c0;}
\margl1440\margr1440\vieww23440\viewh14740\viewkind0
\deftab720
\pard\pardeftab720\partightenfactor0

\f0\fs32 \cf2 \expnd0\expndtw0\kerning0
## Troubleshooting
\f1 \

\f0 \'a0
\f1 \

\f0 If the menu does not display, check the following:
\f1 \

\f0 \'a0
\f1 \

\f0 - Are the "Access administration menu" and "Use the administration pages and
\f1 \

\f0 \'a0 help" permissions enabled for the appropriate roles?
\f1 \

\f0 - Does html.tpl.php of your theme output the `$page_bottom` variable?
\f1 \

\f0 \'a0
\f1 \

\f0 \'a0
\f1 \

\f0 ## FAQ
\f1 \

\f0 \'a0
\f1 \

\f0 **Q: I want to prevent robots from indexing my custom error pages by
\f1 \

\f0 setting the robots meta tag in the HTML head to "noindex".**
\f1 \

\f0 \'a0
\f1 \

\f0 **A:** There is no need to. **Customerror** returns the correct HTTP
\f1 \

\f0 status codes (403 and 404). This will prevent robots from indexing the
\f1 \

\f0 error pages.
\f1 \

\f0 \'a0
\f1 \

\f0 **Q: I want to customize the custom error template output.**
\f1 \

\f0 \'a0
\f1 \

\f0 **A:** In your theme template folder for your site, copy the template
\f1 \

\f0 provided by the **Customerror** module
\f1 \

\f0 (i.e. `templates/customerror.html.twig`) and then make your
\f1 \

\f0 modifications there.
\f1 \

\f0 \'a0
\f1 \

\f0 **Q: I want to have a different template for my 404 and 403 pages.**
\f1 \

\f0 \'a0
\f1 \

\f0 **A:** Copy `customerror.html.twig` to
\f1 \

\f0 `customerror--404.html.twig` and `customerror--403.html.twig`. You
\f1 \

\f0 do not need a `customerror.html.twig` for this to work.
\f1 \

\f0 \'a0
\f1 \

\f0 ## Installation
\f1 \

\f0 Install as you would normally install a contributed Drupal module. For further
\f1 \

\f0 information, see
\f1 \

\f0 [Installing Drupal Modules](https://www.drupal.org/docs/extending-drupal/installing-drupal-modules).
\f1 \
}