# Placement Officer - User Manual

**Version**: 1.0  
**Last Updated**: 2024-12-19  
**Role**: Placement Officer (Role ID: 36)

---

## Table of Contents

1. [Introduction](#introduction)
2. [Getting Started](#getting-started)
3. [Dashboard Overview](#dashboard-overview)
4. [Corporate Partnership & Employer Management](#corporate-partnership--employer-management)
5. [Internship Program Management](#internship-program-management)
6. [Campus Placement Drive Management](#campus-placement-drive-management)
7. [Job Vacancy & Announcement Management](#job-vacancy--announcement-management)
8. [Student Career Profile & Resume Tracking](#student-career-profile--resume-tracking)
9. [Alumni & Employer Relationship Management](#alumni--employer-relationship-management)
10. [Communication Tools](#communication-tools)
11. [Reports & Analytics](#reports--analytics)
12. [Security & Compliance](#security--compliance)
13. [Troubleshooting](#troubleshooting)
14. [FAQs](#faqs)

---

## Introduction

### Role Overview

The Placement Officer is responsible for managing internships, placements, corporate partnerships, job drives, employer relations, and student career services for the institution. This role provides comprehensive tools for managing the entire placement lifecycle from company partnerships to student placements.

### Key Responsibilities

- **Corporate Partnerships**: Register and manage company partnerships, MoUs, and corporate visits
- **Internship Programs**: Manage internship opportunities, applications, shortlisting, evaluations, and completion
- **Placement Drives**: Organize and manage campus placement drives with eligibility rules and interview processes
- **Job Management**: Post job vacancies, track applications, and manage offers
- **Career Development**: Track student career profiles, resumes, and training sessions
- **Alumni Relations**: Maintain alumni employer records and referral programs
- **Communication**: Send announcements, notifications, and updates to students and companies
- **Reporting**: Generate comprehensive placement and internship reports

### Access Requirements

- **Role**: Placement Officer (Role ID: 36)
- **Permissions**: 400+ specific permissions for placement operations
- **Multi-Tenancy**: Access limited to your assigned school only

---

## Getting Started

### Logging In

1. Navigate to your school's login page: `https://your-domain.com/[school-code]/login`
2. Enter your credentials (username/email and password)
3. After successful authentication, you'll be redirected to the Placement Officer dashboard

### Dashboard Access

The dashboard is accessible at:
```
/[school-code]/dashboard/placement-officer
```

### First-Time Setup

1. **Review Permissions**: Ensure you have all necessary permissions assigned
2. **Familiarize with Navigation**: Explore all available modules and tabs
3. **Set Up Company Database**: Register partner companies and their contacts
4. **Configure Communication Templates**: Create email/SMS templates for common communications
5. **Review Student Data**: Understand the student population and their career profiles

---

## Dashboard Overview

### Main Dashboard

The main dashboard provides a comprehensive overview of all placement operations:

#### Statistics Cards

- **Total Companies**: Number of registered partner companies
- **Active Companies**: Companies with active partnerships
- **Total Internships**: Number of internship opportunities
- **Active Internships**: Currently open internship opportunities
- **Total Placement Drives**: Number of placement drives organized
- **Upcoming Drives**: Placement drives scheduled in the near future
- **Total Job Posts**: Number of job postings
- **Active Job Posts**: Currently open job positions
- **Total Offers**: Number of placement offers made
- **Pending Offers**: Offers awaiting verification
- **Placement Percentage**: Overall placement success rate
- **Total Students**: Students in the placement system
- **Students with Resumes**: Students who have uploaded resumes
- **Total Alumni**: Alumni records in the system
- **Alumni Employed**: Alumni currently employed

#### Navigation Tabs

The dashboard is organized into the following tabs:

1. **Overview**: Dashboard statistics and recent activities
2. **Companies**: Corporate partnership management
3. **Internships**: Internship program management
4. **Placements**: Placement drive management
5. **Jobs**: Job vacancy management
6. **Careers**: Student career profiles and resumes
7. **Alumni**: Alumni employer records
8. **Communications**: Communication templates and sending
9. **Reports**: Analytics and reporting

---

## Corporate Partnership & Employer Management

### Managing Companies

#### Viewing Companies

1. Navigate to the **Companies** tab
2. View the list of all registered companies
3. Use filters to search by:
   - Company name
   - Status (Active, Inactive, Blacklisted)
   - Company type (IT, Manufacturing, Finance, etc.)
   - Partnership type (Regular, Premium, Strategic)

#### Adding a New Company

1. Click the **Add Company** button
2. Fill in the company details:
   - **Company Name** (required)
   - **Company Code** (optional, auto-generated if not provided)
   - **Company Type**: Select from dropdown (IT, Manufacturing, Finance, etc.)
   - **Industry Sector**: Enter the industry sector
   - **Company Size**: Select (Small, Medium, Large, Enterprise)
   - **Contact Information**: Email, phone, website
   - **Address**: Full address details
   - **Partnership Details**: Partnership type, start date, end date
   - **Description**: Additional notes about the company
3. Click **Create Company**

#### Editing a Company

1. Click the **Edit** icon next to a company
2. Update the required fields
3. Click **Update Company**

#### Viewing Company Details

1. Click the **View** icon next to a company
2. View comprehensive company information including:
   - Company overview
   - MoUs & Agreements
   - Corporate Visits
   - Contacts

### Managing MoUs & Agreements

#### Creating an MoU

1. Navigate to a company's detail page
2. Click on the **MoUs & Agreements** tab
3. Click **Add MoU**
4. Fill in the MoU details:
   - **MoU Number** (optional, auto-generated)
   - **Type**: Select (MOU, NDA, Agreement, Contract)
   - **Title** (required)
   - **Description**: Details about the agreement
   - **Start Date** and **End Date**
   - **Signed By**: Company and school signatories
   - **Signed Date**
   - **Notes**: Additional information
5. Click **Create MoU**

#### Uploading MoU Documents

1. Click the **Upload** icon next to an MoU
2. Select the document file (PDF, DOC, DOCX - Max 10MB)
3. Click **Upload Document**

#### Managing MoU Status

- **Draft**: MoU is being prepared
- **Pending**: Awaiting signatures
- **Active**: MoU is in effect
- **Expired**: MoU has expired
- **Terminated**: MoU has been terminated

### Managing Corporate Visits

#### Scheduling a Corporate Visit

1. Navigate to a company's detail page
2. Click on the **Corporate Visits** tab
3. Click **Schedule Visit**
4. Fill in the visit details:
   - **Visit Type**: Campus Visit, Pre-placement Talk, Interview, Meeting
   - **Visit Date** and **Time**
   - **Duration**: In minutes
   - **Venue**: Location of the visit
   - **Purpose**: Reason for the visit
   - **Agenda**: Meeting agenda
   - **Attendees**: Company and school representatives
   - **Status**: Scheduled, Completed, Cancelled, Postponed
5. Click **Schedule Visit**

#### Updating Visit Status

1. Click the **Edit** icon next to a visit
2. Update the status and outcome
3. Add follow-up notes if required
4. Click **Update Visit**

### Managing Employer Contacts

1. Navigate to a company's detail page
2. Click on the **Contacts** tab
3. Click **Add Contact**
4. Fill in contact details:
   - **Name** (required)
   - **Designation**
   - **Department**
   - **Email** and **Phone**
   - **Is Primary**: Mark as primary contact
   - **Is Active**: Contact status
5. Click **Create Contact**

---

## Internship Program Management

### Managing Internship Opportunities

#### Creating an Internship Opportunity

1. Navigate to the **Internships** tab
2. Click **Create Internship**
3. Fill in the opportunity details:
   - **Company**: Select from registered companies
   - **Title** (required)
   - **Description**: Detailed description
   - **Department**: Applicable departments
   - **Duration**: Number of weeks
   - **Start Date** and **End Date**
   - **Stipend Amount**: Compensation offered
   - **Location**: Work location
   - **Work Mode**: Onsite, Remote, Hybrid
   - **Skills Required**: Required skills
   - **Eligibility Criteria**: Qualification requirements
   - **Max Students**: Maximum number of students
   - **Application Deadline**
   - **Status**: Draft, Published, Closed, Cancelled
4. Click **Create Opportunity**

#### Managing Applications

1. Navigate to an internship opportunity
2. View all student applications
3. Track application status:
   - **Submitted**: Application received
   - **Shortlisted**: Student is shortlisted
   - **Selected**: Student is selected
   - **Rejected**: Application rejected
   - **Withdrawn**: Student withdrew

### Managing Shortlists

#### Creating a Shortlist

1. Navigate to an internship opportunity
2. Click **Shortlists** tab
3. Click **Add Students**
4. Select students to shortlist:
   - Search for students by name or code
   - Select multiple students
   - Choose shortlist type (Auto or Manual)
   - Add notes if needed
5. Click **Add to Shortlist**

### Managing Allotment Letters

#### Creating an Allotment Letter

1. Navigate to an internship application
2. Click **Allotment Letters** tab
3. Click **Create Allotment**
4. Fill in allotment details:
   - **Allotment Number** (optional, auto-generated)
   - **Start Date** and **End Date**
   - **Supervisor Name**: Company supervisor
   - **Supervisor Email** and **Phone**
   - **Status**: Issued, Acknowledged, Cancelled
5. Click **Create Allotment**

#### Uploading Allotment Letter Document

1. Click the **Upload** icon next to an allotment
2. Select the document file (PDF, DOC, DOCX - Max 10MB)
3. Click **Upload Document**

### Managing Evaluations

#### Creating an Evaluation

1. Navigate to an internship application
2. Click **Evaluations** tab
3. Click **Add Evaluation**
4. Fill in evaluation details:
   - **Evaluation Type**: Mid-term, Final, Company, Student
   - **Evaluated By**: Name of evaluator
   - **Ratings**: Rate on various criteria (1-5 scale):
     - Technical Skills
     - Communication Skills
     - Teamwork
     - Problem Solving
     - Punctuality
     - Overall Rating
   - **Strengths**: Key strengths
   - **Areas for Improvement**: Areas needing work
   - **Recommendations**: Future recommendations
   - **Evaluation Date**
5. Optionally upload evaluation form document
6. Click **Create Evaluation**

### Managing Completion Certificates

1. Navigate to an internship application
2. Click **Completions** tab
3. Upload completion certificate:
   - Select certificate file
   - Enter completion date
   - Enter grade (A, B, C, D, F, Pass, Fail)
   - Add notes
4. Verify the certificate after upload
5. Click **Upload Certificate**

---

## Campus Placement Drive Management

### Managing Placement Drives

#### Creating a Placement Drive

1. Navigate to the **Placements** tab
2. Click **Create Drive**
3. Fill in drive details:
   - **Company**: Select from registered companies
   - **Drive Code** (optional, auto-generated)
   - **Drive Name** (required)
   - **Description**: Drive details
   - **Drive Date** and **Time**
   - **Venue**: Location of the drive
   - **Registration Period**: Start and end dates
   - **Total Positions**: Number of positions available
   - **Package Details**: Min and max salary, currency
   - **Job Roles**: Available positions
   - **Work Locations**: Job locations
   - **Bond Period**: Bond period in months
   - **Selection Process**: Process description
   - **Status**: Draft, Scheduled, Ongoing, Completed, Cancelled
4. Click **Create Drive**

### Managing Eligibility Rules

#### Creating Eligibility Rules

1. Navigate to a placement drive
2. Click **Eligibility Rules** tab
3. Click **Add Rule**
4. Configure eligibility criteria:
   - **Rule Type**: CGPA, Department, Year, Backlog, Attendance
   - **Rule Name**: Descriptive name
   - **Rule Value**: Value (e.g., "7.5" for CGPA, "CSE,ECE" for departments)
   - **Operator**: >=, <=, =, IN, NOT IN
   - **Is Active**: Enable/disable rule
5. Click **Create Rule**

### Managing Shortlists

#### Creating Drive Shortlists

1. Navigate to a placement drive
2. Click **Shortlists** tab
3. Click **Add Students**
4. Select eligible students:
   - System can auto-shortlist based on eligibility rules
   - Or manually select students
   - Add notes if needed
5. Click **Add to Shortlist**

### Managing Interview Rounds

#### Creating Interview Rounds

1. Navigate to a placement drive
2. Click **Interview Rounds** tab
3. Click **Add Round**
4. Fill in round details:
   - **Round Number**: Sequential number
   - **Round Name** (required)
   - **Round Type**: Written, Technical, HR, Group Discussion, Presentation
   - **Scheduled Date** and **Time**
   - **Duration**: In minutes
   - **Venue**: Location
   - **Status**: Scheduled, Completed, Cancelled
5. Click **Create Round**

### Managing Interview Panels

#### Creating Interview Panels

1. Navigate to an interview round
2. Click **Panels** tab
3. Click **Add Panel**
4. Fill in panel details:
   - **Panel Name**: Name of the panel
   - **Panel Members**: Staff members assigned
   - **Assigned Students**: Students assigned to this panel
5. Click **Create Panel**

### Managing Interview Results

#### Recording Interview Results

1. Navigate to an interview round
2. Click **Results** tab
3. Click **Add Results**
4. Enter results for students:
   - **Student**: Select student
   - **Status**: Pending, Passed, Failed, Absent
   - **Score**: Interview score
   - **Feedback**: Interviewer feedback
   - **Interviewer Name**: Name of interviewer
   - **Interview Date** and **Time**
5. Click **Save Results**

**Bulk Results Entry**: You can upload results for multiple students at once using the bulk upload feature.

### Managing Placement Offers

#### Creating an Offer

1. Navigate to a placement drive
2. Click **Offers** tab
3. Click **Create Offer**
4. Fill in offer details:
   - **Student ID** (required)
   - **Offer Number** (optional, auto-generated)
   - **Package Amount**: Salary offered
   - **Currency**: INR, USD, EUR
   - **Job Role**: Position offered
   - **Work Location**: Job location
   - **Joining Date**: Expected joining date
   - **Acceptance Deadline**: Deadline for acceptance
   - **Bond Period**: Bond period in months
   - **Notes**: Additional information
5. Click **Create Offer**

#### Uploading Offer Letter

1. Click the **Upload** icon next to an offer
2. Select the offer letter file (PDF, JPG, PNG - Max 10MB)
3. Click **Upload Document**

#### Verifying Offer Letter

1. After uploading an offer letter, click the **Verify** icon
2. Review the offer letter details
3. Confirm verification

---

## Job Vacancy & Announcement Management

### Managing Job Posts

#### Creating a Job Post

1. Navigate to the **Jobs** tab
2. Click **Create Job Post**
3. Fill in job details:
   - **Company**: Select from registered companies
   - **Job Code** (optional, auto-generated)
   - **Job Title** (required)
   - **Job Description**: Detailed description
   - **Job Type**: Full-time, Part-time, Contract, Internship
   - **Department**: Applicable department
   - **Required Qualifications**: Education requirements
   - **Required Experience**: Experience requirements
   - **Required Skills**: Skills needed
   - **Location**: Job location
   - **Work Mode**: Onsite, Remote, Hybrid
   - **Package Range**: Min and max salary
   - **Application Deadline**
   - **Max Applications**: Maximum number of applications
   - **Status**: Draft, Published, Closed, Cancelled
4. Click **Create Job Post**

#### Managing Applications

1. Navigate to a job post
2. View all applications received
3. Track application status:
   - **Submitted**: Application received
   - **Shortlisted**: Application shortlisted
   - **Selected**: Candidate selected
   - **Rejected**: Application rejected
   - **Withdrawn**: Application withdrawn

---

## Student Career Profile & Resume Tracking

### Managing Career Profiles

#### Viewing Career Profiles

1. Navigate to the **Careers** tab
2. View list of all student career profiles
3. Filter by:
   - Student name or code
   - CGPA range
   - Skills
   - Active status

#### Creating/Updating Career Profile

1. Navigate to a student's career profile
2. Update profile information:
   - **CGPA**: Current CGPA
   - **Skills**: Comma-separated skills
   - **Certifications**: List of certifications
   - **Projects**: Project details
   - **Achievements**: Achievements and awards
   - **Languages**: Languages with proficiency
   - **Links**: LinkedIn, GitHub, Portfolio URLs
3. Click **Update Profile**

### Managing Resumes

#### Uploading a Resume

1. Navigate to a student's career profile
2. Click **Resumes** tab
3. Click **Upload Resume**
4. Select resume file (PDF, DOC, DOCX - Max 10MB)
5. Enter resume name and type (Latest, Backup, Custom)
6. Click **Upload Resume**

#### Verifying Resumes

1. After a resume is uploaded, review it
2. Click **Verify** to mark as verified
3. Add notes if needed

### Managing Training Sessions

#### Creating a Training Session

1. Navigate to the **Training** section (under Careers)
2. Click **Create Session**
3. Fill in session details:
   - **Session Name** (required)
   - **Session Type**: Aptitude, Soft Skills, Technical, Interview Prep, Resume Writing
   - **Description**: Session details
   - **Trainer Name** and **Email**
   - **Session Date** and **Time**
   - **Duration**: In minutes
   - **Venue**: Location
   - **Max Participants**: Maximum number of students
   - **Status**: Scheduled, Completed, Cancelled
4. Click **Create Session**

#### Managing Attendance

1. Navigate to a training session
2. Click **Attendance** tab
3. Click **Mark Attendance**
4. Select students and mark status:
   - **Present**: Student attended
   - **Absent**: Student did not attend
   - **Late**: Student arrived late
5. Add notes if needed
6. Click **Mark Attendance**

**Bulk Attendance**: You can mark attendance for multiple students at once.

---

## Alumni & Employer Relationship Management

### Managing Alumni Employer Records

#### Adding Alumni Employer Record

1. Navigate to the **Alumni** tab
2. Click **Add Alumni Record**
3. Fill in alumni details:
   - **Student**: Select alumni student
   - **Company**: Select from registered companies (optional)
   - **Employer Name**: Current employer
   - **Job Title**: Current position
   - **Department**: Department
   - **Employment Type**: Full-time, Part-time, Contract, Freelance
   - **Start Date** and **End Date**
   - **Is Current**: Mark if current employment
   - **Salary**: Salary amount and currency
   - **Work Location**: Job location
   - **Contact Information**: Email and phone
   - **Notes**: Additional information
4. Click **Create Record**

### Managing Alumni Referrals

#### Creating a Referral

1. Navigate to the **Alumni** tab
2. Click **Referrals** sub-tab
3. Click **Add Referral**
4. Fill in referral details:
   - **Alumni**: Select referring alumni
   - **Referred Student**: Select student being referred
   - **Company**: Select company
   - **Job Post**: Select job post (optional)
   - **Referral Date**
   - **Referral Status**: Pending, Accepted, Rejected, Hired
   - **Referral Notes**: Additional information
5. Click **Create Referral**

---

## Communication Tools

### Managing Communication Templates

#### Creating a Template

1. Navigate to the **Communications** tab
2. Click **Templates** sub-tab
3. Click **Create Template**
4. Fill in template details:
   - **Template Name** (required)
   - **Template Type**: Email, SMS, Announcement
   - **Category**: Internship, Placement, Job, Shortlist, Interview, Offer, Resume, MoU
   - **Subject**: Email subject (for emails)
   - **Body**: Message body with variables (e.g., {{student_name}}, {{company_name}})
   - **Variables**: List of available variables
   - **Is Active**: Enable/disable template
5. Click **Create Template**

#### Using Templates

Templates support variables that are replaced when sending:
- `{{student_name}}`: Student's full name
- `{{student_code}}`: Student code
- `{{company_name}}`: Company name
- `{{internship_title}}`: Internship opportunity title
- `{{drive_name}}`: Placement drive name
- `{{offer_package}}`: Offer package amount
- And more...

### Sending Communications

#### Sending a Communication

1. Navigate to the **Communications** tab
2. Click **Send** sub-tab
3. Click **Send Communication**
4. Fill in communication details:
   - **Use Template** (optional): Select a template to use
   - **Communication Type**: Email, SMS, Announcement, Notification
   - **Recipient Type**: Student, Company, Staff, Bulk
   - **Recipients**: 
     - For single: Enter recipient ID or email/phone
     - For bulk: Select criteria (e.g., all shortlisted students)
   - **Subject**: Email subject (for emails)
   - **Message Body**: Your message (template variables will be replaced)
5. Click **Send**

#### Viewing Communication Logs

1. Navigate to the **Communications** tab
2. Click **Logs** sub-tab
3. View all sent communications with:
   - Communication type
   - Recipient information
   - Status (Pending, Sent, Delivered, Failed)
   - Sent and delivered timestamps

---

## Reports & Analytics

### Accessing Reports

1. Navigate to the **Reports** tab
2. View comprehensive analytics including:

#### Placement Statistics
- Placement percentage by program
- Placement trends over time
- Company-wise placement statistics
- Department-wise placement statistics

#### Internship Statistics
- Internship completion rates
- Company-wise internship statistics
- Student participation rates
- Evaluation scores and feedback

#### Company Engagement Metrics
- Active partnerships
- MoU status
- Corporate visit frequency
- Offer generation by company

#### Student Statistics
- Shortlist statistics
- Application success rates
- Resume upload rates
- Training attendance rates

#### Offer Statistics
- Offer package distribution
- Acceptance rates
- Offer verification status

#### Drive Statistics
- Drive success rates
- Interview round statistics
- Selection rates

#### Alumni Statistics
- Alumni employment sectors
- Alumni referral success rates
- Alumni career trajectories

### Exporting Reports

1. Navigate to the desired report
2. Click **Export** button
3. Choose export format (PDF, Excel, CSV)
4. Download the report

---

## Security & Compliance

### Access Control

- **Multi-Tenancy**: All data is automatically filtered by your school
- **RBAC**: Role-based access control ensures you only see and manage data you're authorized for
- **No Cross-Tenant Access**: You cannot access data from other schools
- **Restricted Access**: You cannot access:
  - Academic configurations
  - Exam processing
  - Payroll and invoicing
  - HR confidential data
  - Fee transactions

### Data Privacy

- **Document Security**: All documents (resumes, offer letters, MoUs) are stored securely
- **Permission Protection**: Private documents require proper permissions to access
- **Audit Logging**: All actions are logged for audit purposes

### Best Practices

1. **Regular Backups**: Ensure important documents are backed up
2. **Data Validation**: Always verify data before submitting
3. **Document Verification**: Verify all uploaded documents
4. **Communication**: Use templates for consistent communication
5. **Status Updates**: Keep statuses updated for accurate reporting

---

## Troubleshooting

### Common Issues

#### Cannot Access Dashboard

**Problem**: Getting "Unauthorized" or "Insufficient permissions" error

**Solution**:
1. Verify your role is correctly assigned
2. Check with system administrator for permission assignment
3. Ensure you're logged in with the correct account

#### File Upload Fails

**Problem**: File upload shows error

**Solution**:
1. Check file size (must be less than 10MB)
2. Verify file format (PDF, DOC, DOCX, JPG, PNG)
3. Check internet connection
4. Try uploading again

#### Data Not Appearing

**Problem**: Expected data not showing in lists

**Solution**:
1. Check filters - they might be hiding data
2. Verify search terms
3. Check if data belongs to your school
4. Refresh the page

#### Communication Not Sending

**Problem**: Communication shows as "Failed"

**Solution**:
1. Verify recipient email/phone is correct
2. Check communication service configuration
3. Review communication logs for error details
4. Try sending again

### Getting Help

1. **Documentation**: Refer to this user manual
2. **System Administrator**: Contact your system administrator
3. **Support**: Reach out to technical support team

---

## FAQs

### General Questions

**Q: Can I access data from other schools?**  
A: No, the system enforces multi-tenancy. You can only access data from your assigned school.

**Q: How do I reset a password?**  
A: Contact your system administrator to reset your password.

**Q: Can I export data?**  
A: Yes, most reports and lists support export functionality (PDF, Excel, CSV).

### Company Management

**Q: How do I add multiple contacts for a company?**  
A: Navigate to the company detail page, go to the Contacts tab, and add each contact separately.

**Q: Can I upload multiple MoU documents?**  
A: Each MoU record can have one document. Create separate MoU records for different documents.

### Internship Management

**Q: How do I shortlist students automatically?**  
A: Use the auto-shortlist feature which applies eligibility criteria automatically. You can also manually shortlist students.

**Q: Can I track multiple evaluations for the same internship?**  
A: Yes, you can create multiple evaluations (mid-term, final, company, student) for the same internship application.

### Placement Drives

**Q: How do I create eligibility rules?**  
A: Navigate to a placement drive, go to Eligibility Rules tab, and create rules based on CGPA, department, year, etc.

**Q: Can I schedule multiple interview rounds?**  
A: Yes, you can create multiple interview rounds with different types (written, technical, HR, etc.).

### Communication

**Q: Can I send bulk communications?**  
A: Yes, select "Bulk" as recipient type and specify criteria (e.g., all shortlisted students for a drive).

**Q: How do I use template variables?**  
A: Use double curly braces in your message body, e.g., `{{student_name}}` will be replaced with the actual student name.

### Reports

**Q: How often are reports updated?**  
A: Reports are generated in real-time based on current data.

**Q: Can I schedule automatic reports?**  
A: Currently, reports are generated on-demand. Contact your administrator for scheduled reports.

---

## Appendix

### Keyboard Shortcuts

- **Ctrl/Cmd + K**: Quick search
- **Esc**: Close dialogs
- **Tab**: Navigate between fields

### Supported File Formats

- **Documents**: PDF, DOC, DOCX
- **Images**: JPG, JPEG, PNG
- **Max File Size**: 10MB per file

### Status Definitions

#### Company Status
- **Active**: Company has active partnership
- **Inactive**: Partnership is inactive
- **Blacklisted**: Company is blacklisted

#### MoU Status
- **Draft**: Being prepared
- **Pending**: Awaiting signatures
- **Active**: In effect
- **Expired**: Has expired
- **Terminated**: Terminated

#### Application Status
- **Submitted**: Application received
- **Shortlisted**: Student shortlisted
- **Selected**: Student selected
- **Rejected**: Application rejected
- **Withdrawn**: Student withdrew

#### Offer Status
- **Pending**: Offer pending acceptance
- **Accepted**: Offer accepted
- **Rejected**: Offer rejected
- **Withdrawn**: Offer withdrawn

---

**Last Updated**: 2024-12-19  
**Version**: 1.0  
**For Support**: Contact your system administrator

