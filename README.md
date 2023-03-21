### Your First Express and React App
Create full stack apps with React and Express. Run your client, server and do a restart of your dump db to have a full-stack project working in minutes

# Step by Step instructions - To use this project as your start point
### For create the whole project

*((notes from Camille in double parentheses and italics in markdown view))

1. Go to your source directory in your terminal and run the command `git clone https://github.com/Yosolita1978/React-Express-PairProgramming.git NAMENEWDIRECTORY`

*((cannot see the image for some reason, except for if we click to open the link))

[!You will something like this in your terminal.]


(https://github.com/Yosolita1978/screenshoots/blob/main/template/Screen%20Shot%202022-03-20%20at%207.50.46%20PM.png?raw=true)

*((this instruction didn't work for us - we don't have the role/user postgres and I believe in pair programming we didn't do this until step 9))
2. To restore the DB dump file that the project already contain, just run the command `psql -U postgres -f db.sql`. Make sure that you have your Postgres password on hand. The psql console will ask you for your password. 
3. To clean your folder from the owner git, run the command `rm -rf .git`
4. Run the command `git init` to start your git repository
5. Go to the server folder in the project (`cd server`) and run the command `npm install`
6. Inside your server folder, create an .env file with `touch .env`
7. Inside your server folder, open the file `.env.example` and copy the file there. 
8. Inside your .env file, paste the string from .env.example and change the variables with the values from the project. For this template, don't change the name of your db.
9. Inside your server file: run the command `psql -U postgres -f db.sql` to restore the DB from the file db.sql                                                         *((this instruction #9 should just be psql -f db.sql))
10. Go to the cliente folder (`cd .. and cd client`) and run the command `npm start`
11. Both server should run now with `npm start` *((this doesn't tell us to add the npm run dev script so we can run both servers concurrently, which would be helpful to have here))
12. Go to localhost:3000 and you should see something like this
[!You will something like this in your terminal.](https://github.com/Yosolita1978/screenshoots/blob/main/template/Screen%20Shot%202022-03-20%20at%208.58.13%20PM.png?raw=true)
