# General Settings

> In this section you can configure all the General options of the site that are applied site-wide.
> All the General Settings of the site can be found under the admin menu `Appearance -> Customize`.
> Inside this Section you can find all options separated into different sub-sections. Here are all the sub-sections: 


1. Site Identity
1. Menus
1. General Settings
1. Widgets
1. Contact Details
1. Homepage Settings
1. Script Tags
1. Additional CSS - Place to add your custom CSS in case you want to override the default CSS for part of the site.


### Site Identity
-------------------

> In this section you can configure all the basic site identity options like Main Logo, Footer Logo, Site Title, etc. 


Head to `Appearance -> Customize` and then choose the `Site Identity` Menu.

Here you have the ability to change the Main logo which is used at the header of the site, Footer logo that is used at the footer of the site, Site Title and Tag line which are used for general SEO purposes, Footer copyrights which are placed at the footer socket of the site and the Site icon which is used as a favicon on the browser tab.

The images format can be pretty much everything from jpg, jpeg, png, svg and gif but it is always better to use SVG format because they leave very small footprint in terms of byte size on the site. Other good alternative is PNG because it provides the ability for logos with transparency so they can be used in many different backgrounds other than white.

For the Site Title and Tagline, you can use pretty much everything but you still need to consider meaningful content that will help you boost your SEO.

The Site icon can be either a GIF, PNG OR SVG and needs to be at least 512x512 px in size for pixel based image formats like GIF or PNG. SVG doesn't need any specific pixels as it is vector based format.
Of course you can use smaller resolution images like 128x128 or even 64x64 but this will make the logo more blurry and less high resolution for retina screens. 





### Menus
-------------------

Here you can set your different menus that are used across the site. Currently we use 5 different menus. 
One is used in the header and it is named `Primary Menu` and there are 4 others that are used at the 4 different columns in the footer of the site named `Footer Menu 1-4`

From this section you can create your different menus and you can also configure the menus from `Appearance -> Menus` as well.

From both within the Customizer options or Menus, you can set the order of the menu items or even delete, add or edit a menu item.

Here you can find some useful docs on how to manage your WordPress Menus:

* https://en.support.wordpress.com/menus/
* https://www.wpbeginner.com/beginners-guide/how-to-add-navigation-menu-in-wordpress-beginners-guide/ 

 

### General Settings
--------------------

This sub-menu is used to store all General settings of the site. Currently we only have one option but it can be further extended in the future if we wish to add more items.

The only option for now is a dropdown to set the careers page. This option is used inside each individual career page so we can dynamically set the main career page to be used from the `Back to careers page`.

If you want to test this option head to `Careers page` and choose one open position. When you choose one open position, you will be redirected to the details page of this opened position. At the top of this page you can find a link that points back to the careers page.

If you are not planning to change the careers page, then it is recommended to leave this option intact.


### Widgets
--------------------

Widgets are sections across the site where you can add different Widgets to make the site more dynamic.
Currently we use 1 Widgetized area which acts as a container to add the 4 different menu items in the footer. 

Please note that you can add pretty much everything there, from static text, images, menu items and other custom widgets.

Here you can find some useful docs on how to manage your WordPress Widgets:

* https://wordpress.org/support/article/wordpress-widgets/
* https://www.wpbeginner.com/glossary/widgets/
* https://www.youtube.com/watch?v=zx258_5Vv9Y


### Contact Details
--------------------

This section holds all the company details that are used across the site and on different sections like the `Contact` page.

Options that you can modify/configure are the following ones:

* Company Name
* Address
* State
* Phone Number
* Secondary Phone Number
* Email Address
* Map


More of these items are pretty self-explanatory but some of them are not.
For example, the Phone Number secondary is used in the contact page to populate the second phone number `Phone: 855-IMI-POGO (855.464.7646)` 

And the map is used to show the map at the bottom of the same page. If you want to change the map, head to `https://www.google.com/maps`, type your address and then press the `Share` button. After this option choose `Embed a map` instead of the first option and copy the code that is provided by Google maps over to the respective field inside WordPress Customizer. 

More info about the Contact page at the respective section.
 

Here you can find some useful docs on how to manage your Map:

* https://embedgooglemaps.com/en/how-to-embed-google-maps-into-your-website/
* https://support.google.com/maps/answer/144361?co=GENIE.Platform%3DDesktop&hl=en



### Homepage Settings
---------------------

The only option inside this page is to set which page will be served as the Homepage. Currently it is set to the Homepage but if you decide to create a new homepage in the future and set this new page as your Homepage, just head to this section and choose the new page from the dropdown.




### Script Tags
--------------------

In this section you can configure any of the most popular script tags on your site and there is no need to do that with any 3rd party plugin.
This section supports for now the current scripts:

* Google Analytics Tracking Code
* Google Tag Manager Tracking Code
* Facebook Pixel Code

You just have to add only the unique id generated by your service and NOT the whole script tag. So for example for Google Analytics you just have to add `UA-147648636-2` and nothing else.
Everything else is done programmatically.

Here you can find some useful docs on how to manage your script tags:

* https://support.google.com/analytics/answer/7476135?hl=en
* https://support.google.com/analytics/answer/1008080?hl=en
* https://www.youtube.com/watch?v=dNtciz-7Ips
* https://www.analyticsmania.com/post/google-tag-manager-id/
* https://www.analyticsmania.com/post/google-tag-manager-id/
* https://www.googleadservices.com/pagead/aclk?sa=L&ai=DChcSEwiAlpCN9svmAhUO5HcKHe3XDY8YABAAGgJlZg&ohost=www.google.com&cid=CAESQeD2fihacPS1JJgx6N86QvbUEBrJCC94BRPnhlNtWRdqGXtJJudPxublugJZHwhDpKH39wEfUzM8HG0UcTLLJ4qb&sig=AOD64_1uYgwxS8jpHDvZpDl-mURx_X_W7w&q=&ved=2ahUKEwi1voeN9svmAhXLZ1AKHbtWBZYQ0Qx6BAgOEAE&adurl=
* https://www.facebook.com/business/help/952192354843755




### Social Media Icons
----------------------


In this section you can set your social media accounts. The only option needed for every social network is the link to your official page.
The social media networks supported are the following ones:

* Facebook
* Twitter
* Instagram
* Linked in
* Youtube

If you wish to add more social networks, this must be done programmatically as an additional request after hand off of the project.
Please note that there is a checkbox on this section named `Show Social Media Icons` which means that even if you have your social media network links saved, these will only be visible at the footer of the site if you have this option checked. 



### Additional CSS
--------------------

This section is used in case you want to override some CSS of the site and you don't want to mess with theme files.
Due to the reason that the CSS on the site is compiled into a minified version, it is always recommended if you are not a theme developer or WordPress expert in general, to not touch those files

Here you can find some useful docs on how to add additional css to your site:

* https://en.support.wordpress.com/custom-design/editing-css/
* https://themeisle.com/blog/css-in-wordpress/
* https://www.hostinger.com/tutorials/wordpress-custom-css
