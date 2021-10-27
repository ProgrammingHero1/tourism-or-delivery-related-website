## Task Description: 
Our company focused on tourism and delivery related services. Currently, we are looking for a front-end web developer to build a full-stack website using `React`, `firebase`, `react router`, `node`, `express`, `mongodb` etc. 

We have a sample task for you.


### Website Purpose:
1. Website has to be a travel, tourism, vacation or delivery service related website. Some examples are: tour planner, tour booking website, vacation planner, traveling agent, tourism related bus/car/plane/cruise/kayak/etc., ticket booking, camping planner, theme park (fantasy kingdom, nandon, etc), any vacation related activity provider. Another option could be delivery services. Like Food delivery, food catering, parcel delivery, courier service, same day delivery service. However, it can not be a restaurant or an e-commerce site. 

2. Make sure your design and website idea is unique. First, finalize your idea (what type of website you want to build). Then google the site design or visit themeforest. to get your website idea. However, your website can not be related to your previous assignments or any demo project displayed in the course or in our conceptual sessions.
3. Do not spend too much on thinking. Start on an idea. sometimes, put a placeholder image and keep developing the functionalities. 

## Task Detail: 
1. Home page will have a header (simple navbar), banner, offerings (Items/services/items/options/travel plan:  the main items that user will purchase), and footer.
2. Add two extra sections in the home page in addition to the 4 sections mentioned above. 

3. The Offerings will have at least 6 items/services. You can put one or more items/services in a row based on your design. Each service should have a relevant name, image, short description and a purchase button (button could say: book now, buy now, order, etc.). 
4. Clicking on the button will take the user to the place order page. This route will be a private/protected route. Please make sure that if the user is not logged in, the private route redirects to the login page. After login, the user will be redirected to the page he/she wanted to go to.
5. The Place Order page should display detailed information of the item, user has clicked. It will display users name and email address from the login system and user will provide address and necessary information to place the order/booking/purchase. 


6. Implement at least one (google, facebook, github,or email/ password) authentication. Once a user is logged in, the user name, logout button should appear on the header which will log out the user once clicked. Displaying user profile pic on the header is optional.
7. If a user is logged in, he/she will see more options like `orders`, `admin:Manage orders`, `admin: new service`, `logout`. Based on your website idea, you can change the name of these menu items. On the orders page, the logged in user will see only his/her orders. If the user wants, he/she should be able to cancel/delete the order.  

8. On the admin: Manage Orders page, the logged in user will see the orders placed by everyone. If multiple users placed the order, everyone's order will be displayed here. and the admin will be able to delete an order.
9. on the `admin: new service`, the admin will be able to add a brand new service. After adding that service, this service will appear on the home page. The name `add new service` could change based on your website. On this page, you can either put an input field to put an image url. (For simplicity, you can upload the image to imgbb or other image hosting website and then put the url on the input field)

10. No Fake data (data has to be hosted on the database). database could be mongodb atlas or any other noSQL database.

### Bonus: 
1. Make the website meaningful and consistent in look and feel. Give your website a relevant name. Images and all the content of the website has to be relevant. No `lorem ipsum` please.
2. Meaningful `readme.md` file containing your website name, a little description, link to your live site. And at least five bullet points mentioning different features and functionality of your website.
3. After reloading the page on a private route, the user should not be redirected to the login page.
4. Make the website responsive. Make sure the site looks different on desktop and mobile responsive. Tablet responsive is optional
5. Ask a confirmation message before deleting or canceling an item. Using browser confirmation dialog is ok. 
6. Clean and organized Code. Organize components and add comments when needed
7. Add a loading spinner on the home page, if data is loading a spinner will be displayed.
8. use .env file to hide db user and password and also use .gitignore file

### Optional:
1. At the time of placing an order, the order will have a pending status. On the admin: Manage orders page, an admin will be able to update the status of the order as approved.
2. Try to use a better looking confirmation dialogue other than the browser's default confirm.
3. On the `add a service` page, try to implement direct image upload from your computer. This image can be hosted on third part image hosting like imgbb or directly to mongodb
4. Add some mouseover animation while taking the mouse on the services/items card
5. Please Use icons whenever applicable and use fonts
6. Make the footer little more realistic
7. Optimize your images
8. Add something extra of your own. This will help you in the future.
9. Most of the booking will have a date, you can use browsers default input type date or any external packages



### Additional information:
1. You can use local image or host image anywhere if you want or both.
3. You are free to use any css library you want. But, we recommend using tailwind css. 
4. If needed you can mix CSS framework with a component library
5. You may use `react hook form`, basic html form or any library for authentication
6. Local storage is optional
7. Environment variable is recommended but optional
8. Try to host your site on Firebase (Netlify host will need extra configuration)
9. Try to host server on heroku

### What to submit 
1. Your client side code github repository
2. Your server side code github repository
3. Your live website link



Have FUN! Have Patience. 
