# High Level Overview

## Description

This lesson is an introduction to WordPress for people who have heard of it, but are not quite sure what it does or if it is the right tool for them. You will learn about the origins of WordPress and its evolution from a blogging platform to a full fledged content management system. We will also look at some of its components and how they are used to build a functional website. Finally, we will talk about the third party services you will need to operate a self-hosted WordPress site.  

## Objectives

At the end of this lesson, you will be able to:

*   Outline and describe the basic history of WordPress.
*   Identify the differences between WordPress.com and WordPress.org.
*   Explain the advantages of self-hosting.
*   Distinguish the various roles involved in a WordPress site.
*   Identify and explain the various building blocks of WordPress.

## Prerequisite Skills

You will be better equipped to work through this lesson if you have experience in and familiarity with:

*   Basic familiarity with a computer
*   Basic familiarity with a web browser
*   General understanding of how the Web works, as a user

## Assets

*   None

## Screening Questions

*   Do you have an interest or involvement in building a website?
*   If yes, would you like to learn more about how websites are built using WordPress software?

## Teacher Notes

*   **Time Estimate:** 30 minutes
*   Words in _italics_ have meaning specific to WordPress or the Internet that are useful for students to know. Only the first instance of these words is italicized.
*   The preferred answers to the screening questions is “yes.” Participants who reply “no” to all either of the questions may not be ready for this lesson.

## Hands-on Walkthrough

### WordPress Origins

WordPress was first released in May 2003 as a blogging application. It was an adaptation (known in the programming world as a _fork_) by Matt Mullenweg and Mike Little of another program called b2/cafelog. 

The word _Blog_ is a contraction of the earlier term _Web Log_. In 2003, blogs were simple websites with a single purpose: display journal entries called _posts_ in reverse chronological order with the most recent at the top. These posts could include text, images, and links. 

One of the key decisions that Matt and Mike made for WordPress was to release it as _open source software_. This means that the software - including the underlying programming code - is licensed for anyone to freely use, copy, and modify in any way they choose. This is in contrast to _proprietary software_, where the software is under restrictive copyright and the source code is usually hidden from the users. 

Matt Mullenweg also founded a company, _Automattic_, which owns and operates WordPress.com (more on that later). In 2010, Automattic transferred the WordPress trademark to the nonprofit _WordPress Foundation_, which operates WordPress.org, manages the WordPress core software, and hosts the official directories of themes and plugins.

### What Is a Content Management System?

When WordPress was released in 2003, the majority of websites were programmed by hand, using a text markup language called _Hypertext Markup Language_ (_HTML)_. While HTML isn't a complex programming language, it does present a barrier to entry for many people who want to publish online. _Content Management Systems_ (_CMS)_ were created to eliminate the need for any kind of programming by the users of a web publishing system. 

The user interface of a CMS for editing web pages looks similar to a word processor. There are controls for formatting text and adding links. Writing tools like spell checking and undo are included. And because web pages need pictures, the CMS is also capable of adding, positioning, and sometimes editing images. 

There are other requirements of a CMS that are unlike those of a word processor:

*   It needs to allow the creation of new web pages and adding them into a navigation system that is visible on the _public-facing_ website.
*   More than one person at a time can use a CMS. It has to include a mechanism to prevent people from overwriting each other's work. Often, this includes a versioning system that makes it possible to compare changes and return to an earlier version of a page if necessary.
*   Each person using a CMS needs a way to sign in and manage their own account.
*   People need to have different levels of permission to make changes, which are called _roles_. While some may be allowed to create and publish new content, others may be restricted to writing or viewing only.

### What Is the Difference Between WordPress.org and WordPress.com?

The same core WordPress software is deployed in two very different ways through WordPress.com and WordPress.org. 

WordPress.com is both a website and a business. You can create a free account on WordPress.com and have access to a _hosted_ version of WordPress on which you can create a website. With a hosted version, the hosting company takes responsibility for maintaining the server and WordPress installation, relieving you of that burden so you can solely create useful content. 

WordPress.com makes money by charging for feature upgrades. For example, if you want to use your own domain name on a WordPress.com site, there is a small fee to do so. There are also many companies that pay WordPress.com to host very large WordPress installations, such as BBC America, The New Yorker Magazine, and the official Star Wars Blog. 

Because WordPress.com has to support many different sizes and types of sites, they are fairly restrictive when it comes to customizing individual sites. There are only a fixed number of _themes_ (site templates) that determine the look-and-feel of their sites, as well as a small number of _plugins_ (software modules) that provide different types of functionality. 

WordPress.org is the official website for _self-hosted_ WordPress installations. Self hosting means that you have downloaded a copy of the WordPress software and installed it on a _server_, which is a computer with special software that lets you serve websites and other data to users through the internet. This server could be an old PC in your basement (which is not really recommended) or in a high-tech data center. It's up to you. A self-hosted installation of WordPress enables you to create a website that you fully own and control, and you are completely responsible for configuring and maintaining the WordPress installation.

### Advantages of Self-Hosting

You may be asking at this point, why go to all the trouble of self hosting when you can use the same software for free over at WordPress.com? Here's a short list of the benefits of a self-hosted WordPress installation:

