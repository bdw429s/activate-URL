# activate-URL

This is a project I did not write.  It is by Joel Mueller and was posted on CFLib. 
http://www.cflib.org/udf/ActivateURL

I added it simply as an example of how to turn a UDF into a simple package that is isntallable via CommandBox as part of this CommandBox Connection webinar.:"
http://experts.adobeconnect.com/p4a8yw05e3i/

This repo is a simple module with a single model that is auto-mapped by WireBox as a singleton.  It contains one method called "activateURL".

install the module like so via CommandBox:
```bash
install activate-url
```

Then use the model in your code like so:

```javascript
getInstance( 'activateURL@activate-URL' ).activateURL( myString )
```
