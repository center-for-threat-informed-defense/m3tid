Implementing Threat-Informed Defense
=============================================

Any organization can apply threat information to their cybersecurity approach. At a minimum, the organization can take the perspective of an adversary and think about what an 
adversary might do to disrupt their business through cyber. Thinking this way helps to identify priorities in security, and leads to a series of questions such as: What 
adversaries are known to target my industry or even my company? What are these adversaries capable of? How well is my organization currently prepared to mitigate, detect, or 
resiliently operate despite a malicious cyber-attack by such adversaries? What should my organization do next to be better prepared? The three dimensions of Threat-Informed 
Defense described below help organizations determine where they are in this process and recommended practices for improving. 

Three Dimensions of Threat-Informed Defense
--------------------------------------------

The Center has historically described Threat-Informed Defense as a continuous process in which defenders and adversaries are constantly learning and evolving. To implement an 
effective Threat-Informed Defense, an organization must understand the threat and implement effective defensive measures. To understand the efficacy of existing or planned 
defensive measures and identify defensive gaps, an organization must evaluate their current posture, as well as potential new defensive measures, against the known threats. 
From a Defense perspective, this process takes place in three main Dimensions: 

1. Cyber Threat Intelligence (CTI) 
2. Defensive (Counter) Measures 
3. Testing & Evaluation 

These three elements are the core of implementing a quality Threat-Informed Program. Crucial to this idea of Threat-Informed Defense is this imperative of proactive defense. 
An effective Threat-Informed Defense must continuously learn and evolve to optimally implement defensive measures to keep pace with new threats and technologies. 


.. figure:: _static/tidcycle.png
   :alt: CTID Threat-Informed Defense Cycle
   :align: center

   CTID Threat-Informed Defense Cycle


Cyber Threat Intelligence - Know the Adversary
----------------------------------------------

The first major dimension of Threat-Informed Defense is Cyber Threat Intelligence, which is focused on understanding the adversary. This dimension measures how well the 
organization understands known behaviors of cyber adversaries; which specific adversaries are targeting its industry, technologies, or geography; and their motivations and 
typical objectives. Ultimately CTI programs enable organizations to produce a tailored threat model of the highest priority adversary behaviors, which ultimately informs the 
rest of the defensive program. Example capabilities such as the Top 10 ATT&CK Technique Calculator [#f1]_ can help organizations with this initial tailoring based on a variety 
of factors. 

.. figure:: _static/topattackttp.png
   :alt: CTID Top ATT&CK TTP Calculator
   :align: center

   CTID Top ATT&CK TTP Calculator

As described in more detail below, ultimately this understanding from CTI directly informs the next two aspects of Threat-Informed Defense.


Defensive Measures - Proactively Defend
----------------------------------------

Defensive Measures is core to the concept of Threat-Informed Defense. Once an organization understands the adversary, if they do not implement real change in their 
organization based on what they learn then they are not achieving the impact of Threat-Informed Defense. Importantly, many organizations might consider that Threat-Informed 
Defense only applies to technical defenses, but the concept of being Threat-Informed should apply across all aspects of a security program. An example of evolving defensive 
measures is the Summitting the Pyramid (StP) [#f2]_ effort from the Center, which focuses on scoring and improving the quality of analytics to create detections that are more 
robust and core to Adversary behaviors. 

.. figure:: _static/stp.png
   :alt: CTID Summiting the Pyramid
   :align: center

   CTID Summiting the Pyramid

Although improvements in defenses typically result in a technical defensive measure, that does not have to mean a firewall rule or a new analytic in a SIEM. Any action taken 
to make a network or system more secure can benefit from insight into threats. This could be stronger polices, prioritized patching, new detections, deception operations, or 
additional security training. 


Testing & Evaluation - Learn and Improve
-----------------------------------------

Testing and Evaluation helps an organization validate and grow. By testing against adversary realistic TTPs, an organization can validate their defenses and illuminate their 
gaps. By continuously testing based on updated threat knowledge and new approaches to adversary TTPs, an organization maintains a realistic picture of their security posture. 
One example of leverage more tailored, threat-informed testing is to focus adversary emulation or purple-teaming testing on the typical behaviors and attack flow of specific, 
relevant adversaries. The graphic below shows the high level FIN6 attack plan [#f3]_ taken from the Center’s Adversary Emulation library. 

.. figure:: _static/fin6advemu.png
   :alt: CTID FIN6 Adversary Emulation Plan
   :align: center

   CTID FIN6 Adversary Emulation Plan

Beyond that, testing can drive product or architecture changes to improve security, inform detection engineering and incident response, validate defensive controls, as well as 
other areas. Testing is an important way to rehearse before any real compromise occurs.  


.. rubric:: References

.. [#f1] https://top-attack-techniques.mitre-engenuity.org/calculator
.. [#f2] https://mitre-engenuity.org/cybersecurity/center-for-threat-informed-defense/our-work/summiting-the-pyramid/
.. [#f3] https://medium.com/mitre-engenuity/center-releases-fin6-adversary-emulation-plan-775d8c5ebe9b

