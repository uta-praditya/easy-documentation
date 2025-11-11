# Manager Operations - Business User Guide

## 🎯 Overview
The Manager Operations module provides administrative tools for daily operations, table management, financial processes, and outlet configuration. This section is designed for managers and supervisors to handle operational tasks and maintain outlet efficiency.

---

## 🏢 Manager Menu Access

### **Menu Grid Layout:**
The Manager Operations screen displays a grid of operational functions, each represented by an icon and title. Access is permission-based, with some functions requiring admin privileges.

### **Available Functions:**
- Daily Operational Lists (Opening/Closing)
- Lock Table Management
- Off Schedule Management
- Reschedule List
- Refund List
- Outlet Layout (Admin only)
- Table Settings (Admin only)

---

## 📋 Daily Operational Functions

### 1. **DAILY OPERATIONAL LIST (OPENING)**
**Purpose**: Morning checklist for outlet opening procedures

#### **Process Flow:**
1. Access from Manager menu
2. View outlet information and current date
3. Complete checklist groups in sequence
4. Each group contains multiple tasks/questions
5. Mark tasks as completed
6. Progress indicator shows completion status
7. Submit when all tasks finished

#### **Required Actions:**
- **Task Completion**: Mark each checklist item as done
- **Photo Upload**: Some tasks require photo evidence
- **Text Input**: Provide notes or observations where required
- **Approval**: Supervisor approval for completion

#### **No Input Required for Access**: Simple menu selection

### 2. **DAILY OPERATIONAL LIST (CLOSING)**
**Purpose**: Evening checklist for outlet closing procedures

#### **Similar Process to Opening:**
- Same interface and workflow
- Different checklist items for closing tasks
- Photo documentation required
- Final approval needed before completion

---

## 🔒 Table Management Functions

### 1. **LOCK TABLE MANAGEMENT**
**Purpose**: Reserve tables for special events or VIP customers

#### **Interface Components:**
- **Visual Layout**: Interactive floor plan
- **Date Picker**: Select reservation date
- **Table Selection**: Multi-table selection capability
- **Layout Selector**: Choose different floor plans (if available)

#### **Lock Table Process:**

**Step 1: Select Date and Layout**
- **Date Selection**: Choose future date from calendar
- **Layout Selection**: Pick appropriate floor plan
- **No Input Required**: Visual selection only

**Step 2: Select Tables**
- **Table Selection**: Click tables to select/deselect
- **Multi-Selection**: Up to 10 tables can be selected
- **Visual Feedback**: Selected tables highlighted
- **Table Names Display**: Shows selected table names

**Step 3: Choose Lock Type**
- **Filler**: Traffic/placeholder reservation
- **Paid Lock**: Customer pays deposit
- **Free Lock**: No payment required

**Step 4: Customer Information (for Paid/Free Lock)**
- **Customer Search**: Find existing customer or add new
- **Required Fields**:
  - **Customer Name**: Full name (auto-filled if existing)
  - **Phone Number**: Contact number (auto-filled if existing)
  - **Email**: Email address (Optional)
  - **Number of Guests**: Party size (Required)
  - **Time**: Reservation time from dropdown
  - **Payment Percentage**: Deposit percentage (20-100%)
  - **Price**: Total amount (Required for paid locks)
  - **Minimum Cost**: Spending requirement (Required)
  - **Entertainer**: Staff assignment (Optional)

#### **Additional Options:**
- **Use Tax**: Include tax in calculation
- **Use Service**: Include service charge
- **Notes**: Special requests or information

#### **Validation:**
- Cannot lock tables between 00:00-06:00 GMT+7
- Ticket reservations not allowed for table locking
- Selected tables must be available

### 2. **TABLE UNLOCK**
**Purpose**: Release locked tables or close occupied tables

#### **Process:**
1. Click on locked/occupied table
2. View table and customer information
3. Choose unlock action
4. Confirm unlock
5. Table becomes available

#### **No Additional Input Required**: Simple confirmation process

---

## 📅 Schedule Management

### 1. **OFF SCHEDULE MANAGEMENT**
**Purpose**: Set non-operational dates and special configurations

#### **Interface:**
- **Calendar View**: Select dates for off-schedule
- **Off Schedule List**: View existing off-schedule dates
- **Configuration Options**: Set special parameters

#### **Create Off Schedule:**
**Required Selections:**
- **Date**: Choose date from calendar
- **Reservation Status**: Allow/disallow reservations
- **Minimum Cost Type**: Weekend or weekday rates
- **Ticket Usage**: Enable/disable ticket reservations

