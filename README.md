# News Site
 News Project website is CMS base project where owner of the website have total control in the website pages like he can add user update user, delete user in this website we add 2 types of user first be a normal user he have only limited permission that he can only add the post and view other post but the Admin user or Owner have all the permission like he can delete normal user edit normal user add post add category add user and many more In this website we see category wise news author wise news and he a search a particular news To control this website from front end we first create a login from where are a check where the user is valid or not if the user is not valid then we so him a error or other vise we redirect to post.php page so if the user is normal user we bring the record from data base where we have save normal user role .in data base we have a table of user in user table we have column name like user_role where we have store 2 type of user that is 1 mins admin user and 0 mins normal user so we create a SESSION of that user user This session help us to protect all the webpages if the normal user know a particular website page we check if the normal user is there don’t entry it in over website so he can’t go to that page if he know a pages name also In this website we see a pagination were only 3 record show at a time so it make more understandable to us in this website new record be display at the top of the webpage Most important we see how to save a images in database where we only store a name of the images in data base and images store at upload type folder well all the images of the website be used