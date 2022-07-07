UI Test:
Done on HP UFT using VB script

Requirements:
HP UFT or any other which supports VB script

In UFT:
Steps:
1.File-->New-->Test
2.Choose the name and path-->save
3.Use the script in Action-->save
4.Run the script

Test Case2:
#Note: Unable to automate Captcha, Captachas are mainly designed to prevent automation or computer interaction.
But there is possibility to disable Captcha in test environment by using Google’s open-source Captcha widget – reCAPTCHA v2, put in the Site Key and the Secret Key, (known as the test keys).  As a result, all verification requests will pass, and automated UI testing can be conducted seamlessly. 


API Test
Requirements:
1.Install Postman API Tool
2.Create new collection
3.Authorisation required
4.Add Request under Collection

Steps:
1.Method to be chosen is 'GET'
2.Enter URL http://api.zippopotam.us/de/bw/stuttgart
3.Click 'Send'
4.API Test1:
Verify the below in the response:
  -Status code is 200 and content type is JSON
  -Response time is bel ow 1s
  -"country" is "Germany" and "state" is "Baden-Württemberg".
  -For Post Code "70597" the place name has "Stuttgart Degerloch".
![API Testcase1](https://user-images.githubusercontent.com/90183632/177715231-9b770b13-7f8e-4575-9f10-ec11d0f9815b.png)
![API Testcase1-plc](https://user-images.githubusercontent.com/90183632/177717160-f31b2a1f-5592-4d56-a5d6-23a9c5d3bdea.png)
![API Testcase1-country](https://user-images.githubusercontent.com/90183632/177545059-668967b0-d0f0-40e3-9ebd-8ae75caaadeb.png)

API Test2:
Test with Country and Postal code
-Verify in Response:
  -Status code is 200 and content type is JSON
  -Response time is bel ow 1s
  -Verify placename for eych input
  ![API Testcase2-ca](https://user-images.githubusercontent.com/90183632/177715873-b17d0e9c-5c8f-41e4-9df3-0d7321dad3e3.png)
![API Testcase2-us1](https://user-images.githubusercontent.com/90183632/177715904-b4d320a7-5210-45e7-a204-43fe13340abe.png)
![API Testcase2-us2](https://user-images.githubusercontent.com/90183632/177715909-e2f9dab5-2ddb-47ae-8852-02e81f860695.png)

 
