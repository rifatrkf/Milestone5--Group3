# Monitor IoT Fuel Distribution Dashboard
This repository will explain how to access the dashboard for IoT fuel distribution management system. There are two ways for accessing the dashboard.
First, we can directly accessing this dashboard via google data studio. Second way is accessing in our local machine, this repository provides the file that was developed by django. For more information about this project development, kindly check to this [link](https://github.com/hadhari/IOT_Fuel-Distribution-Management-System).

## How to clone this repository

1. Open the terminal in our personal computer.

2. go to the root directory that will be save our clone. for example
  ```
  cd project/ms5group3
  ```
  
3. Then clone this repository with the command below:
  ```
  git clone "https://github.com/rifatrkf/Milestone5--Group3.git"
  ```
  
4. We need to create the virtual environment before installing django. To find out why we use a virtual environment, we can see in the following link [Python Virtual Environment](https://www.geeksforgeeks.org/python-virtual-environment/#:~:text=A%20virtual%20environment%20is%20a,of%20the%20Python%20developers%20use.)

5. Create and activate a virtual environment (virtualenv) with the name 'env'. 
```
sudo pip3 install virtualenv
virtualenv env	
source env/bin/activate	
```

6.  install the latest Django via pip
```
pip install Django
```

7. To run the dashboard, go to the milestone5 directory
```
cd milestone5
``` 
8. run the development server "manage.py" using python

```
python manage.py runserver
```

if using python3 use this command

```
python3 manage.py runserver
```

9. Then a message like the one below appears
```
Watching for file changes with StatReloader
Performing system checks...

System check identified no issues (0 silenced).
February 19, 2022 - 11:31:19
Django version 4.0.2, using settings 'milestone5.settings'
Starting development server at http://127.0.0.1:8000/
Quit the server with CONTROL-C.
```
