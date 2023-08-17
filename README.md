# PaymentGateway-Integration-With-RazorPay

<h1>Steps to Create Account in Razorpay</h1>

Step 1 : Go to https://x.razorpay.com/auth .

Step 2 : Click on Sign up to create new Account .

![image](https://github.com/hetasvi/Payment-Integration-With-RazorPay/assets/111453003/b453e2e2-8f27-43bc-a49e-e2c1def6ee6f)

Step 3 : Enter necessary Information .

![image](https://github.com/hetasvi/Payment-Integration-With-RazorPay/assets/111453003/fdf2d409-ccd2-44da-a1df-af9560d0f120)
![image](https://github.com/hetasvi/Payment-Integration-With-RazorPay/assets/111453003/0813f182-8b18-4e8e-8f8d-16c335c1092e)

Step 4 : After successful Account creation you will be redirected to Dashboard. Now select Try RazorpayX [Test Mode]

![image](https://github.com/hetasvi/Payment-Integration-With-RazorPay/assets/111453003/9c2438ea-ba8e-43e9-89f9-4b4119677549)

Step 5 : Click on the profile icon  , Which will open a dropdown menu . Go to My accounts and Settings.

![image](https://github.com/hetasvi/Payment-Integration-With-RazorPay/assets/111453003/da7a9b55-1016-4ee6-ae89-89facee8c066)

Step 6 : Go to Developer Controls.

![image](https://github.com/hetasvi/Payment-Integration-With-RazorPay/assets/111453003/fea92071-121e-4aa1-a365-523ba5901788)

Step 7 : Generate Key for Test mode . 

![image](https://github.com/hetasvi/Payment-Integration-With-RazorPay/assets/111453003/68b69ce9-9a1d-4664-9b6f-19160ac5b407)

Step 8 : Download Key details.

![image](https://github.com/hetasvi/Payment-Integration-With-RazorPay/assets/111453003/aaec39fe-b16c-42b7-bc42-cc3311c202f1)


# Integration with Spring boot

Step 9 : Set the secret key and Secret in application.properties file.

 ![image](https://github.com/hetasvi/Payment-Integration-With-RazorPay/assets/111453003/ceed46f9-a49d-484e-8483-a1ff2ae84c3d)

Step 10 :  Add RazorPay dependency .

![image](https://github.com/hetasvi/Payment-Integration-With-RazorPay/assets/111453003/ecf34a36-e9c7-4328-b546-77ec94941f14)

Step 11 : Create one home.html file to redirect it to the checkout of payment of Razorpay and handle failure and success of the payment .

![image](https://github.com/hetasvi/Payment-Integration-With-RazorPay/assets/111453003/7e0f9792-f2d3-4ed0-9c73-68fa3b771be3)

Step 12 : Create one DTO TransactionDetails .

![image](https://github.com/hetasvi/Payment-Integration-With-RazorPay/assets/111453003/c8e8c314-488e-47c7-91fc-578c1f689521)

Step 13 : Create Payment Service to create Razorpay client and create an order.

![image](https://github.com/hetasvi/Payment-Integration-With-RazorPay/assets/111453003/d65110c1-329d-408d-bc76-aee45783e67c)

 
Step 14 : Create one Controller to access the home.html page . 

![image](https://github.com/hetasvi/Payment-Integration-With-RazorPay/assets/111453003/5808f238-e162-4973-a833-c0c5c3bbb592)

Step 15 : Generate Order Id through localhost:8080/payment/createTransaction/10  

 ![image](https://github.com/hetasvi/Payment-Integration-With-RazorPay/assets/111453003/8e1080d4-1fb8-452d-b132-2d2ec29d9e09)

Step 16 : Go to localhost:8080 in browser  and click on pay button .

![image](https://github.com/hetasvi/Payment-Integration-With-RazorPay/assets/111453003/b8c15e43-ace6-4d87-98b9-c4371238b64a)

Step 17 : It will redirect to razor pay 
# Success 

![image](https://github.com/hetasvi/Payment-Integration-With-RazorPay/assets/111453003/cba5135f-5f74-4dfb-83fe-985675c15749)
![image](https://github.com/hetasvi/Payment-Integration-With-RazorPay/assets/111453003/cb10e7e7-f415-4f04-bdf2-6fbbf645ac10)
![image](https://github.com/hetasvi/Payment-Integration-With-RazorPay/assets/111453003/a2d635f7-f2e7-487d-9c6f-80f0b7217ac4)
![image](https://github.com/hetasvi/Payment-Integration-With-RazorPay/assets/111453003/cfb936e0-569e-48e3-a787-1811dbb86f8f)
![image](https://github.com/hetasvi/Payment-Integration-With-RazorPay/assets/111453003/637c0d61-9c99-4e33-af05-0c9316e4b024)
![image](https://github.com/hetasvi/Payment-Integration-With-RazorPay/assets/111453003/0cb1239a-8e23-4859-86f6-ee8dfaf629f0)
![image](https://github.com/hetasvi/Payment-Integration-With-RazorPay/assets/111453003/1589a81b-0ae1-46bd-b069-01013d8907c3)

# Failure 

![image](https://github.com/hetasvi/Payment-Integration-With-RazorPay/assets/111453003/b4c0fa56-5eb5-42dd-bb80-165745f2b785)
![image](https://github.com/hetasvi/Payment-Integration-With-RazorPay/assets/111453003/652a1c55-4153-4784-a882-cf4bfe591297)





      
 

 
