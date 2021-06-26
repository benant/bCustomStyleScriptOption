# bCustomStyleScriptOption
benant's Custom Style Script Plugin Option

## Custom Style Script
https://mybrowseraddon.com/custom-style-script.html

## Options

### Skip Youtube Ads
* URL : http://www.youtube.com
* Script
```
https://ajax.aspnetcdn.com/ajax/jQuery/jquery-3.6.0.min.js

var skip = function(s){
	$('.ytp-ad-skip-button-text').click();
	setTimeout(skip, s*1000);
}
skip(0.1);
```
* Style
