# Deep Meta Tool version 1.0
Deep Meta Tool: GUI tool to obtain Mean and Standard Deviation (SD) from Median and Interquartile range (IQR)

Manuscript available at DOI: https://doi.org/10.21203/rs.3.rs-828102/v1

![main_screen](https://github.com/DeepanshuSharma-BNB/Deep_Meta_Tool/blob/main/main_screen.png)

*Figure 1. Deep Meta Tool Version 1.0 main screen.*

The software provides fast, user friendly and combined of two different statistical methods for the calculation of Mean and Standard Deviation (SD) from the Median and Interquartile range (IQR) data, which is essential to conduct a meta-analysis.

The included two methods for calculations are –

#### 1. Hozo et al., 2005

S.P. Hozo, B. Djulbegovic, I. Hozo, Estimating the mean and variance from the median, range, and the size of a sample, BMC Medical Research Methodology. 5 (2005) 13. https://doi.org/10.1186/1471-2288-5-13.

#### 2. Bland, 2015

M. Bland, Estimating Mean and Standard Deviation from the Sample Size, Three Quartiles, Minimum, and Maximum, International Journal of Statistics in Medical Research. 4 (2015) 57–64. https://doi.org/10.6000/1929-6029.2015.04.01.6.

### PROCUDURE
After you download and extract the tool, you will get the following files at the installation directory –

1. Deep Meta Tool Version 1.0 folder, which has all the system files.
2. Sample files folder which has the following files –

* Bland 2015 Table 1 raw data.csv
* Bland 2015 Table 3 raw data.csv
* Meta-analysis datasheet format for MetaXL.xlxs
* Meta-analysis datasheet format for RStudio.csv
* R script for sample meta-analysis.r

![folder_screen](https://github.com/DeepanshuSharma-BNB/Deep_Meta_Tool/blob/main/folder_image.png)

*Figure 2. Folder generated after Deep Meta Tool Version 1.0 software installation.*

![user_manual](https://github.com/DeepanshuSharma-BNB/Deep_Meta_Tool/blob/main/user_manual_option.png)

*Figure 3. The User Manual.pdf can also be accessed from the help section.*

#### 1. Hozo et al., 2005 method

DATA FORMAT - Median(IQR)

*Example – 4.7 (3.6-5.8) → 4.7 is mean and 3.6 to 5.8 is the inter quartile range (IQR).*

The process to obtain accurate results are as follows –
1. Sample Size: If sample exceed 25, then median itself is the best estimator.
2. IQR (minimum): Put the lower value of IQR.
3. IQR (maximum): Put the higher value of IQR.
4. Press the "Calculate Mean" button.
5. Mean: The calculated mean is obtained here.
6. Press the "Calculate SD" button.
7. Press "Store Value" button to store the Mean and SD data.
8. After this, you can calculate mean and SD for next number.
9. Finally press "Generate Output" file in the installation folder with the name "Hozo_Method_Output.csv".

![hozo_window](https://github.com/DeepanshuSharma-BNB/Deep_Meta_Tool/blob/main/hozo_window.png)

*Figure 4. Process to calculate Mean and SD by Hozo et al., 2005 method.*

#### NOTE:
* Three values of SD are calculated, use the appropriate value as per your sample size.
* Don’t leave a column empty for any calculation.

#### 2. Bland, 2015 method

DATA FORMAT –

Raw Data → To calculate median, first quartile, third quartile, minimum and maximum values.

or

Median (Data range) → To calculate Mean and SD if you already have the mentioned values.

The process to obtain accurate results are as follows –
1. Enter the .csv file with raw data in the prescribed format. (Sample_Data.csv example file is included for the format reference).
2. Use the "Results" button to generate file - "Bland_Method_Parameters.txt" in the Deep Meta Tool Version 1.0 folder to obtain data.
3. The calculated data will automatically fill into the empty columns.

![output_files](https://github.com/DeepanshuSharma-BNB/Deep_Meta_Tool/blob/main/output_files.png)

*Figure 5. Output files are generated in the folder “Deep Meta Tool Version 1.0”.*

4. Sample Size: More accurate for bigger sample size.
5. Data range (minimum): Put the lower value of data range.
6. First quartile: Enter the value.
7. Median: Enter the median of the data range.
8. Third quartile: Enter the value.
9. Data range (maximum): Put the higher value of data range.
10. Press the "Calculate Mean" button.
11. Mean: The calculated mean is obtained here.
12. Press the "Calculate SD" button.
13. Press "Store Value" button to store the Mean and SD data.
14. After this, you can calculate mean and SD for next number.
15. Finally press "Generate Output" file in the installation folder with the name "Bland_Method_Output.csv".

#### NOTE:
* Column name for raw data to obtain median, first quartile, third quartile, minimum and maximum values should be - MEDIAN_DATA.

### ADDITIONAL INFORMATION

![cite_options](https://github.com/DeepanshuSharma-BNB/Deep_Meta_Tool/blob/main/cite_option.png)

*Figure 6. About section have two subsections - About author and Cite this software.*

The “About author” section will output a window with QR code to access the author’s website for contact, report a bug or feedback.

![qr_code](https://github.com/DeepanshuSharma-BNB/Deep_Meta_Tool/blob/main/contact_info.png)

*Figure 7. About author window with the QR code.*

The next subsection “Cite this software”

![cite_info](https://github.com/DeepanshuSharma-BNB/Deep_Meta_Tool/blob/main/cite_info.png)

*Figure 8. Cite this software section will give Reference message to cite this software in your manuscript.*

#### Metadata

*Table 4. Software metadata.*
* Current software version: 1.0
* Permanent link to executables of this version: https://github.com/DeepanshuSharma-BNB/Deep_Meta_Tool
* Installation requirements & dependencies: Turn off Windows firewall/antivirus software or provide admin access to Deep Meta Tool Version 1.0.exe while installation
* If available Link to user manual - if formally published include a reference to the publication in the reference list: https://github.com/DeepanshuSharma-BNB/Deep_Meta_Tool
* Support email for questions: https://deepanshu-sharma.com/
