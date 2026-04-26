# Student Affairs Officer - User Manual

**Version**: 1.0  
**Last Updated**: 2024  
**Role**: Student Affairs Officer (Role ID: 35)

---

## Table of Contents

1. [Introduction](#introduction)
2. [Getting Started](#getting-started)
3. [Dashboard Overview](#dashboard-overview)
4. [Student Clubs & Organizations](#student-clubs--organizations)
5. [Events & Activities](#events--activities)
6. [Grievances & Complaints](#grievances--complaints)
7. [Counseling & Support](#counseling--support)
8. [Student Engagement & Leadership](#student-engagement--leadership)
9. [Anti-Ragging & Safety](#anti-ragging--safety)
10. [Communications](#communications)
11. [Reports & Analytics](#reports--analytics)
12. [Security & Compliance](#security--compliance)
13. [Troubleshooting](#troubleshooting)
14. [FAQs](#faqs)

---

## Introduction

### Role Overview

The Student Affairs Officer is responsible for managing student clubs, organizing events, handling grievances, coordinating counseling services, and tracking student engagement activities across the institution. This role ensures a vibrant campus life while maintaining safety and compliance standards.

### Key Responsibilities

- **Student Clubs Management**: Create, approve, and manage student clubs and organizations
- **Event Coordination**: Plan, approve, and track institutional events and activities
- **Grievance Management**: Handle student complaints, investigations, and resolutions
- **Counseling Coordination**: Manage counseling requests and track sessions
- **Student Engagement**: Oversee leadership programs, NSS/NCC, and volunteer activities
- **Anti-Ragging Compliance**: Manage undertakings, track incidents, and ensure compliance
- **Communications**: Send announcements, emails, and SMS to students and clubs
- **Reporting**: Generate analytics and reports on student affairs activities

### Access Requirements

- **Role**: Student Affairs Officer (Role ID: 35)
- **Permissions**: 200+ specific permissions for student affairs operations
- **Multi-Tenancy**: Access limited to your assigned school only
- **Access Restrictions**: 
  - ❌ No access to exam marks or results
  - ❌ No access to payroll or financial data
  - ❌ No access to confidential HR data

---

## Getting Started

### Logging In

1. Navigate to your school's login page: `https://your-domain.com/[school-code]/login`
2. Enter your credentials (username/email and password)
3. After successful authentication, you'll be redirected to the Student Affairs Officer dashboard

### Dashboard Access

The dashboard is accessible at:
```
/[school-code]/dashboard/student-affairs-officer
```

### First-Time Setup

1. **Review Permissions**: Ensure you have all necessary permissions assigned
2. **Familiarize with Navigation**: Explore all available modules and tabs
3. **Review Existing Clubs**: Check current student clubs and their status
4. **Review Pending Items**: Check for pending approvals, grievances, or requests
5. **Set Up Communication Templates**: Configure email/SMS templates for common communications

---

## Dashboard Overview

### Main Dashboard

The main dashboard provides a comprehensive overview of all student affairs operations:

#### Statistics Cards

- **Total Clubs**: Number of active student clubs
- **Total Events**: Number of events (upcoming, ongoing, completed)
- **Pending Grievances**: Grievances requiring attention
- **Active Counseling Sessions**: Ongoing counseling sessions

#### Navigation Tabs

The dashboard includes 9 main navigation tabs:

1. **Overview**: Dashboard statistics and recent activities
2. **Student Clubs**: Manage student clubs and organizations
3. **Events & Activities**: Plan and manage institutional events
4. **Grievances**: Handle student complaints and grievances
5. **Counseling & Support**: Coordinate counseling services
6. **Leadership Programs**: Manage engagement and leadership programs
7. **Anti-Ragging & Safety**: Track compliance and incidents
8. **Communications**: Send announcements and messages
9. **Reports & Analytics**: View analytics and generate reports

#### Recent Activities Feed

The dashboard displays recent activities such as:
- New club registrations
- Event approvals
- Grievance updates
- Counseling assignments
- Engagement program activities

---

## Student Clubs & Organizations

### Overview

Manage student clubs, societies, and organizations including tech clubs, arts clubs, sports teams, NSS, NCC, and more.

### Accessing Clubs

Navigate to: `/[school-code]/dashboard/student-affairs-officer/clubs`

### Creating a New Club

1. Click the **"Create Club"** button on the clubs list page
2. Fill in the club information:
   - **Club Name** (required): e.g., "Tech Club", "Arts Society"
   - **Club Code** (optional): Auto-generated if left empty
   - **Club Type** (required): Academic, Cultural, Sports, Technical, Arts, Social, NSS, NCC, or Other
   - **Description**: Purpose, activities, and goals
   - **Coordinator**: Staff member coordinating the club
   - **Faculty Advisor**: Staff member advising the club
   - **Status**: Pending, Active, Inactive, or Suspended
3. Click **"Create Club"** to save

### Approving Club Registrations

1. Navigate to the clubs list
2. Filter by status: **"Pending"**
3. Click on a pending club to view details
4. Review the club information
5. Click **"Approve"** to activate the club
6. Optionally add notes or conditions

### Managing Club Members

1. Navigate to a club's detail page
2. Click on the **"Members"** tab
3. To add a member:
   - Click **"Add Member"**
   - Enter the student ID
   - Select role (Member, President, Vice President, Secretary, Treasurer)
   - Click **"Add Member"**
4. To remove a member:
   - Click the trash icon next to the member
   - Confirm removal

### Managing Club Officers

1. Navigate to a club's detail page
2. Click on the **"Officers"** tab
3. To assign an officer:
   - Click **"Add Officer"**
   - Enter the student ID
   - Select position (President, Vice President, Secretary, Treasurer)
   - Click **"Assign"**
4. Officers can be updated or removed as needed

### Tracking Club Activities

1. Navigate to a club's detail page
2. Click on the **"Activities"** tab
3. View all recorded club activities
4. To add a new activity:
   - Click **"Add Activity"**
   - Enter activity name, type, date, location, and description
   - Record participant count
   - Click **"Save"**

### Uploading Club Documents

1. Navigate to a club's detail page
2. Click on the **"Documents"** tab
3. Click **"Upload Document"**
4. Select file (PDF, DOC, DOCX, JPG, PNG - max 10MB)
5. Enter document name
6. Select document type (Bylaws, Report, Photo, Other)
7. Click **"Upload"**

### Editing Club Information

1. Navigate to a club's detail page
2. Click **"Edit Club"**
3. Update any fields as needed
4. Click **"Update Club"** to save changes

---

## Events & Activities

### Overview

Plan, approve, and manage institutional events including orientations, workshops, festivals, competitions, and seminars.

### Accessing Events

Navigate to: `/[school-code]/dashboard/student-affairs-officer/events`

### Creating a New Event

1. Click the **"Create Event"** button
2. Fill in event information:
   - **Event Name** (required): e.g., "Annual Tech Fest 2024"
   - **Event Code** (optional): Auto-generated if left empty
   - **Event Type** (required): Orientation, Workshop, Festival, Competition, Seminar, Conference, Cultural, Sports, or Other
   - **Description**: Event details and activities
   - **Start Date & Time** (required)
   - **End Date & Time** (optional)
   - **Venue**: Location of the event
   - **Registration Required**: Toggle if participants need to register
   - **Registration Deadline**: If registration is required
   - **Max Participants**: Maximum number of participants
   - **Status**: Draft, Pending Approval, Approved, Ongoing, Completed, or Cancelled
3. Click **"Create Event"** to save

### Approving Events

1. Navigate to the events list
2. Filter by status: **"Pending"**
3. Click on a pending event to view details
4. Review event information
5. Click **"Approve Event"** to approve
6. Optionally reject with a reason

### Managing Event Registrations

1. Navigate to an event's detail page
2. Click on the **"Registrations"** tab
3. View all registered participants
4. To add a registration:
   - Click **"Add Registration"**
   - Enter student ID
   - Click **"Register"**
5. Export registrations list if needed

### Tracking Event Attendance

1. Navigate to an event's detail page
2. Click on the **"Attendance"** tab
3. View all attendance records
4. To mark attendance:
   - Click **"Mark Attendance"**
   - Enter student ID
   - Select method (Manual, QR Code, Biometric)
   - Click **"Mark Attendance"**
5. Use **"QR Scanner"** button for QR code scanning (when implemented)
6. Export attendance list if needed

### Uploading Event Documents

1. Navigate to an event's detail page
2. Click on the **"Documents"** tab
3. Click **"Upload Document"**
4. Select file (reports, photos, etc.)
5. Enter document name and type
6. Click **"Upload"**

---

## Grievances & Complaints

### Overview

Manage student grievance submissions, investigations, and resolutions while ensuring proper categorization and committee assignments.

### Accessing Grievances

Navigate to: `/[school-code]/dashboard/student-affairs-officer/grievances`

### Submitting a Grievance

1. Click the **"Submit Grievance"** button
2. Fill in grievance details:
   - **Title** (required): Brief description
   - **Category** (required): Academic, Administrative, Harassment, Misconduct, Facilities, Discrimination, or Other
   - **Subcategory** (optional): More specific classification
   - **Priority**: Low, Medium, High, or Urgent
   - **Description** (required): Detailed description of the grievance
   - **Anonymous Submission**: Toggle if submitting anonymously
   - **Student ID**: Required if not anonymous
3. Click **"Submit Grievance"**

### Managing Grievances

#### Viewing Grievance Details

1. Click on a grievance from the list
2. View complete grievance information:
   - Grievance code and status
   - Category and priority
   - Student information (if not anonymous)
   - Description
   - Assigned investigator/committee
   - Timeline (submitted, assigned, resolved)

#### Assigning Investigators

1. Navigate to a grievance detail page
2. If status is "Submitted", click **"Assign Investigator"**
3. Select staff member or committee
4. Add assignment notes
5. Click **"Assign"**

#### Adding Investigation Notes

1. Navigate to a grievance detail page
2. Click on the **"Investigation"** tab
3. Scroll to "Add Note" section
4. Enter investigation note
5. Select note type (Investigation, Meeting, Evidence, Decision)
6. Mark as confidential if needed
7. Click **"Add Note"**

#### Resolving Grievances

1. Navigate to a grievance detail page
2. Click on the **"Resolution"** tab
3. Click **"Resolve Grievance"**
4. Enter resolution summary
5. Describe actions taken
6. Upload resolution report if available
7. Click **"Submit Resolution"**

### Grievance Workflow

1. **Submitted** → Grievance is submitted by student
2. **Assigned** → Assigned to investigator or committee
3. **Under Investigation** → Investigation in progress
4. **Resolved** → Resolution report submitted
5. **Closed** → Grievance closed and notified

---

## Counseling & Support

### Overview

Coordinate counseling services, assign counselors, track sessions, and schedule follow-ups while maintaining student privacy.

### Accessing Counseling

Navigate to: `/[school-code]/dashboard/student-affairs-officer/counseling`

### Managing Counseling Requests

#### Viewing Requests

1. Navigate to the counseling requests list
2. View all requests with:
   - Student name
   - Request type
   - Priority
   - Status
   - Requested date

#### Viewing Request Details

1. Click on a request from the list
2. View complete information:
   - Request ID and status
   - Student information
   - Request type and priority
   - Initial concern
   - Assigned counselor
   - Timeline

#### Assigning Counselors

1. Navigate to a request detail page
2. If status is "Pending", click **"Assign Counselor"**
3. Enter counselor staff ID
4. Click **"Assign Counselor"**

### Managing Counseling Sessions

1. Navigate to a request detail page
2. Click on the **"Sessions"** tab
3. View all sessions for the request
4. To add a session:
   - Click **"Add Session"**
   - Enter session date, time, duration
   - Select session type (In-person, Online, Phone, Group)
   - Add location if applicable
   - Enter session notes (privacy-compliant)
   - Record outcome
   - Click **"Save Session"**

### Scheduling Follow-ups

1. Navigate to counseling follow-ups (via sessions or requests)
2. Click **"Schedule Follow-up"**
3. Select request and optional session
4. Enter follow-up date
5. Select type (Scheduled, Ad-hoc, Check-in)
6. Add notes
7. Click **"Schedule"**

---

## Student Engagement & Leadership

### Overview

Manage student ambassador programs, NSS/NCC participation, volunteer tracking, leadership training, and certificate issuance.

### Accessing Engagement Programs

Navigate to: `/[school-code]/dashboard/student-affairs-officer/engagement`

### Managing Leadership Programs

#### Creating a Program

1. Click **"Create Program"**
2. Fill in program details:
   - **Program Name** (required)
   - **Program Type**: Ambassador, NSS, NCC, Volunteer, Training, or Other
   - **Description**: Program details
   - **Start Date** and **End Date**
   - **Coordinator**: Staff member coordinating
   - **Status**: Active, Completed, or Cancelled
3. Click **"Create Program"**

#### Viewing Program Details

1. Click on a program from the list
2. View program information:
   - Program details and description
   - Coordinator information
   - Participant count
   - Duration

#### Managing Participations

1. Navigate to a program detail page
2. Click on the **"Participations"** tab
3. View all participants
4. To add a participant:
   - Click **"Add Participant"**
   - Enter student ID
   - Select role (Participant, Leader, Coordinator, Volunteer)
   - Click **"Add Participant"**
5. Track hours logged and achievements

#### Issuing Certificates

1. Navigate to a program detail page
2. Click on the **"Certificates"** tab
3. View issued certificates
4. To issue a certificate:
   - Click **"Issue Certificate"**
   - Select student
   - Enter certificate name
   - Select certificate type
   - Click **"Issue"**

---

## Anti-Ragging & Safety

### Overview

Manage anti-ragging undertakings, track incidents, and ensure compliance with safety regulations.

### Accessing Anti-Ragging

Navigate to: `/[school-code]/dashboard/student-affairs-officer/antiragging`

### Managing Undertakings

#### Recording Undertakings

1. Click **"Record Undertaking"**
2. Fill in details:
   - **Student ID** (required)
   - **Academic Year** (required)
   - **Semester** (optional)
   - **Undertaking Date** (required)
   - **Signed by Student**: Check if signed
   - **Signed by Parent**: Check if signed
   - **Notes**: Additional information
3. Click **"Save"**

#### Viewing Undertaking Details

1. Click on an undertaking from the list
2. View complete information:
   - Student information
   - Academic year and semester
   - Signature status
   - Verification status
   - Verified by and date

#### Verifying Undertakings

1. Navigate to an undertaking detail page
2. If status is "Pending", click **"Verify Undertaking"**
3. Review all information
4. Confirm verification
5. Add verification notes if needed
6. Click **"Verify"**

### Managing Incidents

#### Reporting Incidents

1. Click **"Report Incident"**
2. Fill in incident details:
   - **Incident Date** (required)
   - **Incident Time** (optional)
   - **Location** (optional)
   - **Description** (required)
   - **Severity**: Low, Medium, High, or Critical
   - **Reported By**: Student or staff information
   - **Anonymous**: Toggle if anonymous
3. Click **"Report Incident"**

#### Tracking Incidents

1. View all incidents in the incidents tab
2. Filter by status or severity
3. Click on an incident to view details
4. Assign to committee or staff member
5. Track investigation progress
6. Record resolution and actions taken

---

## Communications

### Overview

Send announcements, emails, and SMS to students, staff, clubs, or all users. Manage communication templates and track delivery.

### Accessing Communications

Navigate to: `/[school-code]/dashboard/student-affairs-officer/communications`

### Managing Templates

#### Creating Templates

1. Click **"Create Template"**
2. Fill in template details:
   - **Template Name** (required)
   - **Template Type**: Email, SMS, or Announcement
   - **Category**: Event, Grievance, Counseling, Club, Anti-Ragging, or Other
   - **Subject**: For email templates
   - **Body Content**: Message content with variables
   - **Variables**: Define dynamic fields (e.g., {student_name}, {event_name})
   - **Active**: Toggle to enable/disable
3. Click **"Create Template"**

#### Using Templates

1. Navigate to **"Send Communication"**
2. Select communication type (Email, SMS, Announcement)
3. Optionally select a template
4. If template selected, content will be pre-filled
5. Customize content as needed
6. Add recipients
7. Click **"Send"**

### Sending Communications

#### Composing a Message

1. Navigate to **"Send Communication"**
2. Select **Communication Type**:
   - **Email**: For detailed messages with subject
   - **SMS**: For short text messages
   - **Announcement**: For general announcements
3. Optionally select a **Template**
4. Enter **Subject** (for emails)
5. Enter **Message Content**
6. Add **Recipients**:
   - Click **"Add Recipient"**
   - Select recipient type (Student, Staff, Club, All)
   - Enter ID or email/phone
   - Repeat for multiple recipients
7. Click **"Send [Type]"**

#### Recipient Types

- **Student**: Send to specific student by ID or email
- **Staff**: Send to specific staff member by ID or email
- **Club**: Send to all members of a club
- **All**: Send to all students/staff (use with caution)

### Viewing Communication Logs

1. Navigate to the **"Communication Logs"** tab
2. View all sent communications:
   - Communication type
   - Recipient information
   - Subject/content preview
   - Status (Sent, Failed, Pending)
   - Sent date and time
3. Filter by type, status, or date range
4. Search for specific communications

---

## Reports & Analytics

### Overview

Generate comprehensive reports and view analytics on clubs, events, grievances, counseling, engagement, and compliance.

### Accessing Reports

Navigate to: `/[school_code]/dashboard/student-affairs-officer/reports`

### Dashboard Overview

The reports dashboard provides:

#### KPI Cards

- **Total Clubs**: Number of active clubs
- **Total Events**: Events in the selected period
- **Pending Grievances**: Grievances requiring attention
- **Active Counseling**: Ongoing counseling sessions

#### Time Range Selection

- **Last 7 days**: Recent activity
- **Last 30 days**: Monthly view
- **Last 90 days**: Quarterly view
- **Last year**: Annual view

### Analytics Tabs

#### Overview Analytics

- **Activity Trends**: Overall activity over time
- **Distribution by Category**: Breakdown of activities

#### Club Analytics

- Club membership trends
- Activity participation metrics
- Club performance analytics
- Department-wise participation

#### Event Analytics

- Attendance trends
- Registration patterns
- Event popularity metrics
- Participation by department/year

#### Grievance Analytics

- Grievance type distribution
- Average resolution times
- Committee performance metrics
- Resolution rate analytics

#### Counseling Analytics

- Request type trends
- Session statistics
- Counselor workload
- Outcome tracking

#### Engagement Analytics

- Program participation rates
- Volunteer hours tracking
- Certificate issuance statistics
- Department-wise participation

### Exporting Reports

1. Navigate to any analytics tab
2. Click **"Export"** button
3. Select export format (CSV, PDF, Excel)
4. Choose date range
5. Click **"Download"**

---

## Security & Compliance

### Access Control

- **Multi-Tenant Isolation**: All data is automatically filtered by your school
- **RBAC Enforcement**: All actions require appropriate permissions
- **Session-Based Authentication**: Secure session management
- **Rate Limiting**: API abuse prevention

### Data Privacy

- **Student Information**: Private information is masked in counseling/grievances
- **Anonymous Submissions**: Support for anonymous grievance submissions
- **Confidential Notes**: Investigation notes can be marked as confidential

### Access Restrictions

The Student Affairs Officer **CANNOT**:
- ❌ View or modify exam marks or results
- ❌ Access payroll or financial data
- ❌ Modify fee data or invoices
- ❌ Access confidential HR data
- ❌ Access institution-wide academic configuration
- ❌ Escalate to dean, HOD, or controller-of-examinations without authorization

### Audit Logging

All actions are logged including:
- User who performed the action
- Timestamp
- Action type
- Entity affected
- School context

---

## Troubleshooting

### Common Issues

#### Cannot Access Dashboard

**Problem**: Redirected to unauthorized page

**Solutions**:
1. Verify your role is "student-affairs-officer" (Role ID: 35)
2. Check that you have the required permissions assigned
3. Ensure you're accessing the correct school code
4. Contact system administrator if issue persists

#### Cannot Create/Edit Clubs

**Problem**: "Insufficient permissions" error

**Solutions**:
1. Verify you have `club:create` or `club:update` permissions
2. Check that the club belongs to your school
3. Ensure you're logged in with the correct account

#### File Upload Fails

**Problem**: Document upload fails

**Solutions**:
1. Check file size (must be less than 10MB)
2. Verify file type is allowed (PDF, DOC, DOCX, JPG, PNG)
3. Check internet connection
4. Try again after a few moments
5. Contact support if issue persists

#### Cannot Send Communications

**Problem**: Communication sending fails

**Solutions**:
1. Verify you have `email:send` or `sms:send` permissions
2. Check recipient information is correct
3. Ensure content is not empty
4. Verify at least one recipient is added
5. Check communication service configuration

#### Grievance Cannot Be Resolved

**Problem**: Cannot submit resolution

**Solutions**:
1. Verify grievance status allows resolution
2. Ensure resolution summary is provided
3. Check you have `grievance:resolution:write` permission
4. Verify grievance belongs to your school

### Getting Help

- **Technical Support**: Contact your IT administrator
- **Permission Issues**: Contact your school administrator
- **Feature Requests**: Submit through your school's feedback system

---

## FAQs

### General Questions

**Q: Can I access data from other schools?**  
A: No. All data is automatically filtered by your school. You can only access data from your assigned school.

**Q: Can I modify exam marks or results?**  
A: No. The Student Affairs Officer role does not have access to academic results or exam marks.

**Q: How do I approve a club registration?**  
A: Navigate to the club's detail page and click the "Approve" button. You can also approve from the clubs list by filtering for pending clubs.

**Q: Can students submit grievances anonymously?**  
A: Yes, if enabled for your school. When creating a grievance, toggle "Anonymous Submission" to submit without providing student ID.

**Q: How do I track event attendance?**  
A: Navigate to the event's detail page, click the "Attendance" tab, and use "Mark Attendance" to record attendance manually, via QR code, or biometric.

**Q: Can I send bulk communications?**  
A: Yes, you can add multiple recipients or select "All" to send to all students/staff. Use templates for efficiency.

**Q: How do I generate reports?**  
A: Navigate to Reports & Analytics, select the desired analytics tab, choose your time range, and click "Export" to download reports.

**Q: What file types can I upload?**  
A: Supported formats include PDF, DOC, DOCX, JPG, JPEG, and PNG. Maximum file size is 10MB.

**Q: How do I assign a counselor to a request?**  
A: Navigate to the counseling request detail page, click "Assign Counselor", enter the counselor's staff ID, and click "Assign".

**Q: Can I edit a grievance after submission?**  
A: Yes, if you have `grievance:update` permissions. Navigate to the grievance detail page and click "Edit".

---

## Quick Reference

### Navigation Paths

- **Dashboard**: `/[school-code]/dashboard/student-affairs-officer`
- **Clubs**: `/[school-code]/dashboard/student-affairs-officer/clubs`
- **Events**: `/[school-code]/dashboard/student-affairs-officer/events`
- **Grievances**: `/[school-code]/dashboard/student-affairs-officer/grievances`
- **Counseling**: `/[school-code]/dashboard/student-affairs-officer/counseling`
- **Engagement**: `/[school-code]/dashboard/student-affairs-officer/engagement`
- **Anti-Ragging**: `/[school-code]/dashboard/student-affairs-officer/antiragging`
- **Communications**: `/[school-code]/dashboard/student-affairs-officer/communications`
- **Reports**: `/[school-code]/dashboard/student-affairs-officer/reports`

### Common Actions

- **Create Club**: Clubs → Create Club
- **Approve Event**: Events → Event Detail → Approve
- **Submit Grievance**: Grievances → Submit Grievance
- **Assign Counselor**: Counseling → Request Detail → Assign Counselor
- **Send Communication**: Communications → Send Communication
- **View Analytics**: Reports → Analytics

### Keyboard Shortcuts

- **Search**: Press `/` to focus search box
- **Navigate**: Use arrow keys in tables
- **Close Dialog**: Press `Esc`

---

## Support & Contact

For technical support or questions:
- Contact your school's IT administrator
- Refer to the SlateSMS documentation
- Check the troubleshooting section above

---

**Document Version**: 1.0  
**Last Updated**: 2024  
**Maintained By**: SlateSMS Development Team

