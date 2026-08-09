# Patient Registration and Scheduling

## Overview

This phase of the Practice Fusion implementation demonstrates the administrative workflow used to establish a patient record and prepare the patient for a clinical visit.

The workflow begins with patient registration, progresses to appointment scheduling, and concludes with the patient being moved into the arrival workflow for the scheduled visit.

---

## 1. Patient Registration

A fictional patient record was created within Practice Fusion for workflow demonstration purposes.

The patient profile was configured with core demographic and administrative information required to establish a usable electronic health record.

The completed patient chart provides a centralized location for managing:

- Demographics
- Contact information
- Allergies
- Medications
- Diagnoses
- Health concerns
- Goals
- Encounters
- Appointments

### Patient Chart

![Patient Chart Summary](https://raw.githubusercontent.com/cbmaduka/practice-fusion-primary-care-implementation/main/screenshots/01-patient-chart-summary.png)

*Figure 1. Patient chart created in Practice Fusion showing the centralized clinical record used for ongoing patient management.*

The patient chart serves as the foundation for the remaining clinical and administrative workflow.

---

## 2. Appointment Scheduling

Following patient registration, a new patient appointment was created through the Practice Fusion scheduling module.

The appointment was configured as a **New Patient Visit** for an annual physical examination and preventive care.

The scheduling workflow included:

- Patient selection
- Provider assignment
- Facility assignment
- Chief complaint
- Appointment type
- Visit duration
- Coverage type
- Appointment status

### Scheduled New Patient Visit

![New Patient Appointment Scheduled](https://raw.githubusercontent.com/cbmaduka/practice-fusion-primary-care-implementation/main/screenshots/02-new-patient-appointment-scheduled.png)

*Figure 2. New Patient Visit scheduled in Practice Fusion, connecting the patient record with the upcoming clinical encounter.*

---

## 3. Patient Arrival Workflow

At the time of the visit, the appointment status was updated from **Pending arrival** to **In lobby**.

This represents the patient check-in stage and provides the transition between front-office scheduling activities and the clinical encounter.

Once the patient was placed in the arrival workflow, the scheduled appointment was used to initiate the patient's Office Visit encounter.

---

## Workflow Result

This phase established the following workflow:

**Patient Registration → Patient Chart → Appointment Scheduling → Patient Check-In → Clinical Encounter**

The completed process demonstrates how Practice Fusion connects patient demographic information, scheduling, and visit management within the EHR.

---

## Skills Demonstrated

- Patient Registration
- Patient Chart Management
- Demographic Data Entry
- Practice Fusion Scheduling
- Appointment Management
- New Patient Workflow
- Patient Check-In
- Healthcare Administration
- EHR Workflow Management

---

## Portfolio Note

All patient information displayed in this project is fictional and was created solely for portfolio demonstration and training purposes.
