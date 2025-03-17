# TER-Soccer-xT-Variation-Regression
Experimental (research) project carried out during the first graduate year (2024) at Paris Cité University, supervised by SERVANT Logan.

The project was divided in several steps: 
- Finding exploitable datasets of player coordinates during a soccer match
- Generating Voronoï diagrams representing both team's spatial control for each desired frame of a match
- Generating Radial Line Models (RLM) on the field to quantify possession volume in each direction relative to two arbitrary RLM center points, represented in two histograms, for each desired frame of a match
- Generating Expected Threat (xT) variation values
- Regressing xT variation values from the previous RLMs for each desired frame of a match using CNNs
