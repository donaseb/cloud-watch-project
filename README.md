# cloud-watch-project
project:  set up CloudWatch alarms for critical metrics of an application, define appropriate threshold conditions, and configure notification actions.
# Project Setup Steps

1. **EC2 Instance:**
   - Launch an EC2 instance 
2. **Deploy Program:**
   - Upload the `cpu_spike.py` program to the EC2 instance.

3. **Run Program:**
   - Execute `cpu_spike.py` on the EC2 instance and monitor CPU utilization.

4. **CloudWatch Alarm:**
   - Create a CloudWatch alarm for the EC2 instance with a 50% CPU utilization threshold.

5. **SNS Email Notification:**
   - Set up an SNS topic for email notifications and subscribe to it.

6. **Testing:**
   - Intentionally spike the CPU to verify that the CloudWatch alarm triggers and sends email notifications.

