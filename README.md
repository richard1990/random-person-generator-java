# Personal Project - Random Person Generator (Java)
This is a personal project of mine. Written in Java using Eclipse, I created a "random person generator". When you clicked the "Generate" button, a random person is generated. Using the JRadioButtons at the top, you can select to generate a random male or female. The UI (made using Swing) is made up of a BorderLayout with the items inside it being made up of GridLayouts. 

Every person generated has a variety of data, including full name, mother's maiden name, birthplace, age, favorite color/food, height, weight, and lots more. Their phone number has a real-life area code related to their birthplace (e.g. 613 if they are born in Ottawa).

The names and occupations are loaded from text files containing hundreds to thousands of samples to choose from, and with all of the data randomized, there is basically no way two people generated will be the same.

A JAR is included in the files as well, so the program can be launched anywhere. No data is stored, but I made the randomly generated data displayed in JTextFields in case someone wanted to copy & paste some data.

In the future I might include data such as residence, SIN, credit card, and a little story for each person generated.
