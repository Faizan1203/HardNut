# Capstone
#### Video Demo: https://youtu.be/HZkOODibc1c

### Distinctiveness and Complexity:
The purpose of this website is that it provides an opportunity to the student to create his goals, plan the goals based on his own timelines by creating rooms having a timer set or a promo Doro timer to keep track on the time spent on a goal, flexible to make changes to his goals, delete the goals if not relevant and provide a dashboard to view the total goals created, goals achieved and in progress goals. This website is specifically targeted to students who have mild to tough goals set in their academics and would like to have a plan to stay disciplined and track their progress made on the goals periodically and be focussed to achieve their toughest goals with in their planned timelines. The user can also document the reward he would get on successfully achieving the goal, this way he can keep himself motivated to achieve the goals faster.I have created 3 Django models, 8 html files, 6 Java Script files. I have also used different kinds of animations such as grow, move and fade in. I have utilized various bootstrap elements such as buttons, navbars, cards etc.

Home Page: This is the landing page of the website. When the user lands on the home page, he is greeted with a welcome message and website logo which has been animated. The page provides the user to Register for new users and log in for existing users.Once the user is successfully registered, he can login to the website with the valid credentials.The application has primarily three tabs. They are Goals, Study Now and Goal Analysis.The user is provided with log out option to log off the application successfully.

Goals – Create a goal with the title, planned end date and the rewards that the user plans to receive on completing the goal successfully. The purpose of having the rewards is to motivate the user to achieve the goal faster.The user can edit the goal which is in progress to make changes to the title, dates or rewards.The user can delete any goal which is in progress if he finds the goal not relevant.The user can update the status of a goal in progress to complete if the goal is achieved before the end date. The goal then becomes completed and remains un editable.

Study Now – This tab provides the user with the ability to create a room whenever he plans to work on a goal. The user can create a room by clicking on Create Room button.Once the room is created, the user can navigate to the room where he is provided with an option to set a promo Doro timer or a regular timer to work on the goal.The user is provided with the option to start or reset the timer.The user can view the rooms created by him, edit the room name and can also delete the rooms in case he does not want to study.

Goal Analysis – This tab displays the list of total goals created, the list of completed goals and the list of in progress goals with user-friendly interface depicting images.

How to run: The server can be started by using the regular python manage.py runserver command in the terminal

Addtional Packages: I did not use any additional python packages in this project

Files: The capstone Folder has all files that are created by django and I made a few tweaks to them to make the server run. The hardnut folder has the migrations folder which had the details of the history of the migration. The static folder has all the static pictures and js files. the templates folder has all the html files. The rest of the files include admin, models, tests, urls which have all been configured by me to work the way i want them to. The database has some sample data that was used to test the project.