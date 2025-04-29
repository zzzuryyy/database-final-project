# database-final-project

For my project, I’m proposing a web-based database site that will track the Personal
Records(PRs) of a sports team. The main goal is for athletes to be able to track their progress and
for coaches to be able to share their player's lifts with any recruiters or other schools. The app
will do both in a simple and streamlined manner.
The system will be divided into two broad user roles: Players and Coaches. The concept
here is to keep things simple and accessible. Players will only have access to view records of
others, enabling them to get updated about the progress of the team and compare their own
performance. Coaches will, however, be able to modify and update the records, and this will
grant them the autonomy they require to monitor and lead the team's performance over time. Not
allowing the players to edit their own records will also add an extra level of validity to the site
since others will know that only coaches can adjust records so the players can’t lie.
The backend will be implemented with Python. As for the database, MySQL will be
used. The front end shall consist of a combination of HTML, CSS, and JavaScript.
A rough draft for the database design will be Users (UserID, Username, Email,
PasswordHash, Role), Records (RecordID, UserID, ExerciseType, WeightLifted, DateAchieved),
and Exercises (ExerciseID, Name, Category).
My primary objective is to keep it simple. I focus on a design that is well-working:
functional, clean, and simple. The beauty of the system will be a plain, easy-to-conceive layout
where players can see how they are performing and coaches have an easy method for updating
the records.
Overall, I'm envisioning a system that is simple to use, effective, and simple to deploy.
By focusing on these basic things, I'm hoping to create a tool that serves both coaches and
players equally, providing them with the performance data they need without any extra
unnecessary bells and whistles.
