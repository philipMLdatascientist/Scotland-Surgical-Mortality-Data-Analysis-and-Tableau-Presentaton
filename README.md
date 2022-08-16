Project Title

Scotland Surgical Mortality 2007-2012

There is an mp4 file that has a recording of my presentation. Please click on the link below to download and enjoy the video:

https://github.com/philipMLdatascientist/Scotland-Surgical-Mortality-Data-Analysis-and-Tableau-Presentaton/blob/main/Surgical%20Mortality%20(1).mp4?raw=true

I strongly suggest viewing the video. However, if you do not feel comfortable downloading a mp4 video then this link will take you to a powerpoint presentation and please enjoy the information in readme file contained below:



Project Description.

Can any outliers in surgical patient mortality be found per specialty, hospital, or surgical consultant in Scotland from 2007-2012.

Context

1. Background information 
Worldwide, 310 million major surgeries are performed each year; around 40 to 50 
million in USA and 20 million in Europe. Mortality during surgery is relatively rare, 
however, 30-day postoperative mortality is not. It is estimated that 1–4% of these 
patients will die, up to 15% will have serious postoperative morbidity, and 5–15% will 
be readmitted within 30 days. An annual global mortality of around 8 million patients 
places major surgery comparable with the leading causes of death from cardiovascular 
disease and stroke, cancer and injury. If surgical complications were classified as a 
pandemic, like HIV/AIDS or coronavirus (COVID-19), developed countries would work 
together and devise an immediate action plan and allocate resources to address it. 
Seeking to reduce preventable deaths and post-surgical complications would save 
billions of dollars in healthcare costs. (Dobson, 2020) 
The WHO’s (2010) analysis establishes three significant findings: 
•Surgical interventions take place on a massive and previously unrecognized 
scale in all countries and resource settings. 
•The inequity in service provision among countries and settings is dramatic. 
•Little is known about the indications for, and the quality, safety, and outcomes 
of, surgical care. 
The WHO has provided a set of standardized metrics for surgical surveillance (Weiser 
et al., 2009). In addition, a situational analysis tool has been constructed and deployed 
in a number of countries to help assess surgical capacity (WHO, 2010). As many as 50 
percent of these deaths and complications are preventable (Weiser, et al., 2008). 
Surgery is not without hazards in every setting; patients face risk from both the 
technical aspects of the procedures themselves and the anesthesia needed to induce 
insensibility and sedation. Surgery must also continuously measure patient outcomes 
to identify shortcomings, inform improvements, and maintain high levels of quality care. 
Studies from high-income countries (HICs) demonstrate high rates and variability of 
postoperative mortality. In the Netherlands, a review of 3.7 million inpatient surgical 
procedures at 102 hospitals over 15 years reveals a perioperative mortality rate of 1.85 
percent (Noordzij et al., 2010). A similar inpatient surgical death rate has been noted in 
the United States, with all-cause postoperative mortality in 2006 estimated to be 1.14 
percent to 1.32 percent (Weiser et al., 2011). Pearse (2012) studied the outcomes of 
one week of inpatient surgery (excluding cardiac, neurosurgical, radiological, and 
obstetric procedures) in 498 hospitals in 28 European countries. The in-hospital crude 
postoperative mortality ranged from 1.2 percent in Iceland to 21.5 percent in Latvia. 

2.  We need to start analyzing data regarding surgical mortality to find areas for 
improvement to decrease patient morbidity and mortality. 
3. I evaluated patient surgical mortality data in Scotland from 2007-2012. 
4. I found interesting patterns in the surgical data mortality with regards to mortality 
rate per specialty and even found outlier mortality rates within the general surgery specialty within a a few hospitals
from 2007-2012. I also have criticisms regarding the data collection methods used. 
5. The identified outliers can serve as initial leads for process improvement. 

Works Cited 


Dobson G. P. (2020). Trauma of major surgery: A global problem that is not going away. International journal of surgery (London, England), 81, 47–54. https://doi.org/10.1016/j.ijsu.2020.07.017

Noordzij P G, Poldermans D, Schouten O, Bax J J, Schreiner F A. others. 2010. “Postoperative Mortality in the Netherlands: A Population-Based Analysis of Surgery-Speci fic Risk in Adults.” Anesthesiology 112 (5): 1105–15. 

Pearse R M, Moreno R P, Bauer P, Pelosi P, Metnitz P., et al. 2012. “Mortality after Surgery in Europe: A 7 Day Cohort Study.” The Lancet 380 (9847): 1059–65. 

Weiser T G, Regenbogen S E, Thompson K D, Haynes A B, Lipsitz S R. et al. 2008. “An Estimation of the Global Volume of Surgery: A Modelling Strategy Based on Available Data.” The Lancet 372 (9633): 139–44. 

Weiser T G, Makary M A, Haynes A B, Dziekan G, Berry W R. et al. 2009. “Standardised Metrics for Global Surgical Surveillance.” The Lancet 374 (9695): 1113–17. 

Weiser T G, Semel M E, Simon A E, Lipsitz S R, Haynes A B. et al. 2011. “In-Hospital Death Following Inpatient Surgical Procedures in the United States, 1996–2006.” World Journal of Surgery 35 (9): 1950–56.  

WHO (World Health Organization). 2010. “Tool for Situational Analysis to Assess Emergency and Essential Surgical Care.” Geneva: WHO. http://www .who.int/surgery/publications/QuickSitAnalysisEESCsurvey.pdf.

Data

https://www.johnsnowlabs.com/marketplace/surgery-mortality-rates-in-scotland-2007-2012/

This dataset provides data that are routinely provided to health professionals in Scotland, in confidence, to help them assess the outcomes of treatment of their patients. Used in this way, and with knowledge of the cases and the local care system, these data can be an important tool for improving the safety and quality of surgical care. Taken out of context and without this background information, these figures do not provide reliable information about surgeons’ performance. In June 2013, the Information Services Division (ISD) of National Services Scotland provided information about the mortality rates of surgeries in Scotland for six years starting from 2007 to 2012. Planning and delivering effective and specialist national services which co-ordinate, strengthen and support activities aimed at protecting the people of Scotland from infectious diseases and environmental hazards. Since the reporting of surgeon-specific outcomes was introduced in 2013, case numbers and risk-adjusted 90-day mortality rates in patients undergoing an “elective” or “scheduled” major colorectal cancer resection have been reported for individual consultant colorectal surgeons. The increase in the percentage procedures performed as a day case is attributable to a combination of efforts by NHS boards to provide day surgery for relevant cases and improvements in the level of procedure recording for outpatient attendances.

Data Description

Year	Indicates the recording year of data.	date	-

NHS_Board_of_Treatment	Refers to the NHS board of treatment.	string	-

Hospital Indicates the different hospitals for surgeons' mortality in Scotland.	string	-

Specialty	Indicates the name of the different surgical specialties.	string	-

Consultant_Name	Indicates the full name of the consultant.	string	-

Episodes	Refers to the number of episodes.	integer	level : Ratio

Deaths	Indicates the number of deaths.	integer	level : Ratio

Mortality_Rate	Indicates the surgeon's mortality rates. It is calculated by the number of deaths/number of episodes.	number	level : Ratio

Deliverables

A recording of my Tableau presentation regarding my findings of Scotland Surgical Mortality from 2007-2012.

Summary of Findings

A number of hospitals were found to be outliers for general surgery. However, due to data collection methodology, I could not ascertain what attributed to these findings. However, my analysis serves as an excellent starting point for performance-improvement initiatives.



