miller2018_Tongariro_SP_inversion
=================================

.. image:: https://travis-ci.org/simpeg-research/miller2018_Tongariro_SP_inversion.svg?branch=master
    :target: https://travis-ci.org/simpeg-research/miller2018_Tongariro_SP_inversion

Notebooks to run inversion code for SP models at Mt Tongariro hydrothermal system. Published as "Distribution of vapour and condensate in a hydrothermal system: Insights from self-potential inversion at Mount Tongariro, New Zealand"

https://agupubs.onlinelibrary.wiley.com/doi/abs/10.1029/2018GL078780

.. image:: Figure2_Js_model.png
    :width: 70%


**Abstract**

Inversion of self‐potential (SP) data for source current density, js, in complex volcanic settings, yields hydrological information without the need for a prior groundwater flow model. js contains information about pH, pore saturation and permeability, from which we infer the distribution of liquid and vapour phases. To understand the hydrothermal flow dynamics and hydraulic connectivity between surface thermal features at Mt Tongariro volcano, New Zealand, we undertook a reconnaissance scale self‐potential (SP) survey and developed an inversion routine for js, constrained by an existing 3D conductivity model from MT measurements. The 3D distribution of js at Mt Tongariro reveals a discontinuous zero js zone interpreted as vapour or residually saturated pore‐space, surrounded by low to moderate js interpreted as circulating condensate liquid. Bounding faults act as conduits for down flowing groundwater or condensate, as well as barriers for the hydrothermal system. Localised small scale circulation associated with individual surface thermal features, rather than a single circulating system, accounts for the lack of widespread anomalous geochemical observations prior to the 2012 Te Maari eruption.

**Plain Language Summary**

Volcanologists routinely sample fluids from springs and vents on volcanoes to determine that volcano's state of unrest. Prior to the 2012 Te Maari eruptions at Mt Tongariro, New Zealand, changes in water and gas chemistry that preceded the eruption, were found at only a few of the vents and springs sampled, despite evidence for a large hydrothermal system, thought to connect them. We wanted to understand why chemical changes in the water and gas weren't observed more widely on the volcano, and if it was related to the pattern of underground water movement. Water moving within a rock generates a small electrical charge, measurable on the surface as a voltage. We mapped voltage variations around the hydrothermal system at Mt Tongariro, and developed new 3D computer software to simulate the subsurface water movement. We found varying degrees of water and steam within the hydrothermal system that is likely controlled by the rock's ability to allow water movement. Importantly, we found no connectivity between individual springs and vents on the volcano, explaining observations of geographically isolated changes in water and gas chemistry prior to the eruptions. This has important implications for how geochemical monitoring of similar multivent volcanoes is undertaken.


**Notebooks**

There are 2 notebooks in this repository:

- `Js_inversion.ipynb <https://github.com/simpeg-research/miller2018_Tongariro_SP_inversion/blob/master/notebooks/Js_inversion.ipynb>`_ : runs Js (vector) inversion
- `DivJs_inversion.ipynb <https://github.com/simpeg-research/miller2018_Tongariro_SP_inversion/blob/master/notebooks/DivJs_inversion.ipynb>`_ : run Div Js (scalar) inversion


**Usage**

Dependencies are specified in `requirements.txt <https://github.com/simpeg-research/miller2018_Tongariro_SP_inversion/blob/master/requirements.txt>`_

Note that 32Gb ram is recommended to run these models.

.. code::

    pip install -r requirements.txt

Please `make an issue <https://github.com/simpeg-research/miller2018_Tongariro_SP_inversion/issues>`_ if you encounter any problems while trying to run the notebooks.
