# Careers Page Settings

> In this section you can configure the Careers page and how to populate content inside this page.


This page consists of two different options. One is a `Careers` Custom Post Type which can be found at the backend of the site and is used to add, edit or remove job positions.

Just head to the backend of the site and choose the `Career` menu from the admin sidebar. Inside this page you can see all leadership members and you have the following actions (delete, add new or edit existing member).

The options that each individual career position supports are the following ones:

* Name (which is the title of the post type)
* Summary (which is the summary content inside the CPT: Careers Options)
* Different career info separated into different sections

The reason that we have this last section into different sub-sections is to programatically render the different sections at the front end.
You can see the different sections with their respective names like `Position Description`, `Position Qualifications`, etc. Just add individual rows which represent a list item at the front end.


To populate content at this page just head to `Pages -> All Pages` and choose `Careers` page.

Inside this page you can find a normal text and a custom block which is named `Careers List`. If you choose this block, you will see some options at the right hand sidebar.
The options that you have is to fetch data from the Careers Custom Post type and the only ability for you is to add/remove or re-order items. Everything else is done programmatically at the front end.
