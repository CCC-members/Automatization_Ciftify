# Automatization_Ciftify
Shell Script that permit run ciftify tool in one dataset.

RUN_CIFTIFY
Tool for data processing based on CIFTIFY TOOL.

Requeriments:

It's very important,as a previous step, to have installed the following tools:

Freesurfer version 6.0
FSL version 6.0
HCP-Pipelines-4.0.1
Ciftify version
Worbench for Linux version
See the documentation of CIFTIFY TOOL https://github.com/edickie/ciftify.

Ciftify tool requires the output of the freesurfer processing as input parameter.

The run_cifitify script works by calling ciftify tool for all candidates of the dataset described (param1), and collects the results in the output folder (param2)

Use Mode:

./run_cifity param1 param2

Param1 is the folder that contains all candidates.

Param2 is the name of the Output Folder.

Example:

./run_ciftify /home/iris/Mapeo_Study /home/iris/Mapeo_Study cifti_mapeo_output

Authors: Iris Rodriguez Gil.

Date: September ,2019.
