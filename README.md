# FHIR Learning Resources

This page contains resources for
- Learning about FHIR in general
- FHIR Tools and Resources
- Death on FHIR Tools and Resources

These resources are broken up into five sections:
1. The first section is tailored towards a more general audience interested in FHIR and the Death on FHIR work.
2. The second section is tailored towards those looking to better understand the FHIR profile and implementation guide development process, and the tools that support those efforts.
3. The third section is tailored towards a technical/developer audience, and is intended to help developers begin to write software that utilizes FHIR.
4. The fourth section is dedicated to Death on FHIR, and includes the resources/tools/utilities/applications that are being developed to support that effort.
5. The fifth section contains general links of interest that relate to FHIR, Death on FHIR, and mortality data in general.


## FHIR for the General Audience

The following table includes links to various resources for learning more about FHIR, organized by the time investment needed to complete.

| Time Needed   | Description | Reference |
| -----------   | ----------- | --------- |
| A few minutes | [**Webpage**] Wikipedia Summary | https://en.wikipedia.org/wiki/Fast_Healthcare_Interoperability_Resources |
|               | [**Webpage**] HL7 FHIR Overview | https://www.hl7.org/fhir/overview.html |
| A few hours   | [**Textbook**] Practitioner's Guide to Health Informatics, by Mark L. Braunstein, MD., pp. 65-78 - This is good introduction to FHIR from a non-technical perspective. It’s primarily a description of what you can do with FHIR rather than how to do it, a historical perspective of what came before, and some prognostics about where FHIR is headed. The entire book is about 160 pages. | https://www.amazon.com/dp/3319176617 |
| A few days    | [**Course**] Udacity has a free course on Intro to Health Informatics that has several short videos on FHIR; the videos are also hosted on YouTube. | https://www.udacity.com/course/health-informatics-in-the-cloud--ud809 |
| A few weeks   | [**Course**] Health Informatics on FHIR, a 4-week Coursera course. | https://www.coursera.org/learn/fhir |
|               | [**Textbook**] Health Informatics on FHIR: How HL7's New API is Transforming Healthcare | https://www.amazon.com/dp/B07FMN8DTH |

The following table includes links to various tools/sites useful for understanding FHIR.

| Name             | Description | Reference |
| ----             | ----------- | --------- |
| clinFHIR         | An open source tool for Clinicians and Business Analysts who are interested in learning about FHIR, and about FHIR profiling. | http://clinfhir.com/ and https://clinfhir.atlassian.net/wiki/spaces/CLIN/pages/491526/Introduction |
| HL7 FHIR Wiki    | Wiki page for FHIR hosted by HL7. | http://wiki.hl7.org/index.php?title=FHIR |
| Argonaut Project | The Argonaut Project was a cross-industry group of hospital systems, insurance companies, and other private sector entities that came together as an implementer’s workgroup to advance the development and adoption of FHIR (Note: Apple, Google, and hundreds of partners have all agreed to implement the Argonaut profiles). | http://argonautwiki.hl7.org/index.php?title=Main_Page |


## FHIR Profiling

_It is recommended that you gain some familiarity with the resources listed in the first section if you are brand new to FHIR._

The following table includes links to various resources for learning more about FHIR profiling, organized by the time investment needed to complete.

| Time Needed   | Description | Reference |
| ------------- | ----------- | --------- |
| A few minutes | [**Video**] Introduction to FHIR profiles (Ewout Kramer) | https://vimeo.com/87074652 |
| A few hours   | [**Webpage**] Firely Profiling Academy - The Profiling Academy is an online training for FHIR profiling. The learning material consists of instructions, real-world examples and exercises. The Profiling Academy training is available for free to all FHIR profilers. Uses SIMPLIFIER.NET tool. | https://simplifier.net/guide/profilingacademy/modules |

The following list includes links to various tools/sites useful for understanding FHIR profiling.

### clinFHIR

An open source tool for Clinicians and Business Analysts who are interested in learning about FHIR, and about FHIR profiling.

https://clinfhir.atlassian.net/wiki/spaces/CLIN/pages/491526/Introduction
and
http://clinfhir.com/

### The Standard Health Record Collaborative

