# Research Coordinator User Manual

## Table of Contents

1. [Introduction](#introduction)
2. [Getting Started](#getting-started)
3. [Dashboard Overview](#dashboard-overview)
4. [Research Project Management](#research-project-management)
5. [Grant & Funding Management](#grant--funding-management)
6. [Thesis & Dissertation Workflow](#thesis--dissertation-workflow)
7. [Scholar Progress Tracking](#scholar-progress-tracking)
8. [Ethics Committee Workflow](#ethics-committee-workflow)
9. [Research Events Management](#research-events-management)
10. [Communications Tools](#communications-tools)
11. [Publications Management](#publications-management)
12. [Reports & Analytics](#reports--analytics)
13. [Settings & Preferences](#settings--preferences)
14. [Document Management](#document-management)
15. [Troubleshooting](#troubleshooting)
16. [FAQs](#faqs)

---

## Introduction

### About the Research Coordinator Module

The Research Coordinator module is a comprehensive system designed to help research coordinators manage all aspects of research activities within their institution. This includes overseeing research projects, managing grants and funding, tracking thesis submissions, monitoring scholar progress, coordinating ethics approvals, organizing research events, and generating reports.

### Key Features

- **Research Project Management**: Register, track, and manage research projects through their complete lifecycle
- **Grant & Funding Management**: Track grants, allocate funds, and monitor budget utilization
- **Thesis Workflow**: Manage thesis submissions, reviews, and defense scheduling
- **Scholar Progress Tracking**: Monitor MPhil/PhD/PG scholar progress and identify at-risk scholars
- **Ethics Committee**: Manage ethics applications and approval workflows
- **Research Events**: Organize workshops, seminars, and FDPs
- **Communications**: Send automated reminders and notifications
- **Reports & Analytics**: Generate comprehensive research reports
- **Document Management**: Upload, version, and manage research documents

### Access Requirements

- **Role**: Research Coordinator (Role ID: 34)
- **Permissions**: Assigned by system administrator
- **Access Level**: Institution-specific (multi-tenant)

---

## Getting Started

### Accessing the Dashboard

1. **Login**: Navigate to your school's login page: `/[school_code]/login`
2. **Authentication**: Enter your credentials
3. **Dashboard Access**: After login, you'll be automatically redirected to the Research Coordinator Dashboard at `/[school_code]/dashboard/research-coordinator`

### First-Time Setup

1. **Verify Permissions**: Ensure you have the "research-coordinator" role assigned
2. **Review Settings**: Navigate to the Settings tab to configure your preferences
3. **Familiarize with Navigation**: Explore the 10 main tabs in the dashboard

### Dashboard Layout

The Research Coordinator Dashboard consists of:

- **Header**: School name, user info, refresh button, quick actions
- **Navigation Tabs**: 10 main sections (Overview, Projects, Grants, Thesis, Scholars, Ethics, Events, Communications, Reports, Settings)
- **Content Area**: Dynamic content based on selected tab
- **Stats Cards**: Key metrics displayed on the Overview tab

---

## Dashboard Overview

### Overview Tab

The Overview tab provides a comprehensive summary of all research activities.

#### Key Metrics

1. **Total Projects**: Number of all research projects
2. **Active Projects**: Currently ongoing projects
3. **Active Grants**: Number of active grant programs
4. **Pending Theses**: Thesis submissions awaiting review
5. **Scholars in Progress**: MPhil/PhD/PG scholars actively enrolled
6. **At-Risk Scholars**: Scholars identified as delayed or at-risk
7. **Pending Ethics Approvals**: Ethics applications awaiting review
8. **Upcoming Events**: Research events scheduled in the near future
9. **Recent Publications**: Publications from the last year

#### Recent Activities Feed

- Displays the 5 most recent activities across all modules
- Shows activity type, title, description, timestamp, and status
- Color-coded badges indicate activity status (success, warning, error, info, pending)

#### Quick Actions

- **Register New Project**: Create a new research project
- **Add New Grant**: Create a new grant program
- **Process Thesis Submission**: Handle new thesis submissions
- **Submit Ethics Application**: Create a new ethics application
- **Send Announcement**: Send communication to stakeholders

---

## Research Project Management

### Viewing Projects

1. Navigate to the **Projects** tab
2. View all research projects in a table format
3. Use filters to narrow down:
   - **Status**: All, Draft, Submitted, Approved, Ongoing, Completed, Cancelled
   - **Stage**: All, Proposal, Ethics Approval, Ongoing, Mid-term Review, Final Submission, Publication
   - **Search**: Search by project title, code, research area, or PI name

### Creating a New Project

1. Click the **"New Project"** button or use Quick Actions
2. Fill in the required fields:
   - **Project Code**: Unique identifier (e.g., PROJ-2024-001)
   - **Project Title**: Full title of the research project
   - **Project Description**: Detailed description
   - **Research Area**: Field of research
   - **Research Type**: Basic, Applied, Experimental, Theoretical, Field Research
   - **Principal Investigator**: Select from staff list
   - **Department**: Select department
   - **Start Date**: Project start date
   - **Expected End Date**: Projected completion date
   - **Budget Allocated**: Initial budget allocation
3. Click **"Create Project"**

### Managing Project Stages

1. Open a project by clicking the **View** button
2. Navigate to the **Stages** section
3. **Add Stage**:
   - Click "Add Stage"
   - Enter stage name (Proposal, Ethics Approval, Ongoing, etc.)
   - Set start and end dates
   - Set completion percentage
   - Add notes
4. **Update Stage Status**: Mark stages as pending, in progress, or completed

### Assigning Supervisors

1. Open a project
2. Navigate to **Supervisors** section
3. Click **"Assign Supervisor"**
4. Select supervisor from staff list
5. Choose supervisor type:
   - **Primary Supervisor**: Main supervisor
   - **Co-Supervisor**: Secondary supervisor
6. Set assignment date
7. Click **"Assign"**

### Assigning Reviewers

1. Open a project
2. Navigate to **Reviewers** section
3. Click **"Assign Reviewer"**
4. Select reviewer from staff list
5. Choose reviewer role (Internal, External, Committee Member)
6. Click **"Assign"**

### Adding Project Notes

1. Open a project
2. Navigate to **Notes & Logs** section
3. Click **"Add Note"**
4. Select note type:
   - **General Note**: General observations
   - **Meeting Note**: Notes from meetings
   - **Progress Update**: Progress updates
   - **Issue Log**: Issues or concerns
5. Enter note title and content
6. Click **"Save Note"**

### Uploading Project Documents

1. Open a project
2. Navigate to **Documents** section
3. Click **"Upload Document"**
4. Select file (PDF, DOC, DOCX, XLS, XLSX, images, text files - max 50MB)
5. Enter document type and title
6. Add description (optional)
7. Click **"Upload"**

### Editing a Project

1. Find the project in the list
2. Click the **Edit** button (pencil icon)
3. Modify the fields you want to update
4. Click **"Update Project"**

### Deleting a Project

1. Find the project in the list
2. Click the **Delete** button (trash icon)
3. Confirm deletion
4. Note: Projects are soft-deleted (marked as inactive, not permanently removed)

---

## Grant & Funding Management

### Viewing Grants

1. Navigate to the **Grants** tab
2. View all grants in a table format
3. Filter by:
   - **Status**: All, Open, Closed, Awarded, Rejected, Completed, Cancelled
   - **Type**: All, Internal, External, Government, Private, International
   - **Search**: Search by grant code, title, or funding agency

### Creating a New Grant

1. Click **"New Grant"** button
2. Fill in required fields:
   - **Grant Code**: Unique identifier
   - **Grant Title**: Full title
   - **Grant Description**: Detailed description
   - **Funding Agency**: Name of funding organization
   - **Grant Type**: Internal, External, Government, Private, International
   - **Total Amount**: Total funding amount
   - **Start Date**: Grant start date
   - **End Date**: Grant end date
   - **Application Deadline**: Deadline for applications
   - **Status**: Open, Closed, Awarded, etc.
   - **Eligibility Criteria**: Who can apply
   - **Application Requirements**: Required documents/information
3. Click **"Create Grant"**

### Allocating Grants to Projects

1. Navigate to **Grants** tab
2. Open a grant
3. Navigate to **Allocations** section
4. Click **"Allocate to Project"**
5. Select research project
6. Enter allocated amount
7. Set allocation date
8. Add notes (optional)
9. Click **"Allocate"**

### Creating Budget Reports

1. Open a grant
2. Navigate to **Budget Reports** section
3. Click **"Create Budget Report"**
4. Enter:
   - **Report Date**: Date of report
   - **Report Period**: Start and end dates
   - **Total Allocated**: Total allocated amount
   - **Total Utilized**: Amount spent
   - **Budget Breakdown**: Detailed breakdown (JSON format)
   - **Notes**: Additional notes
5. Click **"Generate Report"**

### Tracking Funding Status

1. Open a grant
2. Navigate to **Funding Status** section
3. View funding status history
4. **Add Status Log**:
   - Click "Add Status Log"
   - Enter status date
   - Select new status
   - Enter funding amount (if applicable)
   - Add notes
   - Click "Save"

---

## Thesis & Dissertation Workflow

### Viewing Thesis Submissions

1. Navigate to the **Thesis** tab
2. View all thesis submissions
3. Filter by:
   - **Status**: All, Submitted, Under Review, Reviewed, Approved, Rejected
   - **Type**: All, MPhil, PhD, PG
   - **Search**: Search by thesis title, student name, or supervisor

### Creating a Thesis Submission

1. Click **"New Thesis Submission"**
2. Fill in required fields:
   - **Thesis Title**: Full thesis title
   - **Thesis Type**: MPhil, PhD, PG
   - **Student**: Select student from list
   - **Supervisor**: Select supervisor
   - **Department**: Select department
   - **Submission Date**: Date of submission
   - **Abstract**: Thesis abstract
3. Click **"Create Submission"**

### Uploading Plagiarism Reports

1. Open a thesis submission
2. Navigate to **Plagiarism Reports** section
3. Click **"Upload Plagiarism Report"**
4. Enter:
   - **Plagiarism Percentage**: Similarity percentage
   - **Report URL**: Link to plagiarism report
   - **Checked By**: Staff member who checked
   - **Check Date**: Date of check
   - **Status**: Pass, Fail, Review Required
   - **Notes**: Additional comments
5. Click **"Upload Report"**

### Creating Review Reports

1. Open a thesis submission
2. Navigate to **Review Reports** section
3. Click **"Create Review Report"**
4. Enter:
   - **Reviewer**: Select reviewer
   - **Overall Rating**: Overall assessment (1-10)
   - **Technical Quality Rating**: Technical quality (1-10)
   - **Originality Rating**: Originality assessment (1-10)
   - **Methodology Rating**: Methodology quality (1-10)
   - **Presentation Rating**: Presentation quality (1-10)
   - **Strengths**: List of strengths
   - **Weaknesses**: Areas for improvement
   - **Recommendations**: Recommendations
   - **Decision**: Approve, Reject, Revise
   - **Review Comments**: Detailed comments
5. Click **"Submit Review"**

### Scheduling Defense

1. Open a thesis submission
2. Navigate to **Defense Schedule** section
3. Click **"Schedule Defense"**
4. Enter:
   - **Defense Date**: Date of defense
   - **Defense Time**: Time of defense
   - **Venue**: Location
   - **Defense Type**: Oral, Written, Hybrid
   - **Panel Chair**: Select panel chair
   - **Panel Members**: Select panel members
   - **External Examiner**: Select external examiner (optional)
5. Click **"Schedule Defense"**

### Managing Revisions

1. Open a thesis submission
2. Navigate to **Revision Logs** section
3. View all revision history
4. **Add Revision**:
   - Click "Add Revision"
   - Enter revision type (Minor, Major, Substantial)
   - Enter revision description
   - Select reviewer (optional)
   - Set revision status (Pending, In Progress, Completed)
   - Add comments
   - Click "Save Revision"

---

## Scholar Progress Tracking

### Viewing Scholars

1. Navigate to the **Scholars** tab
2. View all scholar progress records
3. Filter by:
   - **Type**: All, MPhil, PhD, PG
   - **Status**: All, In Progress, At Risk, Delayed, Completed
   - **Search**: Search by student name or ID

### Creating Scholar Progress Record

1. Click **"New Scholar Record"**
2. Fill in required fields:
   - **Student**: Select student
   - **Program Type**: MPhil, PhD, PG
   - **Enrollment Date**: Date of enrollment
   - **Expected Completion Date**: Projected completion
   - **Current Stage**: Current progress stage
   - **Completion Percentage**: Progress percentage (0-100)
   - **GPA**: Current GPA
   - **Status**: In Progress, At Risk, Delayed, Completed
3. Click **"Create Record"**

### Scheduling Advisory Meetings

1. Open a scholar record
2. Navigate to **Advisory Meetings** section
3. Click **"Schedule Meeting"**
4. Enter:
   - **Meeting Date**: Date of meeting
   - **Meeting Time**: Time of meeting
   - **Meeting Type**: Regular, Progress Review, Emergency
   - **Venue**: Meeting location
   - **Agenda**: Meeting agenda
   - **Attendees**: Select attendees
   - **Notes**: Pre-meeting notes
5. Click **"Schedule Meeting"**

### Recording Seminar Attendance

1. Open a scholar record
2. Navigate to **Seminar Attendance** section
3. Click **"Record Attendance"**
4. Enter:
   - **Event**: Select research event
   - **Attendance Date**: Date of attendance
   - **Attendance Status**: Present, Absent, Partial
   - **Hours Attended**: Number of hours
   - **Notes**: Additional notes
5. Click **"Record Attendance"**

### Creating Progress Evaluations

1. Open a scholar record
2. Navigate to **Progress Evaluations** section
3. Click **"Create Evaluation"**
4. Enter:
   - **Evaluation Date**: Date of evaluation
   - **Evaluation Type**: Quarterly, Mid-term, Annual, Final
   - **Overall Rating**: Overall assessment (1-10)
   - **Academic Performance**: Academic performance rating (1-10)
   - **Research Progress**: Research progress rating (1-10)
   - **Publication Activity**: Publication activity rating (1-10)
   - **Seminar Attendance**: Attendance rating (1-10)
   - **Strengths**: List of strengths
   - **Areas for Improvement**: Areas needing improvement
   - **Recommendations**: Recommendations
   - **Evaluation Status**: Completed, Draft
5. Click **"Submit Evaluation"**

### Identifying At-Risk Scholars

The system automatically identifies at-risk scholars based on:
- Low completion percentage relative to expected progress
- Missed advisory meetings
- Poor seminar attendance
- Low GPA
- Delayed milestones

View at-risk scholars in the Overview tab or filter by "At Risk" status in the Scholars tab.

---

## Ethics Committee Workflow

### Viewing Ethics Applications

1. Navigate to the **Ethics** tab
2. View all ethics applications
3. Filter by:
   - **Status**: All, Pending, Under Review, Approved, Rejected, Conditional
   - **Search**: Search by application code, title, or applicant

### Creating Ethics Application

1. Click **"New Ethics Application"**
2. Fill in required fields:
   - **Application Code**: Unique identifier
   - **Application Title**: Title of research
   - **Project**: Link to research project (if applicable)
   - **Applicant**: Select applicant (staff member)
   - **Research Methodology**: Description of research methods
   - **Participant Information**: Information about participants
   - **Informed Consent Procedure**: Consent process
   - **Data Collection Methods**: How data will be collected
   - **Data Storage Procedures**: How data will be stored
   - **Risk Assessment**: Potential risks
   - **Benefits Description**: Expected benefits
   - **Confidentiality Measures**: Confidentiality safeguards
3. Click **"Submit Application"**

### Assigning Committee

1. Open an ethics application
2. Navigate to **Committee Assignment** section
3. Click **"Assign Committee"**
4. Select ethics committee
5. Click **"Assign"**

### Managing Committee Members

1. Navigate to **Ethics** tab
2. Open a committee
3. Navigate to **Members** section
4. **Add Member**:
   - Click "Add Member"
   - Select staff member
   - Choose member role (Chair, Member, Secretary)
   - Click "Add"
5. **Remove Member**: Click remove button (deactivates member)

### Approving/Rejecting Applications

1. Open an ethics application
2. Navigate to **Approval** section
3. **Approve**:
   - Click "Approve"
   - Set approval date
   - Set expiry date (if applicable)
   - Enter conditions for approval (if any)
   - Add approval notes
   - Click "Approve"
4. **Reject**:
   - Click "Reject"
   - Enter rejection reason
   - Add notes
   - Click "Reject"

### Viewing Approval Logs

1. Open an ethics application
2. Navigate to **Approval Logs** section
3. View complete history of:
   - Status changes
   - Approval/rejection actions
   - Committee assignments
   - Notes and comments

---

## Research Events Management

### Viewing Events

1. Navigate to the **Events** tab
2. View all research events
3. Filter by:
   - **Type**: All, Workshop, Seminar, FDP, Conference, Symposium
   - **Status**: All, Scheduled, Ongoing, Completed, Cancelled
   - **Search**: Search by event title, code, or organizer

### Creating a Research Event

1. Click **"New Event"**
2. Fill in required fields:
   - **Event Code**: Unique identifier
   - **Event Title**: Full event title
   - **Event Description**: Detailed description
   - **Event Type**: Workshop, Seminar, FDP, Conference, Symposium
   - **Event Date**: Date of event
   - **Event Time**: Time of event
   - **Venue**: Event location
   - **Organizer**: Select organizer (staff member)
   - **Max Participants**: Maximum number of participants
   - **Registration Deadline**: Registration deadline
   - **Status**: Scheduled, Ongoing, Completed, Cancelled
3. Click **"Create Event"**

### Registering Participants

1. Open an event
2. Navigate to **Participants** section
3. Click **"Register Participant"**
4. Select participant type:
   - **Student**: Select from student list
   - **Staff**: Select from staff list
   - **External**: Enter external participant details
5. Enter:
   - **Payment Status**: Pending, Paid, Waived
   - **Payment Amount**: Amount (if applicable)
6. Click **"Register"**

### Uploading Event Resources

1. Open an event
2. Navigate to **Resources** section
3. Click **"Upload Resource"**
4. Select file (presentations, documents, materials)
5. Enter:
   - **Resource Type**: Presentation, Document, Material, Other
   - **Resource Title**: Title of resource
   - **Description**: Resource description
6. Click **"Upload"**

---

## Communications Tools

### Viewing Communication Logs

1. Navigate to the **Communications** tab
2. View all communication logs
3. Filter by:
   - **Type**: All, Email, SMS, Notification
   - **Status**: All, Sent, Pending, Failed
   - **Search**: Search by recipient, subject, or message

### Sending Communications

1. Click **"Send Communication"**
2. Select communication type:
   - **Email**: Send email
   - **SMS**: Send SMS
   - **Notification**: Send in-app notification
3. Select recipient type:
   - **Student**: Select students
   - **Staff**: Select staff members
   - **Scholar**: Select scholars
   - **Custom**: Enter custom recipients
4. Enter:
   - **Subject**: Message subject (for email)
   - **Message**: Message content
   - **Template**: Select template (optional)
   - **Priority**: Normal, High, Urgent
5. Click **"Send"**

### Managing Templates

1. Navigate to **Communications** tab
2. Click **"Templates"** section
3. View predefined templates:
   - Thesis Submission Reminder
   - Ethics Approval Status Update
   - Grant Approval Notification
   - Research Seminar Invite
   - Supervisor Assignment Notification
   - Progress Review Meeting Reminder
4. **Create Custom Template**:
   - Click "Create Template"
   - Enter template name
   - Select template type (Email, SMS)
   - Enter subject and body
   - Use variables: {student_name}, {deadline_date}, etc.
   - Click "Save Template"

### Using Templates

1. When sending communication, select a template
2. Template variables are automatically replaced with actual data
3. Review and customize message before sending

---

## Publications Management

### Viewing Publications

1. Navigate to the **Publications** tab (under Reports)
2. View all publications
3. Filter by:
   - **Status**: All, Draft, Submitted, Published, Rejected
   - **Department**: Filter by department
   - **Search**: Search by title, author, or journal

### Creating a Publication

1. Click **"New Publication"**
2. Fill in required fields:
   - **Publication Title**: Full title
   - **Publication Type**: Journal Article, Conference Paper, Book, Book Chapter
   - **Publication Date**: Date of publication
   - **Journal/Conference Name**: Name of journal or conference
   - **Publisher**: Publisher name
   - **ISBN/ISSN**: ISBN or ISSN number
   - **DOI**: Digital Object Identifier
   - **Primary Author**: Select author
   - **Department**: Select department
   - **Impact Factor**: Journal impact factor (if applicable)
   - **Citation Count**: Number of citations
   - **Status**: Draft, Submitted, Published, Rejected
3. Click **"Create Publication"**

### Updating Publication Status

1. Open a publication
2. Click **"Edit"**
3. Update status and other fields
4. Click **"Update Publication"**

---

## Reports & Analytics

### Accessing Reports

1. Navigate to the **Reports** tab
2. Select report type from dropdown:
   - **Overview**: Overall research statistics
   - **Projects**: Research projects report
   - **Grants**: Grants and funding utilization
   - **Thesis**: Thesis submission pipeline
   - **Scholars**: Scholar progress analytics
   - **Ethics**: Ethics approval workflow stats
   - **Publications**: Publications report

### Generating Reports

1. Select report type
2. Set date range (optional)
3. Select department (optional)
4. Choose format: JSON (default) or PDF (if available)
5. Click **"Generate Report"**

### Report Types

#### Overview Report
- Total projects by status
- Active grants summary
- Thesis pipeline summary
- Scholar progress summary
- Ethics approval statistics
- Upcoming deadlines

#### Projects Report
- Projects by stage
- Projects by department
- Budget utilization
- Supervisor workload
- Project completion rates

#### Grants Report
- Grant allocation summary
- Budget utilization by project
- Funding status trends
- Grant approval rates

#### Thesis Report
- Thesis submissions by type
- Review status breakdown
- Defense scheduling
- Revision statistics
- Completion rates

#### Scholars Report
- Scholar progress by program type
- At-risk scholar identification
- Meeting attendance rates
- Evaluation statistics
- Completion timelines

#### Ethics Report
- Application status breakdown
- Approval rates
- Average review time
- Committee workload

#### Publications Report
- Publications by department
- Publications by type
- Impact factor statistics
- Citation trends

---

## Settings & Preferences

### Accessing Settings

1. Navigate to the **Settings** tab
2. Or click the link in the Settings tab content to open full settings page

### Notification Preferences

Configure how you receive notifications:

- **Email Notifications**: Enable/disable email notifications
- **SMS Notifications**: Enable/disable SMS notifications
- **Notification Types**:
  - Project Submissions
  - Ethics Approvals
  - Thesis Deadlines
  - Grant Approvals
  - At-Risk Scholars
  - Event Reminders

### Workflow Settings

- **Auto-Assign Supervisor**: Automatically assign supervisor when creating projects
- **Require Ethics Approval**: Require ethics approval before project activation
- **Default Project Stage**: Default stage for new projects
- **Default Grant Status**: Default status for new grants

### Communication Settings

- **Communication Frequency**: Immediate, Daily Digest, Weekly Summary
- **Default Email Template**: Default template for emails
- **Default SMS Template**: Default template for SMS

### Report Settings

- **Auto-Generate Reports**: Automatically generate reports on schedule
- **Report Frequency**: Daily, Weekly, Monthly
- **Include Inactive Projects**: Include completed/cancelled projects in reports

### Display Preferences

- **Items Per Page**: Number of items per page (10-100)
- **Default View**: Table, Grid, List
- **Show Advanced Filters**: Display advanced filtering options by default

### Saving Settings

1. Make your changes
2. Click **"Save Settings"** button at the bottom
3. Settings are saved immediately

---

## Document Management

### Uploading Documents

Documents can be uploaded for:
- Research Projects
- Thesis Submissions
- Grants
- Ethics Applications

**Steps**:
1. Navigate to the relevant entity (project, thesis, grant, etc.)
2. Go to **Documents** section
3. Click **"Upload Document"**
4. Select file (max 50MB)
5. Enter document type and title
6. Add description (optional)
7. Click **"Upload"**

**Supported File Types**:
- PDF (.pdf)
- Word Documents (.doc, .docx)
- Excel Files (.xls, .xlsx)
- Images (.jpg, .png, .gif)
- Text Files (.txt)

### Viewing Document Versions

1. Open a document
2. Navigate to **Versions** section
3. View all versions of the document
4. See version number, upload date, uploader, and change description

### Downloading Documents

1. Open a document or navigate to Documents section
2. Click **"Download"** button
3. Document downloads to your device
4. To download a specific version, select the version first

### Document Versioning

When you upload a new version of an existing document:
- Previous versions are preserved
- Version number auto-increments
- You can add a change description
- All versions remain accessible

---

## Troubleshooting

### Common Issues

#### Cannot Access Dashboard

**Problem**: Getting "Unauthorized" error when accessing dashboard

**Solutions**:
1. Verify you have the "research-coordinator" role assigned
2. Contact system administrator to verify permissions
3. Ensure you're logged in with the correct account
4. Clear browser cache and cookies
5. Try logging out and logging back in

#### Projects Not Showing

**Problem**: Projects list is empty or missing projects

**Solutions**:
1. Check filters - you may have filters applied that hide projects
2. Verify you're viewing the correct school/institution
3. Check project status - inactive projects may be hidden
4. Refresh the page
5. Contact administrator if issue persists

#### Cannot Upload Documents

**Problem**: Document upload fails

**Solutions**:
1. Check file size (must be under 50MB)
2. Verify file type is supported
3. Check internet connection
4. Try a different browser
5. Clear browser cache
6. Contact support if issue persists

#### Settings Not Saving

**Problem**: Settings changes are not saved

**Solutions**:
1. Ensure you click "Save Settings" button
2. Check for error messages
3. Refresh the page and try again
4. Clear browser cache
5. Contact support if issue persists

#### Reports Not Generating

**Problem**: Reports fail to generate or show errors

**Solutions**:
1. Check date range - ensure dates are valid
2. Verify you have permission to generate reports
3. Try a different report type
4. Refresh the page
5. Contact support if issue persists

---

## FAQs

### General Questions

**Q: Can I access data from other schools/institutions?**
A: No. The Research Coordinator module is multi-tenant, meaning you can only access data from your own institution. All queries are automatically filtered by your school_id.

**Q: Can I modify exam results or student grades?**
A: No. Research Coordinators do not have access to exam results, student grades, or academic scores. This is a security restriction.

**Q: Can I access financial records or payroll?**
A: No. Research Coordinators do not have access to financial records, payroll, or student financial data.

**Q: How do I get help if I encounter an issue?**
A: Contact your system administrator or IT support team. Provide details about the issue, including error messages and steps to reproduce.

### Project Management

**Q: How do I change a project's stage?**
A: Open the project, go to the Stages section, and either update an existing stage or create a new stage with the updated status.

**Q: Can I assign multiple supervisors to a project?**
A: Yes. You can assign one primary supervisor and multiple co-supervisors.

**Q: How do I track project budget?**
A: Budget information is displayed in the project detail view. You can update budget_allocated and budget_utilized fields when editing a project.

### Grant Management

**Q: How do I allocate a grant to multiple projects?**
A: You can create multiple allocations for the same grant. Each allocation links the grant to a different project with a specific allocated amount.

**Q: What's the difference between allocated_amount and utilized_amount?**
A: Allocated amount is the amount assigned to a project. Utilized amount is the amount actually spent. The difference shows remaining budget.

### Thesis Workflow

**Q: How do I know when a thesis needs review?**
A: Theses with status "Under Review" or "Submitted" need review. You can filter the thesis list by status to see pending reviews.

**Q: Can I schedule multiple defenses on the same day?**
A: Yes, you can schedule multiple defenses. The system tracks each defense separately.

### Scholar Tracking

**Q: How does the system identify at-risk scholars?**
A: The system identifies at-risk scholars based on:
- Low completion percentage
- Missed meetings
- Poor attendance
- Low GPA
- Delayed milestones

**Q: How often should I update scholar progress?**
A: It's recommended to update progress records regularly, especially after advisory meetings or milestone completions.

### Ethics Committee

**Q: How long does ethics approval take?**
A: Approval time varies. You can track the status in the application detail view and view approval logs for timeline information.

**Q: Can I reassign an ethics application to a different committee?**
A: Yes, you can update the committee assignment in the application detail view.

### Communications

**Q: Can I send bulk communications?**
A: Yes, you can select multiple recipients when sending communications. The system supports bulk email, SMS, and notifications.

**Q: How do I customize communication templates?**
A: Navigate to Communications > Templates, select a template, and click "Edit" to customize it. You can also create new templates.

### Reports

**Q: Can I export reports to Excel or PDF?**
A: Currently, reports are available in JSON format. PDF/Excel export functionality may be added in future updates.

**Q: How far back can I generate reports?**
A: Reports can be generated for any date range. There's no limit on historical data.

---

## Keyboard Shortcuts

- **Ctrl/Cmd + K**: Open search (if available)
- **Ctrl/Cmd + S**: Save (in forms)
- **Esc**: Close dialogs/modals
- **Tab**: Navigate between form fields
- **Enter**: Submit forms

---

## Best Practices

### Project Management
- Register projects as soon as they're proposed
- Keep project stages updated regularly
- Document all important decisions in project notes
- Upload all relevant documents promptly

### Grant Management
- Track grant allocations carefully
- Generate budget reports regularly
- Monitor funding status changes
- Keep grant documents organized

### Thesis Workflow
- Process thesis submissions promptly
- Schedule reviews in a timely manner
- Track all revisions carefully
- Maintain clear communication with students and supervisors

### Scholar Tracking
- Schedule regular advisory meetings
- Update progress records after each meeting
- Monitor attendance closely
- Create evaluations on schedule

### Ethics Committee
- Process ethics applications promptly
- Assign committees efficiently
- Maintain clear approval/rejection communication
- Keep approval logs updated

### Communications
- Use templates for consistency
- Send reminders in advance
- Keep communication logs for reference
- Personalize messages when needed

### Reports
- Generate reports regularly
- Review reports for insights
- Share reports with stakeholders
- Use reports for decision-making

---

## Support & Contact

### Getting Help

- **System Administrator**: Contact your school's system administrator for role/permission issues
- **IT Support**: Contact IT support for technical issues
- **Documentation**: Refer to this manual and other documentation files

### Reporting Issues

When reporting issues, please provide:
- Description of the issue
- Steps to reproduce
- Error messages (if any)
- Screenshots (if helpful)
- Browser and device information

---

## Appendix

### A. Glossary

- **Principal Investigator (PI)**: Lead researcher on a project
- **Co-Supervisor**: Secondary supervisor assisting the primary supervisor
- **Reviewer**: Staff member assigned to review research work
- **Scholar**: MPhil/PhD/PG student engaged in research
- **Ethics Committee**: Committee responsible for ethics approvals
- **FDP**: Faculty Development Program
- **DOI**: Digital Object Identifier for publications
- **Impact Factor**: Measure of journal importance

### B. Status Definitions

#### Project Status
- **Draft**: Project not yet submitted
- **Submitted**: Project submitted for approval
- **Approved**: Project approved and can proceed
- **Rejected**: Project rejected
- **Ongoing**: Project in progress
- **Completed**: Project completed
- **Cancelled**: Project cancelled

#### Thesis Status
- **Submitted**: Thesis submitted for review
- **Under Review**: Thesis being reviewed
- **Reviewed**: Review completed
- **Approved**: Thesis approved
- **Rejected**: Thesis rejected
- **Defended**: Defense completed
- **Accepted**: Thesis accepted

#### Grant Status
- **Open**: Grant accepting applications
- **Closed**: Grant no longer accepting applications
- **Awarded**: Grant awarded to recipient
- **Rejected**: Grant application rejected
- **Completed**: Grant period completed
- **Cancelled**: Grant cancelled

### C. Stage Definitions

- **Proposal**: Initial proposal stage
- **Ethics Approval**: Awaiting or received ethics approval
- **Ongoing**: Research in progress
- **Mid-term Review**: Mid-term review stage
- **Final Submission**: Final submission stage
- **Publication**: Publication stage
- **Completed**: Project completed

---

**Last Updated**: Complete user manual for Research Coordinator module

**Version**: 1.0

**Module Status**: Production Ready

