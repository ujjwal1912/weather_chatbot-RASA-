# weather_chatbot-RASA-
This is a RASA chatbot which tells about the temp of the city.( right now i have included only delhi, raebareli, mumbai, lucknow)

This application is simple demo of using external API in RASA chatbot.

To run this application in your system please follow these steps - 
1. Go to the project folder and open cmd there and run the following command-
```sh
pip install -r requirement.txt
```

2. If you want to change something in the chatbot then to re-train the model - 
```sh
rasa train
```

3. If you don't want to change and run as it is don't do step 2.

4. Run the action server by follwing command - 

```sh
rasa run actions
```

5. Finally to run the chatbot open another cmd and go to the project directory and run - 
```sh
rasa shell
```

Output - 
![Chatbot](https://github.com/ujjwal1912/weather_chatbot-RASA-/blob/master/img/output.PNG)
