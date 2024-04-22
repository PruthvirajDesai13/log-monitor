# log-monitor
1)Log File Monitoring:
Use Python's logging module to create a logger and log messages.
Continuously monitor a specified log file for new entries using a loop.
Display new log entries in real-time using tail or similar commands.
Implement a mechanism to stop the monitoring loop, such as handling a signal like Ctrl+C.

2)Log Analysis:
Enhance the script to perform basic analysis on log entries:
Count occurrences of specific keywords or patterns (e.g., error messages, HTTP status codes).
Generate summary reports, such as the top error messages.

3)Error Handling and Logging:
Include robust error handling to handle exceptions gracefully and provide feedback on script execution.
Log relevant information using the logging module to track script activities and errors.

4)In this script:

main() contains the main loop for logging messages at random intervals.
The script logs INFO, DEBUG, and ERROR messages randomly.
It handles KeyboardInterrupt (Ctrl+C) to stop the monitoring loop.
You can expand this script by adding log analysis functionalities based on your specific requirements.
