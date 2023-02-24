{\rtf1\ansi\ansicpg1252\cocoartf2708
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\fnil\fcharset0 Monaco;}
{\colortbl;\red255\green255\blue255;\red93\green93\blue93;\red255\green255\blue255;\red61\green61\blue61;
\red67\green96\blue122;\red67\green67\blue67;\red39\green114\blue18;\red18\green105\blue176;\red139\green73\blue3;
}
{\*\expandedcolortbl;;\cssrgb\c43970\c43970\c43916;\cssrgb\c100000\c100000\c100000\c0;\cssrgb\c30622\c30622\c30584;
\cssrgb\c32663\c45230\c55385;\cssrgb\c33370\c33370\c33328;\cssrgb\c18710\c50858\c8834;\cssrgb\c4681\c49443\c74516;\cssrgb\c61785\c35853\c0;
}
\margl1440\margr1440\vieww23440\viewh14740\viewkind0
\deftab720
\pard\pardeftab720\partightenfactor0

\f0\fs24 \cf2 \cb3 \expnd0\expndtw0\kerning0
## Installation\cf4 \
\
Install \cf5 as\cf4  you would normally install a contributed Drupal module\cf6 .\cf4  \cf5 For\cf4  further\
information\cf6 ,\cf4  see\
\cf6 [\cf4 Installing Drupal Modules\cf6 ](\cf4 https\cf6 :\cf2 //www.drupal.org/docs/extending-drupal/installing-drupal-modules).\
\
# Administration Menu\cf4 \
\
The Administration Menu module displays the entire administrative menu tree\
\cf6 (\cf5 and\cf4  most local tasks\cf6 )\cf4  in a drop\cf6 -\cf4 down menu\cf6 ,\cf4  providing administrators one\cf6 -\cf4  \cf5 or\cf4 \
two\cf6 -\cf4 click access to most pages\cf6 .\cf4 \
\
\cf5 For\cf4  a full description of the module\cf6 ,\cf4  visit the\
\cf6 [\cf4 project page\cf6 ](\cf4 https\cf6 :\cf2 //www.drupal.org/project/admin_menu).\cf4 \
\
Submit bug reports \cf5 and\cf4  feature suggestions\cf6 ,\cf4  \cf5 or\cf4  track changes in the\
\cf6 [\cf4 issue queue\cf6 ](\cf4 https\cf6 :\cf2 //www.drupal.org/project/issues/admin_menu).\
\
## Configuration\cf4 \
\
\cf2 1\cf6 .\cf4  Enable the module at Administration \cf6 >\cf4  Extend\cf6 .\cf4 \
\cf2 1\cf6 .\cf4  When creating a \cf5 new\cf4  field on a content type \cf5 or\cf4  custom entity type\cf6 ,\cf4  choose\
   \cf7 "Double Field"\cf4  from the drop\cf6 -\cf4 down menu\cf6 .\cf4 \
\cf2 1\cf6 .\cf4  On the Field Settings form \cf5 for\cf4  the Double Field\cf6 ,\cf4  define the two subfields\
   \cf5 as\cf4  you would with any other field\cf6 .\cf4 \
\cf2 1\cf6 .\cf4  Optionally\cf6 ,\cf4  on the \cf7 "Edit"\cf4  form \cf5 for\cf4  the Double Field\cf6 ,\cf4  you may choose\
   options \cf5 for\cf4  whether \cf5 or\cf4  not the subfields are \cf7 "required"\cf6 .\
\
\cf2 ## Troubleshooting\cf4 \
\
\cf5 If\cf4  the menu does not display\cf6 ,\cf4  check the following\cf6 :\cf4 \
\
\cf6 -\cf4  Are the \cf7 "Access administration menu"\cf4  \cf5 and\cf4  "\cf5 Use\cf4  the administration pages \cf5 and\cf4 \
  help" permissions enabled \cf5 for\cf4  the appropriate roles\cf6 ?\cf4 \
\cf6 -\cf4  Does html\cf6 .\cf4 tpl\cf6 .\cf4 php of your theme output the `\cf8 $page_bottom\cf4 ` variable\cf6 ?\cf4 \
\
\
\cf2 ## FAQ\cf4 \
\
\cf6 **\cf4 Q\cf6 :\cf4  I want to prevent robots from indexing my custom error pages by\
setting the robots meta tag in the \cf9 HTML\cf4  head to \cf7 "noindex"\cf6 .**\cf4 \
\
\cf6 **\cf4 A\cf6 :**\cf4  There is no need to\cf6 .\cf4  \cf6 **\cf4 Customerror\cf6 **\cf4  returns the correct \cf9 HTTP\cf4 \
status codes \cf6 (\cf2 403\cf4  \cf5 and\cf4  \cf2 404\cf6 ).\cf4  This will prevent robots from indexing the\
error pages\cf6 .\cf4 \
\
\cf6 **\cf4 Q\cf6 :\cf4  I want to customize the custom error template output\cf6 .**\cf4 \
\
\cf6 **\cf4 A\cf6 :**\cf4  In your theme template folder \cf5 for\cf4  your site\cf6 ,\cf4  copy the template\
provided by the \cf6 **\cf4 Customerror\cf6 **\cf4  module\
\cf6 (\cf4 i\cf6 .\cf4 e\cf6 .\cf4  `templates\cf6 /\cf4 customerror\cf6 .\cf4 html\cf6 .\cf4 twig`\cf6 )\cf4  \cf5 and\cf4  then make your\
modifications there\cf6 .\cf4 \
\
\cf6 **\cf4 Q\cf6 :\cf4  I want to have a different template \cf5 for\cf4  my \cf2 404\cf4  \cf5 and\cf4  \cf2 403\cf4  pages\cf6 .**\cf4 \
\
\cf6 **\cf4 A\cf6 :**\cf4  Copy `customerror\cf6 .\cf4 html\cf6 .\cf4 twig` to\
`customerror\cf6 --\cf2 404\cf6 .\cf4 html\cf6 .\cf4 twig` \cf5 and\cf4  `customerror\cf6 --\cf2 403\cf6 .\cf4 html\cf6 .\cf4 twig`\cf6 .\cf4  You\
\cf5 do\cf4  not need a `customerror\cf6 .\cf4 html\cf6 .\cf4 twig` \cf5 for\cf4  this to work\cf6 .}