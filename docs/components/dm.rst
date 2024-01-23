==================
Defensive Measures
==================

This section outlines the key components that have been identified for the Defensive Measures dimension as well as maturity levels within the components. These components and 
levels form the basis for assessing how threat informed an organization’s Defensive program is. This assessment can be conducted using the companion spreadsheet published with 
this white paper.  

Foundational Security [#f1]_
----------------------------

1. None 
2. Ad Hoc patching, limited asset inventory, basic security measures 
3. Routine, automated patching, full asset inventory, cyber hygiene best-practices implemented [#f2]_ 
4. Prioritized [#f3]_ automated patching [#f4]_ , full asset inventory mapped to business operations and threats, hygiene best-practices implemented 
5. Threat-prioritized design and maintenance of all aspects of cybersecurity 


Data Collection
----------------

1. None 
2. Minimal visibility (e.g., single network sensor at network boundary) 
3. Compliant with best practices for network and devices (e.g., logs collected from each device according to the manufacturer’s recommendations) 
4. Threat-informed detection requirements guide sensor configuration and deployment [#f5]_ (e.g., additional Sysmon configuration driven by detection needs for ATT&CK Techniques) 
5. Threat-Optimized (Sensors evaluated, configured, and deployed to meet all threat-informed detection needs) 


Detection Engineering
------------------------

1. None 
2. Import rules / analytics from open repository 
3. Prioritize and tune imported rules / analytics from repository 
4. Testing and tuning of custom detection analytics 
5. Detection analytics developed based on knowledge of low-variance behaviors, customized to reduce false positives while maintaining robust [#f6]_ recall [#f7]_ 


Incident Response
------------------

1. None 
2. Ad Hoc, Manual, Reactive 
3. Playbook-enabled, partially automated 
4. Informed by knowledge of threat actor (e.g., initial detection leads to follow-on investigation to detect other malicious actions expected in the campaign based on CTI) 
5. Strategic, holistic, optimized to deter future events (e.g., with an understanding of the full campaign and the adversary’s likely reaction to defensive response, the defenders take decisive and coordinated actions that effectively evict the adversary such that it is not easy for them to return)  


Deception Operations [#f8]_
---------------------------------

1. None 
2. Sandboxing of suspicious executables (e.g., email attachment detonation before delivery) 
3. 1 to several Honey* (pot, token, document…) deployed and monitored, enabling detection of malicious use and early warning 
4. Honey network deployed and monitored 
5. Intentional, long-term deception operations in a realistic honey network 


.. rubric:: References

.. [#f1] https://d3fend.mitre.org/
.. [#f2] https://mitre-engenuity.org/cybersecurity/center-for-threat-informed-defense/our-work/nist-800-53-control-mappings/
.. [#f3] https://www.first.org/epss/
.. [#f4] https://mitre-engenuity.org/cybersecurity/center-for-threat-informed-defense/our-work/mapping-attck-to-cve-for-impact/
.. [#f5] https://mitre-engenuity.org/cybersecurity/center-for-threat-informed-defense/our-work/atomic-data-sources/
.. [#f6] https://center-for-threat-informed-defense.github.io/summiting-the-pyramid/
.. [#f7] https://center-for-threat-informed-defense.github.io/summiting-the-pyramid/definitions/
.. [#f8] https://engage.mitre.org/


