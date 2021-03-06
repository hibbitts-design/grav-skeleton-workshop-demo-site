---
title: Home
process:
    twig: false
---

# Grav is Running!
## You have installed **Grav** successfully

Congratulations! You have installed the **Grav Demo Site** that provides a **simple page** and the default **Antimatter** theme to get you started.

>>> If you want a more **full-featured** base install, you should check out other [**Skeleton** packages available for download](http://getgrav.org/downloads).

### Find out all about Grav

* Learn about **Grav** by checking out our dedicated [Learn Grav](http://learn.getgrav.org) site.
* Download **plugins**, **themes**, as well as other Grav **skeleton** packages from the [Grav Downloads](http://getgrav.org/downloads) page.
* Check out our [Grav Development Blog](http://getgrav.org/blog) to find out the latest goings on in the Grav-verse.

### Edit this Page

To edit this page, you can either use the already installed [Admin Panel](../../admin) plugin (accessed by adding '/admin/ to the URL of your **Grav** site) or work with files directly using a text editor of choice such as [Atom.io](http://atom.io) or [Adobe Brackets](http://brackets.io).

**Admin Panel**  
![Image of Grav Admin Panel](admin-panel-pages.png?resize=600,400)  
Press on the **'[Pages](../../admin/pages)'** button on the left-hand toolbar and then choose the **'[Home](../../admin/pages/home)'** page.

**Working with Files**  
Navigate to the folder you installed **Grav** into, and then browse to the `user/pages/01.home` folder and open the `default.md` file in the text editor of your choice. You will see the content of this page in [Markdown format](http://learn.getgrav.org/content/markdown).

### Create a New Page

**Admin Panel**  
1. In the **'[Pages](../../admin/pages)'** panel press the **'Add Page'** button and then enter `My Page` as the **Page Title**. Make sure that the **Page Template** is set to `Default`.  
2. Enter the below page content of your choice on the newly created page, and then tap the `Save` button:

        # My New Page!

        This is the body of **my new page** and I can easily use _Markdown_ syntax here.

Pages in **Grav** can also include the content of other pages (i.e. Modular pages).

**Working with Files**  
1. Navigate to your pages folder: `user/pages/` and create a new folder.  In this example, we will use [explicit default ordering](http://learn.getgrav.org/content/content-pages) and call the folder `06.another-page`.
2. Launch your text editor and paste in the following:

        ---
        title: Another Page
        ---
        # Another New Page!

        This is the body of **a new page** and I can easily use _Markdown_ syntax here.

3. Save this file in the `user/pages/06.another-page/` folder as `default.md`. This will tell **Grav** to render the page using the **default** template.
4. That is it! Reload your browser to see your new page in the menu.

### Work with Media

**Grav** has a lot of built-in media capabilities, with even more capabilities available by using available plugins.

For example, to display a clickable thumbnail which can be pressed on to view the image at full size use the following:

        ![Sample Image](sample-image.jpg?lightbox=533,400&resize=266,200)

Click on the below image to see the result:   
![Sample Image](sample-image.jpg?lightbox=600,400&resize=200,200)  

Here is another example of built-in media processing, this time cropping an image:

        ![Sample Image](sample-image.jpg?crop=150,100,200,200)

And here is the actual cropped image:  
![Sample Image](sample-image.jpg?crop=150,100,200,200)

Learn more about Grav's media capabilities in the [Media](https://learn.getgrav.org/content/media) section of the [Learn Grav](http://learn.getgrav.org/) site.  

### Shortcodes

Just like WordPress, Grav can also support shortcodes - short bits of code that can be included in your Markdown to provide additional elements within your content.

Here is an example of the Tabs element, using the Shortcode UI plugin:

[ui-tabs position="top-left" active="0"]
[ui-tab title="First Tab"]

This is the content of the **first** tab panel.

[/ui-tab]
[ui-tab title="Second Tab"]

This is some different content for the **second** tab panel.

[/ui-tab]
[/ui-tabs]

Ready for more? Explore this site to see a [Modular page](/modular) created by a [Page Collection](https://learn.getgrav.org/content/collections), another [Modular page](/modular-page-inject) using the [Page Inject Plugin](https://github.com/getgrav/grav-plugin-page-inject), and a [Blog page](/blog) created by a [Page Collection](https://learn.getgrav.org/content/collections).
