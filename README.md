# Virtual-Assistant

Enigma is a command-line based virtual assistant program written in C. It offers various functionalities including greeting the user based on the time of day, providing date and time, and executing common tasks such as opening websites, applications, and handling simple queries.

The assistant utilizes the eSpeak speech synthesizer for vocal output and stores unrecognized inputs for future reference.

**#Features**

Greeting: Provides a time-based greeting ("Good Morning", "Good Afternoon", "Good Evening").

Date and Time: Displays the current date and time.

Query Handling: Handles specific queries to open websites like YouTube, Wikipedia, Google, Instagram, Facebook, and other applications like Notepad.

Speech Output: Uses eSpeak to vocalize responses.

Invalid Input Storage: Stores queries that the assistant cannot handle in a file for future analysis.

**Requirements**

C Compiler: Ensure you have a C compiler (e.g., GCC) to compile the code.

eSpeak: Install eSpeak for speech synthesis. You can download it from eSpeak.

Windows OS: The code uses Windows-specific commands like start and cls
