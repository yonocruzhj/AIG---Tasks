<h1>AIG: Respond to Zero Day Attack and Bypassing Ransomware</h1>

<h2>Description</h2>

<br />


<h2>Languages and Utilities Used</h2>

- <b></b> 
- <b></b>

<h2>Environments Used </h2>

- <b></b> (21H2)

<h2>Scenario</h2>
<br/>
<img src="https://imgur.com/xKQyBY5.png" height="80%" width="80%"/>
<br />
<br />
Email Response <br/>
From: AIG Cyber & Information Security Team

To: Product Development Team (product@email.com)

Subject: Security Advisory concerning Product Development Staging Environment's use of Log4j

Hello John Doe,

AIG Cyber & Information Security Team would like to inform you that a recent Log4j vulnerability has been discovered in the security community that may affect the Product Development Staging Environment. Listed below are the vulnerability's description, risk and impact, and remediation.

**Description:** Log4j is a Java-based logging library that contains critical and high vulnerabilities on the Common Vulnerability Scoring System (CVSS)

-  Log4Shell (critical): Remote code execution vulnerability affecting Apache's Log4j library, versions 2.0-beta9 to 2.14.1.
Exists in the action the Java Naming and Directory Interface (JNDI) 
Affected versions of Log4j contain JNDI features that do not protect against adversary-controlled LDAP, DNS, and other JNDI-related endpoints.
Adversary can take full control over system, steal information, launch ransomware, and conduct other malicious activity.

-  CVE-2021-45046 (critical):
Enables remote attacker to cause a remote code execution, a denial-of-service (DoS) condition, or other effects in certain non-default configurations.
Affects versions of Log4j from 2.0-beta9 through 2.12.1 and 2.13.0 through 2.15.0.

-  CVE-2021-45105 (high):
Enables remote attacker to cause a DoS condition or other effects in certain non-default configurations.
Attackers with control over Thread Context Map (MDC) input data can create malicious inputs that contain recursive lookup which terminates the process.
Affected versions are those older than Log4j version 2.17.0 (Java 8).

**Risk/Impact:**
Log4Shell and CVE-2021-45046 are severe because Java is used commonly across IT and OT platforms and are easy to exploit. Malicious actors can remotely run code on vulnerable networks and take full control of systems.
FBI observed attempted exploitation of Log4j vulnerabilities to gain access to the network and deploy crypto mining and botnet malware.

**Remediation:**
-  Identify assets and create inventory of assets that use Log4j.
-  Update products that use Log4j to latest patched version. For environments using Java 8 or later, upgrade to Log4j version 2.17.0 or newer
For environments using Java 7, upgrade to Log4j version 2.12.3. It is recommended to upgrade to Java 8, since Java 7 is end of life.
-  Monitor assets closely and look for signs of compromise or exploitation.

For any questions or issues, don’t hesitate to reach out to us.

Kind regards,
AIG Cyber & Information Security Team

<br />
<br />
<h2>Task 2: Bypassing Ransomware via Brute Force<\h2> <br/>
<img src="https://imgur.com/06wvubS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Confirm your selection:  <br/>
<img src="https://i.imgur.com/cdFHBiU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Wait for process to complete (may take some time):  <br/>
<img src="https://i.imgur.com/JL945Ga.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Sanitization complete:  <br/>
<img src="https://i.imgur.com/K71yaM2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Observe the wiped disk:  <br/>
<img src="https://i.imgur.com/AeZkvFQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
