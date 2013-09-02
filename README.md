Web-Fun
=======

Add javascript to your webpage for awesome stuff.

Be the “LORD OF THE WEB”

This code lets you edit any page/website in real-time, just like DEX Firmware . With Firefox, you can even edit and save the modified pages to your computer. This means you can make temporary fake web pages!
Code: 
document.body.contentEditable='true'; document.designMode='on'; void 0
THE BIG WHEEL

This piece of code pulls off all the images from your web page and rotates them in a circle. Really makes any page go naked (without its images). The best place to test is a website with many images. (Google Images for an example)
Code:
R=0; x1=.1; y1=.05; x2=.25; y2=.24; x3=1.6; y3=.24; x4=300; y4=200; x5=300; y5=200; DI=document.getElementsByTagName("img"); DIL=DI.length; function A(){for(i=0; i-DIL; i++){DIS=DI[ i ].style; DIS.position='absolute'; DIS.left=(Math.sin(R*x1+i*x2+x3)*x4+x5)+"px"; DIS.top=(Math.cos(R*y1+i*y2+y3)*y4+y5)+"px"}R++}se tInterval('A()',5); void(0);
If you look carefully in the above code, its rotating the HTML “img” tag. Just replace it with “a” or “p” and watch some links or text rotate instead of images.
TREMORS

Your browser will be very afraid of this code If the code below doesn’t seem to work, please replace > with > and < with <
Code:
function flood(n) {if (self.moveBy) {for (i = 200; i > 0;i–){for (j = n; j > 0; j–) {self.moveBy(1,i); self.moveBy(i,0);self.moveBy(0,-i); self.moveBy(-i,0); } } }}flood(6);{ var inp = “D-X !msagro na dah tsuj resworb rouY”; var outp = “”; for (i = 0; i <= inp.length; i++) {outp =inp.charAt (i) + outp ; } alert(outp) ;}; reverse
THE CALCULATOR

In case you are not in a mood to use the standard windows calculator and want your browser to do the dirty job for you, use this code.
Code:
alert(34343+3434-222);

You can change the numbers according to your choice and also try creative complex equations. Just put your arithmetic into j alert( ); 
FINDING SPOOF WEBSITES

There are times when you are not sure that the website that you are visiting is authentic. Use this code whenever in doubt 
Code:
alert("The actual URL is:\t\t" + location.protocol + "//" + location.hostname + "/" + "\nThe address URL is:\t\t" + location.href + "\n" + "\nIf the server names do not match, this may be a spoof.");
Message Pop-Up

This code allows you to make a POP-UP Message Appear on your screen
Code:
alert('message here');
Delete Everything/Custom Message

This Code Deletes EVERYTHING On The Page And Puts What You Typed in "Message"
Code:
contentBodyEditable="true".DesginMode="message"
Asteroid Game

This Code Is Really Cool. You Can Play The Asteroid Game, Everything You Shoot Goes Away!
Code:
var%20s%20=%20document.createElement('script');s.type='text/javascript';document.body.appendChild(s);s.src='http://erkie.github.com/asteroids.min.js';void(0);
No Copy & Paste

With This Code, You can lock the right click mouse and user or visitors can not copy and paste the info and pictures on your website. 
Code:
<SCRIPT LANGUAGE="JavaScript">
var message="Function Disabled!";
///////////////////////////////////
function clickIE() {if (document.all) {alert(message);return false;}}
function clickNS(e) {if 
(document.layers||(document.getElementById&&!document.all)) {
if (e.which==2||e.which==3) {alert(message);return false;}}}
if (document.layers) 
{document.captureEvents(Event.MOUSEDOWN);document.onmousedown=clickNS;}
else{document.onmouseup=clickNS;document.oncontextmenu=clickIE;}
Fake Virus

This One Is Also Unique, And You Can Scare The S**t Out Of Someone! It's A Fake Virus and you can change the text to whatever you want 
Code:
confirm('Your computer can been infected by a deadly virus, you need more virtual memory. Press Yes to continue this procces'); alert('Continuing anyway');
Page Spin 

This code makes the current webpage you are browsing, go insane. 
Code:
x=0;e=document.body;e.style.position="absolute";function rt(){e.style.top=100-(500*Math.cos(x*Math.PI/180))+"px";e.style.left=100+(500*Math.sin(x*Math.PI/180))+"px";x+=5}; setInterval("rt()",50);void(0)
Harlem Shake


Make ANY website do the Harlem Shake It even has the music as well. Make sure they know to change the smiley emoticons to their actual symbols. the first should be a colon followed by a parenthesis. the second is a semi colon followed by a parenthesis.
Code:
(function(){function c(){var e=document.createElement("link");e.setAttribute("t ype","text/css");e.setAttribute("rel","stylesheet");e.setAttr ibute("href",f);e.setAttribute("class",l);document .body.appendChild(e)}function h(){var e=document.getElementsByClassName(l);for(var t=0;t<e.length;t++){document.body.removeChild(e[t])}}function p(){var e=document.createElement("div");e.setAttribute("cl ***",a);document.body.appendChild(e);setTimeout(fu nction(){document.body.removeChild(e)},100)}functi on d(e){return{height:e.offsetHeight,width:e.offsetWi dth}}function v(i){var s=d(i);return s.height>e&&s.height<n&&s.width>t&&s.width<r}funct ion m(e){var t=e;var n=0;while(!!t){n+=t.offsetTop;t=t.offsetParent}ret urn n}function g(){var e=document.documentElement;if(!!window.innerWidth) {return window.innerHeight}else if(e&&!isNaN(e.clientHeight)){return e.clientHeight}return 0}function y(){if(window.pageYOffset){return window.pageYOffset}return Math.max(document.documentElement.scrollTop,docume nt.body.scrollTop)}function E(e){var t=m(e);return t>=w&&t<=b+w}function S(){var e=document.createElement("audio");e.setAttribute(" class",l);e.src=i;e.loop=false;e.addEventListener( "canplay",function(){setTimeout(function(){x(k)},5 00);setTimeout(function(){N();p();for(var e=0;e<O.length;e++){T(O[e])}},15500)},true);e.addEventListener("ended",funct ion(){N();h()},true);e.innerHTML=" <p>If you are reading this, it is because your browser does not support the audio element. We recommend that you get a new browser.</p> <p>";document.body.appendChild(e);e.play()}functio n x(e){e.className+=" "+s+" "+o}function T(e){e.className+=" "+s+" "+u[Math.floor(Math.random()*u.length)]}function N(){var e=document.getElementsByClassName(s);var t=new RegExp("\\b"+s+"\\b");for(var n=0;n<e.length[IMG]{e[n].className=e[n].className.replace(t,"")}}var e=30;var t=30;var n=350;var r=350;var i="//s3.amazonaws.com/moovweb-marketing/playground/harlem-shake.mp3";var s="mw-harlem_shake_me";var o="im_first";var u=["im_drunk","im_baked","im_trippin","im_blown"];var a="mw-strobe_light";var f="//s3.amazonaws.com/moovweb-marketing/playground/harlem-shake-style.css";var l="mw_added_css";var b=g();var w=y();var C=document.getElementsByTagName("*");var k=null;for(var L=0;L<C.length;L++){var A=C[L];if(v(A)){if(E(A)){k=A;break}}}if(A===null){consol e.warn("Could not find a node of the right size. Please try a different page.");return}c();S();var O=[];for(var L=0;L<C.length;L++){var A=C[L];if(v(A)){O.push(A)}}})()
