@[TOC](FRIM : A Framework for Satellite - Borne Remote Sensing Image Matching)

# Introduction

FRIM is a remote sensing image matching framework designed to provide efficient methods for matching remote sensing images, particularly for satellite remote sensing image processing and analysis. This framework supports various image matching algorithms and offers flexible block-based processing for handling large-scale remote sensing image data.

# Usage


FRIM runs through a command-line tool. To use it, enter the following command in the CMD (Command Prompt):

> RSFM.exe task.xml

## task.xml Configuration File Description

task.xml is the core configuration file for FRIM, containing various parameters required for running the program. Below are the main configuration items in task.xml and their descriptions:

>MatchType: Matching method, supports the following algorithms:"SIFT";"RIFT";"ORB";"Affine";"BRISK";"Phase"

>BlockMode: Block processing mode, with two options: "image":  Block processing based on image;"object": Block processing based on object

>GridNumX and GridNumY:The number of blocks in the X and Y directions, respectively, indicating how the image is divided in these directions.

>Source: Path to the source image file.

>Reference: Path to the reference image file.

>DEM: Path to the reference image file.

>OutputDir: Path to the output folder (do not include file names). The program will output the processing results in this directory.
# Notes

This software is intended for academic research purposes only and may not be used for commercial purposes.

# Contact Information

If you have any questions or suggestions, feel free to contact us at:
>Author：Geng Zemin
>Contact Email：gengzemin@whu.edu.cn
