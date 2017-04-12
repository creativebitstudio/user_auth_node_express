# User_auth_node_express

This is a user authentication application using sessions and cookies as authentication.

## Technologies used

* node 6.9.0
* npm 4.1.1
* express 4.14.1
* mongodb 3.2.10
* Pug 2.0.0-beta7

Further technologies and dependencies can be found in the package.json file.

#### How to use it

1. Clone (git bash recommended) or download the zip file onto your computer.
2. Open folder in preferred text editor.
3. Before running the application, open three terminals (on git bash or cmd prompt).
4. In the first terminal, type mongod to access the host process for the database. If all goes well you should see zero errors. Usually what will sho win the last line will be an OK, connection 127.0.0.1, or running on port 27017.
5. On the second terminal type mongo, it will be your command line shell. If no errors show, on the last line it will show connecting to: test, or simply test. 
6. On the third terminal type - nodemon app.
7. If no errors show you are all set to go!

Further documentation on mongo shell commands can be found at https://docs.mongodb.com/manual/

On a later date we will be releasing a cheat sheet on mongo shell commands, stay tuned... 

Note: follow steps 4 to 6 exactly to avoid any errors.

## Note 

Feel free to use this application as part of a web project, however, if used in production, consider security when implememnting this code. For starters, always use HTTPs and consider modifying code to add even more authentication.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

### Authors

* Developed for CreativeBitStudio by Danny Mack - Full Stack Developer.
* Developer Feedback or for Hire: creativebitstudio@gmail.com.

### Contact

* To contact or hire us: info@creativebitstudio.com.
* Website: www.creativebitstudio.com

