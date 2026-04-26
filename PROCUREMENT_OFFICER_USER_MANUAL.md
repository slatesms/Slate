# Procurement Officer Module - User Manual

## Table of Contents

1. [Introduction](#introduction)
2. [Getting Started](#getting-started)
3. [Dashboard Overview](#dashboard-overview)
4. [Purchase Request Management](#purchase-request-management)
5. [Vendor Management](#vendor-management)
6. [Quotation & RFQ Management](#quotation--rfq-management)
7. [Purchase Order Management](#purchase-order-management)
8. [GRN & Delivery Tracking](#grn--delivery-tracking)
9. [Handover Management](#handover-management)
10. [Payment Coordination](#payment-coordination)
11. [Communications](#communications)
12. [Reports & Analytics](#reports--analytics)
13. [Settings](#settings)
14. [Troubleshooting](#troubleshooting)

---

## Introduction

### What is the Procurement Officer Module?

The Procurement Officer Module is a comprehensive system for managing the complete lifecycle of institutional purchasing, from initial purchase requests through vendor payment coordination. This module enables procurement officers to:

- Manage purchase requests from departments
- Source and evaluate vendors
- Collect and compare quotations
- Create and manage purchase orders
- Track deliveries and goods receipt
- Coordinate with accounting for payments

### Who Can Use This Module?

- **Procurement Officers** (Role ID: 40) - Full access to all procurement functions
- **Department Heads** - Can create purchase requests (via their respective modules)
- **Accountants** - Can view payment status and process payments (via accounting module)

### Key Features

✅ Complete procurement lifecycle management  
✅ Multi-stage approval workflows  
✅ Vendor performance tracking  
✅ Budget-linked requisitions  
✅ Automated PO generation  
✅ GRN-based verification  
✅ Payment coordination with accounting  
✅ Comprehensive audit trails  
✅ Real-time dashboards and analytics  

---

## Getting Started

### Accessing the Module

1. Log in to SlateSMS with your Procurement Officer credentials
2. Navigate to: `/{school_code}/dashboard/procurement-officer`
3. You will see the Procurement Dashboard

### Navigation Structure

The module is organized into the following sections:

- **Dashboard** - Overview and KPIs
- **Purchase Requests** - Manage PRs from departments
- **Quotations** - Collect and compare vendor quotes
- **Vendors** - Manage vendor profiles and compliance
- **Purchase Orders** - Create and manage POs
- **GRN & Delivery** - Track goods receipt and deliveries
- **Handover** - Transfer goods to departments/inventory
- **Payment Tracking** - Monitor payment status
- **Reports & Analytics** - Generate procurement reports
- **Communications** - Manage templates and send communications
- **Settings** - Configure module preferences

---

## Dashboard Overview

### Purpose

The Dashboard provides a real-time overview of all procurement activities, pending tasks, and key performance indicators.

### Key Metrics Displayed

1. **Pending Purchase Requests** - PRs awaiting verification or approval
2. **Pending Purchase Orders** - POs awaiting approval or dispatch
3. **Pending GRNs** - Goods received notes to be processed
4. **Pending Quotations** - Quotations under review
5. **Active Vendors** - Total number of active vendor accounts
6. **Monthly Procurement Value** - Total procurement value for current month
7. **Delayed Deliveries** - Orders past their delivery date

### Quick Actions

From the dashboard, you can quickly navigate to:
- View all Purchase Requests
- View all Purchase Orders
- View all Quotations
- View all GRNs

### How to Use

1. Review the KPI cards to understand current workload
2. Click on any metric to drill down into detailed views
3. Use Quick Actions for common tasks
4. Monitor delayed deliveries for items requiring attention

---

## Purchase Request Management

### Overview

Purchase Requests (PRs) are requests from departments for goods or services. The Procurement Officer verifies and approves these requests before proceeding with vendor sourcing.

### PR Workflow

```
Draft → Submitted → Verified → Approved → (Quotation Process)
                ↓
            Rejected/Cancelled
```

### Creating a Purchase Request

**Note**: Typically, PRs are created by departments. However, Procurement Officers can also create PRs directly.

1. Navigate to **Purchase Requests**
2. Click **Create New PR**
3. Fill in the required information:
   - **Department** - Select the requesting department
   - **Request Date** - Date of the request
   - **Priority** - Low, Normal, High, or Urgent
   - **Budget Code** - Link to budget allocation (if applicable)
   - **Total Amount** - Estimated cost
   - **Description** - Detailed description of items/services
   - **Justification** - Business justification for the purchase
4. Click **Save as Draft** or **Submit**

### Verifying a Purchase Request

1. Navigate to **Purchase Requests**
2. Filter by status: **Submitted**
3. Click on a PR to view details
4. Review the request:
   - Check budget availability
   - Verify department authorization
   - Validate item descriptions
5. Click **Verify** or **Reject**
6. Add verification notes if needed

### Approving a Purchase Request

1. Navigate to **Purchase Requests**
2. Filter by status: **Verified**
3. Click on a PR to view details
4. Review verification notes and attachments
5. Click **Approve** or **Reject**
6. Add approval notes

### Managing PR Attachments

1. Open a PR detail page
2. Scroll to **Attachments** section
3. Click **Upload Attachment**
4. Select file and document type
5. Click **Upload**

**Supported File Types**: PDF, Images (JPG, PNG), Documents (DOC, DOCX)

### PR Statuses

- **Draft** - PR is being prepared
- **Submitted** - PR submitted for verification
- **Verified** - PR verified by procurement
- **Approved** - PR approved and ready for quotation
- **Rejected** - PR rejected (with reason)
- **Cancelled** - PR cancelled by requester

### Best Practices

- Always verify budget availability before approval
- Request clarification if PR details are unclear
- Maintain clear communication with requesting departments
- Document all decisions with notes

---

## Vendor Management

### Overview

Vendor Management allows you to maintain a database of suppliers, track their performance, and manage compliance documents.

### Registering a New Vendor

1. Navigate to **Vendors**
2. Click **Add New Vendor**
3. Fill in vendor information:
   - **Vendor Name** - Company name
   - **Vendor Type** - Category (e.g., Equipment, Services, Supplies)
   - **Contact Person** - Primary contact name
   - **Email** - Contact email
   - **Phone** - Contact phone
   - **Address** - Complete address
   - **License Number** - Business license (if applicable)
   - **Specialties** - Areas of expertise
4. Click **Save**

### Managing Vendor Documents

Vendor compliance documents are critical for procurement compliance.

1. Navigate to **Vendors**
2. Click on a vendor
3. Go to **Documents** tab
4. Click **Upload Document**
5. Select document type:
   - **GST Certificate**
   - **PAN Card**
   - **Business License**
   - **ISO Certification**
   - **Insurance Certificate**
   - **Other**
6. Upload the file
7. Mark as **Verified** once reviewed

### Vendor Ratings

Track vendor performance to make informed sourcing decisions.

1. Navigate to **Vendors**
2. Click on a vendor
3. Go to **Ratings** tab
4. Click **Add Rating**
5. Rate on criteria:
   - **Quality** (1-5 stars)
   - **Delivery Time** (1-5 stars)
   - **Price Competitiveness** (1-5 stars)
   - **Communication** (1-5 stars)
   - **Overall Rating** (1-5 stars)
6. Add comments
7. Click **Save**

### Vendor Activity Log

View all interactions and transactions with a vendor:

1. Navigate to **Vendors**
2. Click on a vendor
3. Go to **Activity** tab
4. View:
   - Purchase orders
   - Quotations submitted
   - GRNs received
   - Communications sent
   - Rating changes

### Blacklisting/Deactivating Vendors

1. Navigate to **Vendors**
2. Click on a vendor
3. Click **Deactivate** or **Blacklist**
4. Provide reason
5. Confirm action

**Note**: Blacklisted vendors cannot be selected for new POs.

### Best Practices

- Maintain up-to-date vendor information
- Regularly verify compliance documents
- Rate vendors after each transaction
- Keep detailed activity logs
- Review vendor performance quarterly

---

## Quotation & RFQ Management

### Overview

Request for Quotation (RFQ) and Quotation Management enables you to source competitive prices from multiple vendors.

### Creating an RFQ

1. Navigate to **Quotations**
2. Click **Create RFQ**
3. Link to an approved PR (optional)
4. Fill in RFQ details:
   - **RFQ Number** - Auto-generated
   - **RFQ Date** - Date of RFQ
   - **Description** - Detailed requirements
   - **Closing Date** - Deadline for quotations
5. Click **Save**

### Sending RFQ to Vendors

1. Open an RFQ
2. Click **Send RFQ**
3. Select vendors from the list
4. Review email template
5. Customize message if needed
6. Click **Send**

**Note**: RFQ emails are sent automatically to selected vendors.

### Receiving Quotations

1. Navigate to **Quotations**
2. Click **Add Quotation**
3. Link to RFQ (if applicable)
4. Fill in quotation details:
   - **Vendor** - Select vendor
   - **Quotation Number** - Vendor's quote number
   - **Quotation Date** - Date of quote
   - **Valid Until** - Quote validity period
   - **Items** - Add line items with:
     - Item description
     - Quantity
     - Unit price
     - Delivery time
   - **Total Amount** - Auto-calculated
   - **Terms & Conditions** - Vendor terms
5. Upload quotation document
6. Click **Save**

### Comparing Quotations

1. Navigate to **Comparison Sheets**
2. Click **Create Comparison**
3. Select RFQ
4. System auto-populates all quotations for that RFQ
5. Review comparison:
   - Price comparison
   - Delivery time
   - Terms & conditions
6. Add notes for each vendor
7. Click **Select Preferred Vendor**

### Negotiation Notes

Document negotiations with vendors:

1. Navigate to **Negotiation Notes**
2. Click **Add Note**
3. Select quotation
4. Add negotiation details:
   - **Date** - Negotiation date
   - **Participants** - Who was involved
   - **Discussion Points** - What was discussed
   - **Outcome** - Result of negotiation
5. Click **Save**

### Best Practices

- Send RFQs to at least 3 vendors for competitive pricing
- Set clear closing dates
- Document all negotiations
- Compare quotations systematically
- Consider factors beyond price (quality, delivery, service)

---

## Purchase Order Management

### Overview

Purchase Orders (POs) are formal documents sent to vendors to purchase goods or services.

### Creating a Purchase Order

#### Method 1: From Approved PR

1. Navigate to **Purchase Requests**
2. Find an approved PR
3. Click **Create PO**
4. System auto-fills:
   - Items from PR
   - Vendor (if selected from quotation)
5. Complete PO details:
   - **PO Date** - Date of PO
   - **Delivery Date** - Expected delivery
   - **Delivery Address** - Where to deliver
   - **Payment Terms** - Payment conditions
   - **Delivery Terms** - Delivery conditions
   - **Tax Percentage** - Applicable tax
6. Review items and adjust if needed
7. Click **Save as Draft**

#### Method 2: Direct Creation

1. Navigate to **Purchase Orders**
2. Click **Create New PO**
3. Fill in all details manually
4. Add items
5. Click **Save**

### Adding PO Items

1. Open a PO
2. Click **Add Item**
3. Fill in:
   - **Item Code** - SKU or code
   - **Item Name** - Description
   - **Quantity** - Required quantity
   - **Unit** - Unit of measure
   - **Unit Price** - Price per unit
   - **Tax Percentage** - Item tax
4. Click **Add**
5. Repeat for all items

### PO Approval Workflow

1. **Draft** - PO being prepared
2. **Pending Approval** - Submitted for approval
3. **Approved** - Approved and ready to dispatch
4. **Dispatched** - Sent to vendor
5. **Received** - Goods received

### Requesting PO Approval

1. Open a draft PO
2. Review all details
3. Click **Submit for Approval**
4. Select approvers (if multi-level approval)
5. Add notes
6. Click **Submit**

### Approving a PO

1. Navigate to **Purchase Orders**
2. Filter by status: **Pending Approval**
3. Open a PO
4. Review:
   - Items and quantities
   - Pricing
   - Terms and conditions
   - Budget availability
5. Click **Approve** or **Reject**
6. Add approval notes

### Dispatching PO to Vendor

1. Open an approved PO
2. Click **Dispatch to Vendor**
3. Choose dispatch method:
   - **Email** - Send via email
   - **Print** - Print for physical dispatch
4. Review email template
5. Customize if needed
6. Click **Send** or **Print**

### PO Amendments

Sometimes POs need to be modified after dispatch:

1. Open a PO
2. Click **Create Amendment**
3. Select items to amend:
   - Quantity changes
   - Price changes
   - Item additions/deletions
4. Provide reason for amendment
5. Submit for approval
6. Once approved, amendment is applied

### Managing PO Documents

1. Open a PO
2. Go to **Documents** tab
3. Upload:
   - Signed PO copy
   - Vendor acknowledgments
   - Amendments
   - Other related documents

### Best Practices

- Always verify vendor details before dispatch
- Include clear delivery and payment terms
- Maintain signed copies of all POs
- Track PO status regularly
- Document all amendments properly

---

## GRN & Delivery Tracking

### Overview

Goods Received Note (GRN) is created when goods are received from vendors. This section covers GRN creation, delivery tracking, and quality control.

### Creating a GRN

1. Navigate to **GRN & Delivery**
2. Click **Create GRN**
3. Select Purchase Order
4. Fill in GRN details:
   - **GRN Date** - Date of receipt
   - **Delivery Date** - Actual delivery date
   - **Delivery Note Number** - Vendor's delivery note
   - **Is Partial Delivery** - Check if partial
5. Add received items:
   - Select PO item
   - Enter **Received Quantity**
   - Enter **Accepted Quantity** (after QC)
   - Enter **Rejected Quantity** (if any)
   - Select **Condition Status**: Good, Damaged, Defective, Missing
   - Add notes
6. Add QC notes if applicable
7. Click **Save**

### Processing Partial Deliveries

1. When creating GRN, check **Is Partial Delivery**
2. Enter only received quantities
3. Save GRN
4. Create additional GRNs for remaining items when received

### Quality Control Checks

1. Open a GRN
2. Go to **QC Checks** section
3. Click **Add QC Check**
4. Fill in:
   - **Check Date** - Date of inspection
   - **Inspected By** - Person conducting check
   - **Items Checked** - Which items
   - **QC Status** - Pass/Fail
   - **Findings** - Detailed findings
   - **Action Required** - Any corrective actions
5. Click **Save**

### Delivery Tracking

Track delivery status and follow-ups:

1. Navigate to **Delivery Logs**
2. Click **Add Delivery Log**
3. Select PO
4. Fill in:
   - **Expected Date** - Original delivery date
   - **Actual Date** - When delivered (if received)
   - **Status** - Pending, In Transit, Delivered, Delayed
   - **Follow-up Date** - Next follow-up
   - **Notes** - Communication notes
5. Click **Save**

### Return/Replacement Logs

Document returns and replacements:

1. Navigate to **Return Logs**
2. Click **Add Return Log**
3. Select GRN item
4. Fill in:
   - **Return Date** - Date of return
   - **Return Reason** - Why returned
   - **Return Type** - Replacement, Refund, Repair
   - **Status** - Pending, Processed
   - **Notes** - Additional details
5. Click **Save**

### Completing GRN

1. Open a GRN
2. Review all items and QC checks
3. Click **Complete GRN**
4. System will:
   - Mark GRN as completed
   - Update PO status
   - Make items available for handover

### Best Practices

- Create GRN immediately upon receipt
- Conduct QC checks before accepting goods
- Document all defects and issues
- Track delivery timelines
- Follow up on delayed deliveries
- Maintain detailed return logs

---

## Handover Management

### Overview

Handover management transfers received goods to requesting departments or inventory systems.

### Creating a Handover Record

1. Navigate to **Handover**
2. Click **Create Handover**
3. Select completed GRN
4. Fill in details:
   - **Handover Date** - Date of handover
   - **Department** - Receiving department
   - **Handover Type** - Department, Inventory, or Asset
   - **Received By** - Person receiving goods
5. Add notes
6. Click **Save**

### Acknowledging Handover

1. Department receives notification
2. Department head reviews handover
3. Clicks **Acknowledge Receipt**
4. System updates handover status

### Inventory Sync

If inventory system is enabled:

1. After handover creation
2. System automatically syncs items to inventory
3. View sync status in **Inventory Sync Logs**
4. Resolve any sync errors

### Best Practices

- Complete handover promptly after GRN
- Ensure proper acknowledgment from departments
- Verify inventory sync if enabled
- Maintain handover documentation

---

## Payment Coordination

### Overview

Payment Coordination allows Procurement Officers to forward invoices to the Accounting department for payment processing. Procurement Officers have **read-only** access to payment status.

### Creating Payment Handoff

1. Navigate to **Payment Tracking**
2. Click **Create Handoff**
3. Select:
   - **Purchase Order**
   - **GRN** (completed)
4. Fill in invoice details:
   - **Invoice Number** - Vendor invoice number
   - **Invoice Date** - Date on invoice
   - **Invoice Amount** - Total invoice amount
   - **Invoice File** - Upload invoice document
5. Add notes
6. Click **Submit to Accounting**

**Note**: Once submitted, the invoice is forwarded to the Accountant for processing.

### Tracking Payment Status

1. Navigate to **Payment Tracking**
2. View handoff records
3. Status indicators:
   - **Pending** - Awaiting accountant review
   - **Approved** - Approved for payment
   - **Paid** - Payment processed
   - **Rejected** - Rejected (with reason)

### Viewing Payment Details

1. Click on a handoff record
2. View:
   - PO details
   - GRN details
   - Invoice details
   - Payment status
   - Payment date (if paid)
   - Payment amount

### Best Practices

- Forward invoices promptly after GRN completion
- Include all supporting documents
- Track payment status regularly
- Follow up on pending payments
- Maintain reconciliation records

**Important**: Procurement Officers **cannot** process payments. Only Accountants can approve and process vendor payments.

---

## Communications

### Overview

The Communications module manages email/SMS templates and tracks all communications with vendors and departments.

### Managing Templates

1. Navigate to **Communications**
2. Go to **Templates** tab
3. Click **Create Template**
4. Fill in:
   - **Template Name** - Descriptive name
   - **Template Type** - Email or SMS
   - **Category** - RFQ, PO Dispatch, Delivery Reminder, etc.
   - **Subject** - Email subject (for emails)
   - **Body** - Message content
   - **Variables** - Available placeholders (e.g., {vendor_name}, {po_number})
5. Click **Save**

### Using Templates

1. When sending RFQ, PO, or other communications
2. System shows available templates
3. Select template
4. Variables are auto-filled
5. Customize if needed
6. Send

### Communication Logs

1. Navigate to **Communications**
2. Go to **Logs** tab
3. View all sent communications:
   - Date and time
   - Recipient
   - Type (Email/SMS)
   - Subject
   - Status (Sent, Failed, Pending)
4. Click to view full message

### Sending Communications

#### Send RFQ
1. From RFQ page
2. Click **Send RFQ**
3. Select template
4. Select vendors
5. Send

#### Send PO Dispatch
1. From PO page
2. Click **Dispatch to Vendor**
3. Select template
4. Send

#### Send Delivery Reminder
1. From Delivery Logs
2. Select delayed delivery
3. Click **Send Reminder**
4. Select template
5. Send

### Best Practices

- Create templates for common communications
- Use variables for personalization
- Review logs regularly
- Follow up on failed communications
- Maintain professional tone in all communications

---

## Reports & Analytics

### Overview

Reports & Analytics provide insights into procurement activities, spending patterns, and vendor performance.

### Available Reports

1. **Department-wise Procurement**
   - Procurement by department
   - Spending trends
   - Request patterns

2. **Vendor Spending Analysis**
   - Total spending per vendor
   - Vendor comparison
   - Spending trends

3. **Purchase Timelines**
   - Average processing time
   - Bottleneck analysis
   - Efficiency metrics

4. **Budget vs Procurement**
   - Budget utilization
   - Variance analysis
   - Forecast vs actual

5. **Delayed Deliveries**
   - List of delayed orders
   - Vendor performance
   - Impact analysis

6. **Quotation Comparison Stats**
   - Average quotations per RFQ
   - Price variance
   - Vendor participation

### Generating Reports

1. Navigate to **Reports & Analytics**
2. Select report type
3. Set filters:
   - Date range
   - Department
   - Vendor
   - Status
4. Click **Generate Report**
5. Review results
6. Export if needed (PDF, Excel)

### Dashboard Analytics

The main dashboard shows:
- Real-time KPIs
- Pending tasks
- Monthly procurement value
- Delayed deliveries

### Best Practices

- Generate reports regularly
- Analyze trends
- Share insights with management
- Use data for vendor evaluation
- Identify improvement opportunities

---

## Settings

### Overview

Settings allow you to configure module preferences and manage your profile.

### Module Settings

1. Navigate to **Settings**
2. Configure:
   - **Default Currency** - Default currency for POs
   - **Tax Settings** - Default tax percentage
   - **Approval Workflow** - Approval levels
   - **Notification Preferences** - Email/SMS notifications
   - **Document Retention** - How long to keep documents

### User Profile

1. Click on your profile icon (top right)
2. Update:
   - Name
   - Email
   - Phone
   - Password
3. Save changes

---

## Troubleshooting

### Common Issues

#### Cannot Access Module
- **Solution**: Verify you have Procurement Officer role assigned
- Contact system administrator

#### PR Not Showing
- **Solution**: Check filters
- Verify PR belongs to your school
- Check PR status

#### Cannot Approve PO
- **Solution**: Verify you have approval permissions
- Check PO status (must be pending approval)
- Verify budget availability

#### GRN Creation Fails
- **Solution**: Verify PO exists and is dispatched
- Check item quantities
- Verify GRN date is valid

#### Payment Status Not Updating
- **Solution**: Payment status is updated by Accountant
- Contact Accounting department
- Check handoff status

### Getting Help

1. Check this user manual
2. Review system documentation
3. Contact IT support
4. Escalate to system administrator

---

## Appendix

### Glossary

- **PR** - Purchase Request
- **PO** - Purchase Order
- **GRN** - Goods Received Note
- **RFQ** - Request for Quotation
- **QC** - Quality Control
- **KPI** - Key Performance Indicator

### Keyboard Shortcuts

- `Ctrl + K` - Quick search
- `Ctrl + N` - New record
- `Ctrl + S` - Save
- `Esc` - Cancel/Close

### File Size Limits

- **Documents**: 10 MB maximum
- **Images**: 5 MB maximum
- **Supported Formats**: PDF, DOC, DOCX, XLS, XLSX, JPG, PNG

---

## Version History

- **v1.0** - Initial release
  - Complete procurement lifecycle
  - Vendor management
  - Quotation comparison
  - GRN tracking
  - Payment coordination

---

**Last Updated**: [Current Date]  
**Module Version**: 1.0  
**Documentation Version**: 1.0

