# WeatherApp
 Shows the weather and humidity

This Weather App, developed using Visual Studio Code, JavaScript, and Arduino, is a comprehensive solution that allows users to access real-time weather information seamlessly. This project combines the power of web technologies and Arduino hardware to provide accurate weather data, enhancing the user experience.

# Features:

Real-time Weather Data: 

Get up-to-date weather information, including temperature, humidity, and weather conditions.

Arduino Integration: 

Utilize Arduino sensors to provide accurate local weather data.

User-Friendly Interface: 

The app boasts an intuitive user interface, making it easy for users to access weather information effortlessly.

Responsive Design: 

Access the weather app on various devices, ensuring a seamless user experience across platforms, whether it be on a computer or phone. 




# Libraries in Arduino:

Adafruit unified sensor by Adafruit

DHT sensor library by Adafruit

arest by Marco Schwartz

To install these libraries tap on the bookshelf icon on the left side of the screen. Search up the mentioned libraries and install them.

# Technologies Used
Frontend: CSS, JavaScript (Node.js, Express.js)
Hardware: Arduino (sensors for temperature, humidity, etc.), Esp32 with humidity sensor
Development Environment: Visual Studio Code

The data is collected through the Temperature Humidity sensor and then through integration through visual studio code. The file is then converted into a webpage, accessible to those who have the right connection and IP address. 

The app will be accessible at http://localhost:6908.

# Setting Up Arduino and Visual Studio:

Connect the necessary sensors to your Arduino board and esp32. 
Upload the Arduino code (Arduino_code.ino) to your Esp32 using the Arduino IDE.

In Visual Studio, change the SSID and password as well as the IP address and local host to fit your specifications. Make sure you have npm installed as well. Afterwards do npm run dev and the URL should come up and you can access your webpage

# Acknowledgements
Special thanks to JetScholar for inspiration

Citation:

Jet Scholar's original website:

https://github.com/jetscholar/IoT-Weather.git 

https://esp32io.com/tutorials/esp32-temperature-humidity-sensor





Feel free to customize, enhance, and share this weather app with others. Happy coding! 🌦️🚀
