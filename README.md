# Salesforce Placement Assistant (Agentforce)

## Project Overview
Salesforce Placement Assistant is an AI-powered placement eligibility assistant built using Salesforce Agentforce and Salesforce Flow.

It helps students check their eligibility for job openings based on their CGPA, academic branch, job status, and application deadline.

## Key Features
- AI-powered conversational eligibility checking using Agentforce.
- Automated eligibility evaluation using Salesforce Flow.
- CGPA and branch-based eligibility validation.
- Job status and application deadline verification.
- Invalid and nonexistent Job Opening ID handling.
- Multiple job opening records for testing.
- Read-only eligibility checks.

## Technology Stack
- Salesforce Agentforce
- Salesforce Flow (Autolaunched Flow)
- Salesforce Custom Objects
- Permission Sets
- Salesforce Developer Edition

## Eligibility Conditions
A student is eligible when:
1. Their CGPA meets the minimum requirement.
2. Their branch is included in the eligible branches.
3. The job opening status is Open.
4. The application deadline has not passed.

## Testing
The assistant was tested with:
- Eligible student.
- Low CGPA.
- Branch mismatch.
- Closed job opening.
- Expired application deadline.
- Invalid Job Opening ID.
- Nonexistent Job Opening ID.
- Multiple job openings.

## Project Architecture
Student Input → Agentforce → Flow Action → Eligibility Check → Result and Explanation

## Future Enhancements
- Integration with the Student Placement Tracker org.
- Student application tracking.
- Placement officer dashboard integration.
