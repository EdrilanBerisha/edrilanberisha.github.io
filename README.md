<div id="top"></div>
<br />
<div align="center">
    <img src="imagesReadme/chromelogo.png" alt="Logo">
    <img src="imagesReadme/edgelogo.png" alt="Logo">
  </a>
  <h3 align="center">SAP Fiori Launchpad, Browser Extension for SAP S/4HANA</h3>
</div>

<img src="https://media.giphy.com/media/NxQ5wa5XMLG4HmPHcp/giphy.gif" width="100%" height="100%"/>

<details>
  <summary>Table of Content</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>

## About The Project


This Google Chrome/Microsoft Edge extension aims to improve your life as developer or tester, who is working with different fiori applications on different internal or customer systems. You'll save a lot of time in the long-term.

Here's why:
* Internal test systems or customer systems have performance issues
* Launchpad can be broken in internal test systems
* Initial loading of the launchpad takes long

<p align="right">(<a href="#top">back to top</a>)</p>



### Built With

* [![nodejs][nodejs]][nodejs-url]
* [![UI5][ui5-wc]][ui5wc-url]
* [![Webpack][webpack]][webpack-url]
* [![Puppeteer][puppeteer]][puppeteer-url]

<p align="right">(<a href="#top">back to top</a>)</p>


## Getting Started

The extension can be downloaded from the official Chrome Store - which I would also recommend instead of cloning and building this repository!

[https://chromewebstore.google.com/detail/fiori-launchpad-for-sap-s/nelmoakcfgfgkigcjgkmibhmgfpbhcbh?authuser=0&hl=de](https://chromewebstore.google.com/detail/fiori-launchpad-for-sap-s/nelmoakcfgfgkigcjgkmibhmgfpbhcbh?authuser=0&hl=de)

## Usage

So let's get started now with our new Chrome extension. For that we login to any SAP S/4HANA system you have access to.
<br />

![demo1][demo1]

Now we can add the S/4HANA System to our favorite list. For that we will click on the extension logo in our browser. It opens a popup, here we click on the 'Favorite' button on the top right corner.
<br />

![demo2][demo2]

Now we can either add a fiori app or a S/4 system to our favorite list. So for now we click on S/4 System. 
<br />

![demo3][demo3]

Now we can decide how we want to name this new favorite system. In this example, we name it UYT/902. 
<br />

![demo4][demo4]


Now we save the S/4 System.
<br />

![demo5][demo5]

We open the 'Manage Bank Statements' app. And click again on the extension logo. We click again on 'Favorite'.
<br />

![demo6][demo6]

This time we click on 'Fiori App'. To add the current fiori app to our favorites.
<br />

![demo7][demo7]

Fiori App name is already proposed as 'Manage Bank Statements' so that is fine for us. We click on 'save'.
<br />

![demo8][demo8]

If we right click on the extension logo, we have an option to click on 'Options'.
<br />

![demo9][demo9]

Now the options page opens up. On the top left corner we have three buttons (segmented buttons). With the labels 'Current', 'Tab', 'Window'. These are the same settings you do also see on the popover, which opens from the extension logo. These settings are the settings how you wish, to open the new S/4 system or fiori app. 'Current' means it stays in the current browser and tab, and will navigate to it. 'Tab' means it will open the new site in a new tab. 'Window' means accordingly, it will open in a new browser window. On the top right of the table you have actions, with which you can delete, edit or adjust the position of your favorite apps or systems. A bit below the three segmented buttons for the browser settings. You have two table tabs. One with 'Fiori Apps' and one with 'S/4 Systems' as label. With this you can change the view on your favorite lists. On the bottom right you have an upload and download functionality. Keep in mind you have to pre-select the correct table tab. You can't upload fiori apps into your extension, when the S/4 Systems tab is selected and vice versa.
<br />

![demo10][demo10]

The browser settings can be found on the bottom left of your popover.
<br />

![demo11][demo11]

The system settings can be found on the bottom right. Whatever is selected here will the be only valid for your next navigation. Other than the browser settings which we have seen in the steps before.
<br />

![demo12][demo12]

Now we can navigate to a new app. By just clicking on our newly added favorite 'Manage Bank Statements'. The browser settings, are set that the new app will be open in a new window.
<br />

![demo13][demo13]


<p align="right">(<a href="#top">back to top</a>)</p>


## Roadmap

- [x] Finish main development
- [x] Testing automation
- [x] Alpha testing phase (couple of colleagues)
- [x] Beta testing phase (LoB)
- [x] Roll out to SAP internally
- [x] publish it officially in the Chrome Store


<p align="right">(<a href="#top">back to top</a>)</p>

## Contact

Edrilan Berisha - edrilan.berisha@sap.com

Project Link: [https://github.tools.sap/D066511/FLPExtension](https://github.tools.sap/D066511/FLPExtension)

<p align="right">(<a href="#top">back to top</a>)</p>
 
[screenshot-app]: imagesReadme/screenshotStartscreen.png
[ui5-wc]: imagesReadme/ui5logo.png
[ui5wc-url]: https://sap.github.io/ui5-webcomponents/
[puppeteer]: imagesReadme/puppeteerlogo.png
[puppeteer-url]: https://github.com/puppeteer/puppeteer
[webpack]: imagesReadme/webpacklogo.png
[webpack-url]: https://webpack.js.org/
[nodejs]: imagesReadme/nodejslogo.png
[nodejs-url]: https://nodejs.org/en/
[google-chrome]: imagesReadme/chromelogo.png
[microsoft-edge]: imagesReadme/edgelogo.png
[install1]: imagesReadme/threeDots.png
[install2]: imagesReadme/settings.png
[install3]: imagesReadme/extensionTab.png
[install4]: imagesReadme/developerMode.png
[install5]: imagesReadme/loadUnpacked.png
[install6]: imagesReadme/extensionLoaded.png
[install7]: imagesReadme/pinExtension.png
[install8]: imagesReadme/extensionPinned.png
[installedge1]: imagesReadme/installedge1.png
[installedge2]: imagesReadme/installedge2.png
[installedge3]: imagesReadme/installedge3.png
[installedge4]: imagesReadme/installedge4.png
[installedge5]: imagesReadme/installedge5.png
[installedge6]: imagesReadme/installedge6.png
[installedge7]: imagesReadme/installedge7.png
[installedge8]: imagesReadme/installedge8.png
[demo1]: imagesReadme/demo1.png
[demo2]: imagesReadme/demo2.png
[demo3]: imagesReadme/demo3.png
[demo4]: imagesReadme/demo4.png
[demo5]: imagesReadme/demo5.png
[demo6]: imagesReadme/demo6.png
[demo7]: imagesReadme/demo7.png
[demo8]: imagesReadme/demo8.png
[demo9]: imagesReadme/demo9.png
[demo10]: imagesReadme/demo10.png
[demo11]: imagesReadme/demo11.png
[demo12]: imagesReadme/demo12.png
[demo13]: imagesReadme/demo13.png
