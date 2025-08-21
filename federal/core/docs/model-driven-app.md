# Overview

This page describes the model-driven app functionality in the Core module.

## Table of Contents
- [Overview](#overview)
- [Walkthrough](#walkthrough)
- [People](#people)
  - [Personnel Types](#personnel-types)
  - [Organization Units](#organization-units)
  - [Organization Unit Types](#organization-unit-types)
  - [Organization Initiatives](#organization-initiatives)
  - [Clearance Levels](#clearance-levels)
  - [Grade Ranks](#grade-ranks)
  - [Pay Grades](#pay-grades)
  - [Job Series](#job-series)
- [Places](#places)
  - [Countries](#countries)
  - [States or Provinces](#states-or-provinces)
  - [Locations](#locations)
  - [Fiscal Periods](#fiscal-periods)
  - [Products](#products)
  - [Privacy Consents](#privacy-consents)
- [Legal and Compliance](#legal-and-compliance)
  - [Legal Authorities](#legal-authorities)
  - [Analyses](#analyses)
  - [Impacts](#impacts)
  - [Risk Items](#risk-items)
  - [Compliance Frameworks](#compliance-frameworks)
  - [Compliance Framework Categories](#compliance-framework-categories)
  - [Compliance Requirements](#compliance-requirements)
- [Summary](#summary)
- [Sample data](#sample-data)

# Walkthrough
---

In this walkthrough, we'll review the features and functionality available in the Microsoft Federal Core Utility App. 

This app is part of the Microsoft Federal Application Starter Templates, an open-source library specifically designed to help you accelerate your mission modernization, using Microsoft's low code platform, Power Apps.

## Purpose

The Core Utility App provides a user interface for you and your organization to manage common records, reference data, and other lookup information used across the enterprise. It is based on the Government Common Data Model Core solution, allowing you to add and manage reference information common to multiple apps.

This app is intended to be used alongside other modules, to help you centralize and manage multiple common data sets in a single place.

## Navigation

Within the app, you'll see a number of sections available within the main navigation. These sections are People, Places, Things, and Legal and Compliance. Clicking into these sections will allow you to view dashboards, manage records, and more. Let's review these together in more detail.

![alt text](media/navigation.png)

# People

First up is the People section. Navigating into each area withing the People section will display a list of records for that area. Sample data displayed in each of these areas is available for you to download for test environments.

The Persons area allows you to manage individuals within and external to your organization, for various processes. 

## Personnel Types

Personnel Types categorize individuals based on their employment or affiliation with a federal agency, such as federal employees, contractors, or military personnel. This classification supports access management, benefits eligibility, and organizational reporting.

![alt text](media/personnel-types.png)

## Organization Units

Use Organization Units to represent the various departments, divisions, offices, and other structure of your organization. You can model a hierarchy of organization units, by using the Parent Organization field.

![alt text](media/organization-units.png)

## Organization Unit Types

Organization Unit Types allow you to specify the various types of organization units at your agency.

![alt text](media/organization-unit-types.png)

## Organization Initiatives

Use Organization Initiatives to track key agency efforts, programs, or strategic priorities. This reference supports alignment of personnel, resources, and activities to mission-driven initiatives across the organization.

![alt text](media/organization-initiatives.png)

## Clearance Levels

Clearance Levels define the degree of access an individual is authorized to have to classified or sensitive information within a federal organization.

![alt text](media/clearance-levels.png)

## Grade Ranks

Grade-Ranks represent the official classification of federal personnel by grade level or military rank. They are used to determine position authority, responsibilities, and pay scale within federal agencies and the armed forces.

![alt text](media/grade-ranks.png)

## Pay Grades

Pay Grades classify federal and military positions by standardized pay scales, determining compensation levels across different roles, agencies, and services. They support budgeting, HR management, and parity across personnel systems.

![alt text](media/pay-grades.png)

## Job Series

Job Series are four-digit codes used by the U.S. Office of Personnel Management (OPM) to classify federal positions by occupational family and specialized function. They help define job duties, qualification standards, and career paths across agencies.

![alt text](media/job-series.png)

# Places

In the Places section, you'll find Countries, States or Provinces, and Locations. These areas provide standardized references for physical and geopolitical places. These are essential for identifying addresses, determining jurisdictional boundaries, managing assignments or facilities, and supporting reporting and compliance across agencies.

## Countries

![alt text](media/countries.png)

## States or Provinces

![alt text](media/states.png)

## Locations

![alt text](media/locations.png)

## Fiscal Periods

Use Fiscal Periods to define standardized time intervals—such as fiscal years, quarters, and months—for budgeting, financial reporting, performance tracking, and project planning in federal programs. They enable consistent time-based analysis and alignment with government financial cycles.

![alt text](media/fiscal-periods.png)

## Products

Use Products to represent goods, systems, or service offerings managed, procured, or delivered by an agency. Products support inventory tracking, service catalogs, procurement workflows, lifecycle management, and alignment with contracts or vendors.

![alt text](media/products.png)

## Privacy Consents

Use Privacy Consents to capture and manage an individual’s agreement to data collection, sharing, or usage in compliance with federal privacy policies, such as the Privacy Act or GDPR. They support auditability, transparency, and enforcement of consent-based data practices.

![alt text](media/privacy-consents.png)

# Legal and Compliance

## Legal Authorities

Within Legal and Compliance, use Legal Authorities to reference statutes, regulations, executive orders, and other legal mandates that serve as the basis for federal policies, programs, and directives. They provide traceability, justification, and compliance context for agency actions and decisions.

![alt text](media/legal-authorities.png)

## Analyses

Use Analyses to document structured evaluations, assessments, or studies conducted to inform decision-making, measure performance, assess risk, or evaluate program effectiveness. They support evidence-based policy, reporting, and strategic planning.

![alt text](media/analyses.png)

Use Impacts and Risk Items to capture the potential effects and uncertainties identified during an Analysis. You can use them standalone or group them under Analyses to support comprehensive evaluation, prioritization, and mitigation planning based on evidence and strategic context.

## Impacts

Impacts represent positive or negative outcomes—such as cost savings, mission disruption, or stakeholder benefit—associated with a proposed action or event.

![alt text](media/impacts.png)

## Risk Items

Risk Items represent specific threats or uncertainties that could affect objectives, timelines, compliance, or resource availability.

![alt text](media/risk-items.png)

## Compliance Frameworks

Use Compliance Frameworks to represent structured sets of federal standards, controls, or guidelines—such as FedRAMP, NIST SP 800-53, or FISMA—that govern security, privacy, and operational practices. They provide the foundation for managing agency compliance obligations.

![alt text](media/compliance-frameworks.pngpng)

## Compliance Framework Categories

Use Compliance Framework Categories to organize controls or requirements within a framework into thematic areas—such as Access Control, Incident Response, or Data Integrity—to support structured implementation and reporting.

![alt text](media/compliance-framework-categories.png)

## Compliance Requirements

And finally, use Compliance Requirements to define specific controls, rules, or obligations mandated by a Compliance Framework. Track their applicability, status, and evidence to support audits, assessments, and continuous monitoring.

![alt text](media/compliance-requirements.png)

# Summary

In summary, the Core Utility app is a centralized administrative tool that allows designated users to manage foundational reference and lookup data critical to enterprise operations. Organized into four intuitive groups—People, Places, Things, and Legal & Compliance—the app ensures consistent, reusable data across all modules. From clearance levels and job series to physical locations, products, and compliance frameworks, this utility supports clean data, simplifies configuration, and strengthens system-wide integrity.

# Sample data

All data is fictitious and can be imported using the Sample-Data/Core data provided in the Gov CDM repo.



