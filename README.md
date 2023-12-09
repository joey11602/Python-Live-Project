# Python-Live-Project
#### This is my Python Live Project at The Tech Academy. It was a two week sprint in an Azure DevOps style project. The objective was to complete as many boards as possible with the minimum being four to pass. We were at a disadvantage due to this happening the week of Thanksgiving holiday so there were two less days to complete this. I managed to complete 5 stories. 
#### The overview of the project was to create apps designed to take advantage of various Python and Django features. We would create databases to keep track of data, interact with APIs to retrieve data, use data scraping to collect and aggregate data, and more. This project is built using Python, Django, SQLite, and HTML/CSS. 
### Story One
#### The first story that I was assigned was to create a new app for the project, named appropriately for what I was tracking, and to get it to display a home page with basic content. My app was a recipe collection called MyRecipes. The first thing to do was to create a new app using manage.py startapp. I then registered the app to the main project by editing the main apps settings.py. Then I created a base and home HTML template but I used a special naming convention to keep mine from interfering with the main apps templates. I used “MyRecipes_”before my templates individual names. After that I created a [views.py](AppBuilder9000/MyRecipes/views.py) for my app with a function to display my home page. I had to create an [urls.py](AppBuilder9000/MyRecipes/urls.py) to route my view function to the home page. On my home page, [MyRecipes_home.html](AppBuilder9000/MyRecipes/templates/MyRecipes/MyRecipes_home.html) I had to add a title, Navbar, and a footer with some basic CSS to style the background of that page. My CSS file name is [style.css](AppBuilder9000/MyRecipes/static/css/style.css). One of the last things to do was to add an image link to the main app’s home page so you could navigate to my app. I copied my part of that code and named it [code snippet](AppBuilder9000/snippet.html). I did this using a stock picture of a table with some plated food and a glass of wine, which I downloaded from the internet, [cover_photo.jpg](AppBuilder9000/MyRecipes/static/images/app-images/cover_photo.jpg). I opted to use this same picture as a backdrop for my base HTML page, [MyRecepies_base.html](AppBuilder9000/MyRecipes/templates/MyRecipes_base.html). This gave me the theme for each additional page that I would create.
![image](https://github.com/joey11602/Python-Live-Project/assets/137662879/7f4144dd-2893-46db-980a-53fe9e8eeee1)
![image](https://github.com/joey11602/Python-Live-Project/assets/137662879/7f204ece-bd69-442e-8412-00170e240f0e)
![image](https://github.com/joey11602/Python-Live-Project/assets/137662879/685b37ca-2305-4699-8e79-492cb5d9f87b)
