# pp-eleave
Microsoft Power Platform leave management solution, designed for South African public sector organisations.

## Background
This is provided as a solution accelerator. It's a sample solution which is not supported by Microsoft or myself. Use as a starter to help you get going quickly with a leave management solution. It's original source comes from the leave application template which is available in the Power Apps maker portal. However, it has been customised extensively from that code base. This solution uses the Dataverse for storage, and has both a Model Driven application (for HR admin tasks) and a Canvas application (for user and manager tasks). 

It is designed based on public sector department requirements in South Africa. That is, it is not the master of the leave balances. Leave balances are "mastered" in a system called Persal. Therefore, this solution relies on a "feed" from Persal to update leave balances for employees.

## Features
Here is a list of core features of the solution

- Employees create, submit, recall, review leave requests from a full responsive Canvas Power App.
- Managers review, approve/decline with comments, their employees leave requests from the Canvas Power App.
- HR staff review, approve/decline with comments, leave requests. They then capture approved leave requests into Persal. All done via Model Driven Powwer App.
- HR / admin staff, setup core data for the solution, such as defining different leave types, holidays and other settings in the Model Driven Power App.
- Notifications of approval actions and leave request status updates are sent to relevant parties via Power Automate Flow
- Approved leave requests are optionally sent as meeting requests to employees, so they don't miss the leave that has been approved
- Several dashboards added to the Model Driven app for HR users to do basic leave analytics
- Full audit trail on all leave request actions (submitted, approved, declined, recalled etc)
- 3 custom roles defined for each persona

## How it works
There are 2 main applications which makeup this solution. 1 - Admin Model Driven App (Leave Manager) 2 - Employee / Manager Leave App. All data resides in the Microsoft Dataverse. This includes leave requests, leave types, holidays and more.

More information on how the solution works, including demo is in the attached Solution Demo PPT. Installation instructions in the instructions PPT.

## Provided "As-Is"
This is a a starter / sample. It hasn't been well tested, and is missing some key features that I hope to add over time. It not officialy supported by myself or Microsoft. However, because the unmanaged and managed solution is provided, you should be able to support it yourself, either directly or through a certified Microsoft partner.
