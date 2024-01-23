=========================
Cyber Threat Intelligence
=========================

This section outlines the key components that have been identified for the CTI dimension as well as maturity levels within the components. These components and levels form the 
basis for assessing how threat informed an organization’s CTI program is. This assessment can be conducted using the companion spreadsheet published with this white paper.  


Depth of Threat Data [#f1]_
----------------------------

What level of information (roughly relative to the Pyramid of Pain) is being used to track adversaries.

1. None
2. Ephemeral IOCs: hashes, IPs, domains: data sources an adversary can change easily 
3. Tools / Software used by adversaries: tools or software which can be swapped or modified by an adversary to evade detection  
4. Techniques and Tactics used by adversaries: the techniques and behaviors that are harder to change for an adversary 
5. Low-variance adversary behaviors and associated observables: specific actions most implementations of a technique must use so it is very difficult for an adversary to change or avoid 


Breadth of Threat Information
-----------------------------

Complementary to the depth component score above, this component reflects roughly how many relevant Techniques are understood at that level of depth.

1. None 
2. Single Technique 
3. Multiple Techniques 
4. All top-priority Techniques relevant to the organization 
5. All Techniques relevant to the organization [#f2]_ 


Relevance of Threat Data
------------------------

Where is the threat information coming from and how timely is it 

1. None 
2. Generic reports or freely available reporting 
3. Internal reports 
4. Recent, in-depth reporting (often requires a subscription) 
5. Customized briefings 


Utilization of Threat Information
---------------------------------

How is the threat information being used by an organization

1. None 
2. Lightly / occasionally read 
3. Regularly ingested for analysis 
4. Analyzed automatically [#f3]_ and/or by trained analysts 
5. Contextualized in disseminated reports for other internal stakeholders to operationalize 


Dissemination of Threat Reporting
---------------------------------

What threat information is passed along within an organization [#f4]_

1. None 
2. Tactical reporting with highly perishable information (IOCs) 
3. Tactical reporting focused on adversary behavior (TTPs) 
4. Operational reporting on pertinent security trends 
5. Strategic reporting on business impacts of security trends 


.. rubric:: References

.. [#f1] https://center-for-threat-informed-defense.github.io/summiting-the-pyramid/levels/
.. [#f2] https://mitre-engenuity.org/cybersecurity/center-for-threat-informed-defense/our-work/top-attack-techniques/
.. [#f3] https://mitre-engenuity.org/cybersecurity/center-for-threat-informed-defense/our-work/threat-report-attck-mapper-tram/
.. [#f4] https://github.com/center-for-threat-informed-defense/cti-blueprints/wiki


