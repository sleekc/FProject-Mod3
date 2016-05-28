FProject-Mod3 - Project Submission on 19062016-2359

Video Demo Link: https://www.youtube.com/watch?v=9KvlihM34_4

Folder -> yun-fsr-led-simple contain yun-fsr-led-simple.ino (arduino to read sensor data and send the reading to AWS debian)

Folder -> cps contain php script in AWS

1)cps.php->The script connect,and insert the value into the database.

2)cpsdata.php->Script the do a sql query, count all the reading in a day, prepare the return data in json for google chart.

3)cpsdashb.html/index.html/indexl.html->a script that read the json data from cpsdata.php and draw on a line or bar chart.
