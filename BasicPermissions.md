<h1 align=center> Basic Permissions </h1>

<h2> Description </h2>

Can you find out how to get permissions to run the file?

<h2> Break Down </h2>

A file named basic_permissions.zip is given to us. We are looking to open the file and run it. The first thing that comes to mind is the <b>chmod</b> command. </br>
<b>Chmod</b> allows you to change the file permissions of the a file. With that being said we have all the tools we need to solve the problem.

<h2> Step 1 </h2>
Unzip the file. <br>
On linux, you can use the command <b>unzip</b> followed by the file name (i.e., unzip basic_permissions.zip). <br>
This will extract the contents of the zip file into your current directory. <br>

<h2> Step 2 </h2>
List the files in your current directory with long format. <br>
To do this do the command <b>ls -l</b>. This will allow you to see file permissions on every file in your current directory. <br>
You'll notice that the application we unzipped does not have <b>executable</b> permissions. We know this because there is no denoted <b>x</b> character on the line where we can see our application permissions. <br>

<h2> Step 3 </h2>
Change the permissions of the application. <br>
To do this you can use the <b>chmod</b> command. <br>
There are different arguments you can specify to use the <b>chmod</b> command and make the application executable. <br>
I used this like this: <b> chmod 777 "application name" </b> <br>
The 777 allows for each user/group to have read/write/executable permissions. <br>

<h2> Step 4 </h2>
Execute the application. <br>
To do this, you do the following command: ./"application name" (excluding the quotation marks) <br>
You'll then see the flag.






