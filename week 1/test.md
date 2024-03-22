# **بسم الله الرحمن الرحيم " وقل اعملوا فسيرى الله عملكم ورسوله والمؤمنون " صدق الله العظيم**

# `Web Development Basic`

# There are some important concepts that must be studied before starting A journey to learn web programming:  

# Client Server Model (CSM)
# `1.` What is Client Server Model ? 🤔<br>
#### -Client Server Model is Distributed Application Structure that partitions tasks between the User(client) and the Server by using a HTTP(Hyper Text Transfer Protocol ) that get Request from user and send it to server or opposite and send Respond or service from server to user.
#### -Client-Server Model represents a system that consists of two main components the server and the client(user).
# الكلاينت سيرفر مودل بيكون عبارة عن مودل بيربط بين اليوزر والسيرفر بس هل ينفع نربط بينهم بشكل مباشر كدا أكيد لء طب ليه لء عشان لا اليوزر فاهم السيرفر بيعمل اي ولا السيرفر فاهم اليوزر عايز منه اي فبنربط بينهم ببروتوكول

## Click to This link if you want to know more about  [Client Server Model](https://en.wikipedia.org/wiki/Client%E2%80%93server_model)
## This Figure represent  the client server model:
![](images\CSM.png)
---------------------------
# HTTP
# `2. What is HTTP? 💻 `<br>
#### -It's an abbreviation for Hyper Text Transfer Protocol , and also it represent a link between the User and the Server.
#### -It is designed for communication between Wep Browsers(client) and Web Servers(web server).


# باختصار هو حلقة وصل بين الكلينت والسيرفر  
![](images\HTTP.png)
## Click to This link if you want to know more about  [HTTP](https://en.wikipedia.org/wiki/HTTP)

---------------------------
# `3.What is Web Application ? 🤔`<br>
#### -It's Software Application that runs on Web Server.
#### -Web Application is a client side and Server side Software application in which the client runs and can request service via web browser.
#### -It can easily accessed by internet.
#### -It's Distributed application , in which part is front-end and another part is Back-end and we connect between them using API.
# الويب ابلكيشن هو تطبيق بيرن علي سيرفر كبير وممكن نرن اكتر من تطيبق علي السيرفر الواحد.السيرفر الكبير بيserve دينامك سايت مش استاتك سايت.

![](images\API.png)

## Click to This link if you want to know more about  [Web Application](https://en.wikipedia.org/wiki/Web_application)

---------------------------

# `4.What is The difference Between The Static Site and The Dynamic Site ?  🧐`<br>
#### -Static site -->> A static website is made up of web pages created using HTML, CSS and Javascript (all examples of web development languages). Each page on a static website is stored as a single HTML file, which is delivered directly from the server to the web page exactly as is. This content essentially becomes a part of the design on your page, and won’t change unless the original HTML file is edited at a code level. 


#### -Dynamic page -->> Built using server side  language and technology, dynamic websites allow for the content of each page to be delivered and displayed dynamically, or on-the-fly, according to user behavior or from user-generated content(modification). 
# افتراضا عندنا ويب ابليكيشن كبير زي الفيسبوك.الويب ابلكيشن الكبير دا بيستخدمه اكتر من 2 مليار شخص علي كوكب الارض فهل منطقي كدا ينفع نعمل الموقع استاتك اكيد لء فرضا انت عملت الموقع استاتك واول لما بتدخل الموقع بيظهرلك الصفحة الرئيسية فأنت لما تحب تتنقل بين صفحة وصفحة تانية هيجبلك في كل مرة الصفحة الرئيسية عشان الداتا عمرها مهتتغير لأن الويب سيرفر بي serve استاتك سايت فمنطقي يبقي لازم نستخدم دينامك سايت علشان تقدر توصل لأي صفحة انت عايزها طب انت تقدر توصل لأي صفحة ازاي بقي دا الموضوع الخامس اللي بنتكلم عنه         
 ## Click to This link if you want to know more about  [Difference](https://www.wix.com/blog/static-vs-dynamic-website)

 👇👇👇👇

---------------------------
# `5.Dynamic Site Cycle` 


