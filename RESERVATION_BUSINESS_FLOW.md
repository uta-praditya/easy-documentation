# Reservation Management - Business User Guide

## 🎯 Purpose
The Reservation Management system handles customer bookings from initial reservation through completion. Staff can manage different types of reservations, update statuses, and track customer interactions.

## 🚪 Access
**Navigation**: Side Menu → Reservation Management
**Permissions**: All staff levels (features vary by role)
**Related Features**: [Guest Layout](GUEST_LAYOUT_BUSINESS_FLOW.md), [Guest List](GUEST_LIST_BUSINESS_FLOW.md), [Manager Operations](MANAGER_OPERATIONS_BUSINESS_FLOW.md)

## 🖥️ Main Interface
**Components**:
- **Reservation List**: Scrollable list of all bookings
- **Search Bar**: Find reservations by name, phone, or ID
- **QR Scanner**: Quick lookup via QR codes
- **Filter Options**: Date and status filtering
- **Export Button**: Download reservation data
- **Add Button**: Create new reservations

---

## 🔄 Reservation Types & Workflows

### 1. **Regular Reservations**
**Purpose**: Standard table bookings for dining and entertainment

#### **Status Flow:**
```
Pending → Confirmed → Arrived → Completed
   ↓         ↓          ↓
No Answer  No Show   Walkout
   ↓         ↓          ↓
Cancelled Cancelled Cancelled
```

#### **Status Change Actions & Required Fields:**

**1. PENDING → CONFIRMED**
- **Action**: Swipe right → "Confirm"
- **Required Fields**: None (simple confirmation)
- **Process**: Staff confirms reservation is valid
- **Result**: Status changes to Confirmed (Green)

**2. CONFIRMED → ARRIVED**
- **Action**: Swipe right → "Arrived"
- **Required Fields**: 
  - **Number of Guests (Pax)**: Actual number of guests arriving
- **Process**: Customer checks in at venue
- **Result**: Status changes to Arrived (Dark Green)

**3. PENDING → NO ANSWER**
- **Action**: Swipe right → "No Answer"
- **Required Fields**: None
- **Process**: Tracks unanswered confirmation calls
- **Result**: Counter increases (shows "No Answer 1x", "No Answer 2x", etc.)
- **Note**: After multiple no answers, can lead to cancellation

**4. CONFIRMED → NO SHOW**
- **Action**: Swipe right → "No Show"
- **Required Fields**: 
  - **PIN Code**: Security PIN for authorization
- **Process**: Customer doesn't arrive for confirmed reservation
- **Result**: Status changes to Cancelled (Red)

**5. ARRIVED → WALKOUT**
- **Action**: Swipe right → "Walkout"
- **Required Fields**: 
  - **Reason**: Text explanation for walkout
- **Process**: Customer leaves without completing service
- **Result**: Status changes to Cancelled (Red)

**6. ANY STATUS → CANCELLED**
- **Action**: Swipe right → "Cancel"
- **Required Fields**: 
  - **Cancellation Reason**: Detailed text explanation
- **Process**: Manual cancellation by staff or customer request
- **Result**: Status changes to Cancelled (Red)

### 2. **Ticket Reservations**
**Purpose**: Event-based reservations with specific tickets

#### **Status Flow:**
```
Waiting Payment → Waiting Seat → Assigned → Completed
       ↓              ↓           ↓
   Cancelled      Cancelled   Cancelled
```

#### **Key Actions & Required Fields:**

**1. CREATE TICKET RESERVATION**
- **Action**: Header "Add" button
- **Required Fields**:
  - **Customer Name**: Full name
  - **Phone Number**: Contact number
  - **Email**: Email address
  - **Ticket Type**: Select from available tickets
  - **Quantity**: Number of tickets
  - **Event Date**: Date of event

**2. ASSIGN SEAT**
- **Action**: Swipe or button "Assign"
- **Required Fields**:
  - **Table Selection**: Choose available table
  - **Seat Numbers**: Specific seat assignments
- **Process**: Allocate physical seating
- **Result**: Status changes to Assigned

**3. PROCESS REFUND**
- **Action**: "Refund" button
- **Required Fields**:
  - **Refund Amount**: Amount to refund
  - **Refund Reason**: Explanation for refund
  - **Refund Method**: How refund will be processed

### 3. **Restaurant Reservations V2**
**Purpose**: Enhanced dining reservations with course selection

#### **Status Flow:**
```
Waiting Payment → Waiting Seat → Confirmed → Completed
       ↓              ↓           ↓
   Expired        Cancelled   Cancelled
```

#### **Key Actions & Required Fields:**

