//-----------------------------------------------
//-----------------------------------------------
Hoang Long Nguyen - 615661
Xuan Giap Nguyen - 615643
Thi Thu Hang Nguyen - 615716
Hira Sadaf – 615700
//-----------------------------------------------
//-----------------------------------------------

Project includes 3 services running locally
1. Database: MongoDB database server
2. Front End: Web UI services
3. Back End: Web API services


1//--------MongoDB database -----------------
- Install MongoDB
    Download MondoDB server from MongoDB website and install
- Create database on local site
    Database: finalproject
    Collection: goodsusers

2//--------Back End -----------------
- Install node.js
    Download from node.js website and install
- Go to Backend folder
    cd Backend 
- Install dependencies
    npm install
- Run server
    node app.js

3//-------- Front End ----------------
- Install angular cli 
    npm install @angular/cli -g
- Go to Frontend folder
    cd frontend 
- Install dependencies
    npm install
- Run server
    ng serve

//-----------------------------------------
//-----------------------------------------
Open browser on http://localhost:4200/ to see the website.
- At homepage, a list of items will be displayed
(At the beginning when the database is empty, there is no item. After signing in and add items, you will see a list of item in homepage)
Features:
- Sign up to create a new account
- Sign in
- View/Edit account profile
- View purchased item list
- View posted item list
- View general item list
- View item detail
- Purchase/Post an item
- Search (by Address, Category, Status) items
//-----------------------------------------
//-----------------------------------------