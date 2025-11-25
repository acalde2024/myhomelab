# HomeLab Server

This is a repo documenting and showcasing my new HomeLab journey. I started this journey to learn more about deploying, hosting and monitoring all while gaining valuable skills on becoming a Cloud Engineer/DevOps. Each file contains services that I am running on my HomeLab, as well documentations on how it's being ran.

# Documentation of HomeLab Server


<img width="1558" height="855" alt="Image" src="https://github.com/user-attachments/assets/3862c248-9da3-4362-be64-1f0155d46988" />



<ul>
  <li>Migrated my media server from OS install to Container using docker compose and successful on mapping current drives to container.</li>
  <li>Running my RasberryPi as my DNS and Twingateto allow remote connection to my media server and handle local DNS resolution</li>
  <li>On server created a cronjob to update server every day at 7pm and send an email confirming it has been updated with logs. Plans on changing the frequent to every other day to handle security updates</li>
  <li>Running portainer to better visualize and manager containers</li>
  <li>Running a new web app monitor uptime kuma with notifications making sure my services are up and running and notifiy me if it goes down</li>
  <li>Running a dedicated homepage site to have my entire homelab apps in one pane for ease of access</li>
  <li>Running and added Watchtower to mantain and update container images to streamline and automate image updates. However will replace Watchtower since it hasn't been updated for 2 years now.</li>
</ul>

# Future Plans

<ul>
  <li>Deploy a self hosted password manager, to better handle logins locally</li>
  <li>Set up Grafana + Promethus for monitoring and logging my services</li>
  <li>Work and build a brand new NAS Server to host my Media Server and other file sharing services</li>
  <li>Start implementaing a backup solution to back up both my servers and implement tools like ansible to automate configuration management in the event of recovery</li>
  <li>Learn how to utilize CICD pipeline to automate my deployment of Web services</li>
  <li>Implement a Sub and Pub model to push server notifiations as SMS to monitory server's performance</li>
  <li>Find a new replacement for my Proxy manager to a more enterprise grade to handle better SSL certs, authentication of my services, etc..</li>
</ul>

# Tools experience
<ul>
  <li>Docker - Intermediate</li>
  <li>Terraform - Intermediate</li>
  <li>GitHub - Intermediate</li>
  <li>Ansible - Beginner</li>
</ul>

# End goal
<ul>
  <li>Learn tools and skills needed to be job ready in a Cloud Engineer/DevOps role</li>
  <li>Docker exposure to understand containerization and it's benefit on an enterprise level</li>
  <li>Shift towards K8s and learn core concepts on how to deploy, provision and monitor it</li>
  <li>Understand CI/CD, Version Control and Automation</li>
</ul>
