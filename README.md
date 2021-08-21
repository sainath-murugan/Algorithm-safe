# Algorithm-safe
The idea of this project is based on storing passwords and other useful keys in cloud. So the user can access the keys or passowrds at any time. It helps to avoid resetting passwords and keys.

This project is developed in `django` and includes other python libraries. This project uses `allauth` for good user authentication and security. `AbstractUser` class is used to extend user model for good flexibilty. I have used `django_user_agents` to monitor the user device and ip, so the user's address will be stored in every logins.

The keys and passwords also monitored, so the last modified date will be saved. This project includes `Two factor authentication`, so the user can keep his/her account more safer. I have used `pyotp` and `qrcode` libraries to develope `Two factor authentication`. I have also used `captcha` in some forms for better validation.

This project uses `UUID` as primary key for all models, so the real data sets in database are not exposed in browsers.

I have used bootstrap, css, javascript, jquery and other css libraries like AOS for frontend. This project has good and flexible frontend design, so this website can be viewed in both small and big screens.

This project is deployed in heroku and it's now live [click here](https://algorithm-safe.herokuapp.com/) and join in algorithm community.
