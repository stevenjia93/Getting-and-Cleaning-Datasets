{\rtf1\ansi\ansicpg1252\cocoartf1404\cocoasubrtf460
{\fonttbl\f0\fnil\fcharset0 HelveticaNeue;\f1\fnil\fcharset0 Menlo-Regular;}
{\colortbl;\red255\green255\blue255;\red38\green38\blue38;\red0\green0\blue0;}
{\*\listtable{\list\listtemplateid1\listhybrid{\listlevel\levelnfc0\levelnfcn0\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{decimal\}.}{\leveltext\leveltemplateid1\'02\'00.;}{\levelnumbers\'01;}\fi-360\li720\lin720 }{\listname ;}\listid1}}
{\*\listoverridetable{\listoverride\listid1\listoverridecount0\ls1}}
\margl1440\margr1440\vieww10800\viewh8400\viewkind0
\deftab720
\pard\pardeftab720\sl640\sa320\partightenfactor0

\f0\b\fs54 \cf2 \expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Getting and Cleaning Data - Course Project\
\pard\pardeftab720\sl512\sa320\partightenfactor0

\b0\fs32 \cf2 This is the course project for the Getting and Cleaning Data Coursera course. The R script, 
\f1\fs28 \cb3 run_analysis.R
\f0\fs32 \cb1 , does the following:\
\pard\tx220\tx720\pardeftab720\li720\fi-720\sl512\partightenfactor0
\ls1\ilvl0\cf2 \kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	1.	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Download the dataset if it does not already exist in the working directory\
\ls1\ilvl0\kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	2.	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Load the activity and feature info\
\ls1\ilvl0\kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	3.	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Loads both the training and test datasets, keeping only those columns which reflect a mean or standard deviation\
\ls1\ilvl0\kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	4.	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Loads the activity and subject data for each dataset, and merges those columns with the dataset\
\ls1\ilvl0\kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	5.	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Merges the two datasets\
\ls1\ilvl0\kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	6.	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Converts the 
\f1\fs28 \cb3 activity
\f0\fs32 \cb1  and 
\f1\fs28 \cb3 subject
\f0\fs32 \cb1  columns into factors\
\ls1\ilvl0\kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	7.	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Creates a tidy dataset that consists of the average (mean) value of each variable for each subject and activity pair.\
\pard\pardeftab720\sl512\partightenfactor0
\cf2 The end result is shown in the file 
\f1\fs28 \cb3 tidy.txt
\f0\fs32 \cb1 .\
}