#Dissenter Bookmarklet

A simple bookmarklet for Dissenter.com that allows you to comment on any web page on the internet.

## Desktop Instructions

To add this bookmarklet, select your browser and follow the instructions. After added, click the bookmarklet to use it.

<details><summary>Google Chrome</summary>
<p>
  
#### Google Chrome and Firefox
  
Select the code and drag it into your bookmarks bar. Make sure the bookmarks bar is visible on your browser. If you want, you can change the name of the Bookmarklet.

If you are using Google Chrome on linux, you may have to follow the Opera instructions (except the 'heart' is instead a star)
</p>
</details>


<details><summary>Opera</summary>
<p>
  
#### Opera 
  
Go to any website, and click the heart to the right of the URL bar to "add to bookmarks", and select "bookmarks bar", then, on the bookmarks bar, right click > edit the bookmark you just added, and replace the Address with the bookmarklet code, and the name to whatever you'd like. 
</p>
</details>


<details><summary>Vivaldi</summary>
<p>
  
#### Vivaldi
  
Make sure the bookmarks bar is enabled, (Ctrl+Shift+B to enable), then go to any webpage, click the "add bookmark" button on the URL bar to the right. Change the URL to the bookmarklet code, and the name to whatever you'd like.
</p>
</details>


<details><summary>Seamonkey</summary>
<p>
  
#### Seamonkey
  
Make sure the bookmarks bar is enabled, then right click the bookmarks bar > New Bookmark... then add the code in "Location", and change the name to whatever you want.
</p>
</details>


<details><summary>Pale Moon</summary>
<p>
  
#### Pale Moon
  
Make sure the bookmarks bar is enabled, then right click the bookmarks bar > New Bookmark... then add the code in "Location", and change the name to whatever you want.
</p>
</details>
  

<details><summary>Brave Browser</summary>
<p>
  
#### Brave Browser
  
Make sure the bookmarks bar is enabled (Ctrl+Shift+B), then, copy the code, and right click the bookmarks bar, then click "paste". If you want to change the name of the bookmark, right click it and click edit.
</p>
</details>
  

<details><summary>Yandex</summary>
<p>
  
#### Yandex (Russian bots smh)
  
Make sure the bookmarks bar is enabled (Ctrl+Shift+B), then, copy the code, and right click the bookmarks bar, then click "paste". If you want to change the name of the bookmark, right click it and click edit.
</p>
</details>

<details><summary>Browsers that do not work</summary>
<p>
  
#### Browsers that wont work with this because they don't support bookmarklets. Keep in mind there might be a workaround, but it would require digging into complicated instructions.

Microsoft Edge, Waterfox, Konqueror, and qute browser.

</p>
</details>

---

## The Bookmarklet Code

<details><summary>Open dissenter in the same window</summary>
<p>
  
 #### This opens dissenter in the same window. Reccommended for Android.
 
 ```Javascript
 javascript:(function(){window.location=('https://dissenter.com/discussion/begin?url='+location+'')})(); 
 ```
 
 </p>
</details>

<details><summary>Open dissenter in a new tab</summary>
<p>
  
  #### This opens dissenter in a new tab. Works on android, but could be inconvenient based on your browser.
  
 ```javascript
  javascript:(function(){window.open('https://dissenter.com/discussion/begin?url='+location+'')})();
 ```
 
 </p>
</details>

<details><summary>Open dissenter inside the webpage</summary>
<p>
 
 #### This opens dissenter inside the webpage, mimicing a real comments section on a real site. Not recommended for Android. Credits to @Mumberthrax on Gab for this script. Click the bookmarklet to toggle it on/off
 
 ```javascript
 javascript:(function(){var frame=document.getElementById("ifrm");if(frame!==null){frame.parentNode.removeChild(frame)}else{var iframe=document.createElement('iframe');iframe.src='https://dissenter.com/discussion/begin?url='+encodeURIComponent(location.href);iframe.style.width="25%";iframe.style.height=window.innerHeight+'px';iframe.style.top="0";iframe.style.right="0";iframe.style.position="fixed";iframe.style.zIndex="9999";iframe.setAttribute('id','ifrm');document.body.appendChild(iframe)}})();
 ```
 
 </p>
</details>

---

After you add it to your bookmarks bar, make sure you're logged in on https://dissenter.com or you won't be able to comment or rate the posts. To use a bookmarklet, you must click the bookmark.

Currently fixing instructions for Mozilla Firefox. At the moment, they are under "Google Chrome"

More browsers to be added in future updates. Stay tuned.
