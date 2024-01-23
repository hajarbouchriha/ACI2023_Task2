# ACI2023_Task2
This project is my second task as a cyber security intern at Alpha Coding Ignite

Security Automation Script


# Security Automation Script

This Python script automates routine security tasks, specifically focusing on log analysis. Designed to enhance security monitoring and incident response, the script extracts critical information from a syslog log file, providing valuable insights into system events.

## Key Features:

### 1. Log Analysis:
   - Parses the syslog log file to identify and extract error messages.
   - Categorizes and counts occurrences of each error message, aiding in the detection of common issues.

### 2. User Statistics:
   - Extracts user-related information from the log file.
   - Generates statistics on user activities, including counts of INFO and ERROR events for each user.

### 3. CSV Report Generation:
   - Creates two CSV files:
     - `error_message.csv`: Contains a list of unique error messages and their respective counts in descending order.
     - `user_statistics.csv`: Provides a breakdown of user activities, including the count of INFO and ERROR events for each user.

### 4. Additional Security Insights:
   - Includes placeholder functions for additional security tasks such as vulnerability scanning, incident response, and monitoring.
   - Users can extend the script to incorporate specific security measures based on their requirements.

### 5. Alerting Mechanism:
   - Sends an alert to administrators upon successful completion of security tasks, ensuring prompt notification.


***Ensure the presence of the syslog log file.
***Modify the `log_file_path` variable in the script to point to your syslog log file.

