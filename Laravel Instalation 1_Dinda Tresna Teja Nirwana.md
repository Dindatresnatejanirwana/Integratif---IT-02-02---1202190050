# Final Project Phase 1

#### Install Laravel

1. Before we start, **make sure you have xampp and composer installed**

1. The first step is open the Command Prompt. Click Win+R then type cmd and click **OK** to display the Command Prompt.

![1](https://user-images.githubusercontent.com/95134218/172410340-7146f702-4ca1-4298-9daf-54764cca55e4.PNG)

2. Before installing Laravel, direct  Command Prompt to file server directory. File server location on XAMPP by default is in the xampp/htdocs directory. Enter this command in the Command Prompt to enter the htdocs directory.

   ```markdown
   cd \xampp\htdocs
   ```

![2](https://user-images.githubusercontent.com/95134218/172410392-de30871a-e745-454d-b9f9-51644e869617.PNG)

3. Furthermore, if you have entered the htdocs directory, you must make a request to retrieve (and install) Laravel files that have been provided in the Github repository. Use this command to make a request:

   ```markdown
   composer create-project --prefer-dist laravel/laravel nama_projectmu
   ```

   If the command has been successfully entered, Composer will begin the process of fetching data and installing Laravel into the directory you specified. Make sure that the internet connection is stable so that there are no interruptions during the Laravel data retrieval process.

![3](https://user-images.githubusercontent.com/95134218/172410411-06d9e4f8-815e-4738-8b4b-7610c945d54c.PNG)

4. After the Laravel file download process is complete, there will be a new folder in the file server directory with a name according to the project name that you previously specified in the /xampp/htdocs folder.

![4](https://user-images.githubusercontent.com/95134218/172410439-e86c1af0-5eef-4ab2-b1bc-c39827987340.PNG)

​	To ensure that Laravel is successfully installed and ready to use, navigate to Command Prompt or Terminal to the directory you created earlier. Then, enter the following command into Command Prompt or Terminal:

```markdown
php artisan serve
```

![a](https://user-images.githubusercontent.com/95134218/172410521-a929a755-462f-47b3-8e4a-277fadd09517.PNG)

5. If Laravel development server started appears in the Command Prompt or Terminal, the next step is to open the link provided by Laravel. By default, you will be directed to the server address, which is 127.0.0.1:8000. Later, a homepage will appear with Laravel writing in the middle as shown in the image below:

![5](https://user-images.githubusercontent.com/95134218/172410464-c309a545-9c81-4044-8f64-ae83004ad06f.PNG)
