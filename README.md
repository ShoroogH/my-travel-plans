# Eloquent: A Mobile Application For Stuttering Using Artificial Intelligence Algorithms



##  Requirements
- [Python 3.8.6]
- [JDK 13.0.2]
- [XAMPP 8.0.3]
- [Android Studio 4.1.1]
- [Android-based phone]


## Getting Started


### Python
Install Python 3.8.6 and save the dir path to add it in Android Studio.

### JDK
Install JDK 13.0.2.


### Database 
Install the XAMPP 8.0.3, then * Move `/xampp` folder to `C:\` folder.

- [How To Download,Install & Run PhpMyAdmin](https://www.youtube.com/watch?v=zYfv35mi6V8&t=467s)

### Android Studio
Install Android Studio 4.1.1, * Move `/Eloquent` folder to `C:\Users\YourUserName\AndroidStudioProjects` folder.
Then, open Eloquent project and change the following:

#### Gradle

Change the python.exe path with your path

```
python {
            buildPython "C:/Users/YourUserName/AppData/Local/Programs/Python/Python38/python.exe"
            buildPython "python"
            
        }
```

#### Classes

Make sure your computer device and android device are on the same network. Then, open CMD and write:
* ipconfig

Copy the IPv4 Address. In Android Studio * Move to `app/src/main/java/com/example/eloquent`

Replace all ip address in the following classes with your IPv4 Address:
CreateAccount, EasyOnsetPhrases, EasyOnsetWord, ForgetPassword1, ForgetPassword3, HomePage, Login, Profile, 
ScenarioAtLibrary, ScenariosAtRestaurant, ScenariosAtSchool, Settings, StutteringSeverity, StutteringSeverityAtLibrary,
StutteringSeverityAtRestaurant, StutteringSeverityAtSchool, StutteringSeverityPhrases, and StutteringSeverityWord.

## Starting the application

In order to start the application, first you need to first connect your physical Android device to your computer. 
Second, open app XAMPP Control Panel and start Apache and MySQL. Third, open Eloquent project in Android Studio and run the app.


This should build the application and run it on your android device.









