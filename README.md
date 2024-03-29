# IUG Restaurant ordering system
 ** ** There is a lot of scope online food ordering business and we can tap it to the max extent possible as everyone has access to an online ordering facility via the internet. Food business usually will have high demand and hence online business prospect for food ordering should be profitable. We will provide an easily accessible interface wherein the customer can view and place the order easily. 
 
 ** ** The customer can register initially with minimum details and will be allowed to check the menu items before ordering them, adding them to cart and submit the order. The system records the details in MySQL database so that it will be easy to retrieve later. The users of the system also include employee who will handle info related to product addition and delivery or rejection of the request.
 
 
 ** **  هناك الكثير من مجالات طلب الطعام عبر الإنترنت ويمكننا الاستفادة منه إلى أقصى حد ممكن حيث يمكن للجميع الوصول إلى منشأة الطلب عبر الإنترنت عبر الإنترنت. عادة ما يكون هناك طلب مرتفع على تجارة المواد الغذائية ، وبالتالي يجب أن تكون آفاق الأعمال التجارية عبر الإنترنت لطلب الطعام مربحة. سنوفر واجهة يمكن الوصول إليها بسهولة حيث يمكن للعميل عرض الطلب ووضعه بسهولة. 

 ** **  يمكن للعميل التسجيل مبدئيًا مع الحد الأدنى من التفاصيل وسيُسمح له بفحص عناصر القائمة قبل طلبها وإضافتها إلى سلة التسوق وإرسال الطلب. يسجل النظام التفاصيل في قاعدة بيانات MySQL بحيث يكون من السهل استرجاعها لاحقًا. يشمل مستخدمو النظام أيضًا الموظف الذي سيتعامل مع المعلومات المتعلقة بإضافة المنتج وتسليم الطلب أو رفضه.


### User interfaces GIF
![interfaces](screenshot/22.gif)

## This project was programmed by:
 Baraa  Salout        120160721 

## diagram 

### Use case diagram for Customers
![Customers](screenshot/diagram/1.png)
### Use case diagram for Employees
![Employees](screenshot/diagram/2.png)
### sequence diagram for login
![login](screenshot/diagram/3.png)
### sequence diagram for request an order.
![request](screenshot/diagram/4.png)
### Class diagram for order operation.
![operation](screenshot/diagram/5.png)

## Run project in your device:
1. install xampp by [Download xampp link](https://www.apachefriends.org/download.html) and start of **apache and mySQL** from contol panal of xampp.
2. select **explorer** from contol panal of xampp and all folder project *as name "food"* in **htdocs folder** in this folder open after select explorer.
3. add food.sql from **SQL folder** in localhost/phpmyadmin database.  
4. run project in your browser by localhost/food 

## Note:
---------
1. The username and password of sample users are stored in table `users`.
2. Only Customers with "Verified" status can place orders using "Cash on Delivery" option.
3. By default a new customer gets 2000 coins in Wallet on signing up, and a fake Credit card number & CVV number is generated and stored in SQL Table "wallet_details" with corresponding new customer's ID.
4. Use that Card Number & CVV while placing an order, else order won't be successful or use "Cash on delivery" option.
5. What's lacking? Dynamic payment(real payment system) and error reporting lacks in this project. And also one might wish for showing corresponding food item's photo and all that stuff.
