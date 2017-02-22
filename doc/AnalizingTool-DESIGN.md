% AnalizingTool
% **Analizys of conformity of application to PMemFile requrements**
% Vitalii Chernookyi

******

Why we need this tool
---------------------

 - we need to keep Tracing Tool as fast as possible, so we offload this
   functionality to post-processing.
 - in opposit to post-processing conformity criterias depend on versions
   of PMemFile implementation.
 - sometimes we need to apply different criterias to same trace, or ever
   to experiment with conformity criterias.

******

Used technologies
------------------

 - There is no performance requirement, but there are fast-development,
   flexibility and customization requirements, so we choose simple and popular
   scripting language \- Python.

******

System requirements
--------------------

 - Python 3.0

******

Structural Component Diagram
-----------------------------

![DSGN_struct_comp_dia.png](DSGN_struct_comp_dia.png)

******

Behavioral Activity Diagram
----------------------------

![DSGN_beh_act_dia.png](DSGN_beh_act_dia.png)

******

Decision Maker's FSM
--------------------

![DSGN_decision_maker_fsm.png](DSGN_decision_maker_fsm.png)

******

Tasks
------

1. 
