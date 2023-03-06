# Hackvertor encode

Use Hackvertor to apply a URL tag to a URL query string or a Burp Suite target.

* Open **Burp Suite**
* Go to **Hackvertor** > Encode

URL query strings can be added in between the <@urlencode> <@urlencode> tags.

* Select **Send**



Convert a URL in Burp Suite

* Go to **Proxy** > Intercept

The Burp Suite browser will open.

![](<../.gitbook/assets/Burp\_Proxy\_Intercept browser (2).png>)

* Enter a URL address to query in Burp Suite in the browser web address search
* Go to **Proxy** > HTTP history

The Burp Suite browser IP address history will be shown as a list of web page details and requests.

* Right click on the URL address in the list to select > Send to Repeater
* Go to **Repeater**
*
* Insert a query string into the URL **Request**
* Highlight the URL query and select by clicking three times (triple click)
* Right click to select the highlighted text
* Go to **Extensions** > Hackvertor > Encode&#x20;
* Select **Send**

Test Hackvertor URL query&#x20;

1. ![](<../.gitbook/assets/Burp\_Dashboard\_URL shorten Hackvertor.png>)
