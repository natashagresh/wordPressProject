# Word Press Tutorial

![know nothing](https://media0.giphy.com/media/3CRHmg3VCYdb2/200_s.gif)

You have so much to learn...

**What is WordPress?**

WordPress is a free, open-source web publishing system ( in other words: a free tool to help you build websites).It is used by governments, non-profits and fortune 500 companies. 17-20% of the web is powered by WordPress. It's very useful to use, especially for companies that change their content frequently (like a newspaper website) because you dont necessarily have to touch the code but can change the content through a dashboard that only the admins have access to.

##Websites that use WordPress##

 **The New Yorker**

![New Yorker](/Images/TheNewYorker.png)

 **Beyonce**

![Beyonce](/Images/beyonce.png)

 **Star Wars Fan page**

![Star Wars](/Images/starwars.png)

##How to download WordPress##

*[This Youtube tutorial](https://youtu.be/8OBfr46Y0cQ?list=PLpcSpRrAaOaqMA4RdhSnnNcaqOVpX7qi5) was super helpful*

1. Download [**MAMP**](https://www.mamp.info/en/)

   MAMP stands for Macintosh, Apache, MySQL, and PHP. MAMP is an application you can install on your Mac which allows you to have access to a local PHP server and MySQL server. Essentially, MAMP gives you all of the tools you need to run WordPress on your machine, for development and testing purposes.

   After downloading, open MAMP. The following should turn up:

   ![mamp](/Images/mamp.png)

   **Start server** and **open Webstart page.**

2. PhpMyAdmin

   Once you have opened the Webpage -this is what you should be looking at...

   ![php](/Images/PhpMyAdmin.png)

   - Click database
   - Make a new database and give it a name

3. Download [WordPress](https://wordpress.org/)
   
   - Go to the website and download wordpress.
   - Once downloaded, open the zipfile - this should create a document folder called WordPress
   - Save this WordPress folder in a newly created folder done by MAMP. This was htdocs for us
   - After you have done this, go to /localhost:8888. This is what you should see...

   ![index](/Images/index.png)

   - Click on WordPress and this should bring you to a page to make a new configuration file.
   - Fill in the info like below (your username and password is probs going to be roots) :

   ![wordPress](/Images/wordPress.png)

   - After you have filled out all your information. You should be DONE! **Congrats, you have now downloaded WordPress**

   ![dashboard](/Images/dashboard.png)


##Themes##

Word press comes with TONS of default themes you can use when building your website, which is super helpful.

You can use WordPress to search through and install and activate their themes easily to immediately see the style added to your webpage. 

![theme](/Images/theme.png)

BUT we are unique beings and our web. dev. goals might not always fit within the lines of someone else’s template.

That is where the magic of child themes comes in handy. These come in handy when you want to use a Template for your site, but need to make some changes to it to meet your specific needs. In the event that the Template you are using gets an automatic update, all of your styling changes will be lost like tears in the rain. 

Creating a child template ensures that these updates don’t effect your site and cause you some serious trouble down the road.

A child theme is created to inherit the CSS styling of the Template you specify when creating the new template. 

You start by creating a new folder in your ‘Themes’ folder. In our example we use the theme Twenty Sixteen as the Parent theme, so we will name our new themes folder ‘twentysixteen-child’. 

In the ‘twentysixteen-child’ folder you will create an empty ‘functions.php’ file and a ‘style.css’ file.

The ‘style.css’ file is about to get all the love. You need to change the information in the commented out section at the top of the document like so. 

**Twenty Sixteen Head:**

![theme](/Images/twentySixteen.png)

**Twenty Sixteen Child Head:**

![theme](/Images/twentySixteenChild.png)

- Following these steps, you should see a new template called Twenty Sixteen Child available to activate in your WordPress Dashboard.

##Plug Ins##

**What is a Plug In?**

  Plugins in WordPress are like HEAVEN for sad web developers like ourselves. You can compare them to all of the plugins we know and love with Google Chrome. It’s kind of like that. 

  Remember when we had to do geo-tagging? There’s a WordPress plugin for that. Need a calendar in your project? Yeah, there’s a plugin for that too. 

  So how do we use them?? In the Dashboard, you can go to Plugins to see a list of your currently installed plugins and their status.

  ![plugins](/Images/PlugInsTwo.png)
 
  What you’ve got isn’t quite enough? Classic human. Well good news, it’s super easy to install new plugins. Just go to Add New under Plugins in your dashboard and brose the seemingy endless possibility of plugin options, hit install and activate! So easy !

  ![plugins](/Images/PlugIns.png)

  [This](https://deliciousbrains.com/using-composer-manage-wordpress-themes-plugins/) page gives you tools on how to use Git and WordPress together












   



