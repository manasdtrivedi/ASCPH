# Automated System to Connect Patients and Hospitals

## Technical specifications
* Java 7 or above
* MySQL version 5.1 or above

## Installation guide

#### Java
To check if Java is already installed on your system, execute the following command in the Terminal:
```
$ java -version
```

If Java is not present, execute the following command to install the default Java Runtime Environment (JRE), which will install the JRE from OpenJDK 11:
```
$ sudo apt install default-jre
```

To check if the Java compiler is already installed on your system, execute the following command:
```
$ javac -version
```

If the Java compiler is not present, execute the following command to install the default Java Development Kit (JDK):
```
$ sudo apt install default-jdk
```

#### MySQL
To install MySQL, follow all three steps given in [this](https://www.digitalocean.com/community/tutorials/how-to-install-mysql-on-ubuntu-18-04) tutorial, and set `1234` as the `root` password when prompted for the same.

#### NetBeans IDE 8.2
Install NetBeans IDE 8.2 from [here](https://netbeans.org/downloads/old/8.2/), by selecting the Java SE or Java EE bundle.

## Usage

#### 1. Clean and build project

Open the NetBeans IDE, click on File -> Open Project, and open the Java application. Once opened, in the Projects section, expand the 'ASCPH' project node, expand the `Source Packages` subnode, expand the `<default package>` subnode, and double click `ASCPH.java`. Click the `Source` tab. Click the `Run` tab, and click `Clean and Build Project`. Alternatively, press Shift+F11. This produces Database_SQLi.jar, which is the executable file to be run. This file is present at Database_SQLi/dist.

#### 2. Execute the application

To execute the application from within the IDE, click the `Run` tab, and click `Run File`. Alternatively, press Shift+F6.
To execute the application from outside the IDE, double-click ASCPH.jar. If it doesn't run, right click it, go to Properties, and under the Permissions tab tick the 'Allow executing file as program' checkbox.

#### 3. Distribution

To distribute the application, create a zip file of the dist folder, and send it to the users of the application, along with the installation and usage instructions.
