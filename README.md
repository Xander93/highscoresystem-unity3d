# unity3d-highscoresystem
A way to build a highscore system into your application.

How to use this example:

Step(1)<br>
Download the files and create a new unity3d Project.<br>
Step(2)<br>
Insert all files into the asset folder.(except the WWW folder)<br>
Step(3)<br>
Drop the files of my WWW folder into the WWW folder of your choice.<br>
Step(4)<br>
Go into whatever you use to manually modify a MySQL Database (This time i used phpMyAdmin), and create a new database.
Create New Database:
Name: yourname_scores 
Type: Collation

Use this Create Query:<br>
~~~~
CREATE TABLE `scores` (
   `id` INT(10) UNSIGNED NOT NULL AUTO_INCREMENT PRIMARY KEY,
   `name` VARCHAR(15) NOT NULL DEFAULT 'anonymous',
   `score` INT(10) UNSIGNED NOT NULL DEFAULT '0'
)
ENGINE=MyISAM;
~~~~

Step(5)<br>
The only thing you have to do is changing everything to your urls, username & password.(just watch all scripts c# and php).<br>
Run Unity3d!<br>