*   **Control.** From the very beginning, you choose where your site lives, what it looks like, how it is configured, and what it can do. Almost every web hosting service in the world supports WordPress, many of them offering _one-click installation_. If you become unhappy with your current host, you can easily pack up and move your site somewhere else.
*   **Flexibility.** WordPress.com offers only a handful of themes, but there are nearly 5,000 themes in the WordPress.org repository. When you want to add to the functionality of your WordPress site, there are almost 50,000 plugins there as well, almost all of them free.
*   **Community.** Because WordPress has its roots in open source, there is a huge community of people contributing to its development and sharing their knowledge. You'll find a multitude of blogs, forums, and classes like this one devoted to helping users at all levels. And since WordPress is the most widely used CMS in the world, if you decide to hire a professional to help you, you'll have no trouble finding one.
*   **A thriving marketplace.** Although WordPress itself is free, open source software, an entire industry has sprung up around delivering services to WordPress site owners. You may choose to pay for these _premium_ services for the support that they provide and the professionalism that they bring to their products. While there are many excellent free themes and plugins available on WordPress.org, their developers are under no obligation to keep them updated or provide any kind of customer support. The fact than many of them do is one of the great things about the WordPress community.

### WordPress Permissions

There are levels of _permissions_ that allow site visitors and administrators to access different parts of a WordPress site. In most cases, visitors who arrive at a site by clicking a link or typing the site's URL into their browser are known as _anonymous_ users. They see only the front end, or public-facing part of the site, which allows them by default to view the posts and pages. If they have an _account_ on the site (in other words, they have a username and password), they can be given varying levels of access to the WordPress administration panel beyond reading site content. Here is a summary of the roles built in to WordPress, from the most to least restrictive:

*   **Subscriber** – somebody who can only manage their profile.
*   **Contributor** – somebody who can write and manage their own posts, but cannot publish them.
*   **Author** – somebody who can publish and manage their own posts.
*   **Editor** – somebody who can publish and manage posts, including the posts of other users.
*   **Administrator** – somebody who has access to all of the administration features within a single site.
*   **Super Admin** (multi-site installations only) – somebody with access to the site network administration features and all other features.

When you install the single-site version of WordPress, you will automatically be assigned to the Administrator role, having full control of the site and access to all of the administrative pages. If you choose to add more users you can assign them to whatever role is appropriate. Administrators have access to many settings and sections of the administration panel that could break the website if they are configured incorrectly, so make sure that any users that are assigned Administrator permissions can be trusted with this level of access. In general, you should assign a specific user the most restrictive role that assigns the permissions that they need. Besides protecting the site and its content, it simplifies the admin back-end interface for the more restricted roles.

### WordPress Building Blocks

#### WordPress Core

The WordPress core consists of all of the files that make up the WordPress application. These files are placed on a server computer, which may or may not be attached to the Internet. For the purposes of this discussion, let's assume that the server is on a hosting service. You can obtain these files in a couple of ways:

1.  Go to WordPress.org and click the "Download WordPress" button. This will download all of the files bundled together into a single _zip file_, to your local computer. You will then need to copy this file to your hosting server using either their file management tool or a separate _FTP program_. Then the zip file needs to be _unzipped_ into the appropriate location on the server for website files.
2.  A much easier process is to use the hosting service's one-click install to automatically download the WordPress files, put them in the right place, create a database, and do all of the associated initial site configuration. This process takes you right up to creating your own Administrator account.

WordPress is written in a programming language called PHP. That's why many of the core files have the .php _file extension_. Except in very unusual cases, you should **never edit the core files**. When you want to make changes to the way WordPress behaves, it should be done by editing your site's theme - or preferably _child theme_ - files. How to make these changes goes beyond the scope of this class, but there are more advanced classes that go into it in detail.

#### Database

All of the data about your site - including all text content - is stored in a _MySQL_ database. This database is automatically created when you use a one-click install. If you are uploading the core files yourself, you will also need to create this database and enter information about it into a special configuration file, called wp-config.php, in the root directory of your installation. Making changes to this file is one of the few exceptions to the "never edit the core files" rule. 

Other than knowing that the database exists, there isn't anything that you need to know to maintain it. If you suspect a problem with your WordPress database and haven't worked with databases before, it's probably best to contact your hosting service's tech support department for assistance.

#### Theme

Everything about the way your WordPress site appears in the browser, including its layout, colors, and fonts, is controlled by its theme. There are thousands of themes available around the web, both free and paid. If you're going to use a free theme, I recommend using the official theme repository on WordPress.org. The reason is that all of the themes there have been reviewed against a set of guidelines that include code quality, security, licensing, and documentation. It's unfortunate but true that some free themes that do not come from WordPress.org have been purposely infected with malware or have simply been coded insecurely. 

In the theme repository, you can search for themes by color, number of columns, layout, and features. Or you can browse the most popular or newest themes. To use a theme, it must be _installed_ and _activated_. This is easily done from the Themes menu of WordPress administration area. 

