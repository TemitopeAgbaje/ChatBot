# ChatBot

A Real-Time resturant chatbot application
___

## Getting Started
### Requirements
- The ChatBot interface should be designed to resemble a chat interface.
- The interface should not require authentication, but user sessions should be stored based on devices.
- Upon landing on the chatbot page, the bot should present the following options to the customer:
  - Select 1 to Place an order
  - Select 99 to checkout order
  - Select 98 to see order history
  - Select 97 to see current order
  - Select 0 to cancel order
- When a customer selects "1", the bot should return a list of items from the restaurant. The customer should be able to select their preferred items from the list using a number selection system and place an order.
- When a customer selects "99" to check out an order, the bot should respond with "Order placed". If there are no orders to place, the bot should respond with "No order to place". The customer should also be provided with the option to place a new order.
- When a customer selects "98", the bot should be able to return all placed orders.
- When a customer selects "97", the bot should be able to return the current order.
- When a customer selects "0", the bot should cancel the order if one exists.

### Setup
To start up the application, follow the following steps
- Step 1: On your terminal, clone the repository
    ```sh
    git clone https://github.com/TemitopeAgbaje/ChatBot.git
    ```
- Step 2: Navigate into the project folder
    ```sh
    cd chatBot
    ```
 - Step 3: Open your vscode from your browser
    ```sh
    code .
    ```
- Step 4: Install all the project dependencies
    ```sh
    npm install
    ```
- Step 6: Start the server
    ```sh
    npm run dev
    ```
- Step 7: Open the url displayed on the terminal in your web browser and explore the application
   ```sh
   http://localhost:3500/
   ```


Application is live at [ChatBot](https://random-chatbot.onrender.com) 🚀


