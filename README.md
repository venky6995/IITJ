# IIT Jodhpur Assignment - 1
==========================

**About the Project**

This project is a part of the assignment challenge, where I, Doddi Venkatesh(G23AI2122), have showed a series of projects to demonstrate my skills in Docker.

**Running the Container**

To run the container, follow these steps:

### Building the Docker Image
```
docker build -t mybuild -f dockerfile .
```
**Running the Container**
```
docker run -it --name mypro -p 80:80 mybuild
```
**After getting inside the container**
Run the following command:
```
service apache2 start
```
After which open the browser and type the following thing in the browser:
``` 
localhost/myproject/
```

**Installed Packages**
* Git
* Apache2
* Net-tools
* Curl

**For Troubleshooting**

You may also see the following commands for troubleshooting if everything went correctly or not. 

```
docker images
docker ps
docker ps -a
```
or after login into the container into the bash :

```
service apache2 status
```
**Apache Configuration**

Full permissions given to the home folder of Apache
Working directory changed to /var/www/html/
Website cloned from 
```https://github.com/swapnilsparsh/30DaysOfJavaScript.git ```

and populated in 
```/var/www/html/```
Directory renamed to myproject/ for easy access
Server name set to localhost in ```/etc/apache2/apache2.conf```

## Screenshots

![App Screenshot](https://raw.githubusercontent.com/bhagchandaniniraj/iitj/main/screenshots/Screenshot-1.png)

![App Screenshot](https://raw.githubusercontent.com/bhagchandaniniraj/iitj/main/screenshots/Screenshot-2.png)

![App Screenshot](https://raw.githubusercontent.com/bhagchandaniniraj/iitj/main/screenshots/Screenshot-3.png)

![App Screenshot](https://raw.githubusercontent.com/bhagchandaniniraj/iitj/main/screenshots/Screenshot-4.png)

![App Screenshot](https://raw.githubusercontent.com/bhagchandaniniraj/iitj/main/screenshots/Screenshot-5.png)

**Credits** 

Special thanks to Swapnil Srivastava for providing the 30 Days of JavaScript projects on GitHub, which were used in this project.
