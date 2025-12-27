# Internship Coordinator - User Manual

**Version**: 1.0  
**Last Updated**: 2024  
**Role**: Internship Coordinator (Role ID: 37)

---

## Table of Contents

1. [Introduction](#introduction)
2. [Getting Started](#getting-started)
3. [Dashboard Overview](#dashboard-overview)
4. [Employer & Partnership Management](#employer--partnership-management)
5. [Internship Opportunity Management](#internship-opportunity-management)
6. [Student Application Workflow](#student-application-workflow)
7. [Approval & Allotment Workflow](#approval--allotment-workflow)
8. [Attendance & Weekly Reporting](#attendance--weekly-reporting)
9. [Evaluation & Completion](#evaluation--completion)
10. [Student Career Profiles](#student-career-profiles)
11. [Communications Module](#communications-module)
12. [Reports & Analytics](#reports--analytics)
13. [Document Management](#document-management)
14. [Settings & Configuration](#settings--configuration)
15. [Security & Compliance](#security--compliance)
16. [Troubleshooting](#troubleshooting)
17. [FAQs](#faqs)

---

## Introduction

### Role Overview

The Internship Coordinator is responsible for managing the end-to-end lifecycle of student internships, including employer partnerships, opportunity management, application processing, approvals, attendance tracking, evaluations, and completion certificates. This role ensures seamless coordination between students, employers, and the institution.

### Key Responsibilities

- **Employer Partnerships**: Manage internship companies, HR contacts, MoUs, and employer visits
- **Opportunity Management**: Create, publish, and manage internship opportunities
- **Application Processing**: Review, validate, and shortlist student applications
- **Approvals & Allotments**: Approve applications and manage allotment letters
- **Attendance Tracking**: Monitor student attendance and weekly reports
- **Evaluations**: Manage mentor feedback and student evaluations
- **Certificates**: Generate and manage completion certificates
- **Communications**: Send announcements, reminders, and notifications
- **Reporting**: Generate comprehensive internship reports and analytics

### Access Requirements

- **Role**: Internship Coordinator (Role ID: 37)
- **Permissions**: 245+ specific permissions for internship operations
- **Multi-Tenancy**: Access limited to your assigned school only
- **Restrictions**: No access to grades/exams, fees/payroll, or academic configuration

---

## Getting Started

### Logging In

1. Navigate to your school's login page: `https://your-domain.com/[school-code]/login`
2. Enter your credentials (username/email and password)
3. After successful authentication, you'll be redirected to the Internship Coordinator dashboard

### Dashboard Access

The dashboard is accessible at:
```
/[school-code]/dashboard/internship-coordinator
```

### First-Time Setup

1. **Review Permissions**: Ensure you have all necessary permissions assigned
2. **Familiarize with Navigation**: Explore all available modules and tabs
3. **Set Up Company Profiles**: Add internship partner companies
4. **Configure Communication Templates**: Set up email/SMS templates for common communications
5. **Review Student Data**: Understand the student population eligible for internships

---

## Dashboard Overview

### Main Dashboard

The main dashboard provides a comprehensive overview of all internship operations:

#### Statistics Cards

- **Total Companies**: Number of partner companies
- **Active Companies**: Companies with active partnerships
- **Total Opportunities**: All internship opportunities created
- **Active Opportunities**: Currently published opportunities
- **Total Applications**: All student applications received
- **Pending Applications**: Applications awaiting review
- **Approved Applications**: Applications that have been approved
- **Active Internships**: Currently ongoing internships
- **Completed Internships**: Successfully completed internships
- **Participation Rate**: Percentage of students with internships
- **Completion Rate**: Percentage of internships completed successfully
- **Pending Weekly Reports**: Weekly reports awaiting review
- **Pending Evaluations**: Evaluations awaiting completion

#### Navigation Tabs

The dashboard includes 12 main navigation tabs:

1. **Overview** - Dashboard statistics and recent activities
2. **Partners** - Company and partnership management
3. **Opportunities** - Internship opportunity management
4. **Applications** - Student application processing
5. **Shortlisting** - Shortlisted students management
6. **Allotments** - Allotment letters and confirmations
7. **Attendance** - Attendance logs and weekly reports
8. **Evaluations** - Student and mentor evaluations
9. **Certificates** - Completion certificate management
10. **Profiles** - Student internship profiles
11. **Communications** - Email/SMS templates and logs
12. **Reports** - Analytics and reporting

---

## Employer & Partnership Management

### Managing Companies

#### Adding a New Company

1. Navigate to **Partners** tab
2. Click **Add Company** button
3. Fill in company details:
   - Company Name (required)
   - Company Code (optional)
   - Company Type
   - Industry Sector
   - Company Size
   - Contact Information (email, phone, address)
   - Website URL
   - Partnership Type
   - Partnership Start Date
   - Description and Notes
4. Click **Save** to create the company

#### Updating Company Information

1. Go to **Partners** tab
2. Find the company in the list
3. Click **Edit** button
4. Update the required fields
5. Click **Save** to update

#### Deleting a Company

1. Go to **Partners** tab
2. Find the company in the list
3. Click **Delete** button
4. Confirm deletion (Note: Companies with active internships cannot be deleted)

### Managing Company Contacts

#### Adding HR/Mentor Contacts

1. Navigate to **Partners** tab
2. Select a company
3. Click **Manage Contacts**
4. Click **Add Contact**
5. Fill in contact details:
   - Contact Name (required)
   - Designation
   - Department
   - Email
   - Phone Number
   - Alternate Phone
   - Set as Primary Contact (optional)
   - Notes
6. Click **Save**

#### Updating Contacts

1. Go to company contacts list
2. Click **Edit** on the contact
3. Update information
4. Click **Save**

#### Deleting Contacts

1. Go to company contacts list
2. Click **Delete** on the contact
3. Confirm deletion

### Managing MoUs and Agreements

#### Creating MoU/Agreement

1. Navigate to **Partners** tab
2. Select a company
3. Click **MoUs & Agreements**
4. Click **Add MoU**
5. Fill in details:
   - MoU Number (optional)
   - MoU Type (MOU, NDA, Agreement, Contract)
   - Title (required)
   - Description
   - Start Date
   - End Date
   - Signed By (Company and School)
   - Signed Date
   - Renewal Date
   - Terms and Conditions
   - Notes
6. Click **Save**

#### Uploading MoU Document

1. Go to MoU details page
2. Click **Upload Document**
3. Select file (PDF, Word, or Image)
4. Click **Upload**

### Managing Employer Visits

#### Scheduling a Visit

1. Navigate to **Partners** tab
2. Select a company
3. Click **Company Visits**
4. Click **Schedule Visit**
5. Fill in visit details:
   - Visit Type (Campus Visit, Pre-Placement Talk, Interview, Meeting, Internship Discussion)
   - Visit Date (required)
   - Visit Time
   - Duration (minutes)
   - Purpose
   - Agenda
   - Company Attendees
   - School Attendees
   - Venue
   - Status (Scheduled, Completed, Cancelled, Postponed)
6. Click **Save**

#### Logging Visit Outcomes

1. Go to visit details
2. Click **Update Status**
3. Fill in:
   - Outcome
   - Follow-up Required
   - Follow-up Notes
4. Click **Save**

---

## Internship Opportunity Management

### Creating an Opportunity

1. Navigate to **Opportunities** tab
2. Click **Create Opportunity**
3. Fill in opportunity details:
   - Company (select from partners)
   - Opportunity Code (optional)
   - Title (required)
   - Description
   - Department
   - Duration (weeks)
   - Start Date
   - End Date
   - Stipend Amount
   - Location
   - Work Mode (Onsite, Remote, Hybrid)
   - Skills Required
   - Eligibility Criteria
   - Maximum Students
   - Application Deadline
4. Click **Save as Draft** or **Publish**

### Publishing Opportunities

1. Go to **Opportunities** tab
2. Find the draft opportunity
3. Click **Publish**
4. The opportunity will be visible to eligible students

### Managing Opportunity Documents

#### Uploading Documents

1. Go to opportunity details
2. Click **Documents**
3. Click **Upload Document**
4. Select file
5. Enter document type and name
6. Click **Upload**

### Updating Opportunities

1. Go to **Opportunities** tab
2. Find the opportunity
3. Click **Edit**
4. Update required fields
5. Click **Save**

### Closing/Cancelling Opportunities

1. Go to opportunity details
2. Click **Actions**
3. Select **Close** or **Cancel**
4. Confirm action

---

## Student Application Workflow

### Viewing Applications

1. Navigate to **Applications** tab
2. Use filters to find specific applications:
   - Status (Submitted, Shortlisted, Selected, Rejected)
   - Opportunity
   - Student
   - Date Range
3. Click on an application to view details

### Reviewing Applications

1. Go to application details
2. Review:
   - Student Information
   - Opportunity Details
   - Resume/Cover Letter
   - Application Status
   - Application History
3. Take action:
   - **Approve**: Approve the application
   - **Reject**: Reject with reason
   - **Shortlist**: Add to shortlist
   - **Request More Info**: Request additional documents

### Shortlisting Students

#### Manual Shortlisting

1. Go to **Shortlisting** tab
2. Click **Add to Shortlist**
3. Select application(s)
4. Group by employer (optional)
5. Click **Shortlist**

#### Bulk Shortlisting

1. Go to **Applications** tab
2. Select multiple applications
3. Click **Bulk Actions** > **Shortlist**
4. Confirm selection

### Sending Student Lists to Companies

1. Go to **Shortlisting** tab
2. Select shortlisted students for a company
3. Click **Send to Company**
4. Review the list
5. Click **Send**

---

## Approval & Allotment Workflow

### Approving Applications

1. Navigate to **Applications** tab
2. Find pending applications
3. Click **Approve**
4. Review application details
5. Confirm approval
6. System will create an allotment record

### Managing Allotments

#### Viewing Allotments

1. Go to **Allotments** tab
2. View all allotment letters
3. Filter by:
   - Status (Issued, Acknowledged)
   - Company
   - Student
   - Date Range

#### Uploading Allotment Letter

1. Go to allotment details
2. Click **Upload Letter**
3. Select file (PDF, Word, or Image)
4. Click **Upload**
5. Letter path will be updated

#### Generating Allotment Letter

1. Go to allotment details
2. Click **Generate Letter**
3. System will create a formatted letter
4. Download or upload the generated letter

### Tracking Employer Confirmations

1. Go to **Allotments** tab
2. View allotment status
3. Update confirmation:
   - Joining Date
   - Supervisor Details
   - Acknowledgment Date
4. Click **Save**

---

## Attendance & Weekly Reporting

### Managing Attendance

#### Viewing Attendance Logs

1. Navigate to **Attendance** tab
2. View attendance records
3. Filter by:
   - Student
   - Company
   - Date Range
   - Status (Present, Absent, Late, Half Day, Leave)

#### Logging Attendance

1. Go to **Attendance** tab
2. Click **Log Attendance**
3. Select:
   - Application/Student
   - Date
   - Check-in Time
   - Check-out Time
   - Hours Worked
   - Attendance Status
   - Work Description
   - Tasks Completed
   - Mentor Remarks
4. Click **Save**

#### Verifying Attendance

1. Go to attendance record
2. Click **Verify**
3. Add verification notes
4. Click **Verify**

### Managing Weekly Reports

#### Viewing Weekly Reports

1. Go to **Attendance** tab > **Weekly Reports**
2. View all weekly reports
3. Filter by:
   - Student
   - Week Number
   - Status (Draft, Submitted, Reviewed, Approved)

#### Reviewing Reports

1. Go to weekly report details
2. Review:
   - Work Summary
   - Tasks Completed
   - Challenges Faced
   - Learnings
   - Skills Developed
   - Mentor Feedback
   - Next Week Plan
3. Add reviewer comments
4. Click **Approve** or **Request Revision**

### Managing Mentor Feedback

#### Viewing Mentor Feedback

1. Go to **Attendance** tab > **Mentor Feedback**
2. View all feedback records
3. Filter by:
   - Student
   - Feedback Type (Weekly, Mid-term, Final, Ad-hoc)
   - Date Range

#### Adding Mentor Feedback

1. Click **Add Feedback**
2. Select application/student
3. Fill in:
   - Mentor Information (Name, Email, Designation)
   - Feedback Date
   - Ratings (Technical, Communication, Teamwork, Problem-solving, Punctuality, Overall)
   - Strengths
   - Areas for Improvement
   - Specific Achievements
   - Recommendations
   - Would Recommend (Yes/No)
   - Feedback Type
4. Click **Save**

#### Verifying Feedback

1. Go to feedback details
2. Click **Verify**
3. Confirm verification
4. Feedback will be marked as verified

### Managing Site Visits

#### Logging Site Visits

1. Go to **Attendance** tab > **Site Visits**
2. Click **Log Visit**
3. Fill in:
   - Company
   - Visit Date
   - Visit Time
   - Duration
   - Visit Type
   - Coordinator
   - Company Contact
   - Students Met
   - Visit Purpose
   - Observations
   - Student Feedback
   - Company Feedback
   - Issues Identified
   - Action Items
   - Follow-up Required
4. Click **Save**

---

## Evaluation & Completion

### Managing Evaluations

#### Viewing Evaluations

1. Navigate to **Evaluations** tab
2. View all evaluations
3. Filter by:
   - Student
   - Evaluation Type
   - Date Range

#### Creating Evaluation

1. Click **Add Evaluation**
2. Select application/student
3. Fill in:
   - Evaluation Type
   - Evaluated By
   - Ratings (Technical, Communication, Teamwork, Problem-solving, Punctuality, Overall)
   - Strengths
   - Areas for Improvement
   - Recommendations
   - Evaluation Date
4. Click **Save**

#### Uploading Evaluation Form

1. Go to evaluation details
2. Click **Upload Form**
3. Select file (PDF, Word, or Image)
4. Click **Upload**

### Managing Completions

#### Viewing Completions

1. Navigate to **Certificates** tab
2. View all completion records
3. Filter by:
   - Student
   - Company
   - Completion Date
   - Grade

#### Marking Completion

1. Go to application details
2. Click **Mark Complete**
3. Fill in:
   - Completion Date
   - Grade
   - Completion Report
4. Click **Save**

### Generating Certificates

#### Generating Completion Certificate

1. Go to **Certificates** tab
2. Find completion record
3. Click **Generate Certificate**
4. Configure:
   - Template (if available)
   - Include Signature
   - Custom Data (optional)
5. Click **Generate**
6. Certificate will be created and stored
7. Download or share the certificate

#### Uploading Certificate

1. Go to completion details
2. Click **Upload Certificate**
3. Select file
4. Click **Upload**

---

## Student Career Profiles

### Viewing Student Profiles

1. Navigate to **Profiles** tab
2. View all student internship profiles
3. Filter by:
   - Student Name
   - Department
   - Status

### Managing Student Profiles

#### Viewing Profile Details

1. Go to student profile
2. View:
   - Total Internships
   - Completed Internships
   - Ongoing Internships
   - Total Duration
   - Average Evaluation Score
   - Preferred Domains
   - Career Objectives
   - Skills Summary
   - Achievements
   - Portfolio Links (LinkedIn, GitHub, Personal Website)

#### Updating Profile

1. Go to profile details
2. Click **Edit**
3. Update:
   - Career Objectives
   - Skills Summary
   - Achievements
   - Portfolio Links
4. Click **Save**

### Managing Internship History

1. Go to student profile
2. Click **Internship History**
3. View all past internships
4. See:
   - Company
   - Opportunity
   - Duration
   - Status
   - Evaluation Score

### Managing Skills

#### Viewing Skills

1. Go to student profile
2. Click **Skills**
3. View all skills gained during internships

#### Adding Skills

1. Go to skills section
2. Click **Add Skill**
3. Fill in:
   - Skill Name
   - Category (Technical, Soft, Domain-specific, Tool, Language)
   - Proficiency Level (Beginner, Intermediate, Advanced, Expert)
   - Description
   - Verified by Mentor
4. Click **Save**

---

## Communications Module

### Managing Templates

#### Viewing Templates

1. Navigate to **Communications** tab
2. Click **Templates**
3. View all communication templates
4. Filter by:
   - Type (Email, SMS, Announcement, Notification)
   - Category

#### Creating Template

1. Click **Create Template**
2. Fill in:
   - Template Name
   - Type (Email, SMS, Announcement, Notification)
   - Category
   - Subject (for emails)
   - Content (supports variables like {{student_name}}, {{company_name}}, etc.)
   - Description
3. Click **Save**

#### Suggested Templates

The system includes suggested templates:
- **Internship Opportunity Announcement**: Notify students about new opportunities
- **Application Last Date Reminder**: Remind students of approaching deadlines
- **Shortlist Notification**: Notify shortlisted students
- **Weekly Report Reminder**: Remind students to submit weekly reports
- **Evaluation Completion Notice**: Notify about evaluation completion
- **Internship Certificate Ready**: Notify when certificate is ready

### Sending Communications

#### Sending Email/SMS

1. Go to **Communications** tab
2. Click **Send Communication**
3. Select:
   - Template (optional)
   - Type (Email, SMS, Announcement, Notification)
   - Recipients (Students, Companies, or Custom)
4. Fill in:
   - Subject
   - Message (variables will be replaced automatically)
5. Preview message
6. Click **Send**

#### Bulk Communications

1. Go to **Send Communication**
2. Select multiple recipients
3. Choose template or compose message
4. Click **Send to All**

### Viewing Communication Logs

1. Go to **Communications** tab
2. Click **Logs**
3. View all sent communications
4. Filter by:
   - Type
   - Recipient
   - Date Range
   - Status (Sent, Failed, Pending)

---

## Reports & Analytics

### Dashboard Reports

#### Participation Rate

1. Go to **Reports** tab
2. View participation rate by department
3. See:
   - Total Students
   - Students with Internships
   - Participation Percentage

#### Completion Rate

1. View completion metrics
2. See:
   - Total Internships
   - Completed Internships
   - Completion Percentage

#### Stipend Distribution

1. View stipend statistics
2. See:
   - Average Stipend by Department
   - Minimum/Maximum Stipend
   - Total Students with Stipend

#### Company Engagement

1. View company engagement metrics
2. See:
   - Total Opportunities per Company
   - Total Applications
   - Total Selected
   - Average Evaluation Score

#### Evaluation Scores

1. View evaluation distribution
2. See rating ranges:
   - Excellent (4.5-5.0)
   - Good (3.5-4.4)
   - Average (2.5-3.4)
   - Below Average (1.5-2.4)
   - Poor (1.0-1.4)

### Exporting Reports

1. Go to **Reports** tab
2. Select report type:
   - Participation Report
   - Completion Report
   - Company Engagement Report
   - Evaluation Summary
3. Apply filters (department, date range)
4. Click **Export**
5. Report will be downloaded as JSON

### Analytics Charts

The reports section includes interactive charts:
- **Bar Charts**: Participation, Stipend distribution
- **Pie Charts**: Evaluation score distribution
- **Line Charts**: Trends over time

---

## Document Management

### Uploading Documents

#### Opportunity Documents

1. Go to opportunity details
2. Click **Documents** > **Upload**
3. Select file
4. Enter document type and name
5. Click **Upload**

#### Allotment Letters

1. Go to allotment details
2. Click **Upload Letter**
3. Select file (PDF, Word, or Image)
4. Click **Upload**

#### Evaluation Forms

1. Go to evaluation details
2. Click **Upload Form**
3. Select file
4. Click **Upload**

#### MoU Documents

1. Go to MoU details
2. Click **Upload Document**
3. Select file
4. Click **Upload**

### Downloading Documents

1. Go to document list
2. Click **Download** on the document
3. File will be downloaded

### Supported File Types

- **PDF**: `.pdf`
- **Images**: `.png`, `.jpg`, `.jpeg`, `.gif`
- **Word Documents**: `.doc`, `.docx`
- **Text Files**: `.txt`

---

## Settings & Configuration

### Accessing Settings

1. Navigate to **Settings** tab in the dashboard
2. Or go directly to: `/[school-code]/dashboard/internship-coordinator/settings`

### Notification Settings

#### Email Notifications
- Toggle to enable/disable email notifications
- Receive emails for important events like new applications, pending reports, etc.

#### SMS Notifications
- Toggle to enable/disable SMS notifications
- Receive SMS for urgent updates

#### Notification Preferences
- **Notify on New Applications**: Get notified when students submit applications
- **Notify on Pending Reports**: Get notified when weekly reports need review
- **Notify on Evaluation Due**: Get notified when evaluations are due

### Workflow Settings

#### Auto-Approve Applications
- Enable to automatically approve applications that meet eligibility criteria
- Use with caution - review criteria before enabling

#### Require Weekly Reports
- Make weekly reports mandatory for all internships
- Students must submit reports to complete internship

#### Require Mentor Feedback
- Make mentor feedback mandatory for completion
- Ensures all internships have mentor evaluation

### Default Values

#### Default Stipend Amount
- Set default stipend amount for new opportunities
- Pre-fills when creating opportunities

#### Default Internship Duration
- Set default duration in weeks
- Pre-fills when creating opportunities

#### Certificate Template
- Select default template for certificate generation
- Options: Default, Detailed, Simple

### Saving Settings

1. Configure all settings as needed
2. Click **Save Settings** button
3. Settings will be saved and applied immediately

---

## Security & Compliance

### Multi-Tenant Security

- All data is automatically filtered by your school
- You cannot access data from other schools
- All queries include school_id or school_code filters

### Access Restrictions

The Internship Coordinator role has the following restrictions:
- ❌ **No Access** to exam/grades module
- ❌ **No Access** to fee/payroll/HR data
- ❌ **No Access** to dean/HOD academic configuration
- ❌ **No Access** to placement officer's job-drive-only features

### RBAC Permissions

All actions require appropriate permissions:
- **Read Operations**: `internship:read`, `company:read`, etc.
- **Write Operations**: `internship:write`, `company:write`, etc.
- **Create Operations**: `internship:create`, `company:create`, etc.
- **Update Operations**: `internship:update`, `company:update`, etc.
- **Delete Operations**: `internship:delete`, `company:delete`, etc.

### Document Access Control

- Documents are stored securely in S3
- Access is controlled by RBAC permissions
- Only authorized users can view/download documents

---

## Troubleshooting

### Common Issues

#### Cannot Access Dashboard

**Problem**: Getting "Unauthorized" or "Access Denied" error

**Solution**:
1. Verify your role is "internship-coordinator"
2. Check that you have necessary permissions assigned
3. Ensure you're logged into the correct school
4. Contact system administrator if issue persists

#### Cannot Create Opportunity

**Problem**: Error when creating opportunity

**Solution**:
1. Verify company exists and is active
2. Check all required fields are filled
3. Ensure you have `internship:opportunity:create` permission
4. Verify school access

#### Cannot Upload Documents

**Problem**: Document upload fails

**Solution**:
1. Check file size (should be under 10MB)
2. Verify file type is supported
3. Check S3 configuration
4. Ensure you have document upload permissions

#### Reports Not Loading

**Problem**: Reports show no data or error

**Solution**:
1. Check date range filters
2. Verify data exists for selected filters
3. Check browser console for errors
4. Refresh the page

### Error Messages

#### "School access denied"
- Verify you're accessing the correct school
- Check school_code in URL matches your assigned school

#### "Insufficient permissions"
- Contact administrator to assign required permissions
- Verify your role includes necessary permissions

#### "Rate limit exceeded"
- Wait a few minutes before retrying
- Reduce frequency of API calls

---

## FAQs

### General Questions

**Q: Can I access data from other schools?**  
A: No. The system enforces strict multi-tenant isolation. You can only access data from your assigned school.

**Q: Can I modify student grades or exam results?**  
A: No. The Internship Coordinator role has no access to grades or exam modules.

**Q: How do I add a new company?**  
A: Go to Partners tab > Add Company, fill in company details, and save.

**Q: How do I publish an opportunity?**  
A: Create the opportunity, review all details, and click "Publish" button.

**Q: Can I delete a company with active internships?**  
A: No. Companies with active internships cannot be deleted. You must first complete or cancel all related internships.

**Q: How do I generate a completion certificate?**  
A: Go to Certificates tab > Find completion record > Click "Generate Certificate" > Configure options > Generate.

**Q: Can I send bulk communications?**  
A: Yes. Use the Send Communication feature and select multiple recipients.

**Q: How do I track student attendance?**  
A: Go to Attendance tab > Log Attendance > Fill in details > Save.

**Q: What file types are supported for document uploads?**  
A: PDF, Images (PNG, JPG, JPEG, GIF), Word documents (DOC, DOCX), and Text files.

**Q: How do I export reports?**  
A: Go to Reports tab > Select report type > Apply filters > Click Export.

### Workflow Questions

**Q: What is the typical workflow for processing applications?**  
A: 
1. Student applies for opportunity
2. Coordinator reviews application
3. Coordinator validates eligibility
4. Coordinator shortlists (if applicable)
5. Coordinator approves/rejects
6. Allotment letter is generated/uploaded
7. Student starts internship
8. Attendance and reports are tracked
9. Evaluations are completed
10. Certificate is generated upon completion

**Q: How do I handle rejected applications?**  
A: Go to application details > Click "Reject" > Provide rejection reason > Save. The student will be notified.

**Q: Can I edit a published opportunity?**  
A: Yes, but changes may affect existing applications. Use caution when editing published opportunities.

**Q: How do I manage weekly reports?**  
A: Go to Attendance tab > Weekly Reports > Review submitted reports > Add comments > Approve or request revision.

### Technical Questions

**Q: What browsers are supported?**  
A: Modern browsers including Chrome, Firefox, Safari, and Edge (latest versions).

**Q: Is there a mobile app?**  
A: The system is responsive and works on mobile browsers. A dedicated mobile app may be available - check with your administrator.

**Q: How do I reset my password?**  
A: Use the "Forgot Password" link on the login page or contact your system administrator.

**Q: Can I customize communication templates?**  
A: Yes. Go to Communications > Templates > Edit template > Modify content > Save.

---

## Support & Contact

### Getting Help

- **Technical Issues**: Contact your system administrator
- **Permission Issues**: Contact your school admin or IT department
- **Feature Requests**: Submit through your institution's feedback system

### Additional Resources

- **Training Materials**: Check your institution's training portal
- **Video Tutorials**: Available in the help section
- **Documentation**: Refer to this manual and other role-specific guides

---

**End of User Manual**

*For the most up-to-date information, please refer to the online help system or contact your system administrator.*

