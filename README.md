# KeyboardSpammer
c++ spammer for any messenger. Emulates a keyboard and sends predefined text.
This bot simply simulates working with the keyboard by sending a message selected from the config file with the enter button.

The configuration file has the following structure and must be located in the folder with the executable file

5000      Delay before turning on the bot(in ms)
5         Delay between key presses (in ms)
1         1 or 0, auto send message (Enter pressing)
2500      Minimum delay between sending messages (in ms)
5000	    Maximum delay between sending messages (in ms)
<Message 1>
<Message 2>
<Message 3>
...
