## Introductiom
Meet our Etsy Gourmet pastry shop, where multiple sellers can share their delicious pastries, chocolates and cheeses.
This API enables a user to filter all the products displayes on our e-shop as well as find products by category.
It also has an interface for visitors willing to be sellers, and share their products. 
By creating our own API, we are able to pull the products from our database we were able to pull data as well as create a unique UX/UI design, according to our wireframe.
Discover our e-shop at : **https://gourmet-e-shop-front.netlify.app**

## Features : 
Our e-shop offers two sections :
- The fist for visitors/potential buyers. They have the shop all the products and filter them by category. They can also just search for a product, thanks to the search bar. They can combine the category drop-down menu and and the search bar, by searching for a specific product within a category.
- The seller page view : sellers' home page will feature all the products that seller has, give sellers the option to add a new or additional product. The number of units sold per product, will be featured on each product. They are also greeted with the total amount of products sold they've sold, amongts all products. Sellers also have the option to delete and edit each of their products.

## Technology Stack :
**Front-end : **
- vite,
- React,
- Axios as an alternative to fetch data from the backend
- bulma (for the styling)
- using Netlify to deploy the front-end

**Backend (our API): **
- Express,
- mongodb for the database
- Mongoose as well as some of it's features : mongoose unique validator and mongoose hidden.
- Accessing the backend only : https://gourmet-e-shop.netlify.app/api/products
- Uploading the databaase using Mongo Atlas
- Using additional libraries, apps and features such as bcrypt to hash the passwords, JTW(jsonwebtoken) to assign a token to each logged-in user


