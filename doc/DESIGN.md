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

 - We are not limited in time, and need fast-development, flexibility and
   customization at the same time, so we choose simple and popular scripting
   language \- Python.

******

System requirements
--------------------

 - Python 3.0
 - FS which support huge files, over few terrabytes.
