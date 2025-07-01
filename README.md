# MSPM-Fault-Detection
Data and scientific code to go with "Real-Time Data-Driven Fault Detection in Multicomponent Slurries through Data Fusion of Raman Spectroscopy, ATR-FTIR Spectroscopy, and FBRM"

1. MSPM Study.py includes most figures for the study, and makes use of data stored in Fault Data Publication.npz.
2. Design of Experiments - Training.py includes the Latin Hypercube that was used to create both the solid-phase and solution-phase training data.
3. Design of Experiments - Processing.py includes the three-tank mass balance with heels used to create process (validation and test data) in this study.
4. Boric Acid Reference.py includes a boric acid reference at high pH and unmodified pH for comparison.
5. Stokes Law.py includes a Stokes Law study where the time to fall a certain height for spherical particles is calculated.
6. Functions.py includes functions that are used in this work.

The "Raw Data" folder includes all data used in this study.
The "Figures" folder houses three empty folders that hold figures produced by the other Python scripts.
