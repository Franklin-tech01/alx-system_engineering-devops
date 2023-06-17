
<h1 style="text-align:center;">POSTMORTERM<h1>

<img src="https://user-images.githubusercontent.com/79994012/222900235-c1877778-e3ce-4796-a73c-f71568cc2348.jpg">

<h2>ISSUE SUMMARY:</h2>
<p>Duration: The outage lasted from March 1st, 2023 at 2:00 PM UTC to March 2nd, 2023 at 9:00 AM UTC.</p>
<p>Impact: The web assistant was completely down during the outage, resulting in users being unable to use both the chatbot and voice assistant components.</p> <p>Approximately 75% of users were affected.</p>
<p>Root cause: The root cause of the outage was a software bug in the Node.js server that caused it to crash and become unresponsive.</p>
<h2>TIMELINE:</h2>
<ul>
<li>2:00 PM UTC: The issue was first detected when monitoring alerts signaled that the server was unresponsive.</li>
<li>2:05 PM UTC: An engineer was alerted and began investigating the issue.</li>
<li>2:15 PM UTC: The engineer determined that the server was down and began investigating potential causes.</li>
<li>2:30 PM UTC: The engineer assumed the issue was related to a network outage and began investigating network connectivity.</li>
<li>3:00 PM UTC: The engineer determined that the issue was not related to network connectivity and shifted focus to the Node.js server.</li>
<li>4:00 PM UTC: The engineer discovered the software bug that was causing the server to crash and began working on a fix.</li>
<li>9:00 PM UTC: The engineer completed the fix and tested it in a staging environment.</li>
<li>10:00 PM UTC: The engineer deployed the fix to the production environment and began monitoring the server.</li>
<li>9:00 AM UTC: The engineer confirmed that the fix was successful and closed the incident.</li>
</ul>
<p>Misleading investigation/debugging paths that were taken: The engineer initially assumed that the issue was related to network connectivity and spent time </p><p>investigating that before realizing it was a software issue with the server.</p>
<p>Escalation: The incident was escalated to the development team responsible for the Node.js server.</p>

<h2>RESOLUTION:</h2>
<p>Root cause: The root cause of the issue was a software bug in the Node.js server that caused it to crash and become unresponsive.</p>
<p>Resolution: The issue was resolved by fixing the software bug in the Node.js server.</p>
<h3>Corrective and preventative measures:</h3>
<p>To prevent similar incidents in the future, the following measures will be taken:</p>
<ul>
<li>The Node.js server will be updated to the latest stable version to ensure that any known issues are addressed.</li>
<li>The monitoring system will be improved to provide more detailed alerts and enable quicker detection of issues.</li>
<li>The development team will review their development practices to identify potential areas for improvement to prevent similar bugs from being introduced in the future.</li>
</ul>
<p>Specific tasks to address the issue include:</p>
<ul>
<li>Updating the Node.js server to the latest stable version.</li>
<li>Improving the monitoring system to provide more detailed alerts.</li>
<li>Reviewing the development practices to identify potential areas for improvement.</li>
</ul>

