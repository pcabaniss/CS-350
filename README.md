# Emerging Systems Architecture &amp; Design

Summarize the project and what problem it was solving.
- Morse Code: This was a project that involved using the TI CC3220s board to generate morse code messages using the LED lights on the board. It displays an SOS message at first, and when the button on the right is pressed, it switches the message to print OK. 
- Thermostat: Using the same board as above, I implemented functionality to connect and display the current temerature. It also allows you to "set" the temerature of the room using the top and bottom buttons.

What did you do particularly well?
- Morse Code: This was my first time encountering and using UART. The problem was that that library was no longer supported and the code studio only used UART_2. This involved me migrating much of the functionality in the code to support this change. The program still ran and executed perfectly after the changes were made. 
- Thermostat: This was the culmination of all the previous milestones in the course. It combined buttons, LEDs, UART2, I2C, and even the temerature sensor. Using all of these skills I learned allowed me to generate and run the code successfully.

Where could you improve?
- Morse Code: I would like to understand more about the systems image configuration and how to better connect to it.
- Thermostat: I would like to understand the process of reverse engineering the program using the disassembled code while debugging. I think it would lend a lot of insight to the processes and even show where impronments could be made. 

What tools and/or resources are you adding to your support network?

I am definitely adding the Code Composer Studio (CCS) and the flash application as well. These applications helped me tremendously throughout all of my developments in this course. It is my dream to work in robotics, so I will be using this software even after this course is done. 
  
What skills from this project will be particularly transferable to other projects and/or course work?
- Morse Code: My ability to adapt to unforseen changes in functionality due to outdated libraries. 
- Thermostat: My ability to bring all of my skills together to create an application that is running smoothly is something any dev should be able to bring to the table. Specifically, all of these libraries were new to me, so gaining understanding enough to implement is a skill I will use throughout my career.  

How did you make this project maintainable, readable, and adaptable?

For both projects, I maintained a standard throughout of commented and well-documented code. The programs were also free of errors and built successfully in CCS. Due to the TI board being so customizable, the code I implemented can be used for a number of other applications. 
