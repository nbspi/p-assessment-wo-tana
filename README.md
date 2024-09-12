# **Practical Assessment**
## **Lou Geh Tracking System**
Lou Geh prides itself on having up-to-date information on the processing and current location of each shipped item. To do this, Lou Geh relies on a company-wide information system. Shipped items are the heart of the Lou Geh product tracking system. Shipped items can be characterized by item number (unique), weight, dimensions, insurance amount, destination, and final delivery date. Shipped items are received into the Lou Geh system at a single retail center. Retail centers are characterized by their type, uniqueID, and address. Shipped items make their way to their destination via one or more standard Lou Geh transportation events (i.e., flights, truck deliveries). These transportation events are characterized by a unique scheduleNumber, a type (e.g, flight, truck), and a deliveryRoute.

## **Task**
1. Create a prototype based on the attached problem
2. Technologies and design to be used are the following:
    * Backend -  PHP
    * Database - MySQL
    * Frontend - Basic HTML, CSS and Javascript
3. As for your application documentations you need to provide the ff:
   1. ERD
   2. DFD
4. Provide a ```README.md``` containing the setup guide.
5. The application should be published in Github via forked repository and for final version of your prototype will create a ```Pull request``` in Github 
6. You will send the Github link to us thru our email devops@biotechfarms.com on or before **15-09-2024** 12:00 PM


    ### **Directory structure**
    ```
    my-app/
    ├── configs                      (Config scripts)
    |   └── db.php
    ├── controllers                      (PHP Controller scripts)
    |   └── UserController.php
    ├── js/
    |   └── app.js                       (Javascript scripts)
    ├── css/
    |   └── style.css                    (CSS scripts)
    ├── index.html                       (Entry point)
    ├── documentation/                   (Documentation files and assessts)
    |   └── UserController.php
    └── README.md                        (Project documentation)
    ```
    ### **Submission format**
    - Repository should show codebase directory directly **DO NOT PUT YOUR CODE BASE IN A ZIP FILE** use git commands instead to push your code-base and further updates.
    - Prototype's latest version should be the default branch of the repository.
    - Provide a READ.ME file on how to install and deploy your prototype, and its prerequisite, software, sdk(if needed), and driver.
