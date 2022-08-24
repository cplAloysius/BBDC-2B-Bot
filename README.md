# BBDC Class 2B Bot
This is a bot that checks for available slots for class 2B motorcycle lessons at BBDC. 

- It refreshes the page at a specified interval and compares the number of lesson slots available to that of the previous refresh
- If there is a change, a telegram message will be sent to you with a screenshot of the current availabilty of lessons

To use this bot:
1. Enter your BBDC username and password into the code in main.py
2. Get your telegram chat id using [this bot](https://t.me/get_id_bot) and edit the code in main.py appropriately. 
3. Start the [BBDC telegram bot](https://t.me/AloysiusBBDCBot) to receive the screenshots of the availability of lessons.
4. Run main.py on your PC

You may need to add/remove certain lines depending on your BBDC account. For example, I took class 3 at BBDC prior to taking class 2B. Whenever I login to BBDC, it asks if I want to access my class 3 or class 2B account. The lines of code which handle this selection are from lines xx to xx. You may modify it to work with your BBDC account.

Since my schedule was not fixed, I did not implement a booking function so that the bot doesn't book lessons that I would be unable to attend. Creating a booking function should be fairly trivial.
