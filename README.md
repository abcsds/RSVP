# Rapid Serial Visual Presentation (A template)

A short description of the RSVP paradigm.

This file works as an orientation into the usage, mantainance, and development of this research project. Make sure to point from this document to all the necessary documentation.

## Method
Using psychopy for the paradigm, Brain Products' BrainVisionRecorder.

## Project Folder structure
- `data`: a folder to keep the input data for your experiment. These are stimuli, images, videos, sounds, etc., for your paradigm. Datasets for non-recording experiments can be placed here.
- `doc`: Documentation for your research project.
 - `handouts`: Documents to hand out to your participants. This includes a Call for Participants, and an information sheet for the participants.
 - `img`: Figures, images, and plots that help you document your experiment.
 - `settings`: Place your settings or configuration files here.
  - `BrainVisionRecorder`: Workspace and configurations for BP software. An example of a workspace file for BVRecorder is placed here.
  - `layout`: Files related to the electrode placement selected.
- `raw`: This folder contains the `XDF` files required for analysis.
- `para`: The psychopy paradigm folder.
 - `data`: A folder for the logs comming from psychopy.
 - `lists`: The trial lists for the paradigm.
 - `res`: A folder for the resources of your paradigm.
 - `main.psyexp`: The RSVP paradigm programmed for psychopy.
 - `README.md`: Information on the paradigm project.
- `scr`: Scripts for processing and analysis.

## Raw Data
Raw data is stored in the [`xdf`](https://github.com/sccn/xdf/wiki/Specifications) format, under the `out` directory.
