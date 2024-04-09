Measuring Threat-Informed Defense
=================================

Now that threat-informed defense has been defined, its importance emphasized, and the
three dimensions have been covered, there are three key questions:

1. What specific activities do I need to become threat-informed?
2. How threat-informed is my security program now?
3. What are the next steps I need to take to improve my level of threat-informed
   defense?

Each of these questions lead to a need to measure threat-informed defense, something
that has not been done before. On the Key Components and Maturity Levels page, the three
Dimensions of threat-informed defense are further decomposed into an initial set of
components, with measures for each component from least-to-most threat-informed. In the
sections that follow, we explain the methodology to leverage those components to assess
a security program and then apply the methodology to a hypothetical organization.

Methodology
-----------

To ensure consistency, we developed the following steps for threat-informed defense
measurement:

* Each of the threat-informed defense :doc:`dimensions <dimensions>` is decomposed into
  five key components.
* For each of those components, we developed five discrete levels of maturity, from
  least to most threat-informed.
* Within a threat-informed defense dimension (e.g. CTI), all of its subordinate
  components are weighted equally.
* The dimensions themselves are also weighted.

See :doc:`components/index` for the defined key components and maturity levels for all
three dimensions of threat-informed defense. These component and maturity levels form
the basis for the assessment and scoring further described below.

Weighting and Scoring
---------------------

This scoring system consists of three parts. Each of the three dimensions has five
components, and each component has five levels. Scoring is accomplished primarily at the
“level” portion of the framework.

Each level has a number of points associated with it, which are “earned” if the
organization satisfies the requirements of that level. These points are cumulative, so
if an organization satisfies the requirements of level 1 or 2, they earn 1 point each;
satisfying level 3 or 4 earns 2 points each; satisfying both level 1 and 4 earns 3
points (1+2=3 points) for that component. The score for each component can therefore
range from 0 to 6. The score for a dimension is the average of the scores for every
component in that dimension.

Overall Threat-Informed Defense Scoring
---------------------------------------

The total score for an organization is computed as a weighted sum of the dimension
scores. The logic behind this cumulative score is that taking defensive action is the
most important dimension of a threat-informed defense. The importance of CTI is greater
than that of test and evaluation based on the experience of the Center and its members.
This final formula is not meant to be extremely precise, but rather reflects the “best
engineering judgment” of the project team and participants. As with most other
frameworks and maturity models, each organization can, and should, tune and tailor this
formula based on their needs and constraints.

Example Scoring
---------------

As a notional example of implementing this assessment and scoring approach, imagine a
fictitious Company A. Company A has invested in their security program and met a minimum
acceptable level of compliance with their industry standard. They are beginning their
approach to implement threat-informed defense but are doing so unevenly. Based on their
current investments, the bullets below describe their current state of threat-informed
Defense in each dimension:

Company A: In-house implementation of a nascent threat-informed defense.

* CTI: The organization has CTI on IOCs and software used across multiple ATT&CK
  Techniques. Analysts occasionally read freely available generic reports and
  disseminate IOCs to the rest of the team.
* DM: Despite excellent CTI, the company has not leveraged that CTI effectively to
  prioritize their investments in Defensive Measures. They apply patches as needed, have
  identified critical assets, collect data as per standard best-practices, run a set of
  imported SIGMA rules, respond to alerts as needed, and do not conduct any deception
  operations.
* T&E: The company is only minimally investing in Testing & Evaluation, limiting their
  current testing to an annual purple team that is not tailored to any specific
  adversary or set of adversary behaviors. A report is generated.

To aid in leveraging this methodology for assessment, this paper is being released with
a :doc:`spreadsheet calculator <spreadsheet>`. The screenshots below are taken from the
Results tab of that calculator.

.. figure:: _static/ex1scores.png
   :alt: Overall Dimension and Component Scores
   :align: center
   :width: 80%

   Overall Dimension and Component Scores

.. figure:: _static/ex1kiviatdim.png
   :alt: Radar Chart: Comparison of Dimensions
   :align: center
   :width: 80%

   Radar Chart: Comparison of Dimensions

.. figure:: _static/ex1kiviatall.png
   :alt: Radar Chart: Comparison of all Key Components
   :align: center
   :width: 80%

   Radar Chart: Comparison of all Key Components

After an organization conducts this initial assessment and understands the current
status of their threat informed defensive program, the scoring and associated
visualizations highlight opportunities to improve their program. The section that
follows will describe approaches to improving threat-informed defense maturity once an
initial baseline is understood.
