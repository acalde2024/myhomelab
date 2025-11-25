# HomeLab Server

This is a repo documenting and showcasing my new HomeLab journey. I started this journey to learn more about deploying, hosting and monitoring all while gaining valuable skills on becoming a Cloud Engineer/DevOps. Each file contains services that I am running on my HomeLab, as well documentations on how it's being ran.

# Documentation of HomeLab Server


<img width="1558" height="855" alt="Image" src="https://github.com/user-attachments/assets/3862c248-9da3-4362-be64-1f0155d46988" />


# Hardware
<dl>
  <dt>Dell Inspiron 15</dt>
  <dd>- 500GB SSD</dd>
  <dd>- 4GB RAM</dd>
  <dd>Ubuntu server</dd>
  
  <dt>RasberryPI 2</dt>
  <dd>- 64 GB microSD</dd>
  <dd>- 1GB RAM</dd>
  <dd>- Ubuntu Server</dd>
</dl>

# Services that are running on my HomeLab Server

<ul>
  <li>Currently I am running Homarr to centralize all my services that are running. As well bookmarks links to my github, linkedIn, and have a quick RSS feed view. Future improvement want to add monitors to my hardware resources like CPU, Power, Memory, etc. </li>
  <li>Running a Jellyfin media server to host and serve media content locally</li>
  <li>Hosting NGINX Proxy Manager to handle SSL Certificates to my local services to use my domnain name hosted by Cloudflare so I can easily access links via my FQDN vs using IP address and remembering port numbers</li>
  <li>Running portainer to better visualize and manager containers</li>
  <li>Running a new web app monitor uptime kuma with notifications making sure my services are up and running and notifiy me if it goes down</li>
  <li>Hosting a service called IT-Tools to host tools that might be useful for home use.</li>
  <li>Created a Zero Trust tunnel via Twingate so I can connect to my home server wherever I am for those "just in case something goes down" when outside my network</li>

# Future Plans

<p>I am planning on adding and updating my hardware as I grow and learn from what I have. Currently working on formatting a external Hard Drive to create a local backup of my docker configs to restore in the outcome of a disaster. Here are a few updates/upgrades I am planning:</p>

<ul>
  <li>Deploy a self hosted password manager, to better handle logins locally</li>
  <li>Set up Grafana + Promethus for monitoring and logging my services for system monitoring</li>
  <li>Work and build a brand new NAS Server to migrate and host my Media Server and other file sharing services</li>
  <li>Start implementaing a backup solution to back up both my servers and implement tools like ansible to automate configuration management in the event of recovery</li>
  <li>Learn how to utilize CICD pipeline to automate my deployment of Web services</li>
  <li>Implement a Sub and Pub model to push server notifiations as SMS to monitory server's performance</li>
</ul>

# What I learned so far

<p>So what did I learned after all of this? I learned the importance on having backups. I already brought down my service multiple times in which I had no backup on restoring. So the importance on having a 3-2-1 backup strategy in which is my next project. I also learned how containers really work under the hood. For example, my services are running in different docker network to avoid communications between containers that should not be communicating. Learned how to find solutions to automate my set up by leveraging Ansible to deploy my configurations, using GitHub to control Source Versioning and use of cron jobs to automate backups, updates, and server maintance.</p>

# End goal
<ul>
  <li>Learn tools and skills needed to be job ready in a Cloud Engineer/DevOps role</li>
  <li>Docker exposure to understand containerization and it's benefit on an enterprise level</li>
  <li>Shift towards K8s and learn core concepts on how to deploy, provision and monitor it</li>
  <li>Understand CI/CD, Version Control and Automation</li>
</ul>
