# HHA504_assignment_dbs

## Azure ##
- When creating my server, a notification popped up that I did not have access to create a server in the region of *US East*. I choose *US East 2* and that seemed to work fine
- <img width="644" alt="image" src="https://github.com/user-attachments/assets/2be7c3e9-5be5-498a-ab9c-29606aca0fd7">


- Cost Summary: <img width="237" alt="image" src="https://github.com/user-attachments/assets/aa3fe33c-23f0-4c14-bfb6-ffc3c02165d2">

- The database was successfully created: <img width="729" alt="image" src="https://github.com/user-attachments/assets/f7e4b49d-3bd1-4357-ba0d-73de80c367bd">

- Database storage: <img width="547" alt="image" src="https://github.com/user-attachments/assets/f37ee234-ee54-4b3e-b7b0-d3fd8dfd996a">

- Decided to load a database of coffee consumption using Google Colab: <img width="933" alt="image" src="https://github.com/user-attachments/assets/7b687554-050f-46ac-bd49-9ed2aea25183">

- I connected to the database without having to set up variables. Since I also used Microsoft MySQL Database, instead of MySQL Flexible Servers, I didn't have to create a separate database. The admin user and password were blocked in red. : <img width="603" alt="image" src="https://github.com/user-attachments/assets/7bfc07c0-c20e-4615-913d-90be996849ae">

- When I tried reviewing the dataset I had made, an 'error' message appeared that MySQL connection had timed out: <img width="683" alt="image" src="https://github.com/user-attachments/assets/27d03cc8-c526-46a7-85f0-2d4231b7847a">
- This was verified when I went back to my database and got the notification that it had been paused: <img width="281" alt="image" src="https://github.com/user-attachments/assets/4d50f46f-b8aa-4f64-ac00-26e330c0841c">

- I disabled the auto-pause button, changed the firewall settings, and took out the firewall. I continued to get the error notification that the connection to the server had timed out. 

## GCP ##

- Cost estimate: <img width="403" alt="image" src="https://github.com/user-attachments/assets/3b49a2ca-c671-49fa-a9d9-83b11d723272">
- Compared to Azure, this seems much more expensive since it is *cost per hour* instead of *cost per month*
- After the instance was created, it was pretty easy to navigate over to the Database section: <img width="936" alt="image" src="https://github.com/user-attachments/assets/3fcfbe45-d107-4668-a018-b6a91bbd7561">
- Created a database: <img width="503" alt="image" src="https://github.com/user-attachments/assets/e3867577-a7fc-4f23-bdfb-9bf827325f31">
- One of the things I noticed was the database itself did not have the same options as Azure, where I could check the connectivity and security. I would have to go back to the 'Instance' and try to monitor things from there. 

## BigQuery ##

- I created a Python notebook inside the BigQuery feature: <img width="932" alt="image" src="https://github.com/user-attachments/assets/d711c8db-2d22-448c-9d67-fb8a693a4d16">
- When I tried to open a python notebook, it prompted the error message: <img width="911" alt="image" src="https://github.com/user-attachments/assets/551c9de7-8b00-4ed1-9a7a-f1c1ea337d30">
- I opened a SQL query instead but it was also giving me a hard time loading a dataset into the query: <img width="797" alt="image" src="https://github.com/user-attachments/assets/28a0e70b-d8f0-4548-89bf-0c905e9f514f">
- The issue with the SQL query was that it was going to retrieve the data from a bucket instead of the database I created. I clicked around to see if there was a way I could load the csv file directly into a database.
- I clicked the SQL option and was able to navigate my way back into the database I created and import a csv file: <img width="844" alt="image" src="https://github.com/user-attachments/assets/4b359821-d685-4010-b4f0-052ebfcd7ec9">
- This ended up failing with the following error message because I realized there was no existing table under that name: <img width="691" alt="image" src="https://github.com/user-attachments/assets/bc8f3572-709c-4e75-97e3-59cb00e91070">

- I once again tried to open BiQuery to see if I could open a new project but the run time was still giving me an issue


