# writeABit-BlogSite
Live at: [https://writeabit.herokuapp.com/](url)

Public blog site made with Django framework. writeABit-BlogSite is a blog page where you can create your own blogs and can see other blogs from several bloggers.
Don't forget to upload your Profile picture.

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
