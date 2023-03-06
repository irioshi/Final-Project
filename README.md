Unit 24: Final Project README
Unit Description
In this project, you will act as a security engineer supporting an organization's SOC infrastructure. The SOC analysts have noticed some discrepancies with alerting in the Kibana system and the manager has asked the security engineering team to investigate and confirm that newly created alerts are working.

If the alerts are working, you will then monitor live traffic on the wire to detect any abnormalities that aren't reflected in the alerting system. Then, you will report back your findings to the manager with appropriate analysis.

Unit Objectives
Click here to view the daily unit objectives.
Lab Environment
Lab Details
What to Be Aware Of:
It is common to encounter to experience the following issue:



If students encounter this error, explain that Kibana needs time to finish setting up. They should wait five to ten minutes and then try again.

If the issue is still not resolved, ask to students to log into the ELK machine using the machines credentials and run the following commands:

sudo su which will allow the student to become the root user.
docker container ls to find the name of the running docker container.
docker container stop <container-name> which will stop the docker container.
docker container start <container-name> which will start the docker container back up.
When setting alerts in Kibana to send log messages, those messages will not show in Kibana without additional configuration. Instead, the status of alerts can be viewed from the 'Watcher' page where the alerts are created.

Security+ Domains
This unit covers portions of the following domains on the Security+ exam:

1.0 Attacks, Threats, and Vulnerabilities
2.0 Architecture and Design
3.0 Implementation
4.0 Operations and Incident Response
For more information about these Security+ domains, refer to the following resource: Security+ Exam Objectives

Additional Reading and Resources
Click here to view additional reading materials and resources.
© 2020 Trilogy Education Services, a 2U, Inc. brand. All Rights Reserved.
