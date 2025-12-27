# Registrar - User Manual

**Version**: 1.0  
**Last Updated**: 2024  
**Role**: Registrar (Role ID: 31)

---

## Table of Contents

1. [Introduction](#introduction)
2. [Getting Started](#getting-started)
3. [Dashboard Overview](#dashboard-overview)
4. [Student Records Management](#student-records-management)
5. [Enrollment Management](#enrollment-management)
6. [Registration Workflow](#registration-workflow)
7. [Course Registration](#course-registration)
8. [Transcripts Management](#transcripts-management)
9. [Certificates Management](#certificates-management)
10. [Communications](#communications)
11. [Reports & Analytics](#reports--analytics)
12. [Registrar Notes](#registrar-notes)
13. [Document History](#document-history)
14. [Academic Calendar](#academic-calendar)
15. [Student Actions](#student-actions)
16. [Security & Compliance](#security--compliance)
17. [Troubleshooting](#troubleshooting)
18. [FAQs](#faqs)

---

## Introduction

### Role Overview

The Registrar is the central authority for academic records, admissions processing, student verification, and all official document issuance. This role is critical for maintaining accurate student records, processing registrations, and issuing official documents.

### Key Responsibilities

- **Student Records**: Manage all student master records and demographic information
- **Enrollment Processing**: Handle student enrollments and registration workflows
- **Document Issuance**: Generate transcripts, certificates, and official letters
- **Admissions Management**: Approve/reject new admissions and course registrations
- **Compliance**: Maintain academic records integrity and regulatory compliance
- **Communication**: Send notifications to students, parents, and staff

### Access Requirements

- **Role**: Registrar (Role ID: 31)
- **Permissions**: 240+ specific permissions for registrar operations
- **Multi-Tenancy**: Access limited to your assigned school only

---

## Getting Started

### Logging In

1. Navigate to your school's login page: `https://your-domain.com/[school-code]/login`
2. Enter your credentials (username/email and password)
3. After successful authentication, you'll be redirected to the Registrar dashboard

### Dashboard Access

The dashboard is accessible at:
```
/[school-code]/dashboard/registrar
```

### First-Time Setup

1. **Review Permissions**: Ensure you have all necessary permissions assigned
2. **Familiarize with Navigation**: Explore all available modules
3. **Review School Settings**: Verify academic year, programs, and policies
4. **Set Up Templates**: Configure document templates if needed

---

## Dashboard Overview

### Main Dashboard

The main dashboard provides a comprehensive overview of all registrar operations:

#### Statistics Cards

- **Total Students**: Total number of students in the school
- **Pending Registrations**: Registrations awaiting approval
- **Pending Document Requests**: Document requests to be processed
- **Transcripts Issued**: Transcripts issued this academic year
- **Certificates Issued**: Certificates issued this academic year

#### Pending Items

- **Pending Registrations**: List of registrations requiring approval
- **Pending Document Requests**: Document requests to be processed
- **Recent Activities**: Latest registrar operations and updates

#### Navigation Tabs

1. **Overview**: Dashboard summary and key metrics
2. **Records**: Student records and enrollment management
3. **Registration**: Registration and admissions workflow
4. **Transcripts**: Transcript generation and management
5. **Certificates**: Certificate generation and management
6. **Communications**: Send emails/SMS
7. **Reports**: View analytics and reports

---

## Student Records Management

**Location**: `/dashboard/registrar/records`

### Viewing Student Records

1. Navigate to **Student Records**
2. Use the search bar to find students by name or student code
3. Click **"View"** to see complete student details

### Editing Student Records

1. Find the student in the list
2. Click **"Edit"** icon
3. Update the following fields:
   - **Demographic Information**: Name, email, phone
   - **Academic Information**: Grade, enrollment status
   - **Identifiers**: Roll number, registration number, internal ID
4. Click **"Save"**

**Note**: You can update student demographic and academic details, but cannot modify core academic results (read-only for verification).

### Managing Parent/Guardian Information

1. View student details
2. Navigate to **Parents/Guardians** section
3. Add, edit, or remove parent/guardian relationships
4. Update contact information

### Student Actions

#### Transfer Student

1. Navigate to student record
2. Click **"Transfer Student"** button
3. Fill in:
   - **Target School**: Select destination school
   - **Transfer Date**: Date of transfer
   - **Reason**: Transfer reason
   - **Notes**: Additional notes
4. Click **"Process Transfer"**

#### Promote Student

1. Navigate to student record
2. Click **"Promote Student"** button
3. Fill in:
   - **New Grade**: Select new grade level
   - **New Academic Year**: Select academic year
   - **Promotion Date**: Date of promotion
   - **Notes**: Additional notes
4. Click **"Process Promotion"**

#### View Fee Clearance

1. Navigate to student record
2. Click **"View Fee Clearance"** button
3. View read-only fee clearance status
4. Check for any financial blocks

**Note**: Fee information is read-only. You cannot modify fee records.

---

## Enrollment Management

**Location**: `/dashboard/registrar/enrollments`

### Creating Enrollment Records

1. Click **"Create Enrollment"** button
2. Fill in the form:
   - **Student ID**: Enter student ID
   - **Academic Year**: Select academic year (e.g., "2024-2025")
   - **Semester**: Optional semester information
   - **Enrollment Date**: Date of enrollment
   - **Status**: Enrolled, Pending, or Withdrawn
   - **Notes**: Optional notes
3. Click **"Create Enrollment"**

### Managing Enrollments

- **Search/Filter**: Filter by status, academic year, or student name
- **View**: Click **"View"** to see enrollment details
- **Edit**: Click **"Edit"** to modify enrollment information
- **Statistics**: View enrollment statistics on dashboard cards

### Enrollment Statuses

- **Enrolled**: Student is actively enrolled
- **Pending**: Enrollment is pending approval
- **Withdrawn**: Student has withdrawn

---

## Registration Workflow

**Location**: `/dashboard/registrar/registration`

### Approving Registrations

1. View **Pending Registrations** list
2. Click **"View"** to review registration details
3. Review student information and program details
4. Click **"Approve"** or **"Reject"**
5. Add comments if needed
6. Confirm action

### Rejecting Registrations

1. Select registration to reject
2. Click **"Reject"** button
3. Enter rejection reason
4. Click **"Confirm Rejection"**

### Registration Status

- **Pending**: Awaiting approval
- **Approved**: Registration approved
- **Rejected**: Registration rejected

---

## Course Registration

**Location**: `/dashboard/registrar/course-registrations`

### Approving Course Registrations

1. View **Pending Course Registrations** list
2. Review course details and student eligibility
3. Click **"Approve"** or **"Reject"**
4. Add comments if needed
5. Confirm action

### Managing Course Registrations

- **Search/Filter**: Filter by student, course, or status
- **View Details**: See complete course registration information
- **Approve/Reject**: Process course registration requests

---

## Transcripts Management

**Location**: `/dashboard/registrar/transcripts`

### Generating Transcripts

1. Navigate to **Transcripts** page
2. Click **"Go to Transcript Management"**
3. Use the existing transcript system to:
   - Generate official academic transcripts
   - View transcript history
   - Approve transcript requests
   - Download transcripts

### Transcript Features

- **Official Academic Transcript**: Complete academic record
- **Template Customization**: Customize transcript templates
- **Digital Signature**: Add digital signatures
- **Serial Numbers**: Unique serial numbers for verification
- **History Tracking**: Maintain issuance history

---

## Certificates Management

**Location**: `/dashboard/registrar/certificates`

### Generating Certificates

1. Click **"Generate Certificate"** button
2. Select:
   - **Student**: Choose student
   - **Certificate Type**: Select from 7 types:
     - Course Completion Certificate
     - Bonafide Student Certificate
     - Migration Certificate
     - Character Certificate
     - Enrollment Letter
     - Admission Letter
     - Rank Card / Grade Report
   - **Include Signature**: Toggle digital signature
   - **Custom Data**: Optional additional information
3. Click **"Generate"**
4. Certificate PDF will be downloaded automatically

### Certificate Types

#### Course Completion Certificate
- Certifies successful completion of a program
- Includes completion date and program details

#### Bonafide Student Certificate
- Confirms student is currently enrolled
- Includes enrollment date and grade

#### Migration Certificate
- Issued for students transferring to another institution
- Includes enrollment period and academic details

#### Character Certificate
- Certifies student's good character and conduct
- Includes period of study

#### Enrollment Letter
- Confirms student enrollment
- Includes program and academic year details

#### Admission Letter
- Official admission confirmation
- Includes admission date and program

#### Rank Card / Grade Report
- Academic performance summary
- Includes grades and rankings

### Managing Certificates

- **View History**: View all issued certificates
- **Download**: Download previously generated certificates
- **Search**: Find certificates by student or serial number

---

## Communications

**Location**: `/dashboard/registrar/communications`

### Sending Emails/SMS

#### Individual Message

1. Click **"Send Message"** button
2. Select:
   - **Recipient Type**: Student, Parent, or Teacher
   - **Recipient**: Select specific recipient
   - **Message Type**: Email or SMS
   - **Template**: Choose from templates (optional)
   - **Subject**: Message subject
   - **Content**: Message content
3. Click **"Send"**

#### Bulk Messages

1. Click **"Bulk Send"** button
2. Select:
   - **Recipient Group**: All students, specific grade, program participants
   - **Message Type**: Email or SMS
   - **Template**: Choose template
   - **Customize**: Edit template content
3. Click **"Send to All"**

### Email Templates

#### Available Templates

1. **Registration Confirmation**: Confirm successful registration
2. **Document Ready for Pickup**: Notify when documents are ready
3. **Transcript Request Approval**: Confirm transcript approval
4. **Certificate Issuance Confirmation**: Confirm certificate generation
5. **Missing Documents Alert**: Alert about missing documents
6. **Enrollment Pending Notice**: Notify about pending enrollment

#### Managing Templates

- **View Templates**: Browse all available templates
- **Use Template**: Select and customize template
- **Create Custom**: Create new template
- **Edit**: Modify existing templates

### Communication History

- View all sent messages
- Filter by date, recipient, or type
- Track delivery status
- View message content

---

## Reports & Analytics

**Location**: `/dashboard/registrar/reports`

### Enrollment Reports

- **Enrollment Statistics**: Overall enrollment numbers
- **Program-wise Counts**: Students per program
- **Registration Completion Rates**: Percentage of completed registrations
- **Trends**: Enrollment trends over time

### Document Issuance Reports

- **Transcripts Issued**: Number of transcripts issued
- **Certificates Issued**: Number of certificates issued
- **Document Types**: Breakdown by document type
- **Issuance History**: Historical issuance data

### Transfer/Migration Statistics

- **Transfer Students**: Students transferred out
- **Migration Certificates**: Migration certificates issued
- **Transfer Reasons**: Common transfer reasons

### Exporting Reports

- Export reports as PDF
- Export data as CSV/Excel
- Schedule automated reports

---

## Registrar Notes

**Location**: `/dashboard/registrar/notes`

### Creating Notes

1. Click **"Create Note"** button
2. Fill in:
   - **Note Type**: Internal, Student-related, etc.
   - **Related To**: Student, Enrollment, Document Request
   - **Content**: Note content
   - **Is Internal**: Toggle for internal-only notes
3. Click **"Create"**

### Managing Notes

- **View**: View all notes
- **Edit**: Modify existing notes
- **Delete**: Remove notes (soft delete)
- **Filter**: Filter by type or related entity
- **Search**: Search note content

---

## Document History

**Location**: `/dashboard/registrar/documents/history`

### Viewing Document History

1. Navigate to **Document History**
2. View all issued documents:
   - Transcripts
   - Certificates
   - Letters
3. Filter by:
   - Document type
   - Date range
   - Student
4. View document details and download links

---

## Academic Calendar

**Location**: `/dashboard/registrar/academic-calendar`

### Viewing Academic Calendar

1. Navigate to **Academic Calendar**
2. View:
   - Academic years
   - Terms/semesters
   - Important dates
3. **Note**: This is read-only for verification purposes

---

## Student Actions

### Transfer Student

**Location**: `/dashboard/registrar/students/[studentId]/transfer`

1. Navigate to student record
2. Click **"Transfer Student"**
3. Fill in transfer form
4. Process transfer

### Promote Student

**Location**: `/dashboard/registrar/students/[studentId]/promote`

1. Navigate to student record
2. Click **"Promote Student"**
3. Fill in promotion form
4. Process promotion

### View Fee Clearance

**Location**: `/dashboard/registrar/students/[studentId]/fee-clearance`

1. Navigate to student record
2. Click **"View Fee Clearance"**
3. View read-only fee information

---

## Security & Compliance

### Audit Logs

All actions are logged for audit purposes:

- **Student Record Updates**: Who changed what and when
- **Enrollment Changes**: Enrollment modifications
- **Document Issuance**: All document generations
- **Registration Approvals**: Approval/rejection actions

### Security Protocols

1. **Multi-Tenancy**: Strict school-level data isolation
2. **RBAC**: Role-based access control enforced
3. **Read-Only Results**: Cannot modify academic results
4. **Document Security**: All documents tracked with serial numbers

### Compliance Requirements

- All student record changes are logged
- Document issuance is tracked
- Registration approvals are recorded
- Transfer/promotion actions are audited

### Access Restrictions

**Registrar CANNOT:**
- Modify core academic results (read-only for verification)
- Access or modify fee records (read-only)
- Access other schools' data
- Modify system settings

---

## Troubleshooting

### Common Issues

#### Cannot Generate Certificate

**Problem**: Certificate generation fails

**Solutions**:
1. Verify student exists and belongs to your school
2. Check student enrollment status
3. Ensure all required fields are filled
4. Check for validation errors

#### Registration Approval Fails

**Problem**: Cannot approve registration

**Solutions**:
1. Verify you have approval permissions
2. Check student eligibility
3. Ensure all required documents are submitted
4. Review error messages

#### Cannot View Student Records

**Problem**: Student records not visible

**Solutions**:
1. Verify student belongs to your school
2. Check search filters
3. Ensure student is not deleted
4. Verify permissions

#### Document Download Fails

**Problem**: Cannot download generated documents

**Solutions**:
1. Check document generation status
2. Verify document exists
3. Try regenerating document
4. Check browser download settings

### Getting Help

- **System Administrator**: Contact for permission issues
- **Technical Support**: For technical problems
- **Documentation**: Refer to this manual
- **Training**: Request training sessions

---

## FAQs

### Q: Can I modify student academic results?

**A**: No. Academic results are read-only for verification. You can only view them to verify before generating transcripts.

### Q: How do I generate a certificate for a student?

**A**: Navigate to Certificates, click "Generate Certificate", select student and certificate type, then click "Generate". The PDF will download automatically.

### Q: Can I approve registrations in bulk?

**A**: Currently, registrations must be approved individually. Bulk approval may be added in future updates.

### Q: How do I track document issuance history?

**A**: Navigate to Document History to view all issued documents, filter by type or date, and download previously generated documents.

### Q: Can I edit fee information?

**A**: No. Fee information is read-only. You can only view fee clearance status to verify before issuing documents.

### Q: How do I transfer a student to another school?

**A**: Navigate to the student record, click "Transfer Student", fill in the transfer form with target school and details, then process the transfer.

### Q: What certificate types are available?

**A**: Seven types: Course Completion, Bonafide Student, Migration, Character, Enrollment Letter, Admission Letter, and Rank Card/Grade Report.

### Q: How do I send bulk notifications?

**A**: Use the Communications module to send bulk emails/SMS to students, parents, or teachers using templates.

### Q: Can I customize document templates?

**A**: Document templates can be customized through the school-admin module. Contact your system administrator for template customization.

### Q: How do I view enrollment statistics?

**A**: Navigate to Reports to view enrollment statistics, program-wise counts, and registration completion rates.

---

## Appendix

### Keyboard Shortcuts

- **Ctrl + K**: Quick search
- **Ctrl + R**: Refresh data
- **Esc**: Close dialogs
- **Enter**: Submit forms

### Supported File Formats

- **PDF**: For document downloads
- **CSV**: For data exports
- **Excel**: For report exports

### Browser Requirements

- **Chrome**: Version 90+
- **Firefox**: Version 88+
- **Edge**: Version 90+
- **Safari**: Version 14+

### Mobile Access

- Responsive design for tablets
- Limited functionality on mobile devices
- Full features on desktop/laptop

---

**End of User Manual**

For additional support, contact your system administrator or refer to the technical documentation.
