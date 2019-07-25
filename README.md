# Integrated Eligibility & Enrollment Program

> **Welcome!**
> This website contains information about the Vermont Agency of Human Services' Integrated Eligibility and Enrollment (IE&E) modernization program. It is intended to provide a place where program participants and interested parties can keep track of the overall program goals, progress to date, and planned work.

----

_Contents:_

[Vision](#vision) | [Goals](#goals) | [Product Roadmap](#product-roadmap) | [Our Approach](#our-approach) | [New Ways of Working](#new-ways-of-working) | [Technical Principles](#technical-principles) | [Key Products](#key-products) | [In-Scope Benefit Programs](#in-scope-benefit-programs) 


### Vision
*We live in a world where...*

Eligible Vermonters have a simple and easy way to apply for, access, and maintain healthcare and financial benefits, without coverage gaps. We deliver these services efficiently and sustainably, using innovative ways of working and modern technology. 
 

### Goals
*Improve the customer experience in the following ways:*

- Provide a united application, determination, and enrollment experience that allows the customer to engage with the State through the channel of their choosing.

- Facilitate a simple, user-friendly experience that allows the customer to maintain continuous benefits, services, or health coverage, especially during critical life transitions.

- Ensure accurate and timely determination and notification of eligibility.

- Deliver clear and concise information throughout the eligibility and enrollment process through the customer’s chosen method and language.


*An integrated IE&E technology system will also ensure:*

- Staff can serve Vermonters efficiently and effectively by maximizing focus on Case Management and Customer Service.

- Vermont can meet Federal and State mandates and requirements.

- Improved data integrity and robust access to data for analysis, reporting and modeling.

- Financial integrity in the administration of benefit programs.


### Product Roadmap
This is where we communicate our IE&E strategy and delivery plan. On the the left side, you’ll find our vision, goals, and program benefits, followed by Workstream groups (which represent ongoing work outside of Product Teams) that support the program. Additionally, Centers for Medicare and Medicaid Services (CMS) mitigation requirements are represented by numbers on the Roadmap, showing when specific federal regulations will be addressed. The middle of the Roadmap highlights each Product Team and status of work over time. Each increment of work is intended to move the program forward in achieving its goals while providing incremental benefits. The products are in sequential order and track dependencies, key activities, and expected outcomes.   

It is important to understand that the State’s roadmap will evolve over time as new information/experience is gained and the marketplace evolves. The roadmap outlined here represents the State's most current thinking which will be updated as planning and implementation unfolds.  

[IE&E Roadmap](https://app.mural.co/t/gsa6/m/gsa6/1547053563230/5719fa7944aa959795c4ef7efa8a5dad04db6535)

### Our Approach
The IE&E Program will put the needs of the user first. This means letting the business lead and ensuring we understand the problems we are trying to solve before building a solution. 

The IE&E Program will also take smaller financial risks by breaking up large technology projects into small, manageable chunks that deliver clear value to the end user. This approach allows the IE&E Program to find the best vendor to fill a specific need without getting locked in. 

The IE&E Program will also utilize an Agile development methodology, which enables us to be nimbler as we make decisions and to course-correct as we go, resulting in a greater opportunity to achieve our desired outcomes. This incremental approach to delivering value to users, with their needs driving decisions, is a bottom-up instead of top-down mindset.
 
### New Ways of Working
"New ways of working" does not just refer to updating systems built long ago. It means that we are rethinking every aspect of our work and looking for opportunities to improve. This includes product management, risk mitigation, staffing, procurement, development methods, technology choices, oversight response, design, user engagement, vendor management, and more.

We have already seen many benefits from these efforts and seek to spread these lessons throughout the State of Vermont wherever possible.


### Technical Principles

- Build using Agile and iterative practices to deliver value frequently and incrementally
- Default to Open
- Default to Cloud
- Default to open standards and formats to maximize extensibility and interoperability
- Own and manage our data and business rules
- Choose emergent architecture over ‘big up-front design’
- Favor small components and loosely-coupled parts
- Automate testing and deployments
- Value experimentation and innovation

### Key Products  

**Ongoing** 

*Customer Portal Phase II: Online Application*

- Problem: Vermonters trying to apply for healthcare and financial assistance programs find the process to be difficult because it is time consuming, confusing to know where (digital systems or offices) to apply, what to apply for, and need to have multiple accounts and passwords. Each program has different timelines, requirements, and processes which are not tracked in one place. There is no centralized location for Vermonters to apply for State benefits. As a result, Vermonters must repeat the same information multiple times to different State offices simply to apply.

- Vision: To develop a modern, integrated eligibility and enrollment customer portal that provides Vermonters with a single sign-on service allowing them to easily apply to multiple benefit programs to help meet their basic needs. Utilizing agile development, modular procurements, and agile product teams, AHS IE&E has the goal of implementing an online application that not only meets State and federal standards but is user friendly for customers and staff. The technical solution should be hosted and maintained by the State.

*Premium Processing*

- Problem: Vermonters don’t always understand what they need to pay, by when, and how it will impact their coverage. They often do not know who to call when there is a problem. Data inconsistencies, transaction errors, and premium allocation issues make it difficult for staff to understand the information they are seeing and accurately communicate case status to customers. As a result of these issues, the Vermont Legislature has instructed the State to return Qualified Health Plan (QHP) premium processing to insurance carriers. This change will be effective for plan year 2021. Vermont is also out of compliance with State Medicaid rules regarding noticing for late premium payment and termination for nonpayment.

- Vision: To streamline the financial transactions and processes associated with the administration of health coverage and financial benefit programs as a part of the overall IE&E roadmap. This project will occur over a period of three years and capabilities will be delivered in multiple increments. The State will first transition responsibility for Qualified Health Plan premium processing to insurance carriers for coverage starting 1/1/2021. This will allow the State to implement the manual processes necessary to appropriately dun and terminate Medicaid (Dr. Dynasaur) coverage for nonpayment. 

[*Enterprise Content Management*](https://github.com/VermontAHS/IEE-Program/blob/master/ECMCharter_April2019.pdf)

- Problem: Currently, Vermont eligibility and enrollment staff utilize two enterprise content management (ECM) systems for scanning, indexing, workflow and viewing Vermonters’ documentation and notices. This leads to operational inefficiencies, unnecessary maintenance & operations costs, and difficulty coordinating enrollee documentation across programs.

- Vision: To utilize one system to scan, index, manage workflow, and view Vermonters’ documentation and notices. By utilizing only one system, ECM will create a streamlined experience and process for staff that is user-friendly and more efficient for the State to maintain. Training, documentation, and processes will be easier and faster resulting in less waste and improved quality.  

[*Customer Portal Phase I: Document Uploader*](https://github.com/VermontAHS/IEE-Program/blob/master/Customer%20Portal%20Phase%201%20Charter_April2019.pdf)

- Problem: Vermonters find satisfying verification requirements to be a challenging, time-consuming, and frustrating experience. For staff, verifying Vermonters’ income (and other requirements) routinely involves delays, stressful conversations, and duplicative work. Mail and paper slow the entire process from initial notification, to mailing documents, to scanning and indexing. Internal staff wait for Vermonters’ submission of required documentation such as pay stubs, employment forms, or attestations to process applications or changes, which lengthens the eligibility determination process.

- Vision: To make it easier for Vermonters to submit- and staff to process- manual verification documentation. We will implement a technical solution which allows Vermonters to utilize mobile and online technology to submit verification documents and to automate the classification of these documents. This solution will improve the efficiency of the eligibility determination process and result in a better customer experience for Vermonters.  

[*Business Intelligence*](https://github.com/VermontAHS/IEE-Program/blob/master/BusinessIntelligenceCharter_April2019.pdf)

- Problem: The current reporting system used by Vermont Health Connect (VHC) is expensive, complicated, and does not perform to our standards. It requires outside contractor expertise to support and is manually intensive and time consuming for State staff to maintain. It also means that VHC data is housed separately from the rest of IE&E Program data, which is in Microsoft SQL Server.  

- Vision: To align data storage and reporting for MAGI health coverage programs with the other in-scope benefit programs for IE&E, by migrating the data from the OBIEE data warehouse to Microsoft SQL Server. The new system will be easier for staff to use, enable self-service, and allow for real-time reporting and analytics. It will also be more affordable and enable in-house State of Vermont expertise to sustain support and maintenance of the solution.

**Completed**

[*Healthcare Paper Application Usability*](https://github.com/VermontAHS/IEE-Program/blob/master/HCAUCharter_April2019.pdf)

- Problem:  Healthcare paper applications contain essential information needed for staff to process health benefit eligibility determinations decisions. Currently, paper application forms are out of compliance with the Federal mandate to have a single application for all MAGI and non-MAGI healthcare programs. Additionally, the forms do not comply with plain language requirements, making it harder for applicants to complete the application correctly, often leading to requests for additional information which in turn causes processing delays.

- Vision:  A newly designed paper application, branded with VT logo and colors, that is easy for applicants to complete, enables full healthcare screening for both MAGI and non-MAGI based eligibility determinations, collects information needed for efficient and accurate eligibility decisions, and reduces data entry and processing time for staff.

### In-Scope Benefit Programs

Explore the 30 AHS benefit programs that are in scope for this modernization effort [here](https://github.com/VermontAHS/IEE-Program/blob/master/Benefit%20Programs%20In%20Scope.pdf).
