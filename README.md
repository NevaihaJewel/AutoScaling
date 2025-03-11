<h1>Amazon EC2 and Auto Scaling</h1>

<h2>Description</h2>
This project demonstrates the deployment and management of amazon EC2 instances, including configuring auto-scaling to ensure application reliability and cost efficiency. It covers key aspects of launching, resizing, monitoring, and managing EC2 instances in a cloud environment.
<br></br>
<b>Key Features:</b>

- <b>Instance Deployment:</b> Created and configured EC2 instances using the AWS Management Console.
- <b>Auto-Scaling Configuration:</b> Implemented scaling policies to automatically adjust compute resources based on demand.
- <b>Monitoring and Logging:</b> Utilized Amazon CloudWatch to track performance metrics and automate alerts.
- <b>Security Group Setup:</b> Configured firewall rules to manage inbound and outbound traffic for EC2 instances.
<br></br>

<h2>Technologies Used</h2>

- <b>Amazon EC2</b>
- <b>AWS Auto Scaling</b>
- <b>Amazon CloudWatch</b>
- <b>AWS IAM (Identity and Access Management)</b>
<br></br>

<h2>Environments Used</h2>

- <b>AWS Management Console</b>
<br></br>

<h2>Project Walk-Through:</h2>

<p align="center">
<b>Step 1:</b> Launching an EC2 Instance<br/>
<img src="https://i.imgur.com/nK9S5HO.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

- Selected an Amazon Machine Image (AMI) and instance type.
- Configured key pair authentication and assigned security groups.
<br />
<br />
</p>
<p align="center">
<b>Step 2:</b> Configuring Instace Details<br/>
<img src="https://imgur.com/x3o9aNo.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

- Set up network settings, including VPC, and subnet selection.
- Attached storage volumes and assigned IAM roles for permissions.
<br />
<br />
</p>
<p align="center">
<b>Step 3:</b> Setting Up Auto Scaling<br/>
<img src="https://imgur.com/RsNQ55Q.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

- Created an Auto Scaling Group to maintain instance availability.
- Configured scaling policies based on CPU utilization and traffic load.
<br />
<br />
</p>
<p align="center">
<b>Step 4:</b> Monitoring and Performance Tracking<br/>
<img src="https://imgur.com/xYkiEMu.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

- Used Amazon CloudWatch to monitor instance performance and logs.
- Set up alerts and notifications for high resource usage.
<br />
  
</p>
