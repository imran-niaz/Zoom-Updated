# Zoom
Zoom is a lightning fast wordpress vulnerability scanner equipped with subdomain & infinite username enumeration.. It doesn't support plugin & theme enumeration at the moment.
> What's infinite enumeration? Try enumerating usernames of cybrary.com with Zoom & wpscan (or your fav tool).

Twitter: [@bicodev](http://twitter.com/weareultimates)
Website: [Bicodev](https://Bicodev.com)

#### Usages
##### Manual Mode
``` bash
python3 zoom.py -u <wordpress website>
```
In the manual mode, you will need to specify a wordpress website to scan for vulnerabilities and to enumerate subdomains.
##### Automatic Mode
``` bash
python3 zoom.py -u <website> --auto
``` 
In the automatic mode, Zoom will find subdomains and check the ones using wordpress for vulnerabilities.

### Automatic Mode Demo
![subdomains](https://i.imgur.com/oIEtbw2.png)
![vulnerability](https://i.imgur.com/kbUyhIV.png)

#### Manual Mode Demo
![vulnerability](https://i.imgur.com/Gl9Jv78.png)
![usernames](https://i.imgur.com/gVcdDia.png)

#### License
Zoom is licensed under [MIT](https://opensource.org/licenses/MIT) license.
