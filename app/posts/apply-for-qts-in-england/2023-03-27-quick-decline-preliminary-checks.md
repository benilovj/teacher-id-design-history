---
title: Quick decline and preliminary checks
date: 2023-03-27
screenshots:
items:

- text: "Preliminary check task item"
- src: preliminary-check-task.png
- text: "Preliminary check task completed"
- src: preliminary-check-task-completed.png
- text: "Preliminary check page content"
- src: preliminary-check-content.png
---

### Background

Since announcing that the Apply for qualified teacher status (QTS) in England service will be available to teachers from newly added countries, there has been a large increase in the number of people using the eligibility checker to find out whether they’re eligible to apply for QTS.

We felt it was important to design an approach that would help assessors to efficiently deal with such a large influx of applications, especially since applicants from some countries must pay (often a sizeable sum) to request their letter of professional standing (LOPs) to use as evidence in their QTS application.

We discovered that many applicants were requesting their LOPs before completing their application, despite being ineligible for QTS on other grounds, meaning costs incurred for an application that cannot progress. We felt a responsibility to help prevent applicants from spending money on a letter of professional standing unnecessarily.


### User needs we’ve tried to meet

#### Applicant
As an applicant, I need to know if I should request my LOPs, as I do not want to spend money on proof of my professional standing if I’m not eligible for QTS.

#### Assessor

As an assessor, I need to be able to complete a quick check of applications from certain countries or states so that I can determine whether they’re suitable to move into a full assessment.


#### Teacher Regulation Agency (TRA) senior leader

As a TRA senior leader, I need to be able to determine if applications from specific states or countries require a preliminary check before being moved to full ‘initial assessment’ so that assessor time is not wasted fully assessing applications from states/countries where we have high volumes of ineligible applications.


### What we’ve done

We’ve created a way to triage applications so that we can quickly identify and decline those that are ineligible, but also identify applications that have potential to be successful and progress them to a full assessment.

Assessors are now able to make ‘preliminary checks’ on applications from countries that have previously submitted large numbers of ineligible applications. This approach will allow us to make more efficient use of assessors’ time, as it strips away the need for assessors to review entire applications before declining them.

For ineligible applicants, assessors can decline applications quickly so that the applicant does not unnecessarily spend money requesting their LOPs document. Staff with administrator-level permissions can now switch on the ‘requires preliminary checks’ feature for countries or states by using the support console. Once switched on, a ‘Pre-assessment tasks’ section is added to all applications from that given country/state.

#### How it works

Once an application is submitted, a note is added to the case history saying, “Application requires a preliminary check before it can progress to full initial assessment.” If the country's teaching registration authority will only provide a letter of professional standing (LOPs) directly to the Teaching Regulation Agency (TRA), the ‘Awaiting third party professional standing’ spoke will be marked as ‘CANNOT START’.

On the ‘Preliminary checks’ page, if an assessor answers “Yes” to the question “Do you want to move this application to full assessment?” the spoke status will change to ‘COMPLETED’. If there are no other pre-assessment tasks, the application status changes from ‘PRELIMINARY CHECK’ to ‘NOT STARTED’. A case history note will then be applied, which states “Preliminary checks completed. Application can progress to initial assessment”.

If a LOPs has not been submitted to support the application, the ‘Awaiting third-party professional standing’ status changes to ‘WAITING ON’. For this, the case history note applied will be ‘Preliminary checks completed’. Once the LOPs is added, the application status changes to ‘NOT STARTED’.

When an application that’s still awaiting a letter of professional standing has its status changed to ‘WAITING ON’, the case history note will be “Once we’ve received written evidence of professional standing from the applicant’s teaching authority, we’ll add the application to the queue to be assigned to an assessor.”

If the assessor answers “No, I’ll decline it in the appropriate section” to the question “Do you want to move this application to full assessment?” on the ‘Preliminary checks’ page, then the preliminary check spoke will be changed to ‘COMPLETED’.

For countries awaiting a letter of professional standing, when the application status changes to ‘WAITING ON’, an email is sent to the applicant notifying them that they can request their letter (in cases where no triage is required, this would be as soon as their application is received).

### Screenshots

![Preliminary check task item](preliminary-check-task.png)

![Preliminary check task completed](preliminary-check-task-completed.png)

![Preliminary check page content](preliminary-check-content.png)
