UI Test:
Done on HP UFT using VB script

Requirements:
HP UFT or any other which supports VB script

In UFT:
Steps:
1.File-->New-->Test
2.Choose the name and path-->save
3.Use the script in Action
4.Run the script

Test Case1:
Launch browser-->Hover 'Services'-->Verify for Automation Text-->Click 'Services'-->Click 'Automation'
[TC01_script.txt](https://github.com/sreelu105/codechallenge-Sogeti/files/9057482/TC01_script.txt)

Test Case2:
Launch Browser-->Services-->Automation-->Contact us-Fill the Details
[TC02_Script.txt](https://github.com/sreelu105/codechallenge-Sogeti/files/9057491/TC02_Script.txt)

Test Case3:


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
![image](https://user-images.githubusercontent.com/90183632/177408693-a56341bd-7d7e-4626-b0c5-6307c56d4494.png)
![API Testcase1-plc](https://user-images.githubusercontent.com/90183632/177545027-3a6712e7-bf0b-47d3-bb3b-ec51e7070bb9.png)
![API Testcase1-country](https://user-images.githubusercontent.com/90183632/177545059-668967b0-d0f0-40e3-9ebd-8ae75caaadeb.png)
