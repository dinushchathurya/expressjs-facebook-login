# Node.js Facebook Authentication with Passport 

In here, I have created Facebook authentication with Passport and Node.js. 

## Requirements

* Node.js

## Credentials

Facebook Credentials can be obtained from the Facebook for Developers portal

* Visit https://developers.facebook.com/
* Open the "My Apps" dropdown and select "Add a New App"
* Give the App a name and sleect "Create App ID"
* Select "Facebook Login" from the "Select a Product" page, and then select "Web"
* You might have to select "Add Product" on the sidebar to get here
* Enter a Site URL of "http://localhost:3000" and save this
* Select "Settings" under "Facebook Login" on the sidebar
* Enter "http://localhost:3000/api/authentication/facebook/redirect" in the "Valid OAuth redirect URIs" box and save this
* Select "Dashboard" in the sidebar, and write down the App ID and App Secret.

When you run the application, you will first need to set the environment variables FACEBOOK_CLIENTID and FACEBOOK_CLIENTSECRET to the App ID and App Secret you have just obtained.

## Run this Application

To run this application, 

* clone this repository `git clone https://github.com/dinushchathurya/expressjs-facebook-login` 

* Then `cd expressjs-facebook-login`

* Run `npm install`

* Then goto ".env"

* Paste your IDs on their

* Then run `node server.js`

* Then visit "http://localhost:3000"

## Contact

For further more clarifications or regarding any issues, please contact me via my E-Mail.

## License

Copyright (c) 2020 <a href="https://dinushchathurya.github.io/">Dinush Chathurya</a> and <a href="https://codingtricks.io/">codingtricks.io</a>

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
"Software"), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE
LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION
OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION
WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

## Blog

https://codingtricks.io/

## 

<p ><h2 align="center">Happy<i class="fa fa-heart" style="color:red;"></i> Coding<i class="fa fa-code" style="color:orange;"> </i></h2></p>
