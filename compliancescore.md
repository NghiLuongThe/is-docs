<center><h3>What is Compliance Score?</h3></center>
<hr/>
<p class="p1" style="text-align: justify;">Compliance score is a measurement used to assess the security posture of systems within an organization, ensuring they meet specific security and operational standards. The score is calculated based on eight criteria, each of which is rated as either <em>Compliant</em> or <em>Uncompliant</em>. These criteria are designed to ensure systems are secure, properly configured, and centrally managed. Below is a detailed explanation of each criterion:</p>
<p class="p3" style="text-align: justify;"><span class="s1"> 1. </span><strong>Operating System (OS):&nbsp;</strong>The system must be running a Windows operating system that is still supported by Microsoft. Unsupported operating systems increase the risk of vulnerabilities that cannot be patched.</p>
<ul>
<li class="p4"><em>Compliant</em>: Running a supported version of Windows.</li>
<li class="p4"><em>Uncompliant</em>: Running an unsupported or outdated version of Windows.</li>
</ul>
<p class="p3" style="text-align: justify;"><span class="s1"> 2. </span><strong>Updates:&nbsp;</strong>This criterion ensures that all available security and critical updates are installed. Keeping the system updated with the latest patches is essential to protect against known vulnerabilities.</p>
<ul>
<li class="p4"><em>Compliant</em>: All security and critical updates are installed.</li>
<li class="p4"><em>Uncompliant</em>: Missing essential updates or patches.</li>
</ul>
<p class="p3" style="text-align: justify;"><span class="s1"> 3. </span><strong>Rights:&nbsp;</strong>User privileges are carefully managed under this criterion. Users should only use domain accounts, avoid using administrative rights unless necessary, and remove any unused accounts. Each computer should have only one administrative account to limit exposure.</p>
<ul>
<li class="p4" style="text-align: justify;"><em>Compliant</em>: Domain account usage with restricted administrative rights and clean-up of unused accounts.</li>
<li class="p4" style="text-align: justify;"><em>Uncompliant</em>: Multiple administrative accounts, unused accounts, or use of local administrative privileges.</li>
</ul>
<p class="p3" style="text-align: justify;"><span class="s1"> 4. </span><strong>Hardening:&nbsp;</strong>Hardening focuses on reducing the attack surface of the operating system. This includes disabling unnecessary services, enabling User Account Control (UAC), disabling autoplay features, and enabling audit logs. These steps increase the system&rsquo;s resilience against threats.</p>
<ul>
<li class="p4"><em>Compliant</em>: The system has been hardened according to best practices.</li>
<li class="p4"><em>Uncompliant</em>: The system lacks sufficient hardening measures.</li>
</ul>
<p class="p3" style="text-align: justify;"><span class="s1"> 5. </span><strong>Identification:&nbsp;</strong>Systems must be properly identified within the organization&rsquo;s management portal. This includes adhering to standardized hostname conventions and ensuring all relevant identification information is recorded.</p>
<ul>
<li class="p4" style="text-align: justify;"><em>Compliant</em>: Hostname follows organizational standards and identification details are properly logged.</li>
<li class="p4"><em>Uncompliant</em>: Incorrect hostname or missing identification information.</li>
</ul>
<p class="p3" style="text-align: justify;"><span class="s1"> 6. </span><strong>External Device:&nbsp;</strong>To control potential threats from external devices, this criterion ensures that only approved external devices are connected to systems. For example, USB devices should be clearly sourced and used according to IT department guidance.</p>
<ul>
<li class="p4"><em>Compliant</em>: No unauthorized external devices, proper usage of IT-approved devices.</li>
<li class="p4"><em>Uncompliant</em>: Use of unapproved external devices.</li>
</ul>
<p class="p3" style="text-align: justify;"><span class="s1"> 7. </span><strong>Centralized Management:&nbsp;</strong>Systems must be joined to the organization&rsquo;s domain (e.g., <em>saigonnewport.local</em>) and internet access should be routed through a secure proxy. This enables centralized control and monitoring of network traffic.</p>
<ul>
<li class="p4" style="text-align: justify;"><em>Compliant</em>: System is part of the domain and uses the organization&rsquo;s proxy for internet access.</li>
<li class="p4"><em>Uncompliant</em>: System is not joined to the domain or bypasses the proxy.</li>
</ul>
<p class="p3" style="text-align: justify;"><span class="s1"> 8. </span><strong>Centralized Monitoring:&nbsp;</strong>Monitoring tools for information security and log collection must be installed on all systems. These tools help detect potential security incidents and ensure the system is continuously monitored for abnormal behavior.</p>
<ul>
<li class="p4" style="text-align: justify;"><em>Compliant</em>: Security monitoring and logging tools are installed and operational.</li>
<li class="p4"><em>Uncompliant</em>: Missing or misconfigured monitoring tools.</li>
</ul>
<p class="p2">&nbsp;</p>
<p class="p1" style="text-align: justify;">Each of these eight criteria is reviewed for compliance, and the overall compliance score is calculated based on how many of the criteria are marked as <em>Compliant</em>. The goal is to ensure that all systems meet the security and operational standards of the organization, reducing the risk of breaches and maintaining system integrity.</p>