Once a theme is activated, it may include features such as changing colors or layouts. The documentation for the theme will describe all of these options. There's nothing wrong with trying out as many themes as you like before settling on the best one for your site. 

There is an also subset of themes known as child themes. A child theme is a theme that inherits the functionality of another theme, called the _parent theme_. Child themes allow you to modify or add to the functionality of the parent. A child theme can be created from any theme and using one will prevent changes that you make from being lost if you update the parent theme. 

If you're using a child theme, note that both the child and parent themes need to be installed, but that only the child will be activated.

#### Plugins

If themes control how your site looks, plugins control what it does. Plugins are software modules that work with the WordPress core to make your site do everything from e-commerce to photo slideshows. 

As with themes, the best place to find free plugins is in the WordPress.org plugin repository. You can search for the type of plugin that you're looking for and read descriptions and reviews of those available. A few suggestions on selecting plugins:

*   Look for those with large numbers of positive reviews, downloads, and ratings. A plugin with a 5-star rating and 100 downloads may not be as good as a one with a 4-star rating and 100,000 downloads.
*   Look for those that are compatible with the current version of WordPress and have a recent "last updated" date. That indicates that the plugin is under active development.
*   Click the "Support" link and see what kind of problems users are reporting. All software has bugs, but make sure that the plugin you are planning to use isn't crippled by them.

Some plugins are built on a _freemium_ model. This means that a basic version of the plugin is provided for free, but that more advanced or add-on features are available for a fee. Make sure that you read the descriptions carefully to see what, if any, paid features you will want to use. And like themes, you can always try out multiple plugins before settling on one that best meets your needs.

### Services You Will Need

#### Domains

To host your own WordPress site, you will need a _domain name_. These are the unique names that end in .com, .org, .net, or any of the other available extensions. These extensions are actually called _top level domains_ (_TLD)_. Domains are registered and managed through companies called _domain registrars_. 

Every domain name must be unique, which is why it can be so hard to find one that is short and memorable in the most common TLDs. Recently, a whole slew of new TLDs have been created including .computer, .dating, .gift, and yes, .pizza. Most people try and stick with .com, especially for a business, because it is what people are most used to and find easiest to remember. 

Once you find an available domain name, you will need to register it. During this process, you will be asked to designate four contacts: Registrant, Admin, Technical, and Billing. These can all be the same person or different people. Registrant and Admin are the most important, because they have the most control over the domain registration record and the approval process for how the domain is used. 

The other important setting in the domain registration is for the _nameservers_ used by the domain. Nameservers are computers on the Internet that act like address books, mapping domain names to the address of computers that host services like websites and email. When you first register a name, it will use the nameserver of the domain registrar itself. At this point, if you type the domain name into a browser, you'll probably get a "this page under construction" page, branded with the registrar's name and logo. 

If the company you've registered with is also your web hosting company, you may not need to change the nameservers. However, if the companies are different, you will need to change the nameservers (there are always at least 2 of them for redundancy) to those of the company where your WordPress site is hosted. 

Make sure that you write down the account access information for your domain registrar. Because the information there tends to be of the set-and-forget type, people often lose track of their username and password, or change email address without updating it at the registrar. Eventually, you'll need to log back into this account and there's nothing more frustrating than trying to retrieve the password for an account that was set up by someone whose email address no longer exists.

#### Web Hosting

Web hosting companies provide space on their computers for the files and databases that make up most websites, including your WordPress site. These computers are usually located in large data centers with multiple power sources and large networks connecting them to the Internet. 

There are two main types of hosting services: _shared hosting_ and _dedicated hosting_. Shared hosting is the most common configuration since it is the least expensive, and means that you share computer hardware with many other websites but that all of these sites are all kept separate by special software. No one is able to access anyone else's site. Each shared hosting account has its own _control panel_ that lets you control various aspects of your site. This is where the "one-click install" for WordPress is found, provided that the hosting company offers it. 

Dedicated hosting means that your website is hosted on a computer that has the sole function of hosting your website. With a dedicated server, you do not share hardware with other websites. 

When selecting a web hosting company, it's a good idea to go online and look for reviews about the different companies. You want to choose one that's in your price range but that also has a good reputation for customer service and performance. 

Once you have a web host with WordPress installed and a domain name that is pointed to the host's nameservers, you're online! You can then move on to the actual business of setting up your self-hosted WordPress site.  

## Exercises

N/A  

## Quiz

**Name one of the advantages of a self-hosted WordPress installation.**

1.  Pretty fonts
2.  Control over hosting location and configuration
3.  Choose from many top level domains
4.  Make changes to core files

**Answer:** 2\. Control over hosting location and configuration

* * *

**If you have limited computer skills and want to focus on creating comment, which type of hosting should you use?**

1.  WordPress.com managed hosting
2.  Self-hosting

**Answer:** 1. WordPress.com managed hosting

* * *

**When registering a domain name, be sure to:**

1.  Choose a domain name of less than 10 characters
2.  List a Technical Contact who understands computers
3.  Hire a developer
4.  Remember your username and password

**Answer:** Remember your username and password

## Additional Resources

[WordPress Features](https://codex.wordpress.org/WordPress_Features) @ Codex
