# Programming Assignment 4

<b>Deadline:</b> September 17, 2024

## I. Intended Learning Outcomes:
  1. To identify the codes and functions needed in cleaning and visualizing data
  2. To be able to apply and use the different codes and functions in creating a Python program that will be used in data wrangling and data visualization

## II. Instructions:
  Write a Python script/code in the Jupyter Notebook to do the given problems. You may submit your Jupyter notebook in the dedicated submission bin.
  > [!IMPORTANT]
  > Download the ECE Board Exam 2 dataset found on this link: bit.ly/ECEBoardExamDataset

### ECE Board Exam Problem
  1. Create the following data frames based on the format provided:
  > [!NOTE]
  > Example: Vis = [“Name”, “Gender”, “Track”, “Math<70”]; hometown is constant as Visayas
  > | Name | Gender | Track           | Math |
  > | ---- | ------ | --------------- | ---- |
  > | S4   | Male   | Instrumentation | 65   |
  > | S11  | Female | Communication   | 48   |
  > | S22  | Female | Communication   | 64   |

  &nbsp;&nbsp;&nbsp;&nbsp;a. Filename: Instru = ["Name”, “GEAS”, “Electronics >70”]; where track is constant as Instrumentation and hometown Luzon
  &nbsp;&nbsp;&nbsp;&nbsp;b. Filename: Mindy = [ “Name”, “Track”, “Electronics”, “Average >=55”]; where hometown is constant as Mindanao and gender Female

  2. Create a visualization that shows how the different features contributes to average grade. Does chosen track in college, gender, or hometown contributes to a higher average score?

## III. Utilized Integrated Development Environment (IDE)
  > [!NOTE]
  > Jupyter Notebook via Anaconda Navigator

## IV. Libraries
  > [!IMPORTANT]
  > It is essential to import this library:
  > ``` import pandas as pd ```

## V. ECE Board Exam Results
| Name | Gender | Track            | Hometown | Math | Electronics | GEAS | Communication |
| ---- | ------ | ---------------- | -------- | ---- | ----------- | ---- | ------------- |
| S1   | Male   | Instrumentation  | Luzon    | 58   | 89          | 75   | 78            |
| S2   | Female | Communication    | Mindanao | 52   | 75          | 90   | 52            |
| S3   | Female | Instrumentation  | Mindanao | 83   | 74          | 77   | 57            |
| S4   | Male   | Instrumentation  | Visayas  | 65   | 58          | 91   | 68            |
| S5   | Male   | Communication    | Luzon    | 59   | 86          | 43   | 88            |
| S6   | Female | Microelectronics | Visayas  | 88   | 45          | 86   | 83            |
| S7   | Female | Instrumentation  | Luzon    | 66   | 60          | 60   | 48            |
| S8   | Male   | Instrumentation  | Luzon    | 49   | 81          | 64   | 53            |
| S9   | Male   | Instrumentation  | Luzon    | 50   | 36          | 63   | 42            |
| S10  | Male   | Microelectronics | Mindanao | 80   | 84          | 61   | 44            |
| S11  | Female | Communication    | Visayas  | 48   | 56          | 48   | 67            |
| S12  | Male   | Communication    | Visayas  | 89   | 67          | 84   | 64            |
| S13  | Female | Microelectronics | Luzon    | 88   | 35          | 83   | 43            |
| S14  | Female | Microelectronics | Luzon    | 83   | 77          | 89   | 73            |
| S15  | Female | Microelectronics | Mindanao | 69   | 41          | 40   | 86            |
| S16  | Female | Communication    | Luzon    | 71   | 70          | 87   | 81            |
| S17  | Female | Microelectronics | Mindanao | 81   | 79          | 77   | 45            |
| S18  | Male   | Communication    | Visayas  | 81   | 40          | 81   | 52            |
| S19  | Male   | Microelectronics | Luzon    | 79   | 63          | 79   | 71            |
| S20  | Female | Communication    | Mindanao | 59   | 60          | 62   | 85            |
| S21  | Female | Microelectronics | Visayas  | 83   | 51          | 68   | 72            |
| S22  | Female | Communication    | Visayas  | 64   | 39          | 89   | 58            |
| S23  | Male   | Instrumentation  | Luzon    | 84   | 70          | 74   | 47            |
| S24  | Female | Microelectronics | Visayas  | 85   | 45          | 60   | 41            |
| S25  | Male   | Communication    | Luzon    | 74   | 91          | 94   | 42            |
| S26  | Female | Instrumentation  | Visayas  | 71   | 47          | 83   | 62            |
| S27  | Male   | Microelectronics | Visayas  | 70   | 47          | 40   | 86            |
| S28  | Male   | Communication    | Visayas  | 85   | 53          | 80   | 53            |
| S29  | Male   | Instrumentation  | Mindanao | 73   | 48          | 71   | 62            |
| S30  | Male   | Instrumentation  | Luzon    | 78   | 81          | 57   | 56            |

## VI. Author
  * Name: AFIDCHAO, Danielle Taylan<br/>
  * Section: 2ECE-A