#### - User want to see  something in a web page.
#### - HTTP send request to the web Server.
#### - The Server determined Product ID.
#### - The web Server determined that the request is dynamic and forward it to the web application to  generate HTML code.
#### -Fetch data from Data Base according to ID.
#### -Construct HTML from files that exist in the server and inserting data that fetched in it as HTML template.
#### -Send the template to the client.
# ازاي نقدر نتنقل من صفحة لصفحة دي الويب ابلكيشن اول من عنوان URL الي عنوان URL تاني ؟؟؟؟
# اول لما المستخدم يكتب علي البراوزر عنوان ال URL اللي عايز يوصله تلقائي كدا البروتوكول بيرسل ريكويست للويب سيرفر والويب سيرفر يقرأ الريكوست وبعدين يقبله ولو اليوزر كان طالب static site  هيرجعها علطول انما لو طالب dynamic site  يروح عند الداتا بيز وبعدين في الداتا بيز بيكون موجود اكتر من صفحة يمكن الوصول لها او بالتحديد عدد الصفح المتاح لليوزر ان هو يوصلها في الابليكشن المفتوح علي الويب سيرفر فالوقت دا وليكن انا فاتح الفيس خلاص يبقي موجود في الداتا بيز الصفح اللي انا اقدر اوصلها من خلال عنوان URL اللي المستخدم عايزه وبعد منجيب الداتا المطلوبة محتاجين صفحة HTML علشان ندخل فيها الداتا اللي جيبناها دي ونرسلها للويب سيرفر مرة تانية وييجي هنا دور البروتوكول بقي ويرجع الصفحة للمستخدم وبكدا يكون البروتوكول نفذ مهمته وجع صفحة HTML للمستخدم فيظهر في البراوزر الصفحة اللي هو كان عايز يوصلها. العملية دي تتم في وقت صغير جدا جدا يكاد يكون مش ملحوظ لو مفيش ضغط عالويب سيرفر.


----------------------------

# `6.HTML,CSS,JavaScript` <br>
#### -HTML is used to create the structure of web page.
#### -CSS is used to design how it looks like.
#### -Javascript is used to make interactive features and هt gives the site a special dynamism.

# علشان ابني موقع لازم استخدم لغة HTML اللغة دي هي اللي بتحدد الهيكل بتاع الموقع او بتصف الهيكل بتاع الموقع وهي عبارة عن مجموعة Tags   وبعدين لازم نضيف بعض الألوان للمواقع كدا عشان يبقي شيك وعشان يكون  في تغذية بصرية للموقع بردو احنا دورنا اي غير اننا نريح العميل 😁 وبعدين بقي لغة جافا اسكربت هي اللي بتدي للموقع ديناميكية خاصة كدا وتخلي الموقع interactive كدا .
# بس وجود لغة جافا اسكربت لا تعني ان الموقع dynamic لء هي بتكون موجوده عشان تinteract بين ال component
---------------------------- 
# `7.Web Server `

#### -It's what derive web application or web application runs in it .
#### -It hanle  Authentication .
#### -It  handle Routing .
#### -It connect with Database .
# الويب ابلكيشن هو تطبيق بيرن علي سيرفر كبير وممكن نرن اكتر من تطيبق علي السيرفر الواحد.السيرفر الكبير بيserve دينامك سايت مش استاتك سايت.
----------------------------
# `8.FrameWork`
# هو structure مكتوب فيه اكواد كتير هحتاجها فبدل مكتبها كلها تاني بستخدم الframework فهتوفر معايا مهام كتير

---------------------------
# The Software Architecture
## We Knew the High level System Architecture " Client Srever Model " . It's time to know the design of our web application .  

## `1.Design Patterns`
### -"A pattern is a soluton to a problem in the context" .         
### -context : Creating web application
### -problem : separete the functionality of web application
### -solution : using organisations of classes
# الديزاين باترن هو طريقة لحل مشكلة ميعنة وال context هو بناء ابلكيشن والبروبلم هو اني اجزء الfunctionality الي اجزاء صغيرة عن طريق اساخدام مجموعة من ال classes

---------------------------
# `2.MVC`

#### -It's abbreviation for Model View Controller . 
#### -It's a paradigm that factoring your code into functional segments so your brain doesn't explode and make code resuable .
#### view : الجزء اللي بيinteract مع ال اليوزر 
#### model : الجزء اللي بيتعامل مع الداتا بيز
#### controller : الجزء اللي بيربط بين ال view  وال model 
![](images\MVC.png)