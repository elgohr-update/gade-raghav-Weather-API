# I-Weather

I-Weather is a java application which uses Spring-boot framework to get weather information.

## Requirements

[java](https://java.com/en/download/help/download_options.xml) 

spring-boot framework


## Usage

Clone the repository

Set up an environment variable **WEB_APPID** and map it to APPID which you can get after signing up on [openweathermap](https://home.openweathermap.org/users/sign_up).
Use this [link](https://www.serverlab.ca/tutorials/linux/administration-linux/how-to-set-environment-variables-in-linux/) in case there's an issue in setting up an environment variable.


run the following command on Linux CLI
```bash 
./mvnw spring-boot:run
```

### Proceed only if there are no errors after running the previous command.


* Current Weather

You can make a curl request 
```bash
curl "http://localhost:8080/weather/current?location={city name}"
```
You can enter the following url with required parameters in browser.

```bash
http://localhost:8080/weather/current?location={city name}
```

## Acknowledgement

Thanks to [openweathermap api](https://openweathermap.org/api)
