# PHP Standards

It is vital we keep projects/packages all to a specific standard. Therefore an example of your PHP projects 
Direcotry structure should look like so :

**[ vendor ]**
* All composer packages you may be using


**[ public ]**
* **This** is the webroot for you to tell Apache or Nginx to load.
* We keep all publically assessible scripts and files within this directory including your `.htaccess` file and `index.php`


**[ src ]**
* All custom PHP scripts and packages you are using.
* If using a library such as TWIG the views can be stored within here, as it is then storing custom code in all one place
