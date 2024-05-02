# FFRDTemplates
A draft repository for FFRD Templates and Schemas

```yaml
# FEMA Future of Flood Risk Development Folder Structure Template
"{{huc4code}}_{{huc4name}}":
    - "CommonFiles":
        # The common files directory stores all pre-model datasets, guidance, and documentation for the project
        # This directory houses all of the official data delivered prior to kickoff as listed in Section 2.4.3. Ad-hoc 
        # sharing of unofficial data should not be posted to the common files directory
        - "00_GuidanceSOP"
        - "01_DataPrep":
            - "CalibrationMetrics"
            - "ExistingModels"
            - "ExistingReportReferencesEtc"
            - "Geospatial"
            - "MeshRefinementDetermination"
            - "ModelUnitDetermination"
            - "ObservedData"
            - "StormDatabase"
            - "TranspositionRegions"
        - "02_Documentation"
    - "CP1_ModelsForReview: 
        # Checkpoint #1 is the location for posting the initial review for draft calibrated hydrologic, reservoir 
        # operations, hydraulics, and consequence models
        - "Consequences"
        - "Hydraulics"
        - "Hydrology"
        - "ReservoirOperations"
    - "CP2_ModelForBackCheck":
        # Checkpoint #2 is the location for posting updated models after QC review comments are addressed and responded to.
        - "Consequences"
        - "Hydraulics"
        - "Hydrology"
        - "ReservoirOperations"
    - "CP3_InitialIntegratedModels":
        # Checkpoint #3 is the location for posting the full suite of integrated models based on the initial draft
        # constituent models. The project’s model integration lead combines the models from check point #1, 
        # ensures they function as a system in a desktop environment, and posts results to check point #3. This is
        # a location for testing cloud computing capabilities of the initial integrated model dataset. The model 
        # integration lead provides feedback to individual modelers based on results of this initial integration step
        - "Consequences"
        - "Hydraulics"
        - "Hydrology"
        - "ReservoirOperations"
    - "CP4_FinalDeliveredModels":
        # Checkpoint #4 is the location where individual modelers post final delivered models. These models
        # represent final models after all QC comments are addressed and closed out by the reviewers and
        # incorporate feedback from the model integration lead from lessons learned from the initial integration step
        - "Consequences"
        - "Hydraulics"
        - "Hydrology"
        - "ReservoirOperations"
    - "CP5_FinalIntegratedModels":
        # Checkpoint #5 is the location for posting the final integrated model dataset. This location provides a 
        # location for testing the response of the integrated models in the cloud environment.
        - "Consequences"
        - "Hydraulics"
        - "Hydrology"
        - "ReservoirOperations"
    - "CP6_ModelStagedForFFRDCompute":
        # Checkpoint #6 is the location for staging models in preparation for cloud compute FFRD production runs.
        # The boundary conditions of these models are adjusted to accept generic storm events from the
        # randomized meteorology.
        - "Consequences"
        - "Hydraulics"
        - "Hydrology"
        - "ReservoirOperations"
    - "CP7_ProductionRuns":
        # Checkpoint #7, also known as Final FFRD, is the location for all final results for the FFRD study. 
        # The integrated models from checkpoint #6 are run for each of the randomized storms in the storms database
        - "Consequences"
        - "Hydraulics"
        - "Hydrology"
        - "ReservoirOperations"
    - "QuickShare": 
        # Temporary ad-hoc shared data can be shared among team members through the quick share directory. 
        # This allows sharing amongst team members large files that are temporary in nature, but useful for 
        # collaboration or technical discussions.
        
```
