# :pizza: Pizza Bot

## :pencil: Description

Pizza Bot is a chatbot designed to simplify the process of ordering pizza. With its intuitive interface and interactive conversation flow, Pizza Bot provides a seamless user experience for ordering pizza online.

## :computer: Usage

- [Click here](https://hbarry89.github.io/Pizza-Bot/) for the live link.

- For reference, the exported work from Dialogflow is available in the "PizzaBot" folder.

## :wrench: Technologies Used

- Dialogflow
- VS Code

## :star2: Features

- Intents:
    - Order Pizza
    - Specials
    - Contact Info

- Entities: 
    - Size
    - Crust
    - Ingredients

- Contexts:
    - OrderPizzaIntent-followup

- Integration: 
    - Web Demo

## :star: Work Flow

- Dialogflow Integration: Pizza Bot utilizes Dialogflow to create an intelligent chatbot interface that understands and responds to user inputs.

- Intents: Order Pizza, Specials, Contact Info - Pizza Bot includes intents specifically designed to handle pizza orders and to handle specials requests. Users can initiate the ordering process by interacting with the bot and specifying their pizza preferences through *OrderPizzaInten*. Additionally, it includes an intent to provide information about any current specials or deals available. Users can inquire about special offers and promotions through this intent through *SpecialsIntent*. Lastly, the contact info will be activiate once the user confirms that order is correct and that there is nothing else to add or edit through *ContactInfoIntent*.

- Entities: Size, Crust, Ingredients - PPizza Bot utilizes entity recognition to capture and understand important information about the pizza order. Users can specify the size (Large, Medium, Small), crust type (Regular, Thin), and select desired ingredients (e.g., Cheese, Sausage, Pepperoni, etc.).

- Contexts: OrderPizzaIntent-followup - Pizza Bot utilizes contexts to maintain the conversation flow. After receiving the pizza order details, the bot will prompt the user if the order is complete and correct. If the user confirms, the bot will proceed to ask for contact information. If the user indicates that the order is not complete, the bot will inquire about the additional items they would like to add to the order.

- Webhook Fulfillment - *This is currently hard coded for testing purposes*. However, in a real world senario, Pizza Bot would leverage webhook fulfillment to integrate with external services or APIs. This would enable seamless order processing, payment handling, and other backend operations, ensuring a smooth end-to-end experience for the users.

## :books: Resources

- [Building Chatbots Using Google Dialogflow](https://www.linkedin.com/learning/building-chatbots-using-google-dialogflow/chatbot-creation-with-google-dialogflow)
- [Favicon](https://fav.farm/)

<p align="center">Thank you for visiting! :ribbon:</p>