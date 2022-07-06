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
4.Verify the below in the response:
  -Status code is 200 and content type is JSON
  -Response time is bel ow 1s
  -"country" is "Germany" and "state" is "Baden-Württemberg".
  -For Post Code "70597" the place name has "Stuttgart Degerloch".
![image](https://user-images.githubusercontent.com/90183632/177408693-a56341bd-7d7e-4626-b0c5-6307c56d4494.png)
