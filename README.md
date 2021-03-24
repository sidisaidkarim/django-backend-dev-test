# django-backend-dev-test
A test to accomplish for a django backend dev position


given a simple Django app, with registration and authentification done,  create simple integration for a statistics functionality (stats about a detailView, for listing model ).

create models.py and views.py


![image](https://user-images.githubusercontent.com/13240505/112318785-b3e08a00-8cad-11eb-8c94-a2350f33500b.png)


## requirement 
#### 1. for each listing we need to have:
  - number of all visits per day (anonymous and conneected users visits )
  - number of anonymous visits per day ( all visits made but not connected users, for this we use user IP, a visit is counted only if last visit was 2 hours ago)
  - number of connected users visits per day ( same as for anonymous users )
  - number of all unique visits per day
  - number of anonymous unique visits per day ( a user visit is counted once for all)
  - number of connected users unique visits day( a user visit is counted once for all)
#### 2. the statistics view should return a json response, formatted to be used with Charjs

  ![image](https://user-images.githubusercontent.com/13240505/112321145-fefb9c80-8caf-11eb-9865-53ac0505b9c2.png)
  
  an exemple of real data display in chrom dev tools consol
  ![image](https://user-images.githubusercontent.com/13240505/112325714-38cea200-8cb4-11eb-82ef-7031f3c5c06d.png)

  
#### 3. the stats view can take 2 arguments , start_date and end_date
#### 4. comment the code to explain the process of adding stats, and displaying them 
#### 5. no external package, no copy past from other repos 
#### 6. This is a part of an actual feature we already implemented for our projects
