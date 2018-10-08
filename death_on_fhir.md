# Death on FHIR

Some resources/tools/utilities/applications that are being developed to support the Death on FHIR effort. 

## Standard Death Record Implementation Guide

The Standard Death Record (SDR) Implementation Guide (IG) describes how FHIR can be used to exchange death event information between death certifiers, funeral directors and death registration systems.

https://nightingaleproject.github.io/fhir-death-record/guide/index.html and https://simplifier.net/StandardDeathRecord/~introduction

## "SMART on FHIR" Death Certification App

A SMART on FHIR app that gives medical certifiers the ability to report and certify to jurisdiction electronic death registration systems (EDRS) from a hospital setting. It uses SMART on FHIR to pull decedent information from hospital electronic health record (EHR) systems and FHIR profiles for mortality data to submit information to EDRS.

Source code: https://github.com/nightingaleproject/fhir-death-refactor

You can see how the app works by testing it in the SMART on FHIR Sandbox environment, using synthetic patient data. This simulates the experience of a certifier running the app from within an EHR.

1. [Launch the App](https://launch.smarthealthit.org/ehr.html?app=https%3A%2F%2Fnightingaleproject.github.io%2Ffhir-death-refactor%2Flaunch%3Flaunch%3DeyJhIjoiMSIsImYiOiIxIn0%26iss%3Dhttps%253A%252F%252Flaunch.smarthealthit.org%252Fv%252Fr3%252Ffhir&user=)
2. Sign in using the pre-populated provider credentials on the login screen
3. Select a synthetic patient record from the options provided; the app itself will then launch
4. Fill out the death certificate form on each tab of the app; you can select conditions from the patient record to provide cause of death information

## csharp-fhir-death-record

A .NET based reference implementation library for producing and consuming the preliminary version of the Standard Death Record (SDR) Health Level 7 (HL7) Fast Healthcare Interoperability Resources (FHIR). This library also includes support for converting to and from the Standard Death Record format and the IJE mortality format.

https://github.com/nightingaleproject/csharp-fhir-death-record

## Nightingale

Nightingale is a prototype electronic death registration system (EDRS), built to both demonstrate basic EDRS capabilities and act as a foundation for exploring next generation EDRS concepts. Nightingale supports consuming and producing FHIR Standard Death Records.

https://github.com/nightingaleproject/nightingale

## Canary

Canary is a testing framework for electronic death registration systems (EDRS). Canary can be used to test support for various mortality related data formats, including support for FHIR Standard Death Records.

https://github.com/nightingaleproject/canary

## ruby-fhir-death-record

A Ruby Gem that provides a reference implementation module for producing and consuming the preliminary version of the Standard Death Record (SDR) Health Level 7 (HL7) Fast Healthcare Interoperability Resources (FHIR).

https://github.com/nightingaleproject/ruby-fhir-death-record

## Death_Data_Hub

This project is the central repository for standardizing death reporting in collaboration with EDRS systems, medical data providers, and parties interested in data exchange around death records.

https://github.com/gt-health/Death_Data_Hub
