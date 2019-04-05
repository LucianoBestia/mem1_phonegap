Things are changing fast. This is the situation on 2019-04-04.
# mem1_phonegap
Trying phonegap with Wasm with the game mem1 written in Rust Webassembly with Virtual Dom.  
On Win10 the development version is served from PhoneGap Desktop.  
Running the app in Chrome browser works fine.  
But running it on my android 6.0.1 (Galaxy Note 4) with PhoneGap Developer app does NOT work.  
The index.html content is rendered well until it comes to the javascript for Wasm.  
I don't know why.  
Cannot try it this way on iPhone, because Apple does not allow the PhoneGap Developer app.  

The source code of the original app is here:  
[https://github.com/LucianoBestia/mem1](https://github.com/LucianoBestia/mem1)  

# How to install phonegap on Win10
1. Win10 : Go to https://phonegap.com/getstarted/ and download and start the installer for PhoneGap Desktop.  
2. Android : install PhoneGap Developer app  

# Cloning the code
3. Clone this repository.  
```
git clone https://github.com/LucianoBestia/mem1_phonegap
```
It is based on the Hello sample generated by PhoneGap Desktop.  
Inside the www folder I added the folders: www/pkg and www/content  
and the files www/index.html and www/css/mem1.css.  

# Running the code on Win10 - development mode
4. Start PhoneGap Desktop, click the Plus button and open existing PhoneGap project.
5. On PhoneGap Desktop clik the Play button (Top Right) to start the development server.
6. On the bottom of PhoneGap Desktop click the URL of the running server.  
It will open the app in the browser.  
The application works as intended.  
![snap01](https://user-images.githubusercontent.com/31509965/55611398-94de4a00-57af-11e9-9e75-0b00266d6270.JPG)

# Running the code on Android - development mode
7. Start the PhoneGap Developer app  
8. Type in the URL of the PhoneGap Desktop Server  
It will open the app, but it will NOT work correctly.  
It will render index.html till the point where is the Wasm script. Then it stops.  




#References
https://phonegap.com/



