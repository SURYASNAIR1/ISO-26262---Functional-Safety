# ISO-26262---Functional-Safety

- Published in 2011, In 2018 it was republished 

- Functional Safety is a general approach to make car electronics safe.

- ISO 26262 : Contain guidelines to protect road users(drivers and pedestrians) from injuries 
  caused by faults in vehicle electronics and software.

- Functional safety aims to reduce risks to a level that society finds acceptable.

- There are different safety standards
  
  - IEC 61508 : Generic standard 
     
      - IEC 61511: Industrial processes
    
      - IEC 61513: Nuclear industry
    
      - IEC 62061: Machine safety
    
      - EN 50126/8/9 : Railways
    
      - ISO 26262 : Automotive

 - D0178B/C : For areonautics

 - ECSS : Space(ESA)

 - IEC 62304 (Medical devices)

- 12 parts are there for ISO

# 1st Part: Vocabulary 

- Give the terms, definitions and abbrevations used in the standard 

- Gives an idea on ISO, requirement for functional safety, scope of functional safety

# 2nd Part: Managementof functional safety
- How to handle functional safety
  
- At the organizational level what are the things that we need to do to ensure functional 
  safety

- What are project dependent and project independent activities and how they're going to do it

- Who is responsible for what, in a team how many people do we need for functional safety, 
  what is the need of safety manager in your team

# 3rd Part - 7th part: safety life cycle

**Part 3**: Concept Phase

- When we start a product we need to have concept on what the product is all about or we have 
  to define the product like the specification of the product, different supporting factors 
  need for the product. This is called item definition and is done by OEM.

 - This part will define the item then after that we'll see what are the hazards that are 
   going to happen to the item and what are the risks that will happen if this hazard is 
   persisting. This is called hazard analysis and risk assessment.

- Depending on the hazard analysis and risk assessment there are different classification for 
  risks. Which is called as ASIL level.

- Depending on ASIL level we will be defining the safety goal for product.

**Part 4**: System (mainly ECU) development

- Safety plan (first work product), requirements, system design, system intergration, 
  assessment, releases etc..

**Part 5**: Hardware development

- Requirements, safety plans, verification, metrics etc...

**Part 6**: Software development

- Requirements, architecture, data calibration etc...

**Part 7**: Manufacturing, operation, service, decommissiong

- Manufacturing, control plan, service manula for decommissiong etc...

**Part 8**: Supporting Processes

- Qualification of hardware components, interfaces to customers and suppliers, documentation, 
  qualification of software tools etc...

**Part 9**: ASIL (Automotive Safety Integrity Level) and safety oriented analysis

- Safety analaysis (FMEA, FTA, DFA)

- ASIL level A to D is there

- ASIL D : critical level product

- ASIL A : Not critical product

**Part 10**: Guidelunes on ISO 26262

**Part 11**: Guidelines on application of ISO 26262 to semiconductors

**Part 12**: Adapatation for motor cycle

- Hazards, MSIL etc...

# Management of functional safety
- Overall safety management ---> defines the requirement for the organization

- Safety management during product development: all activities are carried out by ISO need to 
  check by safety manager

- Safety management after the release for production: keep track of the product after release 
  also
  
- Safety case is called the safety product

# Safety life cycle

Whenever we agree to the customer requirement and when project is coming to the company, we do 2 work projects which are DIA(Development Interface Agreement) and impact analysis.

In  DIA(Development Interface Agreement) we'll have a handshake with OEM to deliver which products and which products can be shown.

- RASIC(Responsible Approve Support Informed Contribution): technical term used in the whole 
  product life cycle. Who is responsible, who would  be the approval, to whom will be 
  informed about the work product and who will be supporting.

# Safety Release Process

- Goal: to summarize the current project safety status and verification result in order to 
  request for the product safety release.

- This step focuses on the finialization of safety work products- safety requirement, safety 
  manual and safety assessment report.

- Bosch uses level 1 to level 4.

- Safety releases is provided for the level 3 and level 4 releases only.

- **Level 1:** We are going to test that vehicle with walking speed (less than 5kmph)

- **Level 2:** Testing on a track

- **Level 3:** Testing on public road

- **Level 4:** Giving to public without any restriction (customer release)

- This process step starts once the safety plan is fixed and the project specific safety a 
  argumentation is available. And the final work product is a safety case/report.
 
- Safety case: evidence for the implemenatation of ISO 26262 for the developed product and 
  reflects the current state of the project/ safety concept implemetation.

- Safety release is recommended by the safety manager and approved by development management.









