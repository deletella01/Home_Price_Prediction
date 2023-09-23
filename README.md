![](landing page.png)

# Home Price Prediction
Home Price is a web application that predicts the estimated cost of Accommodation in Bangalore, India. The user will provide the size of accommodation in square feet(Area), Number of Rooms, Number of Bathrooms and desired Location. The application uses a Machine Learning Linear Regression technique to develop a model trained with a dataset of prices in Bangalore, India, obtained from kaggle.com. A Python flask server that uses the saved model to serve HTTP requests is written and the website is built in HTML, CSS and JavaScript which calls the Python flask server to retrieve the predicted price based on user input. 

Technology and tools used in this project include:

1. Python
2. Numpy and Pandas for data cleaning
3. Matplotlib for data visualization
4. Sklearn for model building
5. Jupyter notebook, visual studio code and pycharm as IDE
6. Python flask for HTTP server
7. HTML/CSS/Javascript for UI


## Deploy this app to the cloud on Amazon Web Services (AWS) EC2

An EC2 instance using Amazon console was created and The Web Application is hosted on the free server provided by Amazon Web Services. Nginx is used to connect the Front-end and Back-end to the AWS EC2 server.

Check out the Fully functional website running in a production cloud environment: [Home Price](ec2-13-53-143-109.eu-north-1.compute.amazonaws.com)
