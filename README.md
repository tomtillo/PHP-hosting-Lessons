# PHP-hosting-Lessons

These are some of the things you will invariably use after setting up your own PHP site from scratch 

### Redirection 
Configure you .htaccess to enable redirection 


### Session Variables 
Passing session variables from one page to other using session Variables

### Lots of Traffic 
Once you set up your 
1. Set up your robots.txt
2. Find who is visiting your site ( USER_AGENT)
```
$user_agent = $_SERVER['HTTP_USER_AGENT']; 
```
The result might look like this .
````
HTTP_USER_AGENT = Mozilla/5.0 (Windows NT 6.1; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/61.0.3163.100 Safari/537.36
````
or sometime when Google Bots crawl your page - 

``` HTTP_USER_AGENT = Mozilla/5.0 (compatible; Googlebot/2.1; +http://www.google.com/bot.html) ```

or Bing bots come to your site.

``` HTTP_USER_AGENT = Mozilla/5.0 (compatible; bingbot/2.0; +http://www.bing.com/bingbot.htm) ```

Usually this means - Its a browser and a normal browsing session. 
**Remember -** - The USER_AGENT string can be faked by a script ( by explicitly writing it into its header )

### SEO Tips


### Redirect problems in Chrome - The nasty favicon.ico call by browser
Check out the simple solution to this- 
https://stackoverflow.com/questions/27344435/chrome-favicon-ico-get-request
