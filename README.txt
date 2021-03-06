***************
*YOS Version:
***************

2.0.1 03/12/2020


***************
*Support:
***************

Please write: info@youronlineshop.net


***************
*Autor Note*
***************

This program has been developed by: Alberto Melchor Herrera, melchorherrera@gmail.com. I am greateful to the people that have developed software in which I got inspiration. This version of the software is free to use and modify. I am available at the email for any support and other issues.


***************
*About*
***************

It implements an e-commerce system (Ajax and WYSIWYG). It is written in PHP (As well as HTML, CSS and JavaScript). It uses MariaDB/Mysql for a database.


**************
*Installation*
**************

If you prefer we offer YOUR ONLINE SHOP installation and hosting service for 10 eur per Year: melchorherrera@gmail.com

1 - Upload the compressed file to your web server.
2 - Unpack it to the destination folder (You may have to create it first).
3 - Create a database. You can use PhpMyAdmin for this pourpose.
4 - Edit database settings at: includes/config.php.
5 - Give write permisions to folders catalog/images/small and catalog/images/big (To allow upload product images).
6 - Also you can change some system settings at file: javascript/config.js.
7 - *** Installation Video Tutorial: https://youtu.be/eDbpvEcX95Y ***
8 - For further database control install the complement DbManager: https://sourceforge.net/projects/freshhh-dbmanager/


*****************
*Getting started*
*****************

Open the browser (chrome or firefox) at the main folder URL. The ecommerce system will appear. You must click "Initialize database" button at the very first time to fulfill the database.

There are some already created users: like "webadmin" and "ordersadmin". These are the users names, and users passwords are the same as users names.

User "ordersadmin" is order administrator and can watch and edit all the orders. Once you log in with this user click at "Show orders" button.

User "webadmin" is web administrator user and can edit the web page content, the catalog (categories and items) and the checkout process options.

There are also some other admin users: productsadmin, productseller and systemadmin.

Once editing some content press Intro or click outside of the editable area to save changes.

To reach the checkout process edition you should log in with the webadmin user and make an order as you were logged in as a normal user. Once you get to some checkout steps you should be able to edit the checkout step options. Some extra edition elements that can not be reached as a web user can be accessed by cicking the Extra Elements button that will appear at the left bar just after log in as webadmin.

For system configuration edit file javascript/config.js (check out javascript/default.js).

More information at our youtube chanel.


****************************
*Frequently Asked Questions*
****************************

------

How can I enable the paypal account for the payment process?

You must add your merchantId in the required parameter. That parameter can be accessed by getting to the checkout payment step logged in as admin.


*****************
*More*
*****************

Find us at http://www.youronlineshop.net/ for more information.

Some project documentation (Wiki): https://github.com/petazeta/youronlineshop/wiki/
