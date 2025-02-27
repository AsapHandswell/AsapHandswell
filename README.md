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
- [EC2 Instance Running]![image](https://github.com/user-attachments/assets/878c5eb2-94da-4edc-af4b-249408326b52)


- [Alarm Configuration]![image](https://github.com/user-attachments/assets/6c5b5602-4181-45aa-ad74-933047a1eaa2)

- [SNS Subscription Confirmation]![image](https://github.com/user-attachments/assets/668db35d-f361-4a51-a36c-c76aff6ab10b)


## Takeaways
- Learned to set up monitoring alerts and verify notification delivery.
- Troubleshot alarm state changes by checking SNS and instance status.
