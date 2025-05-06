# OCP
Ontology for Chronological Processes

This ontology is based on the OWL-Time ontology (Cox & Little) - in appreciation of their great work!
OCP serves as an extension of the OWL-Time ontology, adding a variety of classes, datatype properties and object properties to better describe ongoing and unfinished processes.
Major contributions include:

New classes:
- ocp:process
- ocp:cycle
- ocp:phase
- ocp:transition

New object properties:
- extended relative start/end description 
  - ocp:beginsAfter , ocp:beginsBefore , ocp:beginsWith
  - ocp:endsAfter , ocp:endsBefore , ocp:endsWith

- explicit distiction between actual and estimated time references
  - ocp:hasActualBeginning , ocp:hasActualEnd
  - ocp:hasEstimatedBeginning , ocp:hasEstimatedEnd

- OCP-class-related process description properties
  - ocp:startsCycle , ocp:startsPhase
  - ocp:endsCycle , ocp:endsPhase
  - ocp:isInPhase
  - ocp:belongsToCycle , ocp:belongsToInstant , ocp:belongsToPhase , ocp:belongsToProcess
 
New datatype properties:
- explicit distinction between actual and estimated time stamps
  - ocp:hasActualTime , ocp:hasEstimatedTime

- OCP-class-related element information properties
  - ocp:hasCycleNumber
  - ocp:hasProcessID

For more information about the OCP, see the documentation.
