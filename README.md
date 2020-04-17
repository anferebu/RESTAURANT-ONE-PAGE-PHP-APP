# Restaurant-One-Page-PHP-App

Web PHP App designed for a Restaurant.  the App can interact with the browser dynamically rewriting the current web page with new data from the web server, instead of loading entire new pages.  Using the navigation buttons, the user will be able to see the Home page, the Team, the Menu (When the user enters to the menu, the user will be able to click every dish in the menu and see its description, price, suggested drink and suggested tip).  Finally in the contact option, the user is going to see a submission form to contact the owners of the business and send a message to them.

A warning message in the footer of the page, informs the user if the restaurant is open or closed (When the restaurant is open, the message appears in green color and when the restaurant is closed the restaurant appears in red color).  The implementation of this function is possible using the php-store-hours-master class that updates and calculates automatically the current time, depending of the geographical location of the Restaurant.  This class is an open-source class and its available for developers online.

<strong>INSTRUCTIONS</strong>

1. In order to be able to visualize the web application you need first to download and install XAMPP Apache server.  You can download XAMPP in the following link: https://www.apachefriends.org/download.html.

2. Install and download XAMPP (Be sure to use port: 80 to run the Apache server).

3. Start XAMPP apache server.

5. Configure the root directory of the Apache server to be compatible with the directory where you save the repository folder.  Follow the instructions:

      - Go to C:\xampp\apache\conf\httpd.conf
      - Open httpd.conf
      - Find tag : DocumentRoot "C:/xampp/htdocs"
      - Edit tag to : DocumentRoot "C:/xampp/htdocs/myproject/web"
      - Now find tag and change it to < Directory "C:/xampp/htdocs/myproject/web" >
      - Restart Your Apache

6. Download and unzip the repository folder.

7. Inside the unziped repository folder you will see the next zipped folders:
      - assets.rar
      - img.rar
      - includes.rar
      - php-store-hours-master-rar
   Unzip these folders with the option right click, extract here (please don't select the option that creates a folder with the same name).
   
8. Go to your Google Chrome and type localhost:80.  You will see the repository folder listed in an index.  Open the RESTAURANT-ONE-PAGE-APP folder and you will see inside another folder with the same name.  Click in that folder and you will be able to see the App.



The first two images show the Home page.

![HOME](https://github.com/anferebu/Restaurant-One-Page-PHP-App/blob/master/Home.jpg)

![CLICKTEAM](https://github.com/anferebu/Restaurant-One-Page-PHP-App/blob/master/ClickTeam.jpg)

The next image shows the Team page.

![TEAM](https://github.com/anferebu/Restaurant-One-Page-PHP-App/blob/master/Team.jpg)

![CLICKMENU](https://github.com/anferebu/Restaurant-One-Page-PHP-App/blob/master/ClickMenu.jpg)

The next image shows the Menu page.

![MENU](https://github.com/anferebu/Restaurant-One-Page-PHP-App/blob/master/MENU.jpg)

![DISHES](https://github.com/anferebu/Restaurant-One-Page-PHP-App/blob/master/Dishes.jpg)

The next image shows the Dishes.

![DISHES](https://github.com/anferebu/Restaurant-One-Page-PHP-App/blob/master/ClickContact.jpg)

The next image shows the contact page.

![CONTACT](https://github.com/anferebu/Restaurant-One-Page-PHP-App/blob/master/Contact.jpg)

# Author: Andrés R. Bucheli.
