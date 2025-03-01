<h1>Cloud Security Project: AWS Cloud Security Monitoring with CIS Benchmark Compliance</h1>



<h2>Description</h2>
This project focuses on strengthening cloud security monitoring by leveraging AWS security services. The goal was to enable AWS Config, AWS Security Hub, and AWS CloudTrail while integrating the CIS (Center for Internet Security) framework for compliance assessment. After configuring these services, I downloaded and analyzed the security report to identify potential misconfigurations and compliance gaps.<br/>


<br />

<h2>Tools and Technologies Used</h2>

- **AWS Config** – For monitoring and assessing resource configurations.

- **AWS Security Hub** – For centralized security visibility and compliance.

- **CIS Benchmark Framework** – For security best practices and compliance checks.

- **AWS CloudTrail** – For logging and monitoring API activity.


<h2>Key Features</h2>

- Security monitoring using AWS Config.

- Security findings centralized in AWS Security Hub.

- Compliance checks using the CIS Benchmark framework.

- API activity logging through AWS CloudTrail.

- Security report generation and analysis.


<h2>Steps Undertaken :</h2>

 1. **Enabling AWS Config**

- I enabled AWS Config to monitor resource configurations. In the AWS Management Console, I selected Record all resources, created an S3 bucket for storing configurations, and allowed the IAM role to manage permissions. After confirming the settings, AWS Config started tracking changes and displaying compliance statuses.

    

     <img src="https://i.imgur.com/RADpHG4.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>
     <img src="https://i.imgur.com/H0pQT5R.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>
     
<br />
<br />

 2. **Enabling AWS Security Hub**

- Enabled AWS Security Hub to aggregate security findings. Upon activation, it auto-created the required IAM role and started collecting data from AWS Config. The dashboard displayed security alerts and compliance statuses.

  

<img src="https://i.imgur.com/Xdj6Cfn.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>
<br />
<br />

 3. **Enabling CIS Benchmark in AWS Security Hub**

- Enabled the CIS AWS Foundations Benchmark to assess compliance with AWS security best practices. In AWS Security Hub, selected the CIS AWS Foundations Benchmark from the Standards section and clicked Enable. Security Hub automatically evaluated resources against CIS controls, including IAM, logging, monitoring, and network security. Non-compliant findings appeared on the dashboard.


<img src="https://i.imgur.com/YBDS8LG.png" height="90%" width="80%" alt="Disk Sanitization Steps"/>

<img src="https://i.imgur.com/2x1xo2Q.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>
<br />
<br />

4. **Enabling AWS CloudTrail**

- Enabled AWS CloudTrail to track API actions and security events. Created a trail named SecurityTrail, selected Read/Write events to log API activity, and configured an S3 bucket for log storage with encryption. Enabled CloudWatch Logs integration for real-time security monitoring. CloudTrail started logging all API requests within the AWS account.

     
<img src="https://i.imgur.com/6vcW9me.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>
<br/>

5. **Downloading and Examining Security Reports**

- Reviewed security findings and compliance reports after configuring security tools. In AWS Security Hub > Findings, viewed security alerts categorized by severity to prioritize issues. Exported findings as a CSV file for compliance analysis. Examined the CIS Benchmark compliance report for misconfigurations and security risks. AWS Config generated detailed reports showing resources failing specific security controls. Identified key misconfigurations and noted remediation steps.
     
<img src="https://i.imgur.com/SEnMr05.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>

<br />
<br />

<h2>Key Learnings</h2>

- Gained hands-on experience with AWS security monitoring.

- Learned how to configure AWS Config, Security Hub, and CloudTrail.

- Improved skills in analyzing security reports and detecting misconfigurations.

- Understood CIS Benchmark compliance and how AWS evaluates it.

- Developed experience in AWS security best practices and auditing.


</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
