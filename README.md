# gae-firewall-rule-generator
Block bots, automated scripts and spam visits to your Google App Engine App with our automated gcloud firewall rule command generator.

Our App takes care of the manual work of parsing logs, extracting IPs, and generating firewall rules. In seconds, you can have a firewall rule in place to block unwanted traffic.

## Website
https://firewall.nocommandline.com/

## How it Works

1. Paste raw log (in JSON format) from your GAE App 
2. Click the Submit button
3. We'll parse the logs and display the results
    - The results will list each IP we've identified as Spam, the links on your site they attempted to visit and **gcloud command to create a firewall rule against the IP**
    - The results will be available on our website for the next 30 days anytime you login 
    - Both your results and underlying log entries are deleted after 30 days. **Delete means the data is erased and not that we no longer display it to you.**
4. You can change the priority of a firewall rule
5. For complete instructions, see [this](https://firewall.nocommandline.com/how_it_works/)
