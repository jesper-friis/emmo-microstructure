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

The aim is to support both microstructure modelling as well as
characterisation.

For modelling, we will distinguish between
  - evolution models (that changes the microstructure through a
    succession of states) and
  - property models (that relates a microstructure state to a property).

It should support describing same concept at different spacial
resolutions, like mean field, 1D, 2D and 3D.

For mean field descriptions (what about spatially resolved), it should
be possible describe quantities at different statistical levels, like
mean size, normalised size distribution (mean + standard deviation)
and full size distribution.


Open questions
--------------
Should processes that changes the microstructure, like
  - casting (solidification)
  - homogenisation
  - extrusion/rolling
  - deformation (forming)
  - aging

be included in this, or a separate ontology?  The processes connects
closely to evolution models.




Obtaining emmo-microstructure
-----------------------------
Clone it from github with

    git clone --recurse-submodules --shallow-submodules https://git@github.com/jesper-friis/emmo-microstructure.git
