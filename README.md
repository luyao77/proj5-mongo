# Project 5: Brevet time calculator with Ajax and MongoDB

* The rules of the brevet time calculator is based on the https://rusa.org/octime_alg.html ,                   
  https://rusa.org/pages/rulesForRiders, it works should like  https://rusa.org/octime_acp.html.
* More details of the rules:
  the open time is calculated by the max speed, close time is calculated by the min speed.
  different control distances has different min, max speed, control distances got by the km(user input)
  the job here is to determine the range of control distances, and get it open and close time correspond
  to it speed.
* More things of this project:
  This project need us to collect the data in the database and display them using "submit" "display" buttons
  it practices the skills of using docker-compose, flask, ajax, and mongodb (pymongo).

## Author and Contact
Luyao Wang     :     luyaow@uoregon.edu

## Run
  In the terminal, find the correspond directory and type:
  * docker-compose build
  * docker-compose up
  then go to the http://127.0.0.1:5000/ to test them
