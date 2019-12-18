First draft of an EMMO-based ontology for microstructures
=========================================================
This is intended to be a domain ontology for metallic microstructures,
covering aspects like:
  - composition
  - particles, both stable (primary) and metastable (precipitates)
  - grains
  - subgrains
  - grain boundaries & particle free zones (PFZs)
  - texture
  - dislocations

Should processes that changes the microstructure, like
  - casting (solidification)
  - homogenisation
  - extrusion/rolling
  - deformation (forming)
  - aging
be included in this, or a separate ontology?  The processes connects closely
to models (both evolution and property models).



Obtaining emmo-microstructure
-----------------------------
Clone it from github with

    git clone --recurse-submodules --shallow-submodules git@github.com:jesper-friis/emmo-microstructure.git
