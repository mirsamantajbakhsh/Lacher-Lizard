
![](./Lacher_Lizard_Logo.png)

# Security Crawler

## About
_security crawler can crawling all urls of website by set in seed(website url), extract signature(pattern) each of them and choose uniqe signtures as target for penterate...at least you can test sql injection or xss for target urls...or you can improve it :)_

## SIGN MEANS
_abc.com/news/123da224/%8c%4d../weather-middle-east  => abc.com/news/randnum/encoded/title_

## FrameWorks & APPS
_crawler core written from bucky roberts Spider's (Most of it changed) and sql injection & xss testing with sqlmap and arachni scanner framworks_<br />

_Spider_[ GitHub ](https://github.com/buckyroberts/Spider)<br />
_Sqlmap_[ GitHub ](http://sqlmap.org/)<br />
_Arachni_[ Site ](https://www.arachni-scanner.com/)<br />


## About US
_I'm **Ali Farhadian** who are responsible for coding of this Thesis project at **Urmia University of Technology** (UUT)_<br />
_This project is under the supervision of Dr. **Mir Saman Tajbakhsh**._<br />

* **Ali Farhadian** [ GitHub ](https://github.com/alifrd)<br />
* **Mir Saman Tajbakhsh** [ Personal Website ](https://mstajbakhsh.ir/) &nbsp;      [ GitHub ](https://github.com/mirsamantajbakhsh)<br />
* **Urmia University of Technology (UUT)** [ Website ](http://uut.ac.ir/)<br />

## config file
_at ./config file in config.json_<br />
<pre>
    * ProjectName : name of project<br />
    * URL : url of project<br />
    * Setting<br />
        * Mode : SLOW / FAST (explore repeated urls signutre or repeated signture)<br />
        * MiddleWare : NORMAL / PROXY / SOCKS (use my ip / proxy ip(in ./config/proxy.json) , each thread use one proxy that means you must set proxy in order to you'r setting threads / socks encrypte)<br />
        * SIGN : DEPTH / NORMAL (explore sing state tree)<br />
    * ThreadNumber : number of threads<br />
    * SQLMAP : <br />
        * manaul : for manual setting<br />
        * threads : sqlmap app threads<br />
        * timeout : time of app request , response timeout<br />
        * answer : auto answer question of app<br />
    * XSS :<br />
        * path : path directory of arachni file<br />
        * manual : for manual setting<br />
</pre>
<br />
**Ask and You Will learn** [*~Imam Ali*]
