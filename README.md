# php-url

## getting started  
``` 
include 'Url.php';  
use Prototypeblocks\Url;  
``` 
## examples  
#### current
``` 
$currentUrl = Url::current();
// $currentUrl contains current page URL for example: http://local.prototypeblocks.com/example/
``` 
#### previous
``` 
$previousUrl = Url::previous();
// $previousUrl contains previous page URL (refferer)
``` 
#### isHttps
``` 
$isSecure = Url::isHttps();
// $isSecure is a boolean with weither or not the current page is requested over HTTPS
``` 
#### redirect
``` 
$redirectTo = 'http://www.prototypeblocks.com/';
Url::isHttps($redirectTo);
// Will redirect (header location) to given page, in this case 'http://www.prototypeblocks.com/'
``` 
