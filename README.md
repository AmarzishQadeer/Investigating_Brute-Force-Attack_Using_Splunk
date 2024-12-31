# Investigating_Brute-Force-Attack_Using_Splunk
Detecting Brute force Attack


## <h3>What is Brute force</h3>

A brute-force attack attempts to gain unauthorized access by systematically trying a large number of possible passwords or usernames. In a typical scenario, an attacker repeatedly attempts to log in to a system using different password combinations for a single account or multiple accounts over a short period.

## <h3> History of Brute-Force Attacks </h3>

Brute-force attacks have a long history that traces back to the early days of cryptography and computing. This attack method is one of the simplest forms of hacking, leveraging exhaustive trial-and-error techniques to break into systems, crack passwords, or decipher encryption keys.

<h3> Early Cryptography (Before Computers)</h3>

<ul>
<li>Historical Context: The concept of brute force emerged with cryptographic ciphers. Before computers, attackers manually tried all possible combinations to decipher messages encrypted with substitution or transposition ciphers.</li>
<li>Example: The Caesar Cipher could be broken by manually trying all 25 possible shifts.</li>  
</ul>

<h3> The Rise of Computers (1940s–1970s) </h3> 

<ul>
  <li> Impact of Technology: The advent of computers in the mid-20th century enabled faster computations, making brute-force attacks more feasible.</li>
  <li> Example: During World War II, Alan Turing and his team at Bletchley Park developed machines to systematically test cipher combinations used by Germany's Enigma machine.</li>
  <li> Though not purely brute force, Turing's methods laid the foundation for automated attack strategies.</li>
</ul>

<h3> Password Authentication Era (1970s–1980s) </h3>

<ul>
  <li>Password Cracking Emerges: As computers became more widely used, password authentication systems were introduced. Attackers began using brute-force techniques to guess user credentials.</li>
  <li>Example: Early UNIX systems stored passwords in hashed form. Attackers used brute force to compute hash values for commonly used passwords.</li>
</ul>

<h3>Distributed Brute-Force (2000s)</h3>

<ul>
  <li>Distributed Systems: With the rise of distributed computing, brute-force attacks became more powerful as attackers could leverage multiple systems to speed up their attempts.</li>
  <li>Botnets: Botnets were used to perform large-scale distributed brute-force attacks on services like SSH and online accounts.</li>
</ul>

<h3>Modern Era (2010s–Present)</h3>

<ul>
  <li>Password Spraying: Attackers evolved brute-force tactics into "password spraying," where common passwords are tried across many accounts to avoid detection.</li>
  <li>Credential Stuffing: The widespread availability of leaked credentials led to brute-force attacks targeting reused passwords across multiple platforms.</li>
  <li>Cloud Computing and GPUs: Modern hardware, including GPUs and cloud services, has exponentially increased the speed of brute-force attempts, enabling attackers to break even moderately strong passwords in shorter timeframes.</li>
</ul>

## <h3> Project Overview </h3>

This project demonstrates how to investigate, detect, and mitigate brute-force attacks using Splunk. It includes multiple search queries tailored to identify potential brute-force attempts and highlights best practices for analyzing login patterns, alerting on suspicious behavior, and hardening security against such attacks.

<h3> Features </h3>
<ul>
  <li> Six different methods using Splunk queries to detect suspicious login patterns.</li>
  <li> Methods to identify failed login attempts, anomalies, and compromised accounts. </li>
  <li> Search queries for detecting brute-force attack patterns and log analysis </li>
</ul>

<h3> How to Use </h3>

<ul>
  <li> Set Up Splunk: Ensure Splunk is installed and configured with the relevant log data.</li>
  <li> Choose a query based on your investigation needs </li>
  <li> Execute the query to analyze the data and detect suspicious behavior.</li>
</ul>










