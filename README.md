- 👋 Hi, I’m Tynael Benham @AsapHandswell
- 👀 I’m interested in CyberSecurity and Linux.
- 💞️ I’m looking to collaborate on pretty much anything that can help in expanding my IT knowledge (maybe we can help each other).
- 📫 How to reach me  (302)615-0075
- ⚡ Fun fact: In my other life I was a dj!!!!

<!---
AsapHandswell/AsapHandswell is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
## Lab 1: S3 Static Website via AWS
- Hosted a website...
  
![Screenshot 2025-02-21 at 9 19 56 PM](https://github.com/user-attachments/assets/fbe78b5a-5af7-4011-aa02-cef7f913a4db)
![Screenshot 2025-02-21 at 9 20 09 PM](https://github.com/user-attachments/assets/e3f2b96b-201d-4e91-9562-a514500b5780)
![Screenshot 2025-02-21 at 9 19 42 PM](https://github.com/user-attachments/assets/f82d2eee-4a79-415e-ad8b-22b8f0813b3e)


# Lab 2: AWS CloudWatch Alarm Setup and Troubleshooting

## Objective
Set up a CloudWatch alarm to monitor EC2 CPU usage and troubleshoot notification issues, simulating proactive system monitoring for help desk support.

## Steps
1. Launched a t2.micro EC2 instance with Amazon Linux 2 via AWS Console.
2. Navigated to CloudWatch, created an alarm for CPUUtilization > 50% over 5 minutes.
3. Configured SNS notification to email, confirmed subscription via link.
4. Stopped the instance to simulate a state change, checked alarm status.
5. Restarted instance and verified alarm updated correctly.

## Screenshots
- [EC2 Instance Running](![image](https://github.com/user-attachments/assets/8bf25928-7a84-4138-99b0-28a883a1b2eb)
)
- [Alarm Configuration](![image](https://github.com/user-attachments/assets/d8dc3b63-d339-46e3-b99a-c5cf43c39480)
)
- [SNS Subscription Confirmation](![image](https://github.com/user-attachments/assets/614213b6-2e30-4063-877c-a3bffe561459)
)

## Takeaways
- Learned to set up monitoring alerts and verify notification delivery.
- Troubleshot alarm state changes by checking SNS and instance status.
