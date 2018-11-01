iSpindle Dashboard is a Bootstrap tool to manage and visualize data about your iSpindle.
You can display Density, Temperature, Battery life, Wifi and many other things and export your database data to a csv file.
It's intended to work with a database, but you can tweak it to read data from a csv file instead.
Enjoy. -Nikko-

V 1.0.4

For now it displays data from only 1 device, could change that in the future.

ps : i'm not a dev, so the code is not clean and there's still unnecessary stuff inside.
Might clean that in the future, or might not ^^

## How to

- You need to creat the Data table inside your database, use the model inside the package
- Then inside your iSpindle configuration page, for "Service Type" use HTTP, for "Server Adress" enter your website adress (ex: mywebsite.com) and for "Server URL" your folder url (ex: /myfolder/)
- Send everything to your ftp and edit index.php file with your database informations
- You also have to edit csvexport.php file with the same informations and can change this "$f = fopen('php://memory', 'w');" to this "$f = fopen('../csv/FILE_NAME.csv', 'w');" if you also want to export your csv to your ftp


## Licensing

- Everything is tweaked and mixed by Nikko
- Base of work by DottoreTozzi (https://github.com/DottoreTozzi/iSpindel-TCP-Server)
- Dashboard base code by Creative Tim (https://www.creative-tim.com/)
  | Licensed under MIT (https://github.com/creativetimofficial/black-dashboard/issues/blob/master/LICENSE.md)
- Charts by Highcharts (https://www.highcharts.com) and Fusioncharts (https://www.fusioncharts.com)


## Useful Links

- [iSpindel](https://github.com/universam1/iSpindel)
- [TCP Server](https://github.com/DottoreTozzi/iSpindel-TCP-Server)

