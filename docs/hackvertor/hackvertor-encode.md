# Hackvertor encode

Use the Hackvertor extension to apply a URL address format to a query string in Burp Suite.

* Open **Burp Suite**

#### **Quick encode**

* Go to **Hackvertor** > Encode
* Select **Burp\_encode**

Paste a query string between <><>

* Select **Paste Tags**



#### Encode a URL request in Burp Suite using Hackvertor

* Go to **Proxy** > Intercept
* Select **Open Browser**



The Burp Suite browser will open.

![](<../.gitbook/assets/Burp\_Proxy\_Intercept browser (2).png>)

* Enter a URL address to query in Burp Suite in the browser web address search
* Go to **Proxy** > HTTP history

The Burp Suite browser IP address history will be shown as a list of web page details and requests. Locate the URL address entered into the Burp Suite browser.

* Right click on the URL address in the list to select > Send to Repeater
* Go to **Repeater**

The URL request details can be seen in the Request panel.

* Insert a query string into the URL **Request** to be encoded by Hackvertor

****

* Highlight the edited URL query string in the request and select by clicking three times (triple click)
* Right click the highlighted text to select > **Extensions** > Hackvertor > Encode&#x20;
* Select **Send**



<@urlencode><@urlencode> tags are added to the URL.

* Go to **Logger** to see the actual send request details

**Info:** Scroll to the bottom of the list to see the most recent Logger request

The server response will show the request details

**Info:** If a query generates a successful server response the encoded text will be shown



#### Test a Hackvertor URL

* Enter the encoded URL into the Burp Suite browser web address search
* Go to **Dashboard**

![](<../.gitbook/assets/Burp\_Dashboard\_URL shorten Hackvertor.png>)

* Locate the URL http response in the Issue Activity panel **** on the right of the Dashboard screen&#x20;
