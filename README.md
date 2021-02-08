# WebEraser
Erase parts of webpages.

###
Below you will find two screenshots of a typical website that uses banner ads.

The first screenshot shows the page after using this script to erase the ad.  
The second screenshot shows the page as it normally appears without using this script.

Runs on Firefox and on Google Chrome browsers as of Nov 2017. 

Sept 2020: Moving to the use of TamperMonkey, however, for now it still works under GreaseMonkey.  
An extra Export/Import function has been added to allow moving between browsers.  
Firefox was crashing in GreaseMonkey during script editing and appears to have been left without recent updates.

### How To Use
After installing this script clicking on any advert/image/text etc., whilst holding down the "Ctrl" key, erases it by drawing curtains over it.  Upon revisiting the page at another time, the advert/image etc. will still be erased.  A double Click on an erased (curtained) space temporarily reveals that which was erased.

If clicking on the item tends to cause other effects such as opening a new tab or visiting another page, the the 
special mennu option "Erase via mouse hover" can be invoked without having to click on the item.

The script also adds to the TamperMonkey (GreaseMonkey) menu a command that gives access to the scripts options.  One of which allows one to set the 'curtain' image to a http image address or a base64 string.  It also allows manual alteration of the selectors used to find elements for erasure.  Another option allows for complete erasure of items leaving more space for other items on the page (for this, untick the "preserve layout" tickbox).

To access this script's options: ctrl-click anywhere, you should see a small popup, then click on link named 'Preferences...' that appears within the small popup.  

### Installing on Browser without TamperMonkey/GreaseMonkey

Save this script by clicking the right mouse button upon the "install" button at the top of this page and choose "Save link as...".  Then drag and drop the downloaded script from a file manager onto chrome's "extensions" page. Chrome's extensions page is accessible from the Chrome menu "More tools->Extensions.", also switch the top right "Developer mode" button to the "on" position and reload the page before drag-drop operation.

The script's menu is then accessible from any webpage in Chrome via the small 'Monkey' icon at the top right of any page.

### Screenshot One:
![Large banner ad at the StackOverflow website has been erased whilst preserving layout](https://github.com/SloaneFox/imgstore/raw/master/StackoverflowCurtainedAd.png "Large banner ad at stack overflow has been erased whilst preserving layout")
<br><br><br><br>

### ================================================================================
### Screenshot Two:
### ================================================================================

![Stackoverflow as it normally is with banner ad.](https://github.com/SloaneFox/imgstore/raw/master/StackoverflowWithAd.png "StackOverflow as it normally appears.")

WebEraser, Nuke Anything on the web with Weberaser.
