# NZRIS Label Schemes & Code Sets  

There are several label schemes available in NZRIS allowing for categorisation of data. All labels are captured in a single field on the grants-metadata record. The format of the field is as follows:  
  
•	**Label Value** (e.g. 220302 Electronic information storage and retrieval services)\
•	**pipe delimiter**\
•	**Label Scheme Identifier** (e.g. for-2020)\
•	**pipe delimiter**\
•	**Percentage** (e.g. 25)\
•	**semicolon delimiter** = end of record.  

Example:  
310803 Plant cell and molecular biology|for-2020|25;310804 Plant developmental and reproductive biology|for-2020|50;310806 Plant physiology|for-2020|25;260205 Softwood plantations|seo-2020|30;260506 Kiwifruit|seo-2020|70   
  
In the example above there are three Fields of Research 2020 codes:  
  
* *310803 Plant cell and molecular biology (25%)*  
* *310804 Plant developmental and reproductive biology (50%)*  
* *310806 Plant physiology (25%)*  

and two Socio-Economic Objectives 2020 codes:  
  
* *260205 Softwood plantations (30%)*  
* *260506 Kiwifruit (70%)*  

This same format applies to all label schemes and all label schemes can be entered in the same field as a string.  For example Strategic Programme information would be added in the same format:  
  
310803 Plant cell and molecular biology|for-2020|25;310804 Plant developmental and reproductive biology|for-2020|50;310806 Plant physiology|for-2020|25;260205 Softwood plantations|seo-2020|30;260506 Kiwifruit|seo-2020|70 **;CoRE Bio Protection Research Centre|c-strategic-programme|**  

Files for each of the label schemes are included in this repository.  The first column of each csv file contains the "Label Value" and the file name includes the "Label Scheme Identifier" (e.g. for-2020 label values.csv).   

## ANZSRC  
Label Scheme files are provided for ANZSRC codes.  Further information can be found in Stats NZ’s classification management system Aria as follows:

[Field of Research V2]([external link](https://aria.stats.govt.nz/aria/#ClassificationView:uri=http://stats.govt.nz/cms/ClassificationVersion/d3TYSTsmz2uc8CY1))

[Socio-Economic Objective V2]([external link](https://aria.stats.govt.nz/aria/#ClassificationView:uri=http://stats.govt.nz/cms/ClassificationVersion/d1iJyaEzjWHJiRej))

[Type of Activity V2]([external link](https://aria.stats.govt.nz/aria/#ClassificationView:uri=http://stats.govt.nz/cms/ClassificationVersion/Wg615FKY3OhnyOzL))

Differences between the previous and new versions (also on Aria):

[Field of Research V1-2]([external link](https://aria.stats.govt.nz/aria/#ConcordanceView:uri=http://stats.govt.nz/cms/ConcordanceVersion/Z5oCDBWNUDccW089))

[Socio Economic Activity V1-2]([external link](https://aria.stats.govt.nz/aria/#ConcordanceView:uri=http://stats.govt.nz/cms/ConcordanceVersion/DUfQ3q5mjGcCH4tU))
