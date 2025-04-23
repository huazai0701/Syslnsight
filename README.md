This script runs in a Node.js environment and accomplishes the following functions:

The getSystemInfo function fetches information about the system's CPU, memory, disk, uptime, operating system, etc.

There are several performance testing functions, like cpuPerformanceTest, memoryPerformanceTest, diskIOPerformanceTest, and networkSpeedTest, which simulate the performance tests for CPU, memory, disk, and network respectively.

Newly added functional module functions, such as streamingServiceUnlockTest, ipQualityTest, returnRouteTest, and portCheckTest, simulate the detection of streaming service unlocking, IP quality inspection, return route testing, and port checking.

It uses async/await to deal with asynchronous operations and also keeps statistics on the execution time of the script.

Please note that in practical usage, some functions might need more in-depth development and adjustment according to the specific running environment and requirements.

This JavaScript script runs based on the Node.js environment. Here are the specific steps to use it:

1. Make sure Node.js is installed: You can download and install the Node.js version suitable for your operating system from the official Node.js website (https://nodejs.org/). After installation, type node -v in the command line. If the version number is shown, it indicates that the installation is successful.

2. Create a file: Open your favorite text editor (such as Visual Studio Code, Sublime Text, etc.). Copy and paste the provided JavaScript code into a new file, and then save the file with a .js suffix, for example, systemTest.js.

3. Run the script: Open the command line terminal (Command Prompt or PowerShell on Windows, and Terminal on macOS and Linux). Use the cd command to enter the directory where the script file is saved. For example, if the file is saved in the C:\scripts directory, in the Windows Command Prompt, type cd C:\scripts and press Enter. After entering the directory, type node systemTest.js (here systemTest.js is the file name you saved, which should be modified according to the actual situation), and then press Enter.

4. Check the results: After the script runs, it will successively output the system information, the results of each simulated test, and the total execution time of the script in the command line. You can understand the simulated test situations according to these output messages.

Hope these steps can help you run this script smoothly. If you encounter any problems during the running process, feel free to ask me at any time.
