<center><h3>What is Risk Score?</h3></center>
<hr/>
<em><h4>Classifying Risk Scores Based on Critical Functions of Devices and the Impact of CVEs</h4></em>
<strong>1. Definition of Risk Score</strong>
<p style="text-align: justify;">A <strong>risk score</strong>&nbsp;is a quantitative metric used to evaluate the level of risk associated with a device within a network system. This score is determined based on various factors, including the device's critical functions, type of device, and the impact of known security vulnerabilities (CVE). Accurately assessing the risk score helps organizations prioritize their protection and remediation efforts.</p>
<strong>2. Factors for Evaluating Risk Score</strong>
<p class="p1"><strong>Critical Functions of the Device:</strong></p>
<ul>
<li><strong style="text-align: justify;">Critical Devices:</strong>&nbsp;Devices that play essential roles in the operation of the system, such as database servers and firewalls.</li>
<li><strong>Supporting Devices:</strong>&nbsp;Devices that are not critical but can pose risks if exploited, such as printers and peripheral devices.</li>
</ul>
<p class="p1"><strong>Type of Device:</strong></p>
<ul>
<li><strong>End Devices:</strong>&nbsp;Computers, laptops, smartphones.</li>
<li><strong>Network Devices:</strong>&nbsp;Routers, switches, firewalls.</li>
<li><strong>IoT Devices:</strong>&nbsp;Internet-connected devices such as security cameras and sensors.</li>
</ul>
<p class="p1"><strong>Impact of CVEs:</strong></p>
<ul>
<li><strong>High Severity CVEs:</strong>&nbsp;Vulnerabilities that can be easily exploited and lead to severe damage (e.g., unauthorized access to sensitive data).</li>
<li><strong>Medium Severity CVEs:</strong>&nbsp;Vulnerabilities that can be exploited but require certain conditions to be met (e.g., user interaction needed).</li>
<li><strong>Low Severity CVEs:</strong>&nbsp;Vulnerabilities that are difficult to exploit or only affect non-critical functions.</li>
</ul>
<strong>3. Risk Score Calculation Process</strong>
<ol>
<li style="text-align: justify;"><strong>Identify the Critical Functions of the Device:</strong>&nbsp;Analyze the role and importance of the device within the system to determine its priority for security.</li>
<li><strong>Classify the Type of Device:</strong>&nbsp;Identify the type of device (end device, network device, IoT device) to better understand potential risks.</li>
<li style="text-align: justify;"><strong>Evaluate Relevant CVEs:</strong>&nbsp;Search for known vulnerabilities that affect the device, classifying them by severity (using CVSS - Common Vulnerability Scoring System).</li>
<li style="text-align: justify;"><strong>Calculate the Risk Score:</strong>&nbsp;Use a scoring scale to calculate the score based on the analyzed factors. A formula may be applied as follows:<br /><em><span style="color: #ff0000;"><code>Risk Score = Impact &times; Likelihood</code></span></em>
<ul>
<li><strong>Impact:</strong>&nbsp;Assesses the potential damage if the vulnerability is exploited (scoring scale from 1 to 10).</li>
<li><strong>Likelihood:</strong>&nbsp;Assesses the probability of exploitation of the vulnerability (scoring scale from 1 to 10).</li>
</ul>
</li>
<li style="text-align: justify;"><strong>Develop a Protection Plan:</strong>&nbsp;Based on the risk score, prioritize protective measures, focusing on devices with the highest scores to remediate critical vulnerabilities first.</li>
</ol>
