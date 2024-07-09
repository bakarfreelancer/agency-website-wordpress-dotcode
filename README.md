# Dot Code

Agency Website WordPress Template - Astra Theme with Elementor

## Steps to run the website

- You have to add custom domain name in xampp before running this project on localhost, otherwise you will face some issue with links and inserted media.
- To add custom domian name to Xampp [Click here to watch detailed guide](https://youtu.be/2aYBlQeiIds?si=-O6bHe6Wn86oAkfq)
- Also the configuration text shown in the video will be available in this file.
- Download this GitHub project and extract it to get backup files. [Learn How to download GitHub Project](https://youtu.be/zVUyUFI0D3I)
- Create a website on localhost folder name will be `dotcode` [Learn how to install Xampp and WordPress](https://youtu.be/pUuWkz37whk?si=Mm7CdNdeFLy9AIdg)
- Create a database named `dotcode`
- After WordPress installation, install the plugin [`UpdraftPlus - Backup/Restore`](https://wordpress.org/plugins/updraftplus/)
- Import all zip files and restore backup.

## Xamp custom domain setting 
1. Edit `C:\Xampp\apache\conf\extra\httpd-vhosts` and add the below code

```
<VirtualHost *:80>
    DocumentRoot "C:/xampp/htdocs/dotcode"
    ServerName dotcode.test
</VirtualHost>

<VirtualHost *:80>
    DocumentRoot "C:/xampp/htdocs"
    ServerName localhost
</VirtualHost>
```
2. Then open the hosts file :  `C:\Windows\System32\drivers\etc\hosts` and add this entry at the end

     `127.0.0.1       dotcode.test`

3. Restart Xampp Apache server.
4. Open your website at [http://dotcode.test](http://dotcode.test)

   
## Home page

![Home Page](https://github.com/bakarfreelancer/agency-website-wordpress-dotcode/blob/main/home.jpeg?raw=true)


## Services Page

![Services Page](https://github.com/bakarfreelancer/agency-website-wordpress-dotcode/blob/main/services.jpeg?raw=true)

## Services Page

![Projects Page](https://github.com/bakarfreelancer/agency-website-wordpress-dotcode/blob/main/projects.jpeg?raw=true)

## Contact Page

![Contact Page](https://github.com/bakarfreelancer/agency-website-wordpress-dotcode/blob/main/contact.jpeg?raw=true)
