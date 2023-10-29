## WhatsApp Bot Project with Twilio API and Python Fundamentals
### Project Overview

The WhatsApp Bot project is a cutting-edge application built with Python and integrated with the Twilio API. This innovative bot leverages the power of Twilio's messaging capabilities to interact with users on the popular messaging platform, WhatsApp. By harnessing the fundamentals of Python, this project empowers users to automate and streamline various tasks and interactions within the WhatsApp ecosystem.

## Key Features:

1. Automated Responses:  The WhatsApp Bot can respond to user messages in real time, providing instant replies to common queries or commands. By utilizing Python, the bot can process incoming messages and generate personalized responses based on pre-defined rules or user interactions.

2. Customizable Commands: Users can define custom commands and keywords that trigger specific responses from the bot. This feature allows for tailored interactions and automation of tasks such as fetching data, sending reminders, or answering FAQs.

3. Interactive Menu: The bot can provide users with an interactive menu that offers a range of options and services. Users can navigate through the menu to access information, request services, or execute specific actions.

4. Integration with External Services: By combining Python's versatility with the Twilio API, the WhatsApp Bot can connect with external services and databases. This enables it to fetch real-time information, access databases, or perform operations like weather updates, news retrieval, or even e-commerce transactions.

5. Notification System: Users can set up notifications and reminders using the bot. Whether it's for appointments, events, or important deadlines, the bot will send timely reminders to ensure users stay organized.

6. Error Handling: Python's robust error-handling capabilities ensure that the WhatsApp Bot can manage unexpected situations gracefully, providing clear feedback to users in case of errors or misunderstandings. 



## Technology Stack:
. Python: The core programming language used to build the bot.

. Twilio API: The Twilio API provides the essential infrastructure for sending and receiving WhatsApp messages.

. Flask: A lightweight web framework used to create a web application to interface with the WhatsApp Bot.

. Database (Optional): Depending on the project requirements, you can integrate a database system to store user preferences or 
   data.

## Implementation 
    
    pip3 install twilio flask requests
   
After the above proceed to implement the attached main.py code file. The main issue which may arise is that the compiler may return :

    
     ERROR: Failed building wheel for multidict
    Failed to build yarl multidict
    ERROR: Could not build wheels for yarl, multidict, which is required to install pyproject.toml-based projects
    
To solve this issue you may need to import each of the libraries separately and also keep your pip installer up-to-date. 
## Scope 

On further Exploring I found that you can actually clone the WhatsApp API itself to create your own version of WhatsApp however, it is restricted to personal use and one can promote or implement it as the official WhatsApp App. Twilio provides the necessary directions to implement changes across the UI as well as the data limit in WhatsApp such as putting a GIF/ Video as your pfp as well as sending more than 20 MB video files across and no limit restrictions over sending the number of pictures in one iteration. Moreover, the setting.API also allows changes across the UI making it more dynamic than the normal WhatsApp. The only downside to the above-mentioned features is that it is not completely free and to directly change the UI and make significant changes across one needs the premium access to use those tools.   

## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.
