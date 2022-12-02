# OneTab Night-Mode
Little theme for the [onetab page](chrome-extension://chphlpgkkbolifaimnlloiipkdnihall/onetab.html) to make it less hostile to the eyes.

[Onetab](https://chrome.google.com/webstore/detail/onetab/chphlpgkkbolifaimnlloiipkdnihall) is a chrome extentsion to help you stay organized by collapsing all your tabs into a list in "one tab."

<details>
   <summary><b><font size="24">Image Preview</b></font></summary>
  <p>
<!-- the above p cannot start right at the beginning of the line and is mandatory for everything else to work -->
<img src=https://i.imgur.com/kyQLht5.png>
  </p></details>
</p></details>

## Table of Contents

1. <b><a href="#Installation">Installation</a></b>
   * <a href="#Chrome"><i>Chrome</i></a>
   * <a href="#Firefox"><i>Firefox</i></a>
   * <a href="#Linux"><i>Linux</i></a>
2. <a href="#Uninstall"><b>Uninstall</a></b>
1. <a href="#Info"><b>Info</a></b>
1. <a href="#Troubleshooting"><b>Troubleshooting</a></b>







## <a id=Installation>Installation:</a>
**Windows**

### <a id=Chrome>Chrome</a>

**1.**  Download the [onetab.css file](https://raw.githubusercontent.com/pullup/OneTab-Night-Mode/master/onetab.css) (right click --> "Save as...")

  or the [Easy Install zip](https://github.com/pullup/OneTab-Night-Mode/raw/master/Install/Easy%20Drag%20and%20Drop%20Install.zip), instructions <a href="#Lazy_Method">here</a>.


**2.** Drop / paste it into (note you must replace `YOUR_WINDOWS_USERNAME_HERE` with your windows username, and make sure it's on the correct drive.)
<pre>C:\Users\<b>YOUR_WINDOWS_USERNAME_HERE</b>\AppData\Local\Google\Chrome\User Data\Default\Extensions\chphlpgkkbolifaimnlloiipkdnihall\1.18_0</pre>
   **a.**  If that doesn't work, hit "Windowskey + R" then type `%appdata` this will usually put you in `%\AppData\Roaming>`, you now need to delete everything after "AppData\" in the navigation bar, then replace it with `<Local\Google\Chrome\User Data\Default\Extensions\chphlpgkkbolifaimnlloiipkdnihall\1.18_0>` now you should be in a folder with the onetab.css file. Just drag and drop the oneclass.css file that you downloaded into this folder and click the option to replace the file. Installation complete.
   
   **b** <a id=Lazy_Method>or</a> just download [this handy dandy zip file](https://github.com/pullup/OneTab-Night-Mode/raw/master/Easy%20Drag%20and%20Drop%20Install.zip), hit "Windows Key + R" type `%appdata`, click back from `%\AppData\Roaming` to `%\AppData` (just click "AppData" in the navigation bar) then just drag and drop the "Local" folder from the zip into any empty space in the "AppData" folder. Now just click "Replace the file in this destination" and your installation is complete.
***
### <a id=Firefox>Firefox</a>

Update: Found a [similar extension for Firefox](https://github.com/cnwangjie/better-onetab) that offers a night mode, **I'd still advise reading below, though.**

Couldn't figure out how to compile it in a way that didn't make firefox recognize it as "corrupt."

If you want night mode everywhere in firefox and on Windows too, I'd highly recommend checking out Windows "High Contrast" settings.

I use them myself and can't believe it took me so damn long to find them. They're truly a blessing from heaven.

~~**1.** Download the [onetab.css file](https://raw.githubusercontent.com/pullup/OneTab-Night-Mode/master/onetab.css) (right click --> "Save as...")~~

~~**2.**  Navigate to (replace things in caps) `C:\Users\YOUR_WINDOWS_USERNAME\AppData\Roaming\Mozilla\Firefox\Profiles\WHATEVER_YOUR_PROFILE_IS\extensions`~~

~~**3.** Then open "extension@one-tab.com.xpi" with 7zip, now you can delete the "onetab.css" file.~~

~~**4.** Drag and drop the onetab.css file you downloaded in step one into the zip.~~

***
### <a id=Linux>Linux</a>

Poke around for where extensions are installed and when you find the onetab extension location, replace the onetab.css file with this one. Doesn't seem to work with Firefox, and I don't use it enough to put effort into figuring it out. Firefox has has a [different version of the extension with a dark / night mode](https://github.com/cnwangjie/better-onetab). It can be found [here](https://github.com/cnwangjie/better-onetab). I have no affileation with this addon, I just saw somneone on reddit who wanted a night mode fore onetab had updated his post with a link to that.

I won't be attempting to make a guide for every distribution of linux, and we usually know our way around our systems. 
If someone wants to do a merge request or add an issue with a specific linux distribution guide, I'll add it here.



## <a id=Uninstall>Uninstall</a>
**1.** The easiest thing to do is right click the extentsion then click "remove from chrome."

 Now you can just click "add extentsion" [here](https://chrome.google.com/webstore/detail/onetab/chphlpgkkbolifaimnlloiipkdnihall) and the theme will be gone.

**2.** Alternatively you can follow the same steps as instillation, but using the [uninstall file](https://raw.githubusercontent.com/pullup/OneTab-Night-Mode/master/UnInstall/onetab.css) (which is also included in the [Easy Install zip](https://github.com/pullup/OneTab-Night-Mode/raw/master/Install/Easy%20Drag%20and%20Drop%20Install.zip).)

***
## <a id=Info>Info:</a>
Just downloaded the plugin and I see that the main page it creates is quite eye raping with no apparent option to fix this.
So I've gone and whipped up a little alternative theme they could create a toggle for.

I also hope that they will consider making their project open source on Github so that people can suggest edits like this a bit easier.

***
## <a id=Troubleshooting>Troubleshooting:</a>
If the plugin is updated I'll likely need to update the install directions and easy install zip, please just post an issue [here](https://github.com/pullup/OneTab-Night-Mode/issues) to let me know. I'll deal with it whenever I see it.

If you have any other troubles, feel free to post them in [#Issues](https://github.com/pullup/OneTab-Night-Mode/issues), I'll try to get back to you when I can.