The Standard Health Record (SHR) initiative is working to create a single, high-quality health record for every individual in the United States. SHRs can be used to generate FHIR profiles using https://github.com/standardhealth/shr-cli.

http://standardhealthrecord.org/

### SIMPLIFIER.NET

Simplifier.net is a FHIR collaboration platform for developers, designers, architects and product managers.

https://simplifier.net/

### Forge

Forge is a user-friendly Windows desktop application for authoring FHIR profiles.

https://simplifier.net/forge

### Trifolia

Trifolia is an open source tool for creating FHIR profiles and CDA templates.

https://trifolia.lantanagroup.com/


## FHIR for Developers

_It is recommended that you gain some familiarity with the resources listed in the first two sections if you are brand new to FHIR. You may also want to review the resources listed for FHIR profiling work._

The following table includes links to various resources for learning more about developing software around FHIR, organized by the time investment needed to complete. 

| Time Needed   | Description | Reference |
| -----------   | ----------- | --------- |
| A few hours   | [**Tutorial**] Firely "FHIR starters" - A collection of example projects to help developers get up to speed with HL7 FHIR. Includes tutorials using a web browser, Java, .NET, and iOS. | https://github.com/FirelyTeam/fhirstarters |
| A few weeks   | [**Course**] HL7 FHIR Fundamentals Course | http://www.hl7.org/events/fhir_fun.cfm |
|               | [**Course**] HL7 FHIR Intermediate Series | http://www.hl7.org/events/webinar/fhir/intermediate/ |

The following table includes links to various tools/sites useful for understanding developing software around FHIR.

### SMART on FHIR

SMART on FHIR is a set of open specifications to integrate apps with Electronic Health Records, portals, Health Information Exchanges, and other Health IT systems.

http://docs.smarthealthit.org/

### Official FHIR validator

A Java jar file that can be used to validate resources. See https://www.hl7.org/fhir/validation.html for use.

https://www.hl7.org/fhir/validator.zip

### Implementation Guide Publishing Tool

See: http://wiki.hl7.org/index.php?title=IG_Publisher_Documentation for use.

http://build.fhir.org/org.hl7.fhir.igpublisher.jar

### Ruby FHIR Reference Implementation

FHIR STU3 Resource models generated from FHIR StructureDefinitions.

https://github.com/fhir-crucible/fhir_models

### Java FHIR Reference Implementation: HAPI-FHIR

Object Models, Parsers, Client + Server Framework, FHIR Validator, & Utilities.

http://jamesagnew.github.io/hapi-fhir/

### C# FHIR Reference Implementation: HL7.FHIR

Object models, Parsers/Serialisers, Utilities, and a Client.

http://www.nuget.org/packages/Hl7.Fhir

### Pascal FHIR Reference Implementation: FhirServer

Object models, Parsers/Serialisers, Validator, Utilities, Client, and the FHIR Reference server.

http://github.com/grahamegrieve/fhirserver

### XML FHIR Reference Implementation: XML Tools

Document Rendering Stylesheet, supplementary implementation schemas and transforms.

https://www.hl7.org/fhir/fhir-3.0.1-XMLTools-0.01.zip

### JavaScript FHIR Reference Implementation: FHIR.js

JavaScript Client and Utilities.

https://github.com/FHIR/fhir.js

### Swift FHIR Reference Implementation: Swift-FHIR

Object Model, Client and Utilities.

https://github.com/smart-on-fhir/Swift-FHIR


## Death on FHIR

Some resources/tools/utilities/applications that are being developed to support the Death on FHIR effort. 

### Standard Death Record Implementation Guide

The Standard Death Record (SDR) Implementation Guide (IG) describes how FHIR can be used to exchange death event information between death certifiers, funeral directors and death registration systems.

https://nightingaleproject.github.io/fhir-death-record/guide/index.html and https://simplifier.net/StandardDeathRecord/~introduction

### "SMART on FHIR" Death Certification App

A SMART on FHIR app that gives medical certifiers the ability to report and certify to jurisdiction electronic death registration systems (EDRS) from a hospital setting. It uses SMART on FHIR to pull decedent information from hospital electronic health record (EHR) systems and FHIR profiles for mortality data to submit information to EDRS.

