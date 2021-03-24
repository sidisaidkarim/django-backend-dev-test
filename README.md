# django-backend-dev-test
A test to accomplish for a django backend dev position


given a simple Django app, with registration and authentification done,  create simple integration for a statistics functionality (stats about a detailView, for listing model ).

create models.py and views.py


![image](https://user-images.githubusercontent.com/13240505/112318785-b3e08a00-8cad-11eb-8c94-a2350f33500b.png)


## requirement 
#### 1. for each listing we need to have:
  - number of all visits
  - number of anonymous visits by day ( all visits made but not connected users, for this we use user IP, a visit is counted only if last visit was 2 hours ago)
  - number of connected users visits by day ( same as for anonymous users )
  - number of all unique visits
  - number of anonymous unique visits ( a user visit is counted once for all)
  - number of connected users unique visits ( a user visit is counted once for all)
#### 2. the statistics view should return a json response, formatted to be used with Charjs

  ![image](https://user-images.githubusercontent.com/13240505/112321145-fefb9c80-8caf-11eb-9865-53ac0505b9c2.png)
  
#### 3. the stats view can take 2 arguments , start_date and end_date
#### 4. comment the code to explain the process of adding stats, and displaying them 
#### 5. no external package, no copy past from other repos 