#### **Process:**
1. Select date from calendar
2. Configure reservation settings
3. Set minimum cost type
4. Enable/disable ticket system
5. Save configuration

#### **Delete Off Schedule:**
- **Action**: Click "Delete" button on existing entry
- **Confirmation**: Confirm deletion
- **No Additional Input**: Simple removal process

---

## 💰 Financial Management

### 1. **REFUND LIST**
**Purpose**: Manage customer refund requests and processing

#### **Interface:**
- **Data Table**: Comprehensive refund information
- **Status Filter**: Filter by refund status
- **Search Function**: Find specific refunds
- **Export Capability**: Download refund data

#### **Displayed Information:**
- **Refund ID**: Unique identifier
- **Customer Name**: Customer information
- **Phone Number**: Contact details
- **Original Amount**: Initial payment amount
- **Refund Amount**: Amount to be refunded
- **Status**: Current refund status with color coding
- **Reservation ID**: Associated reservation
- **Ticket Purchase ID**: Associated ticket (if applicable)
- **Type**: Refund type/reason
- **Reservation Date**: Original booking date
- **Updated Date**: Last modification date

#### **Available Actions (for Pending Refunds):**
- **Change Info**: Modify refund details
- **Change Amount**: Adjust refund amount

#### **Required Fields for Changes:**
- **New Amount**: Updated refund amount
- **Reason**: Explanation for change
- **Notes**: Additional information

### 2. **RESCHEDULE LIST**
**Purpose**: Manage reservation date/time change requests

#### **Interface:**
- **Data Table**: Comprehensive reschedule information
- **Status Filter**: Filter by reschedule status
- **Search Function**: Find specific reschedules

#### **Displayed Information:**
- **Reschedule ID**: Unique identifier
- **Requested By**: Staff member who requested
- **Reservation ID**: Original reservation
- **Original Tables**: Current table assignment
- **New Tables**: Requested table assignment
- **Source Date**: Original reservation date
- **Target Date**: Requested new date
- **Status**: Current reschedule status
- **Notes**: Reschedule reason/details

#### **Status Options:**
- **Pending**: Awaiting approval
- **Approved**: Reschedule confirmed
- **Rejected**: Reschedule denied
- **Completed**: Reschedule processed

#### **View Notes:**
- **Action**: Click "See Notes" button
- **Display**: Shows detailed reschedule reason
- **No Input Required**: View-only function

---

## 🔧 Administrative Functions (Admin Only)

### 1. **OUTLET LAYOUT**
**Purpose**: Configure restaurant floor plans and table arrangements
- **Access**: Admin permissions required
- **Function**: Visual layout editor
- **Details**: See Layout Manager System guide

### 2. **TABLE SETTINGS**
**Purpose**: Configure table categories and properties
- **Access**: Admin permissions required
- **Function**: Table category management
- **Configuration**: Table types, capacities, pricing

---

## 🎯 Quick Actions Summary

### **No Input Required:**
- **Menu Navigation**: Simple icon selection
- **View Lists**: Automatic data loading
- **Status Viewing**: Real-time status display
- **Export Functions**: One-click data download

### **Input Required:**
- **Lock Table**: Customer details, payment info, time selection
- **Off Schedule**: Date selection, configuration options
- **Refund Changes**: Amount modifications, reason explanations
- **Checklist Completion**: Task marking, photo uploads, notes

---

## 🔐 Permission Requirements

### **Manager Level:**
- Access to all operational functions
- Lock/unlock tables
- View financial lists
- Complete daily checklists
- Manage off schedules

### **Admin Level:**
- All manager functions
- Outlet layout configuration
- Table settings management
- System configuration access

### **Supervisor Level:**
- Daily operational approvals
- Refund processing
- Reschedule approvals
- Staff oversight functions

---

## 💡 Best Practices

### **Daily Operations:**
- Complete opening checklist before service
- Document all required photos and notes
- Ensure supervisor approval for completion
- Complete closing checklist after service

### **Table Management:**
- Plan table locks in advance
- Avoid locking during restricted hours
- Confirm customer details before locking
- Monitor locked table usage

### **Financial Processing:**
- Review refund requests promptly
- Verify refund amounts and reasons
- Process reschedules efficiently
- Maintain accurate documentation

### **Schedule Management:**
- Set off schedules well in advance
- Communicate schedule changes to staff
- Monitor reservation impacts
- Update configurations as needed

This guide covers the essential administrative and operational functions available to managers and supervisors for maintaining efficient outlet operations in the HolyWings Board system.