Source code: https://github.com/nightingaleproject/fhir-death-refactor

You can see how the app works by testing it in the SMART on FHIR Sandbox environment, using synthetic patient data. This simulates the experience of a certifier running the app from within an EHR.

1. [Launch the App](https://launch.smarthealthit.org/ehr.html?app=https%3A%2F%2Fnightingaleproject.github.io%2Ffhir-death-refactor%2Flaunch%3Flaunch%3DeyJhIjoiMSIsImYiOiIxIn0%26iss%3Dhttps%253A%252F%252Flaunch.smarthealthit.org%252Fv%252Fr3%252Ffhir&user=)
2. Sign in using the pre-populated provider credentials on the login screen
3. Select a synthetic patient record from the options provided; the app itself will then launch
4. Fill out the death certificate form on each tab of the app; you can select conditions from the patient record to provide cause of death information

### Nightingale

Nightingale is a prototype electronic death registration system (EDRS), built to both demonstrate basic EDRS capabilities and act as a foundation for exploring next generation EDRS concepts. Nightingale supports consuming and producing FHIR Standard Death Records.

https://github.com/nightingaleproject/nightingale

### Canary

Canary is a testing framework for electronic death registration systems (EDRS). Canary can be used to test support for various mortality related data formats, including support for FHIR Standard Death Records.

https://github.com/nightingaleproject/canary

### csharp-fhir-death-record

A .NET based reference implementation library for producing and consuming the preliminary version of the Standard Death Record (SDR) Health Level 7 (HL7) Fast Healthcare Interoperability Resources (FHIR). This library also includes support for converting to and from the Standard Death Record format and the IJE mortality format.

https://github.com/nightingaleproject/csharp-fhir-death-record

### ruby-fhir-death-record

A Ruby Gem that provides a reference implementation module for producing and consuming the preliminary version of the Standard Death Record (SDR) Health Level 7 (HL7) Fast Healthcare Interoperability Resources (FHIR).

https://github.com/nightingaleproject/ruby-fhir-death-record

### Death_Data_Hub

This project is the central repository for standardizing death reporting in collaboration with EDRS systems, medical data providers, and parties interested in data exchange around death records.

https://github.com/gt-health/Death_Data_Hub


## General Links of Interest

The following is a list of interesting articles about Health IT, FHIR, Death on FHIR, and their applications to Mortality Data.

- White House Report on **Strengthening the Medicolegal Death Investigation System: Improving Data Systems** (Note recommendation on interoperability between existing data systems, also note Appendix A which lists 40+ Federal agencies that rely on mortality data to support their missions): https://obamawhitehouse.archives.gov/sites/default/files/microsites/ostp/NSTC/strengthening_the_medicolegal_death_investigation_system_final.pdf
- ASTHO Report on **Improving Drug Specificity and Completeness on Death Certificates** (Note recommendation on interoperability): http://www.astho.org/Rx/Improving-Drug-Spec-and-Comp-on-Death-Certs-for-Overdose-Deaths-Meeting-Report/
- **Observational Health Data Science and Informatics** (OHDSI, pronounced “Odyssey”):
..- Landing Page: https://www.ohdsi.org/
..-	Dr. Duke Explains how it works with an example: [https://www.youtube.com/watch?v=h2twteX6PuQ]
..-	More Youtube Videos about OHDSI and how they do their work to help researchers answer questions by querying data and running analyses across multiple sites: https://www.youtube.com/user/OHDSIJoinTheJourney/videos?disable_polymer=1
- The **American Society of Crime Laboratory Directors (ASCLD)** maintains an **Opioid Resource Center**: https://www.ascld.org/]opioid-resources/ Scroll down to find a link to a full listing of newly identified Novel Psychoactive Substances found in seized drugs (which you may see written on death certificates in your jurisdiction).
- **Trusted Exchange Framework and Common Agreement**: A Common Sense Approach to Achieving Health Information Interoperability (Note emphasis on Open and Accessible APIs.  The open comment period for this draft document closed February 20th): https://www.healthit.gov/buzz-blog/interoperability/trusted-exchange-framework-common-agreement-common-sense-approach-achieving-health-information-interoperability/
