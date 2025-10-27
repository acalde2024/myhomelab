# HomeLab Server

This is a repo documenting and showcasing my new HomeLab journey. I started this journey to learn more about deploying, hosting and monitoring all while gaining valuable skills on becoming a Cloud Engineer/DevOps. Each file contains services that I am running on my HomeLab, as well documentations on how it's being ran.

# Documentation of HomeLab Server

<ul>
  <li>Migrated my media server from OS install to Container using docker compose and successful on mapping current drives to container.</li>
  <li>Running AdGuard as my Network Wide add blocker and Malicious filtering to better protect home network.</li>
  <li>Running Twingate on server to create a tunnel to connect remotely from anywhere</li>
  <li>Using NPM as my Proxy Manager that only allows connection from within LAN or from Twingate by configuring ACL security groups, pointing to Proxy Endpoint and Twingate Public IP and serve my SSL certificats</li>
  <li>On server created a cronjob to update server every sunday at midnight and send an email confirming it has been updated with logs. Plans on changing the frequent to every other day to handle security updates</li>
  <li>Running portainer to better visualize and manager containers</li>
  <li>Running a new web app monitor uptime kuma with notifications making sure my services are up and running and notifiy me if it goes down</li>
  <li>Running a dedicated homepage site to have my entire homelab apps in one pane for ease of access</li>
</ul>

# Future Plans

<ul>
  <li>Deploy a self hosted password manager, to better handle logins locally</li>
  <li>Set up Grafana + Promethus for monitoring and logging my services</li>
  <li>Work and build a brand new server and add 2TB HDD to act as my main server to cluster a Docker swarm for orchestration and availability of my apps</li>
  <li>Host a Container image watchtower in which goal is to always have the latest container image with least hands on configuration</li>
  <li>Start implementaing a backup solution to back up both my servers and implement tools like ansible to automate configuration management in the event of recovery</li>
  <li>Learn how to utilize CICD pipeline to automate my deployment of Web services</li>

# Tools experience
<ul>
  <li>Docker</li>
  <li>Terraform</li>
  <li>GitHub</li>
</ul>

# End goal
<ul>
  <li>Learn how to create and mantain container by using tools like Portainer</li>
  <li>Learn how to migrate services that was previously installed on the OS to Docker. E.X using docker-compose</li>
  <li>Shift towards K8s and learn core concepts on how to deploy, provision and monitor it</li>
  <li>Understand CI/CD, Version Control and Automation</li>
  <li>Gain valuable skills for a Cloud Engineer/DevOps career</li>
</ul>