- š Hi, Iām @Ultimateking911
- š Iām interested in ...
- š± Iām currently learning ...
- šļø Iām looking to collaborate on ...
- š« How to reach me ...

<!---
Ultimateking911/Ultimateking911 is a āØ special āØ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
function getBrowserType(){ 

    if( navigator.userAgent.indexOf('MSIE 7') > -1 ){
        return BrowserString("MSIE 7");
    }
    if( navigator.userAgent.indexOf('MSIE 8') > -1 ){
        return BrowserString("MSIE 8");
    }
    if( navigator.userAgent.indexOf('MSIE 9') > -1 ){
        return BrowserString("MSIE 9");
    }
    if( navigator.userAgent.indexOf('MSIE 10') > -1 ){
        return BrowserString("MSIE 10");
    }
    if( navigator.userAgent.indexOf('rv:11.0') > -1 ){
        return BrowserString("rv:11.0");
    }
    if( navigator.userAgent.indexOf('Firefox') > -1 ){
        return BrowserString("Firefox");
    }
    if( navigator.userAgent.indexOf('Chrome') > -1 ){
        return BrowserString("Chrome");
    }
    if( navigator.userAgent.indexOf('Opera') > -1 ){
        return BrowserString("Opera");
    }

    else{
        return "Unknown";
    }
    
}
