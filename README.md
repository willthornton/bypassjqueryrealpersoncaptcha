# Bypass jQuery Real Person Captcha (BJRPC)
A Chrome Extension written as a proof of concept to bypass jQuery Real Person Captcha (tested with version 2.0.1).

The plugin is configured by default to run on the plugin developer's website. If it detects the jQuery Real Person Captcha it will attempt to parse the captcha content and fill in the captcha answer field with the captcha value. 

Instead of using a browser extension, the relevant JavaScript code could be copied into a web page's source to achieve a similar effect. 

<h2>To install</h2>

To install the plugin, use the following steps:
1. Save plugin folder to your desktop. 
2. In Chrome, click Menu > More Tools > Extensions. 
3. Click the "Load unpacked extension..." button. 
4. Select the saved plugin directory. 

<h2>To test</h2>

To test the plugin, you can navigate to the developer's homepage or basic captcha test page:
1. http://keith-wood.name/realPerson.html
2. http://keith-wood.name/realPersonBasics.html

Note: The extension does not currently work for the fields on the "Options" tab of http://keith-wood.name/realPerson.html (see To do section).

<h2>To do</h2>

The following items will enhance this exploit:
1. Add functionality to work for different length captchas.
2. Add functionality to parse for numbers.
3. Add functionality to parse for other types of dots.
4. Add different browser extension/plugin versions.
