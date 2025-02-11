**COMPANY**: CODTECH IT SOLUTIONS

**NAME**: GAYATHRI.N

**INTERN ID**: CT08NPC

**DOMAIN**: CLOUD COMPUTING

**DURATION**: 4 WEEKS

**MENTOR**: NEELA SANTHOSH KUMAR

**DESCRIPTION**: TASK-2: CLOUD MONITORING AND ALERTS

**Introduction**

In cloud-based application environments, proactive monitoring is essential to ensure optimal performance and address potential issues before they impact users. AWS CloudWatch provides a comprehensive solution for monitoring, logging, and setting alarms based on predefined thresholds. This report outlines the process of setting up CloudWatch to monitor key application metrics, create alarms for performance thresholds, and configure notifications for critical system events.

**CloudWatch Setup and Configuration**

To begin, I created an AWS CloudWatch dashboard to monitor the essential metrics of the deployed web application, primarily focusing on EC2 instances. The dashboard was configured to display CPU utilization, disk I/O, network traffic, and memory usage metrics. By tracking these metrics, I was able to gain insight into the application’s health and performance.

For more granular monitoring, the CloudWatch Agent was installed on the EC2 instance to provide additional system metrics. This step ensured that memory usage and disk space were also being tracked in real-time, further enhancing our ability to manage resources effectively.

**Configuring Alarms**

Alarms were configured to trigger notifications when specific performance thresholds were exceeded. I focused on setting CPU utilization alarms as a primary metric, triggering alerts if the utilization exceeded 80% for a sustained period of 5 minutes. Other key thresholds, such as network in/out and disk usage, were also monitored to ensure no performance degradation occurred due to resource limitations.

Each alarm was linked to an Amazon SNS (Simple Notification Service) topic, allowing for immediate email notifications upon alarm activation. This setup ensured that the team would be promptly informed of any anomalies, enabling swift response actions.

**Testing and Validation**

Once the alarms were configured, I conducted multiple tests by simulating high CPU usage on the EC2 instance to verify the system’s response. Upon triggering the threshold conditions, I received timely email alerts via SNS, confirming that the alarm mechanism was functioning correctly. The testing process validated the robustness of the monitoring and alerting system, ensuring it would operate effectively in real-world conditions.

**Challenges and Solutions**

During the configuration, one challenge was ensuring that the correct metrics were being tracked. The initial CloudWatch setup did not provide sufficient visibility into memory usage, which required the installation and configuration of the CloudWatch Agent. Additionally, ensuring accurate alarm thresholds involved careful analysis of the application’s typical resource usage to avoid false positives or missed alerts.

**Conclusion**

The successful setup of AWS CloudWatch for monitoring and alerting has significantly enhanced the ability to proactively manage the web application’s performance. The system now offers real-time insights into key metrics, with automated alerts providing timely notifications for any performance degradation. This implementation highlights the importance of cloud monitoring for maintaining system health and ensuring seamless application operation.

**OUTPUT**:

**PROOF1**:

![Image](https://github.com/user-attachments/assets/dc9ebdfa-3f81-4d95-8522-972e9aef0227)



**PROOF2**:

![Image](https://github.com/user-attachments/assets/4aa3dbb0-522c-4907-aed7-147d931bc91c)



**PROOF3**:

![Image](https://github.com/user-attachments/assets/babd406a-3e74-4d28-9329-0a5bd0f13f77)


**PROOF4**:

![Image](https://github.com/user-attachments/assets/abf6d580-cbce-4233-891c-56046f02a462)



**PROOF5**:

![Image](https://github.com/user-attachments/assets/042225dd-ae52-4d6e-82e8-bdf70b0bdcd4)

