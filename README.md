# Circuit defects Detection Using Yolo V5

## Introduction
The aim of this project is to detect the defects of circuit boards.

## Dataset
Circuit dataset was used for the Circuit defects detection project. This dataset consists of approximately 11k images of different circuit boards.
## Preprocessing
The preprocessing steps of the proposed project are following:

•	Annotate the Images of defects

•	Annotation Criteria

o	Residue (If the portion of circuit contains some residue)

o	Short (If two portions of circuits are connected accidently)

o	Bubble (If the portion of circuit is emerged)

o	Metallization defects (If the metal of the circuit is damaged)

o	Surface defects (If the surface of the circuit is damaged)

o	Flakes (If the portion of the circuit is broken)

o	Unclassified (Any defect does not belong to above classes)

## Model Training 
For the Circuit defects Detection, Yolo V5 model was trained with the annotated images. The details of the model training are following:

•	Use 7500 Annotated Images

## Results

•	Use 3500 Annotated Samples for Evaluation

•	Calculate Mean Average Precision (MAP)

•	Got 0.71 Mean Average Precision of all classes

## Documentation
Access the Prepared Dataset and Report from [here](paset google drive link here)

