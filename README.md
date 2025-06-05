# Pyramid of Pain Lab
<b>Platform:</b> TryHackMe | <b>Type:</b> Hands-On Lab | <b>Focus:</b> Adversary Disruption, Indicator Analysis, Threat Hunting
<h2>Overview:</h2>
This lab explored the <b>Pyramid of Pain</b> threat intelligence model developed by David J. Bianco, which categorizes indicators of compromise (IOCs) based on how much they “hurt” the adversary when detected or mitigated. The pyramid helped me understand the strategic value of different indicators—from simple file hashes to complex attacker behaviors.

Levels covered in the lab:

<li><b>Hash Values (Trivial)</b> – Identifying file-based malware signatures</li>
<li><b>IP Address (Easy)</b> – Detecting adversary infrastructure</li>
<li><b>Domain Names (Simple)</b> – Tracing phishing and command & control domains</li>
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

<h2>Outcome:</h2>
This lab enhanced my ability to think like a defender by focusing not just on detecting attacks, but on maximizing impact to adversaries. I now understand how to apply the Pyramid of Pain model to build more resilient detection strategies that disrupt adversary operations at a behavioral level.
