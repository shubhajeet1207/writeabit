# writeABit-BlogSite

Public blog site made with Django framework. writeABit-BlogSite is a blog page where you can create your own blogs and can see other blogs from several bloggers.
Don't forget to upload your Profile picture.
## Preview
![mockup1](https://user-images.githubusercontent.com/76960580/147415012-0afa55b8-99d7-497d-9844-1326426bd0b2.jpg)
![img-3](https://user-images.githubusercontent.com/76960580/147415016-9e146db2-5dea-45bc-80a8-3bc732a0a525.jpg)
![img-4](https://user-images.githubusercontent.com/76960580/147415019-7bc63ba8-a738-401e-b4d1-cc7ca7594cab.jpg)
![img-5](https://user-images.githubusercontent.com/76960580/147414999-5ffb213a-35b8-4c2c-859c-b5349ae6a6b6.jpg)

### Installation Process
  Run the following command in sequence for better experience of project. 
  
  ```sh 
    virtualenv [YOUR_CHOICE]  
   .\YOUR_CHOICE\Scripts\activate
  ```
  for creating & activating virtual environment.
  
  ```sh 
  pip install -r requirements.txt
  ```
  for installing packages for this particular project.
  
  ```sh
  python manage.py makemigrations
  python manage.py migrate
  ```
  for migrating the changes in database.
  
  ```sh
  python manage.py runserver
  ```
  for running web app in localhost.
  
 > NOTE: If you're using Amazon AWS S3 bucket for file storage then change the default file storage in settngs.py and add AWS credentials(Secret Key, Bucket name etc.). 
 > Don't forget to create environment variable in your system with the mentioned name in settiings.py file otherwise change parameter name according to yourself.
