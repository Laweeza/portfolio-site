---
title: 'Patient Questionnaire Web Application'
description: 'MVP for a patient questionnaire web app'
date: 'Mar 18 2024'
demoURL: 'https://patient-questionnaire.vercel.app'
repoURL: 'https://github.com/Laweeza/PatientQuestionnaire'
images: '/assets/screenshots/TeachBack.png'
---

## Project Overview

A modern, user-friendly web application designed to streamline the patient appointment process. The application provides a comprehensive, dynamic form that adapts to different patient types, ensuring a smooth and personalized registration experience.

## Screenshots
![TeachBack Application Screenshot](/assets/screenshots/TeachBack.png)

## Key Features

- **Adaptive Patient Registration**: Distinguishes between new and returning patients
- **Dynamic Form Flow**: Adjusts form fields and options based on patient type
- **Comprehensive Patient Information Capture**:
  - Patient name
  - Appointment date
  - Assigned doctor
  - Patient type (new or returning)
  - Specific appointment type selection

## Technical Architecture

- **Frontend**: Svelte.js
- **Backend**: Firebase Firestore
- **State Management**: Custom form store
- **Responsive Design**: Tailored for various device sizes

## Form Workflow

1. Patient selects their patient type (New or Returning)
2. Based on patient type, relevant appointment types are dynamically loaded
3. Patient fills out personal and appointment details
4. Form validates and progresses to next stage upon complete information

## Technologies Used

- Svelte
- TypeScript
- Firebase Firestore
- Custom form state management

