# HHA504_assignment_nosql_dbs
Assignment due 10/29

# GCP

BigQuery was already initialized from previous projects.  I created a new dataset titled HW and a new data table named MyData.  I uploaded the .CSV file to it, and than ran a query.  I was able to expand the job details tab to see the cost and information associated with the query.

![GCP_BigQuery_Create_Database](https://github.com/user-attachments/assets/6a3e5f22-c792-47cf-961a-9256bb25743a)
![GCP_BigQuery_Create_Table_add_Data](https://github.com/user-attachments/assets/057cdf64-3fd1-4cb2-8894-ea867a559f49)
![GCP_BigQuery_Run_Query_Check_Costs](https://github.com/user-attachments/assets/0275d3b8-d480-422b-a262-68320ec9bea4)

# MongoDB

MongoDB was setup while following along during class.  To proceed easier I donwloaded and installed MongoCompass GUI.  After connecting I created a Database named HW and a file named MyData.  Mongo compass has a feature to install from a .csv which I did, and Compass was able to format the .csv into a MongoDB Format.  After that running queries was easy, using compass which incorporates gemini to assist in proper query syntax.

![MongoDB_Start](https://github.com/user-attachments/assets/0f1dd29b-4386-46e6-a19c-c076239b8449)
![MongoDB_Connect1](https://github.com/user-attachments/assets/cd3551ab-3360-4d8d-8130-7536e533fb35)
![MongoDB_connect2](https://github.com/user-attachments/assets/cac70df6-a17a-4d01-8766-e0f1d5dab8a8)
![MongoDB_Add_Data](https://github.com/user-attachments/assets/0e7ead6b-27a9-4e76-8b35-fe208f1d9176)
![MongoDB_Query](https://github.com/user-attachments/assets/affed60c-9351-4dfb-b815-0abf908202a1)

# Redis

Signed up for Reddis which gives you accees to 1 free database, so that had to be the database I used.  Installed Redid Insight to make interacting easier.  Had troubble using the Python code to upload the info from the .csv.  Instead I converted the .csv to Json using a conversition tool, and the had to manually insert each key.  After that I looked up the proper syntax for redis queried and made sure the data was entered correctly.

![Redis_Start](https://github.com/user-attachments/assets/6f1c2690-3754-4f2a-8286-a83cb0a14d79)
![Redis_add_keys](https://github.com/user-attachments/assets/67c63ed5-670c-48df-b75d-ab8b07969765)
![Redis_key_info_JSON](https://github.com/user-attachments/assets/08068ca0-d9be-4dcf-884f-c7a4b3ed910c)
![Redis_Query](https://github.com/user-attachments/assets/2caf23eb-3729-439a-93f4-9d55d5dac2fa)
![Redis_result](https://github.com/user-attachments/assets/e6e6d10e-769a-4c17-8beb-4475e5792616)


### Reflections

Bigquery was the easiest to work with due to my familiarity with GCP and SQL.  Both mongoDB and Redis required installing and working with unfamiliar programs.  MongoDB and Redis also work in JSON formats when Im more familiar using data from .csv. The helper programs MongoDB's Atlas and redis insight did help to navigate the programs.  Atlus even simplified the process of converting my .csv to JSON format without using any extra coding.  Im sure things would have been much harder wihout them.  If I were using Redis again in the future, I would use a manual sign up process instead of sigining in with my google account so I would be able to set my password myself.  I think that was why I was having troule accessing Redis using python. 
