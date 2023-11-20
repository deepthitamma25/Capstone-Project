# Fairfax County Fire & Rescue Department

Fairfax County Fire and Rescue department is a provider of fire suppression, technical rescue, water rescue, life safety education, fire prevention, arson investigation and emergency 
medical services to Fairfax County, Virginia. Emergency medical services include advanced life support response by ALS (Advanced Life Support) capable engines and transport units. As 
the leading provider of fire suppression, technical rescue, hazardous materials, water rescue, life safety education, fire prevention, arson investigation and emergency medical services
through capable transport units, the department’s data volume increases daily, and it is important to turn data into knowledge. This will effectively address the data growth concerns 
since it will allow the department to plan for the long-term by implementing strategic business decisions. More specifically depending upon the risks and benefits of the patients while 
the patient is transported, providers must give recommendations of destination and get the patient’s consent to destination which can improve the transport making emergency units 
reliable and optimal. 

The aim of this project is to introduce operation efficiency in the provision of emergency and non-emergency services by the Fairfax County Fire and Rescue Department by using 
Classification Models. Specifically wanted to see if there are any patterns in the transport decision-making for different, shifts, fire stations, units, and providers given the 
location of the incident, the location of the transport destination, and the reason for choosing that destination through data analysis and visualizations. This analysis will also 
help in determining whether providers are compliant with the Emergency Medical Services (EMS) manual and Office of the Medical Director (OMD) directives regarding patient transport 
destinations. From the visualizations, we found that the providers are compliant with respect to transporting the patients to the facilities with transport interval of less than 60 
minutes.  

## Introduction

This project is based on the Transport Decision Making for the Fairfax Fire Department. The dataset has all the information, if there is an emergency call that was made by the patient.
This dataset gives us the information about every unit which is assigned, which hospital that the unit reaches based on the preference by the patient, what procedures and medications 
were given to the patient after they were taken to the hospital. 

**Choice of Hospital:** When the emergency unit arrives at the place of accident. The patient is given a choice to choose which emergency care or hospital. If the patient has a specific 
preference, the provider is instructed to take them to the desired hospital. 

**Type of Injury:** After the emergency providers arrive at the place of accident. They do a complete examination of the injured patient and then decide about the type of treatment that 
they require. The decision of selecting a hospital is completely based on the injury. 

**Availability in the hospital:** When the healthcare providers filter the hospitals based on the injuries, the provider needs to have immediate information about the availability of 
doctors or care for the hospital. 

## Project Objectives

The Fairfax County Fire & Rescue Department needs a mechanism to determine the provider's collaboration with the Emergency Medical Services manual and the instructions published by 
the Officer of Medical Director regarding the patient transport destinations. 

 ## Solution Space
Our system delivers accuracy to the Fairfax Department which provides accuracy reports for the emergency service. There is no department that is flawless, which is why with our 
project we deliver reports which identifies and minimizes the flaws of the department. By doing this we can make the decision of transport making emergency units reliable and optimal, 
which results in saving the lives of people. 

We formulate the best recommendation based on: 
-	Matching clinical need and ED capability – Trauma center, stroke center, STEMI center, etc.
-	Home hospital status – If all the patient's treatment is provided by a single hospital or health system, every effort should be taken to relocate the patient to that site — this includes patients who have recently undergone surgery. 
-	Patient preference is considered both step one and step two.
-	If the patient’s preference involves a long transport interval (greater than 60 minutes one way), contact the UFO and EMS Supervisor for approval. 
- If the patient requests transport out of state, contact the UFO and EMS Supervisor for approval.
-	If system demand is high and/or unit availability low, then contact the UFO       and EMS Supervisor for approval. 
-	Step two is crucial if the patient's desire poses a risk owing to instability or a poor match to clinical need/ED capability, so the patient is aware of the dangers connected with their choice when we recommend differently.
-	Proximity is a factor to be considered but should not be the sole determinant. (Rescue, 2019)


## Definition of Terms

There are certain terms which need to be explained for a better understanding. There are listed below: 

ALS - Advanced Life Support
BLS - Basic Life Support
ACCIMF - Accident with Injury
CPRF - Cardiac Arrest - CPR in progress
EMS - Emergency Medical Services


## Data Context:
Data Context is defined as the network of connections among data points. Those connections may be created as metadata or simply identified and correlated. In the dataset that was provided to us, we consider the Primary Key data item to be the data point. As Primary key has all the information about a specific incident like patient information. Units transported, Injury Type, Medication Given and Level of Care (LOC) given to the patient. This data point holds significance and useful information about events for the organization. 

There are also 4 Level of Care:
Level 1: Situations requiring immediate treatment.
Level 2: Acute ALS patient who will require active, continuing ALS treatment while being transported.
Level 3: A stable patient who will be monitored for ALS but will not require active treatment during transit.
Level 4: A stable patient who requires BLS or monitoring while being transported.

## Data Conditioning
Data conditioning improves data flow and administration to safeguard and boost efficiency. Data conditioning allows both cloud and business data centers to dramatically enhance the allocation of system resources while increasing application performance by using specialized techniques meant to route, optimize, and secure stored data or data as it flows through a computer system. As a result, both operational and capital expenses are reduced. All the columns of the datasets are specified in a certain condition so that the values which are entered follow proper constraints and the values that do not fit the constraint are replaced. 

## Data Quality Assessment

<img width="684" alt="image" src="https://github.com/deepthitamma25/Capstone-Project/assets/89256455/8e8db00b-8182-45dd-952c-df5a5a40c516">



DOMAIN OF PROBLEM: Health Care (Service Operations to Local Communities) 
IMPORTANCE OF PROBLEM:  For providing better safety to the people, there needs to be better understanding of the process that is being followed and if the providers are following 
the guidelines mentioned by the department and are all the patterns between different factors being reasonable to find out where there is a lag and what needs to be improved.
To determine whether providers are compliant with the Emergency Medical Services (EMS) manual and Office of the Medical Director (OMD) directives regarding patient transport destinations.
To find if there are any patterns in the transport decision-making for different, shifts, fire stations, units, and providers given the location of the incident, the location of the
transport destination, and the reason for choosing that destination. 
WHY DATA ANALYSIS:  
To extract insights of problems that are being faced.
To improve resource availability of resources to combat incidents.
To identify any training needs.