**1. CREATE RESTAURANT RESERVATION**
- **Action**: Header "Add" button
- **Required Fields**:
  - **Customer Information**: Name, phone, email
  - **Dining Date & Time**: Reservation datetime
  - **Number of Guests**: Party size
  - **Course Selection**: Choose meal courses
  - **Allergy Information**: Customer allergies/dietary restrictions
  - **Special Requests**: Additional notes

**2. VIEW ALLERGY INFO**
- **Action**: "Allergy Info" button
- **Display**: Shows detailed allergy information
- **No Input Required**: View-only function

### 4. **Standing Reservations**
**Purpose**: Recurring reservations for VIP/regular customers

#### **Status Flow:**
```
Payment → Pending → Confirmed → Arrived → Completed
    ↓        ↓         ↓          ↓
Cancelled Cancelled No Show   Walkout
```

#### **Key Actions & Required Fields:**

**1. CREATE STANDING RESERVATION**
- **Action**: "Add" button
- **Required Fields**:
  - **Customer Details**: Name, phone, email, membership level
  - **Recurring Schedule**: Days/frequency of reservation
  - **Default Table Preference**: Preferred seating area
  - **Default Party Size**: Usual number of guests
  - **Special Notes**: VIP preferences or requirements

---

## 📋 Common Input Fields Across All Types

### **Customer Information:**
- **Name**: Full customer name (Required)
- **Phone**: Contact number with country code (Required)
- **Email**: Email address (Optional but recommended)
- **Membership Level**: VIP status if applicable

### **Reservation Details:**
- **Date & Time**: When reservation is for (Required)
- **Number of Guests (Pax)**: Party size (Required)
- **Table Preference**: Specific table or area request
- **Special Notes**: Additional requests or information

### **Payment Information:**
- **Payment Method**: Cash, Card, Bank Transfer, etc.
- **Amount**: Total reservation amount
- **Deposit**: Advance payment if required
- **Payment Status**: Paid, Pending, Partial

### **Status Change Fields:**
- **Reason**: Required for cancellations, walkouts
- **PIN**: Required for sensitive actions (No Show)
- **Actual Pax**: Required when marking as Arrived
- **Notes**: Optional additional information

---

## 🎯 Quick Actions (No Input Required)

### **Communication Actions:**
- **Call**: Direct phone call to customer
- **WhatsApp**: Send WhatsApp message
- **Info Detail**: View complete reservation details

### **View Actions:**
- **Table Info**: See table assignment details
- **Payment Info**: View payment status and history
- **Customer History**: See past reservations

### **Filter Actions:**
- **Date Filter**: Select specific date
- **Status Filter**: Show only specific status
- **Search**: Find by name, phone, or ID
- **QR Search**: Scan QR code for quick lookup

---

## 🔄 Status Color Coding

- **Blue**: Pending, Waiting Payment
- **Green**: Confirmed, Waiting Seat
- **Dark Green**: Arrived, Assigned
- **Red**: Cancelled, No Show, Walkout, Expired
- **Orange/Yellow**: No Answer (with counter)

---

## 📊 Export & Reporting

### **Export Options:**
- **Excel Export**: Complete reservation data
- **Date Range**: Select specific date range
- **Status Filter**: Export only specific statuses
- **Custom Fields**: Choose which data to include

### **No Input Required for Export:**
- System automatically includes all relevant data
- File naming is automatic with outlet name and date
- Download progress is tracked automatically

---

## 🔐 Permission-Based Actions

Some actions require specific user permissions:
- **Cancellations**: May require supervisor approval
- **Refunds**: Financial permissions needed
- **No Show**: PIN required for security
- **Export**: Data access permissions required

## 🔗 Related Features
- **[Guest Layout](GUEST_LAYOUT_BUSINESS_FLOW.md)**: Confirmed reservations appear as yellow tables
- **[Manager Operations](MANAGER_OPERATIONS_BUSINESS_FLOW.md)**: Lock tables for special reservations
- **[Guest History](GUEST_HISTORY_BUSINESS_FLOW.md)**: All reservation activities are tracked
- **[Guest List](GUEST_LIST_BUSINESS_FLOW.md)**: Walk-in guests can be converted to reservations

## 🚨 Troubleshooting

### **Common Issues:**
- **Reservation not found**: Use QR search or check different dates
- **Cannot confirm**: Verify customer details and table availability
- **Status not changing**: Check permissions and required fields
- **Export failing**: Ensure proper date range selection

### **Quick Fixes:**
- **Refresh data**: Pull down to refresh reservation list
- **Clear search**: Remove filters to see all reservations
- **Check permissions**: Contact supervisor for restricted actions
- **Verify network**: Ensure stable internet connection

This guide covers the essential workflows and input requirements for managing reservations effectively in the HolyWings Board system.