# Program Coordinator - User Manual

**Version**: 1.0  
**Last Updated**: 2025-01-XX  
**Role**: Program Coordinator (Role ID: 33)

---

## Table of Contents

1. [Introduction](#introduction)
2. [Getting Started](#getting-started)
3. [Dashboard Overview](#dashboard-overview)
4. [Program Management](#program-management)
5. [Curriculum Management](#curriculum-management)
6. [Course Planning & Allocation](#course-planning--allocation)
7. [Faculty Allocation](#faculty-allocation)
8. [Timetable Coordination](#timetable-coordination)
9. [Student Progress & Advising](#student-progress--advising)
10. [Syllabus & Lesson Plan Tracking](#syllabus--lesson-plan-tracking)
11. [Academic Events & Training](#academic-events--training)
12. [Communications](#communications)
13. [Reports & Analytics](#reports--analytics)
14. [Document Generation](#document-generation)
15. [Settings](#settings)
16. [Security & Compliance](#security--compliance)
17. [Troubleshooting](#troubleshooting)
18. [FAQs](#faqs)

---

## Introduction

### Role Overview

The Program Coordinator is responsible for the execution of academic programs, curriculum planning, course allocation, faculty coordination, student advising, and academic quality at the program level. This role provides program-specific management capabilities while maintaining appropriate access boundaries and multi-tenant security.

### Key Responsibilities

- **Program Management**: Create and manage academic programs, update program structure, and track implementation progress
- **Curriculum Planning**: Manage curriculum versions, map courses to programs, and track curriculum implementation
- **Course Planning**: Create semester-wise course offerings, manage prerequisites, and assign faculty
- **Faculty Coordination**: Allocate faculty to courses, monitor workload, and coordinate schedules
- **Student Advising**: Monitor student progression, identify at-risk students, and provide academic advising
- **Syllabus Tracking**: Monitor syllabus coverage, verify lesson plan completion, and notify faculty
- **Event Coordination**: Coordinate academic events, nominate participants for training, and track attendance
- **Communication**: Send bulk emails/SMS to students and faculty, manage templates, and view communication logs
- **Reporting**: Generate program reports, analyze enrollment, completion rates, and accreditation readiness

### Access Requirements

- **Role**: Program Coordinator (Role ID: 33)
- **Permissions**: 200+ specific permissions for program coordinator operations
- **Multi-Tenancy**: Access limited to your assigned school only
- **Program Scope**: Access limited to programs explicitly assigned to you

### Important Restrictions

⚠️ **Critical Security Restrictions**:
- **NO** modification of student marks or exam results
- **NO** access to payroll or financial information
- **NO** modification of institution-wide settings
- **NO** access to programs not assigned to you
- **NO** cross-tenant data access

---

## Getting Started

### Logging In

1. Navigate to your school's login page: `https://your-domain.com/[school-code]/login`
2. Enter your credentials (username/email and password)
3. After successful authentication, you'll be redirected to the Program Coordinator dashboard

### Dashboard Access

The dashboard is accessible at:
```
/[school-code]/dashboard/program-coordinator
```

### First-Time Setup

1. **Review Assigned Programs**: Check which programs have been assigned to you
2. **Familiarize with Navigation**: Explore all available modules and tabs
3. **Review Program Structure**: Understand the programs under your coordination
4. **Set Up Communication Templates**: Configure email/SMS templates for common communications
5. **Review Current Curriculum**: Check active curriculum versions for your programs
6. **Verify Faculty Assignments**: Review current faculty allocations

---

## Dashboard Overview

### Main Dashboard

The main dashboard provides a comprehensive overview of all program coordinator operations:

#### Statistics Cards

- **Total Programs**: Number of programs assigned to you
- **Total Students**: Total student population across your programs
- **Active Courses**: Number of active course offerings in current semester
- **Syllabus Coverage**: Average syllabus coverage percentage across courses
- **Student Progression**: Overall student progression rate
- **Upcoming Events**: Number of scheduled academic events
- **Pending Approvals**: Approval requests awaiting your action
- **Faculty Count**: Number of faculty members allocated to your programs

#### Navigation Tabs

The dashboard includes 10 main tabs:

1. **Overview**: Dashboard summary and key metrics
2. **Programs**: Program management and structure
3. **Curriculum**: Curriculum structures and course mappings
4. **Course Planning**: Course offerings and prerequisites
5. **Timetables**: Program-specific timetable coordination
6. **Faculty Allocation**: Faculty assignments and workload
7. **Progress & Advising**: Student progression and advising
8. **Events**: Academic events and training nominations
9. **Communications**: Email, SMS, and announcements
10. **Reports**: Program reports and analytics

#### Recent Activities

The dashboard displays recent activities including:
- Program updates
- Curriculum changes
- Course offering creations
- Faculty allocations
- Student progression notes
- Communication sent
- Event coordination
- System updates

---

## Program Management

### Viewing Programs

**Location**: Dashboard → Programs Tab

#### Accessing Programs

1. Navigate to the **Programs** tab on the main dashboard
2. Or access directly: `/[school-code]/dashboard/program-coordinator/programs`

#### Program List View

The programs page displays:
- **Program Code**: Unique identifier for the program
- **Program Name**: Full name of the program
- **Student Count**: Number of enrolled students
- **Course Count**: Number of courses in the program
- **Completion Rate**: Overall program completion percentage
- **Status**: Active, Inactive, or Archived

#### Filtering Programs

- **Search**: Use the search bar to filter by program name or code
- **Status Filter**: Filter by Active, Inactive, or All statuses
- **Sort**: Click column headers to sort by name, code, or student count

### Creating a New Program

**Note**: Program creation may require approval from Dean or School Admin depending on your institution's policies.

1. Click the **"New Program"** button
2. Fill in the program details:
   - **Program Code**: Unique code (e.g., "BSC-CS")
   - **Program Name**: Full name (e.g., "Bachelor of Science in Computer Science")
   - **Department**: Select department (if applicable)
   - **Degree Type**: Bachelor, Master, Diploma, etc.
   - **Duration**: Number of years
   - **Total Credits**: Total credit hours required
   - **Description**: Program overview
   - **Objectives**: Learning objectives
   - **Learning Outcomes**: Expected outcomes
   - **Admission Requirements**: Prerequisites for admission
   - **Start Date**: Program start date
   - **Accreditation Status**: Current accreditation status
3. Click **"Create Program"**
4. The program will be created and assigned to you as coordinator

### Editing a Program

1. Click on a program from the list
2. Click the **"Edit"** button
3. Update program details
4. Click **"Save Changes"**

**Note**: Some fields may be restricted based on your permissions.

### Viewing Program Details

1. Click on a program from the list
2. View detailed information:
   - **Program Information**: All program details
   - **Curriculum Versions**: Active and archived curriculum versions
   - **Course Offerings**: Current and past course offerings
   - **Student Enrollment**: Enrollment statistics
   - **Faculty Assignments**: Assigned faculty members
   - **Recent Activities**: Program-related activities

### Program Requirements

#### Managing Program Requirements

1. Navigate to a program's detail page
2. Go to the **"Requirements"** section
3. Add or edit requirements:
   - **Credit Requirements**: Minimum credits per semester/year
   - **Course Requirements**: Mandatory courses
   - **GPA Requirements**: Minimum GPA for progression
   - **Attendance Requirements**: Minimum attendance percentage

---

## Curriculum Management

### Viewing Curriculum Structures

**Location**: Dashboard → Curriculum Tab

#### Accessing Curriculum

1. Navigate to the **Curriculum** tab on the main dashboard
2. Or access directly: `/[school-code]/dashboard/program-coordinator/curriculum`

#### Curriculum List View

The curriculum page displays:
- **Program**: Associated program name
- **Version**: Curriculum version (e.g., "2024-25")
- **Academic Year**: Academic year
- **Total Semesters**: Number of semesters
- **Total Credits**: Total credit hours
- **Status**: Draft, Active, or Archived
- **Implementation Date**: When the curriculum becomes active

#### Filtering Curriculum

- **Search**: Filter by version, program name, or academic year
- **Status Filter**: Filter by Draft, Active, Archived, or All
- **Program Filter**: Filter by specific program

### Creating a New Curriculum

1. Click the **"New Curriculum"** button
2. Fill in the curriculum details:
   - **Program**: Select the program
   - **Version**: Enter version (e.g., "2024-25")
   - **Academic Year**: Enter academic year (e.g., "2024-2025")
   - **Total Semesters**: Number of semesters
   - **Total Credits**: Total credit hours
   - **Structure Data**: JSON structure for flexible curriculum design
   - **Implementation Date**: When this curriculum becomes active
   - **Notes**: Additional notes
3. Click **"Create Curriculum"**
4. The curriculum will be created in "Draft" status

### Managing Curriculum Versions

#### Activating a Curriculum

1. Navigate to a curriculum's detail page
2. If status is "Draft", click **"Submit for Approval"**
3. Once approved, click **"Activate"** to make it the active curriculum
4. Previous active curriculum will be automatically archived

#### Archiving a Curriculum

1. Navigate to a curriculum's detail page
2. Click **"Archive"** button
3. Confirm the action
4. Archived curriculum cannot be modified but can be viewed

### Course Mappings

#### Mapping Courses to Curriculum

1. Navigate to a curriculum's detail page
2. Go to the **"Course Mappings"** section
3. Click **"Add Course Mapping"**
4. Fill in the mapping details:
   - **Course**: Select the course
   - **Semester**: Semester number (1-8)
   - **Is Core**: Whether it's a core course
   - **Credits**: Credit hours for this course
   - **Notes**: Additional notes
5. Click **"Add Mapping"**

#### Editing Course Mappings

1. Find the course mapping in the list
2. Click **"Edit"**
3. Update the mapping details
4. Click **"Save Changes"**

#### Removing Course Mappings

1. Find the course mapping in the list
2. Click **"Delete"**
3. Confirm the action

### Curriculum Implementation Tracking

#### Tracking Implementation Progress

1. Navigate to a curriculum's detail page
2. View the **"Implementation Progress"** section
3. Monitor:
   - **Courses Implemented**: Number of courses currently offered
   - **Completion Percentage**: Overall implementation progress
   - **Semester-wise Progress**: Progress per semester
   - **Pending Actions**: Courses not yet implemented

---

## Course Planning & Allocation

### Viewing Course Offerings

**Location**: Dashboard → Course Planning Tab

#### Accessing Course Offerings

1. Navigate to the **Course Planning** tab on the main dashboard
2. Or access directly: `/[school-code]/dashboard/program-coordinator/course-planning`

#### Course Offerings List View

The course offerings page displays:
- **Course Code**: Course identifier
- **Course Name**: Full course name
- **Program**: Associated program
- **Semester**: Semester number
- **Academic Year**: Academic year
- **Section**: Section identifier (if applicable)
- **Faculty**: Assigned faculty member
- **Enrolled Students**: Number of enrolled students
- **Status**: Scheduled, Ongoing, Completed, or Cancelled

#### Filtering Course Offerings

- **Search**: Filter by course name or code
- **Program Filter**: Filter by specific program
- **Semester Filter**: Filter by semester
- **Academic Year Filter**: Filter by academic year
- **Status Filter**: Filter by status

### Creating a Course Offering

1. Click the **"New Course Offering"** button
2. Fill in the offering details:
   - **Program**: Select the program
   - **Course**: Select the course
   - **Semester**: Select semester
   - **Academic Year**: Enter academic year
   - **Section**: Enter section (optional)
   - **Max Students**: Maximum enrollment capacity
   - **Faculty**: Select assigned faculty (optional, can assign later)
   - **Classroom Location**: Room number or location
   - **Time Slot**: Class timing
   - **Day of Week**: Day(s) of the week
   - **Start Date**: Course start date
   - **End Date**: Course end date
   - **Notes**: Additional notes
3. Click **"Create Offering"**

### Managing Course Prerequisites

#### Viewing Prerequisites

1. Navigate to a course's detail page
2. Go to the **"Prerequisites"** section
3. View all prerequisite courses

#### Adding Prerequisites

1. Navigate to a course's detail page
2. Go to the **"Prerequisites"** section
3. Click **"Add Prerequisite"**
4. Fill in the details:
   - **Prerequisite Course**: Select the prerequisite course
   - **Is Mandatory**: Whether it's mandatory or optional
   - **Minimum Grade**: Minimum grade required (if applicable)
   - **Notes**: Additional notes
5. Click **"Add Prerequisite"**

#### Removing Prerequisites

1. Find the prerequisite in the list
2. Click **"Delete"**
3. Confirm the action

### Reviewing Syllabus Submissions

**Note**: Syllabus review permissions may vary by institution.

1. Navigate to the **Course Planning** tab
2. Go to the **"Syllabus Submissions"** section
3. View pending syllabus submissions:
   - **Course**: Course name
   - **Faculty**: Submitting faculty member
   - **Submission Date**: When it was submitted
   - **Status**: Pending, Approved, or Rejected
4. Click on a submission to review
5. Review the syllabus content
6. Click **"Approve"** or **"Request Changes"** (if permitted)

---

## Faculty Allocation

### Viewing Faculty Allocations

**Location**: Dashboard → Faculty Allocation Tab

#### Accessing Faculty Allocations

1. Navigate to the **Faculty Allocation** tab on the main dashboard
2. Or access directly: `/[school-code]/dashboard/program-coordinator/faculty-allocation`

#### Faculty Allocations List View

The faculty allocations page displays:
- **Faculty Name**: Faculty member name
- **Course**: Course name and code
- **Program**: Associated program
- **Allocation Type**: Primary, Co-instructor, or Teaching Assistant
- **Workload Hours**: Estimated hours per week
- **Start Date**: Allocation start date
- **End Date**: Allocation end date
- **Status**: Active, Completed, or Cancelled

#### Filtering Allocations

- **Search**: Filter by faculty name or course name
- **Program Filter**: Filter by specific program
- **Status Filter**: Filter by allocation status

### Assigning Faculty to Courses

1. Click the **"New Allocation"** button
2. Fill in the allocation details:
   - **Program**: Select the program
   - **Course Offering**: Select the course offering
   - **Faculty**: Select the faculty member
   - **Allocation Type**: Primary, Co-instructor, or Teaching Assistant
   - **Workload Hours**: Estimated hours per week
   - **Start Date**: Allocation start date
   - **End Date**: Allocation end date
   - **Notes**: Additional notes
3. Click **"Create Allocation"**

**Note**: The system will check for schedule conflicts automatically.

### Viewing Faculty Workload

#### Workload Overview

1. Navigate to the **Faculty Allocation** tab
2. View the **"Faculty Workload"** section
3. See workload distribution:
   - **Faculty Name**: Faculty member
   - **Total Courses**: Number of courses assigned
   - **Total Hours**: Total workload hours per week
   - **Workload Status**: High, Medium, or Low

#### Workload Details

1. Click on a faculty member's name
2. View detailed workload:
   - **Course List**: All assigned courses
   - **Weekly Schedule**: Time distribution
   - **Workload Breakdown**: Hours per course
   - **Conflict Warnings**: Any schedule conflicts

### Managing Allocations

#### Editing an Allocation

1. Find the allocation in the list
2. Click **"Edit"**
3. Update allocation details
4. Click **"Save Changes"**

#### Cancelling an Allocation

1. Find the allocation in the list
2. Click **"Cancel"**
3. Confirm the action
4. Provide reason for cancellation (optional)

---

## Timetable Coordination

### Viewing Timetables

**Location**: Dashboard → Timetables Tab

#### Accessing Timetables

1. Navigate to the **Timetables** tab on the main dashboard
2. Or access directly: `/[school-code]/dashboard/program-coordinator/timetables`

#### Timetable View

The timetable page displays:
- **Program-specific Timetable**: All courses for your programs
- **Time Slots**: Day and time for each course
- **Classroom Locations**: Room assignments
- **Faculty Assignments**: Assigned faculty members
- **Conflict Indicators**: Visual warnings for schedule conflicts

#### Filtering Timetables

- **Program Filter**: Filter by specific program
- **Semester Filter**: Filter by semester
- **Academic Year Filter**: Filter by academic year

### Updating Time Slots

**Note**: Time slot modification permissions may vary by institution.

1. Navigate to a course offering's detail page
2. Click **"Edit Time Slot"**
3. Update:
   - **Time Slot**: Class timing
   - **Day of Week**: Day(s) of the week
   - **Classroom Location**: Room assignment
4. Click **"Save Changes"**

**Note**: The system will check for conflicts before saving.

### Managing Schedule Conflicts

#### Viewing Conflicts

1. Navigate to the **Timetables** tab
2. View the **"Conflict Warnings"** section
3. Conflicts are highlighted in red

#### Resolving Conflicts

1. Click on a conflict warning
2. View conflict details:
   - **Faculty**: Faculty member with conflict
   - **Conflicting Courses**: Courses with overlapping times
   - **Time Overlap**: Overlapping time slots
3. Resolve by:
   - **Changing Time Slot**: Update one of the conflicting courses
   - **Reassigning Faculty**: Assign different faculty to one course
   - **Changing Classroom**: Move one course to a different room

### Classroom Allocation Requests

#### Requesting Classroom Allocation

1. Navigate to a course offering's detail page
2. Click **"Request Classroom"**
3. Fill in the request:
   - **Preferred Room**: Preferred classroom
   - **Required Capacity**: Minimum student capacity
   - **Special Requirements**: Lab equipment, projectors, etc.
   - **Preferred Time**: Preferred time slot
4. Click **"Submit Request"**

#### Viewing Allocation Status

1. Navigate to the **Timetables** tab
2. Go to **"Classroom Requests"** section
3. View request status:
   - **Pending**: Awaiting approval
   - **Approved**: Request approved
   - **Rejected**: Request rejected (with reason)

---

## Student Progress & Advising

### Viewing Student Lists

**Location**: Dashboard → Progress & Advising Tab

#### Accessing Student Progress

1. Navigate to the **Progress & Advising** tab on the main dashboard
2. Or access directly: `/[school-code]/dashboard/program-coordinator/progress-advising`

#### Student List View

The student progress page displays:
- **Student Name**: Student full name
- **Student ID**: Unique identifier
- **Program**: Enrolled program
- **Semester**: Current semester
- **GPA**: Current GPA
- **Attendance**: Attendance percentage
- **Status**: Active, At-Risk, or On-Probation

#### Filtering Students

- **Search**: Filter by student name or ID
- **Program Filter**: Filter by specific program
- **Status Filter**: Filter by student status

### Viewing Student Details

1. Click on a student's name
2. View detailed information:
   - **Academic Performance**: Grades, GPA, credits
   - **Attendance**: Attendance records
   - **Course Enrollment**: Current and past courses
   - **Progression Notes**: Notes from coordinators
   - **Advising Records**: Academic advising history

### Identifying At-Risk Students

#### At-Risk Indicators

Students are flagged as "At-Risk" if they have:
- **Low GPA**: Below minimum threshold
- **Poor Attendance**: Below required percentage
- **Failed Courses**: Multiple course failures
- **Academic Warnings**: Previous warnings

#### Viewing At-Risk Students

1. Navigate to the **Progress & Advising** tab
2. Go to **"At-Risk Students"** section
3. View list of at-risk students with:
   - **Risk Level**: High, Medium, or Low
   - **Risk Factors**: Reasons for at-risk status
   - **Last Intervention**: Date of last intervention

### Creating Progression Notes

1. Navigate to a student's detail page
2. Go to **"Progression Notes"** section
3. Click **"Add Note"**
4. Fill in the note:
   - **Note Type**: General, Academic, Advising, or Intervention
   - **Title**: Note title
   - **Content**: Note content
   - **Action Items**: Required actions
   - **Follow-up Date**: Date for follow-up
5. Click **"Save Note"**

### Academic Advising

#### Creating Advising Records

1. Navigate to a student's detail page
2. Go to **"Advising Records"** section
3. Click **"New Advising Session"**
4. Fill in the record:
   - **Date**: Session date
   - **Topics Discussed**: Discussion topics
   - **Recommendations**: Recommendations given
   - **Action Items**: Follow-up actions
   - **Next Meeting**: Scheduled next meeting date
5. Click **"Save Record"**

### Approving Semester Registration

**Note**: This feature may be optional per institution.

1. Navigate to the **Progress & Advising** tab
2. Go to **"Registration Approvals"** section
3. View pending registrations:
   - **Student**: Student name
   - **Semester**: Registration semester
   - **Courses**: Requested courses
   - **Status**: Pending approval
4. Review the registration
5. Click **"Approve"** or **"Reject"** (with reason)

### Monitoring Student Progression

#### Progression Dashboard

1. Navigate to the **Progress & Advising** tab
2. View the **"Progression Overview"** section
3. See metrics:
   - **Overall Progression Rate**: Percentage of students progressing
   - **Semester-wise Progression**: Progression by semester
   - **Program-wise Progression**: Progression by program
   - **Trend Analysis**: Progression trends over time

---

## Syllabus & Lesson Plan Tracking

### Monitoring Syllabus Coverage

**Location**: Dashboard → Overview Tab → Syllabus Coverage Section

#### Viewing Syllabus Coverage

1. Navigate to the **Overview** tab
2. View the **"Syllabus Coverage"** card
3. See average coverage percentage across all courses

#### Detailed Coverage View

1. Navigate to a course offering's detail page
2. Go to **"Syllabus Progress"** section
3. View:
   - **Total Topics**: Number of topics in syllabus
   - **Completed Topics**: Topics covered
   - **Coverage Percentage**: Percentage completed
   - **Status**: In Progress, Completed, or Delayed

### Viewing Lesson Plan Submissions

1. Navigate to the **Course Planning** tab
2. Go to **"Lesson Plans"** section
3. View lesson plan submissions:
   - **Course**: Course name
   - **Faculty**: Submitting faculty
   - **Semester**: Semester
   - **Submission Date**: When submitted
   - **Status**: Submitted, Reviewed, or Approved

### Verifying Completion Rates

1. Navigate to a course offering's detail page
2. Go to **"Lesson Plan Progress"** section
3. View completion metrics:
   - **Total Topics**: Total topics planned
   - **Completed Topics**: Topics completed
   - **Completion Rate**: Percentage completed
   - **Last Updated**: Last update date

### Notifying Faculty for Pending Items

1. Navigate to the **Course Planning** tab
2. Go to **"Pending Items"** section
3. View pending items:
   - **Faculty**: Faculty member
   - **Course**: Course name
   - **Pending Item**: Type of pending item (syllabus, lesson plan, etc.)
   - **Due Date**: Due date
4. Click **"Send Reminder"** to notify faculty
5. Select notification method: Email, SMS, or Both

---

## Academic Events & Training

### Viewing Events

**Location**: Dashboard → Events Tab

#### Accessing Events

1. Navigate to the **Events** tab on the main dashboard
2. Or access directly: `/[school-code]/dashboard/program-coordinator/events`

#### Events List View

The events page displays:
- **Event Name**: Event title
- **Event Type**: Workshop, Seminar, Orientation, Training, Meeting
- **Program**: Associated program
- **Event Date**: Scheduled date
- **Location**: Event location
- **Coordinator**: Event coordinator
- **Registered Participants**: Number of registered participants
- **Status**: Scheduled, Ongoing, Completed, or Cancelled

#### Filtering Events

- **Search**: Filter by event name
- **Program Filter**: Filter by specific program
- **Status Filter**: Filter by event status
- **Type Filter**: Filter by event type

### Creating an Event

1. Click the **"New Event"** button
2. Fill in the event details:
   - **Event Name**: Event title
   - **Event Type**: Select type
   - **Program**: Select associated program
   - **Description**: Event description
   - **Event Date**: Scheduled date
   - **Event Time**: Scheduled time
   - **Location**: Event location
   - **Max Participants**: Maximum capacity
   - **Notes**: Additional notes
3. Click **"Create Event"**

### Managing Event Participants

#### Viewing Participants

1. Navigate to an event's detail page
2. Go to **"Participants"** section
3. View registered participants:
   - **Name**: Participant name
   - **Type**: Faculty or Student
   - **Registration Date**: When registered
   - **Status**: Registered, Attended, or Absent

#### Adding Participants

1. Navigate to an event's detail page
2. Go to **"Participants"** section
3. Click **"Add Participant"**
4. Select participant type: Faculty or Student
5. Search and select participants
6. Click **"Add Participants"**

### Training Nominations

#### Viewing Training Nominations

1. Navigate to the **Events** tab
2. Go to **"Training Nominations"** section
3. View nominations:
   - **Training Program**: Training program name
   - **Nominee**: Nominated person
   - **Nominee Type**: Faculty or Student
   - **Nominated By**: Coordinator who nominated
   - **Status**: Pending, Approved, Rejected, or Completed

#### Creating a Training Nomination

1. Navigate to the **Events** tab
2. Go to **"Training Nominations"** section
3. Click **"New Nomination"**
4. Fill in the nomination:
   - **Program**: Select your program
   - **Training Program**: Select training program
   - **Nominee**: Select faculty or student
   - **Nominee Type**: Faculty or Student
   - **Notes**: Additional notes
5. Click **"Submit Nomination"**

### Tracking Event Attendance

1. Navigate to an event's detail page
2. Go to **"Attendance"** section
3. Mark attendance:
   - **Present**: Mark as present
   - **Absent**: Mark as absent
   - **Late**: Mark as late (with time)
4. Click **"Save Attendance"**

---

## Communications

### Sending Communications

**Location**: Dashboard → Communications Tab

#### Accessing Communications

1. Navigate to the **Communications** tab on the main dashboard
2. Or access directly: `/[school-code]/dashboard/program-coordinator/communications`

#### Sending Bulk Email

1. Click **"Send Email"** button
2. Fill in the email details:
   - **Program**: Select program (leave empty for all programs)
   - **Recipient Type**: Students, Faculty, Both, or All
   - **Subject**: Email subject
   - **Message**: Email content
   - **Template**: Select template (optional)
3. Preview the email
4. Click **"Send Email"**

#### Sending Bulk SMS

1. Click **"Send SMS"** button
2. Fill in the SMS details:
   - **Program**: Select program (leave empty for all programs)
   - **Recipient Type**: Students, Faculty, Both, or All
   - **Message**: SMS content (max 160 characters)
   - **Template**: Select template (optional)
3. Preview the SMS
4. Click **"Send SMS"**

#### Sending Announcements

1. Click **"Send Announcement"** button
2. Fill in the announcement:
   - **Program**: Select program (leave empty for all programs)
   - **Recipient Type**: Students, Faculty, Both, or All
   - **Subject**: Announcement title
   - **Message**: Announcement content
   - **Priority**: High, Medium, or Low
3. Click **"Send Announcement"**

### Managing Templates

#### Viewing Templates

1. Navigate to the **Communications** tab
2. Go to **"Templates"** section
3. View available templates:
   - **Template Name**: Template title
   - **Type**: Email, SMS, or Announcement
   - **Category**: Category (e.g., Course Registration, Event Announcement)
   - **Last Modified**: Last update date

#### Creating a Template

1. Navigate to **"Templates"** section
2. Click **"New Template"**
3. Fill in template details:
   - **Template Name**: Template title
   - **Type**: Email, SMS, or Announcement
   - **Category**: Select category
   - **Subject**: Email/announcement subject (if applicable)
   - **Content**: Template content
   - **Variables**: Available variables (e.g., {student_name}, {program_name})
4. Click **"Save Template"**

#### Editing Templates

1. Find the template in the list
2. Click **"Edit"**
3. Update template content
4. Click **"Save Changes"**

#### Suggested Templates

The system includes suggested templates:
- **Course Registration Reminder**: Remind students about course registration
- **Faculty Allocation Notification**: Notify faculty of course assignments
- **Curriculum Update Alert**: Alert about curriculum changes
- **Program Orientation Invite**: Invite to program orientation
- **Academic Event Announcement**: Announce academic events
- **Student Advisory Meeting Notice**: Notify about advisory meetings

### Viewing Communication History

1. Navigate to the **Communications** tab
2. Go to **"History"** section
3. View communication logs:
   - **Date**: Sent date and time
   - **Type**: Email, SMS, or Announcement
   - **Recipient Type**: Students, Faculty, Both, or All
   - **Subject**: Communication subject
   - **Recipients Count**: Number of recipients
   - **Status**: Sent, Failed, or Pending

#### Filtering History

- **Date Range**: Filter by date range
- **Type Filter**: Filter by communication type
- **Program Filter**: Filter by program
- **Status Filter**: Filter by status

---

## Reports & Analytics

### Generating Reports

**Location**: Dashboard → Reports Tab

#### Accessing Reports

1. Navigate to the **Reports** tab on the main dashboard
2. Or access directly: `/[school-code]/dashboard/program-coordinator/reports`

#### Available Reports

The reports page provides access to:

1. **Program Enrollment Report**: Student enrollment statistics
2. **Course Completion Report**: Course completion rates
3. **Faculty Workload Report**: Faculty workload distribution
4. **Syllabus Coverage Report**: Syllabus coverage analytics
5. **Student Progression Report**: Student progression rates
6. **Attendance Report**: Program-level attendance metrics
7. **Accreditation Readiness Report**: Accreditation readiness indicators

#### Generating a Report

1. Navigate to the **Reports** tab
2. Select report type
3. Configure report parameters:
   - **Program**: Select program (if applicable)
   - **Report Period**: Semester, Academic Year, or Custom
   - **Start Date**: Start date (for custom period)
   - **End Date**: End date (for custom period)
4. Click **"Generate Report"**
5. Wait for report generation
6. Download or view the report

### Program Enrollment Statistics

#### Viewing Enrollment Dashboard

1. Navigate to the **Reports** tab
2. Select **"Program Enrollment Report"**
3. View statistics:
   - **Total Enrollment**: Total students enrolled
   - **Enrollment by Program**: Enrollment per program
   - **Enrollment Trends**: Enrollment over time
   - **New vs. Returning**: New vs. returning students

### Course Completion Rates

1. Navigate to the **Reports** tab
2. Select **"Course Completion Report"**
3. View metrics:
   - **Overall Completion Rate**: Average completion rate
   - **Completion by Course**: Completion per course
   - **Completion by Semester**: Completion per semester
   - **Trend Analysis**: Completion trends

### Faculty Workload Distribution

1. Navigate to the **Reports** tab
2. Select **"Faculty Workload Report"**
3. View distribution:
   - **Workload by Faculty**: Workload per faculty member
   - **Workload by Program**: Workload per program
   - **Average Workload**: Average hours per week
   - **Overload Warnings**: Faculty with excessive workload

### Syllabus Coverage Analytics

1. Navigate to the **Reports** tab
2. Select **"Syllabus Coverage Report"**
3. View analytics:
   - **Overall Coverage**: Average coverage percentage
   - **Coverage by Course**: Coverage per course
   - **Coverage by Faculty**: Coverage per faculty
   - **Delayed Courses**: Courses with delayed coverage

### Student Progression Rates

1. Navigate to the **Reports** tab
2. Select **"Student Progression Report"**
3. View rates:
   - **Overall Progression Rate**: Average progression rate
   - **Progression by Program**: Progression per program
   - **Progression by Semester**: Progression per semester
   - **At-Risk Students**: Students at risk of not progressing

### Attendance Metrics

1. Navigate to the **Reports** tab
2. Select **"Attendance Report"**
3. View metrics:
   - **Overall Attendance**: Average attendance percentage
   - **Attendance by Program**: Attendance per program
   - **Attendance by Course**: Attendance per course
   - **Low Attendance Alerts**: Students with low attendance

### Accreditation Readiness Indicators

1. Navigate to the **Reports** tab
2. Select **"Accreditation Readiness Report"**
3. View indicators:
   - **Readiness Score**: Overall readiness score
   - **Compliance Areas**: Areas of compliance
   - **Gap Analysis**: Areas needing improvement
   - **Recommendations**: Recommendations for improvement

---

## Document Generation

### Generating Documents

**Location**: Dashboard → Reports Tab → Document Generation

#### Available Documents

The system can generate:

1. **Program Handbook**: Comprehensive program handbook
2. **Curriculum Guide**: Detailed curriculum guide
3. **Academic Plan**: Academic plan document

#### Generating a Program Handbook

1. Navigate to the **Reports** tab
2. Go to **"Document Generation"** section
3. Select **"Program Handbook"**
4. Configure options:
   - **Program**: Select program
   - **Include Sections**: Select sections to include
   - **Format**: PDF or Word
5. Click **"Generate Handbook"**
6. Wait for generation
7. Download the document

#### Generating a Curriculum Guide

1. Navigate to the **Reports** tab
2. Go to **"Document Generation"** section
3. Select **"Curriculum Guide"**
4. Configure options:
   - **Program**: Select program
   - **Curriculum Version**: Select version
   - **Include Details**: Select details to include
   - **Format**: PDF or Word
5. Click **"Generate Guide"**
6. Wait for generation
7. Download the document

#### Generating an Academic Plan

1. Navigate to the **Reports** tab
2. Go to **"Document Generation"** section
3. Select **"Academic Plan"**
4. Configure options:
   - **Program**: Select program
   - **Academic Year**: Select academic year
   - **Include Sections**: Select sections to include
   - **Format**: PDF or Word
5. Click **"Generate Plan"**
6. Wait for generation
7. Download the document

---

## Settings

### Program Settings

**Location**: Dashboard → Settings Tab

#### Accessing Settings

1. Navigate to the **Settings** tab (if available)
2. Or access directly: `/[school-code]/dashboard/program-coordinator/settings`

#### Notification Preferences

1. Navigate to **"Notification Preferences"** section
2. Configure:
   - **Email Notifications**: Enable/disable email notifications
   - **SMS Notifications**: Enable/disable SMS notifications
   - **Notification Types**: Select types to receive
3. Click **"Save Preferences"**

#### Workflow Preferences

1. Navigate to **"Workflow Preferences"** section
2. Configure:
   - **Auto-approve**: Enable/disable auto-approval (if permitted)
   - **Default Filters**: Set default filters for views
   - **Display Preferences**: Configure display options
3. Click **"Save Preferences"**

---

## Security & Compliance

### Access Control

#### Program Access

- You can only access programs explicitly assigned to you
- You cannot view or modify programs assigned to other coordinators
- Program assignments are managed by Dean or School Admin

#### Data Access

- **Read-Only Access**: Student marks, exam results, and financial data are read-only
- **No Modification**: You cannot modify exam results or payroll information
- **Sensitive Data**: Sensitive student data may be masked for privacy

### Multi-Tenant Security

- **School Isolation**: All data is filtered by school_id
- **No Cross-Tenant Access**: You cannot access data from other schools
- **Tenant Verification**: All queries include school_id filtering

### Audit Logging

All actions are logged:
- **Program Changes**: All program modifications
- **Curriculum Updates**: Curriculum structure changes
- **Faculty Allocations**: Faculty assignment changes
- **Student Notes**: Student progression notes
- **Communications**: All sent communications
- **Report Generation**: Generated reports

### Compliance

#### Data Privacy

- Student data is handled according to privacy regulations
- Sensitive information is masked when necessary
- Access is logged for audit purposes

#### Academic Integrity

- You cannot modify student grades or exam results
- All academic changes require appropriate approvals
- Progression decisions are tracked and audited

---

## Troubleshooting

### Common Issues

#### Cannot Access Programs

**Problem**: You cannot see any programs in your dashboard.

**Solutions**:
1. Verify you are assigned as coordinator for programs
2. Contact Dean or School Admin to assign programs
3. Check your role permissions
4. Clear browser cache and refresh

#### Cannot Create Course Offerings

**Problem**: "New Course Offering" button is disabled or missing.

**Solutions**:
1. Verify you have `course:offering:create` permission
2. Ensure a program is selected
3. Check if you have access to the selected program
4. Contact system administrator

#### Communication Not Sending

**Problem**: Emails/SMS are not being sent.

**Solutions**:
1. Check recipient list is not empty
2. Verify communication service is configured
3. Check communication logs for errors
4. Ensure you have `email:send` or `sms:send` permission
5. Contact system administrator

#### Reports Not Generating

**Problem**: Reports fail to generate or take too long.

**Solutions**:
1. Check report parameters are valid
2. Ensure date ranges are correct
3. Verify you have `report:generate` permission
4. Try generating with smaller date range
5. Contact system administrator if issue persists

#### Faculty Allocation Conflicts

**Problem**: Cannot assign faculty due to schedule conflicts.

**Solutions**:
1. Review faculty's current schedule
2. Adjust time slots to avoid conflicts
3. Consider assigning different faculty
4. Use conflict resolution tools
5. Contact faculty to discuss schedule changes

### Getting Help

#### Contact Support

- **Email**: support@slatesms.com
- **Phone**: [Support Phone Number]
- **Help Desk**: Access help desk from dashboard

#### Documentation

- **User Manual**: This document
- **API Documentation**: Available for developers
- **Video Tutorials**: Available in help section

---

## FAQs

### General Questions

**Q: Can I access programs assigned to other coordinators?**  
A: No, you can only access programs explicitly assigned to you. This is a security feature to ensure data isolation.

**Q: Can I modify student grades or exam results?**  
A: No, Program Coordinators have read-only access to student marks and exam results. This ensures academic integrity.

**Q: How do I get assigned to a program?**  
A: Program assignments are managed by Dean or School Admin. Contact them to request program assignment.

**Q: Can I create new programs?**  
A: Yes, if you have `program:create` permission. However, new programs may require approval from Dean or School Admin.

### Curriculum Questions

**Q: How many curriculum versions can be active at once?**  
A: Only one curriculum version can be active per program at a time. Activating a new version automatically archives the previous one.

**Q: Can I modify an archived curriculum?**  
A: No, archived curricula are read-only. You can view them but cannot modify them.

**Q: How do I map courses to a curriculum?**  
A: Navigate to the curriculum's detail page, go to "Course Mappings" section, and click "Add Course Mapping".

### Faculty Questions

**Q: How do I check for faculty schedule conflicts?**  
A: The system automatically checks for conflicts when assigning faculty. Conflicts are highlighted in red in the timetable view.

**Q: Can I view faculty workload across all programs?**  
A: You can only view workload for faculty assigned to your programs. You cannot see workload for other coordinators' programs.

**Q: How do I reassign faculty to a different course?**  
A: Navigate to the faculty allocation, click "Edit", update the course offering, and save. The system will check for conflicts.

### Student Questions

**Q: Can I modify student enrollment?**  
A: You can view student enrollment and create progression notes, but enrollment modifications may require approval depending on your permissions.

**Q: How do I identify at-risk students?**  
A: Navigate to "Progress & Advising" tab, go to "At-Risk Students" section. Students are automatically flagged based on GPA, attendance, and course failures.

**Q: Can I approve semester registrations?**  
A: This depends on your institution's policies. If enabled, you can approve registrations from the "Registration Approvals" section.

### Communication Questions

**Q: How many recipients can I send to at once?**  
A: There is no hard limit, but very large recipient lists may take longer to process. The system will show progress.

**Q: Can I schedule communications for later?**  
A: Currently, communications are sent immediately. Scheduled sending may be available in future updates.

**Q: How do I create email templates?**  
A: Navigate to "Communications" tab, go to "Templates" section, click "New Template", and fill in the template details.

### Report Questions

**Q: How long do reports take to generate?**  
A: Report generation time depends on data volume and report complexity. Simple reports take seconds, complex reports may take minutes.

**Q: Can I export reports to Excel?**  
A: Yes, most reports can be exported to Excel, PDF, or CSV formats.

**Q: How far back can I generate reports?**  
A: Reports can be generated for any date range within your program's history. There is no limit on historical data.

---

## Appendix

### Keyboard Shortcuts

- **Ctrl/Cmd + K**: Open search
- **Ctrl/Cmd + S**: Save current form
- **Esc**: Close dialog/modal
- **Ctrl/Cmd + /**: Show keyboard shortcuts

### Browser Compatibility

- **Chrome**: Recommended (latest version)
- **Firefox**: Supported (latest version)
- **Safari**: Supported (latest version)
- **Edge**: Supported (latest version)

### Mobile Access

The dashboard is mobile-friendly and can be accessed from:
- Smartphones (iOS and Android)
- Tablets (iOS and Android)
- Responsive design adapts to screen size

### Data Export Formats

- **PDF**: For reports and documents
- **Excel**: For data analysis
- **CSV**: For data import/export
- **Word**: For documents

---

**End of User Manual**

For additional support, please contact your system administrator or refer to the help documentation.

