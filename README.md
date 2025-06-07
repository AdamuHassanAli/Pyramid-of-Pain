# Pyramid of Pain Lab
<b>Platform:</b> TryHackMe | <b>Type:</b> Hands-On Lab | <b>Focus:</b> Adversary Disruption, Indicator Analysis, Threat Hunting
<h2>Overview:</h2>
This lab explored the <b>Pyramid of Pain</b> threat intelligence model developed by David J. Bianco, which categorizes indicators of compromise (IOCs) based on how much they “hurt” the adversary when detected or mitigated. The pyramid helped me understand the strategic value of different indicators—from simple file hashes to complex attacker behaviors.

Levels covered in the lab:

<li><b>Hash Values (Trivial)</b> – Unique file identifiers; easily changed by attackers</li>
<li><b>IP Address (Easy)</b> – Detecting adversary or Infrastructure locations; quick to alter</li>
<li><b>Domain Names (Simple)</b> – URLs used in attacks; moderately difficult to rotate</li>
<li><b>Network & Host Artifacts (Annoying)</b> – Uncovering system changes and unusual traffic</li>
<li><b>Tools (Challenging)</b> – Recognizing attacker frameworks like Cobalt Strike</li>
<li><b>Tactics, Techniques, and Procedures (TTPs)</b> – Understanding adversary methodology through the MITRE ATT&CK framework</li>

<h2>What I Learned:</h2>

<li>How to identify and prioritize IOCs based on adversary pain level</li>
<li>How to analyze threat behaviors using network and host forensic data</li>
<li>The strategic advantage of targeting higher-order indicators (TTPs, Tools)</li>
<li>How threat hunters can use frameworks like MITRE ATT&CK alongside the Pyramid of Pain</li>
<li>How attacker agility varies depending on the type of detection in place</li>

<h2>Skills Gained:</h2>
<li>IOC classification and enrichment</li>
<li>Threat intelligence analysis</li>
<li>Defensive prioritization based on adversary cost</li>
<li>Use of MITRE ATT&CK for mapping TTPs</li>
<li>Foundational threat hunting and blue teaming techniques</li>

## Practical Scenario

<b>Platform:</b> TryHackMe | <b>Type: interactive lab | <b>Focus:</b> IOC Mapping, Pyramid of Pain Application

## Summary
I completed a practical challenge by deploying a static site that required mapping real-world attacker descriptions to the correct tiers of the Pyramid of Pain. Correct classification revealed a flag, confirming accurate understanding.

## What I Did:
I Mapped each scenario to the correct IOC level:

- <b>Hash Values</b> – "These signatures can be used to attribute payloads and artefacts to an actor."
- <b>IP Addresses</b> – "These addresses can be used to identify the infrastructure an attacker is using for their campaign."
- <b>Domain Names</b> – "An attacker has purchased this and used it in a typo-squatting campaign."
- <b>Network/Host Artifacts</b> – "These artefacts can present themselves as C2 traffic for example."
- <b>Tools</b> – "The attacker has utilised these to accomplish their objective."
- <b>Tactics, Techniques, and Procedures (TTPs)</b> – "The attackers plans and objectives."
  </br>
  </br>

<p align="center">
This Image is required mapping real-world attacker descriptions to the correct tiers of the <b>Pyramid of Pain:</b> <br/>
<img src="https://github.com/AdamuHassanAli/Pyramid-of-Pain/blob/main/Images/001.jpeg?raw=true"/>
<br/>
<br/>
<p align="center">
I mapped the correct real-world attackers descriptions the tiers of the <b>Pyramid of Pain:</b> <br/>
<img src="https://github.com/AdamuHassanAli/Pyramid-of-Pain/blob/main/Images/Pyramid%20of%20pain%20Activiry.jpeg?raw=true"/>
<br/>
<br/>
<p align="center">
Here is the Flag I Catched After succssfuly Mapped<b>Pyramid of Pain:</b> <br/>
<img src="https://github.com/AdamuHassanAli/Pyramid-of-Pain/blob/main/Images/Pyramid%20of%20pain%20Catched%20the%20flag.jpeg?raw=true"/>
<br/>
<br/>
  
## Outcome:
This lab enhanced my ability to think like a defender by focusing not just on detecting attacks, but on maximizing impact to adversaries. I now understand how to apply the Pyramid of Pain model to build more resilient detection strategies that disrupt adversary operations at a behavioral level.
