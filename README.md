This project is created to convert open source materials to kindle supported format (`.mobi`)

The conversion is limited to open source licensed books. This project does not include any generated `.mobi` files and only includes the `.recipe` file for Calibre.

# About calibre recipes

[Calibre](http://calibre-ebook.com/) is a free electronic book management tool. It allows the generation of e-book through scraping RSS or HTML contents. It can be done through a Calibre recipe (in Python). For more details of Calibre recipe kindly refer to [Calibre Manual](http://manual.calibre-ebook.com/news.html)

List of Recipes in `calibre-recipes` Folder

## English
+ AOSABook.recipe - [The Architecture of Open Source Applications](http://www.aosabook.org/en/index.html)
+ Computer_Science_from_the_Bottom_Up.recipe - [Computer Science from the Bottom Up](http://www.bottomupcs.com/index.html)
+ CS183_Peter_Thiel.recipe - [Notes Essays—Peter Thiel’s CS183: Startup](http://blakemasters.com/peter-thiels-cs183-startup)
+ Designing_Evolvable_Web_APIs_with_ASP_NET - [Designing Evolvable Web APIs with ASP.NET](http://chimera.labs.oreilly.com/books/1234000001708)
+ Dive_Into_Python_3.recipe - [Dive Into Python 3](http://www.diveintopython3.net/)
+ Explore_Flask.recipe - [Explore Flask](http://exploreflask.com/)
+ Forecasting_Principles_and_Practice.recipe - [Forecasting Principles and Practice](http://otexts.com/fpp/)
+ Git_Pocket_Guide.recipe - [Git Pocket Guide](http://chimera.labs.oreilly.com/books/1230000000561)
+ High_Performance_Browser_Networking.recipe - [High Performance Browser Networking](http://chimera.labs.oreilly.com/books/1230000000545/index.html)
+ Introduction_to_Linux.recipe - [Introduction to Linux](http://tldp.org/LDP/intro-linux/html/)
+ Learn_Python_the_Hard_Way.recipe - [Learn Python The Hard Way, 3rd Edition](http://learnpythonthehardway.org/book/)
+ Learn_Vimscript_the_Hard_Way.recipe - [Learn Vimscript the Hard Way](http://learnvimscriptthehardway.stevelosh.com/)
+ Mastering_Perl.recipe - [Mastering Perl](http://chimera.labs.oreilly.com/books/1234000001527)
+ Programming_JavaScript_Applications.recipe - [Programming JavaScript Applications](http://chimera.labs.oreilly.com/books/1234000000262)
+ Python_Cookbook.recipe - [Python Cookbook](http://chimera.labs.oreilly.com/books/1230000000393)
+ SICP.recipe - [Structure and Interpretation of Computer Programs](http://mitpress.mit.edu/sicp/full-text/book/book.html)
+ Test_Driven_Web_Development_with_Python - [Test-Driven Web Development with Python](http://chimera.labs.oreilly.com/books/1234000000754)



## Simplified Chinese
+ A_Mathematical_Theory_of_Communication.recipe - [通信的数学理论](http://www.ituring.com.cn/minibook/611)
+ AngularJS_Tutorial_Cn.recipe - [AngularJS入门教程](http://www.ituring.com.cn/minibook/303)

# Usage

## GUI

1. Install Calibre [Download](http://calibre-ebook.com/download)
2. Go to `Fetch news`, `Load recipe from file` to add your recipe.
3. Go to `Fetch news`, `Schedule news download`, `Custom`, select the recipe added in step 1 and click `Download Now`
4. For more details, kindly refer to [Calibre Manual](http://manual.calibre-ebook.com/news.html)

## Terminal

1. Install Calibre

   * Archlinux

   ```bash
   pacman -S calibre
   ```

   * Debian/Ubuntu

   ```bash
   apt-get install calibre
   ```

   * RedHat/Fedora/CentOS

   ```bash
   yum -y install calibre
   ```

   * Mac OSX - Requires [Command Line Tool] (http://manual.calibre-ebook.com/cli/cli-index.html)。

3. Execute the following command in `calibre-recipes` folder

   ```bash
   ebook-convert xxx.recipe xxx.mobi
   ```

   For example

   ```bash
   ebook-convert AOSABook.recipe AOSABook.mobi
   ```

   It will generate `AOSABook.mobi` in the same folder.

# Contributor
```bash
authors:
19   ericzhang               50.0%
9    lord63                  23.7%
5    Eric Zhang              13.2%
3    Sian Lerk Lau           7.9%
1    ljhero                  2.6%
1    soooldier               2.6%
```
