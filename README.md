# PrimeFaces test with Gradle

This is a Java project using gradle and prime faces, following common structure for a java project. 

## Set-up

Use the git command to clone the project and then you must use [gradle](https://gradle.org/install/) to install dependencies.

### To clone first

```bash
git clone https://github.com/carlospatinos/minesweeper
```

### To install dependencies

To build the project and install all the dependencies please run the following command:
```bash
gradle build
```
You should get a result similar to this in your console:

<img src="doc/build.png?raw=true" width="300" />

### To run
After building the project you should be able to run the application and see it live in the browser, please run the following command:
```bash
gradle appRun
```
You should get a result similar to this in your console:


<img src="doc/run.png?raw=true" width="300" />

Then go to http://localhost:8080/spring4 in your browser and you should see something like this:


<img src="doc/screenshot.png?raw=true" width="400" />

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
You can find the licence by clickling here at [MIT](LICENSE)