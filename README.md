About
=====
Create a PoC for CSRF attacks in a split second. Select any log present in IronWASP and run this module to create a HTML file. When this file is opened from the browser, the browser will send a request similar to the one on which this module was run. It supports requests that have normal body format and also JSON and XML request body formats.


Features
========
*	Handles GET,POST,XML and JSON Requests.
*	Generates HTML Code to exploit CSRF.
*	Saves a HTML file and provides the location of the file  in a text box.


Steps to use
============
*	Set IronWASP as proxy.
*	Traverse through the flows to be exploited (using the browser) , so the logs will be captured in IronWASP's Proxy Logs.
*	Right click any log and Goto "Run Modules on this Request/Response" -> Exploitation -> CSRF PoC Generator.
*	It generates the HTML code to exploit CSRF vulnerability and saves it the location specified.
*	Run the file in the browser which has the authenticated session and execute CSRF.


CSRFPOCGenerator Screenshots
============================

![CSRFPOCGenerator Screenshot 0](https://github.com/jayeshchauhan/csrf_poc_generator/blob/master/image0.JPG?raw=true "Screenshot 0")

![CSRFPOCGenerator Screenshot 1](https://github.com/jayeshchauhan/csrf_poc_generator/blob/master/image1.JPG?raw=true "Screenshot 1")


![CSRFPOCGenerator Screenshot 1](https://github.com/jayeshchauhan/csrf_poc_generator/blob/master/image2.JPG?raw=true "Screenshot 2")

