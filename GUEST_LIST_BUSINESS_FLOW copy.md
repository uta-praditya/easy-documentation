# Guest List Management - Business User Guide

## 🎯 Overview
The Guest List Management system handles walk-in customers and manages seating assignments. Staff can register new guests, track waiting lists, and monitor guest flow through the venue.

---

## 🔄 Guest Status Flow

### **Main Status Workflow:**
```
Waiting → Seated → Completed
   ↓
Cancelled
```

### **Status Definitions:**
- **Waiting**: Guest registered, waiting for table assignment
- **Seated**: Guest assigned to table and seated
- **Completed**: Guest finished service and left
- **Cancelled**: Guest removed from waiting list

---

## 📋 Core Functions & Required Fields

### 1. **ADD NEW GUEST**
**Action**: Header "Add" button → Search Member → Add Guest Form

#### **Required Fields:**
- **Customer Name**: Full name (Required)
- **Phone Number**: Contact number (Required, numbers only)
- **Number of Guests (Pax)**: Total party size (Required, minimum 1)
- **Current Pax**: Actual guests arriving (Required, numbers only)

#### **Optional Fields:**
- **Table Preference**: Specific table request
- **Minimum Charge**: Spending requirement (currency format)
- **Notes**: Special requests or information

#### **Process:**
1. Click "Add" button in header
2. Search for existing member or create new
3. Fill required guest information
4. Confirm to add to waiting list
5. Guest appears in waiting list with "Waiting" status

### 2. **EDIT GUEST INFORMATION**
**Action**: Tap on guest card → "Edit Info"

#### **Editable Fields:**
- **Current Pax**: Update actual number of arriving guests
  - Use +/- buttons or direct input
  - Must be numbers only, minimum 1
- **Table Name**: Change table assignment (format: "S-3", "VIP-1")
- **Notes**: Update special requests or information (max length limit)

#### **Process:**
1. Tap guest card to open options
2. Select "Edit Info"
3. Modify required fields
4. Save changes
5. Updated information reflects immediately

### 3. **VIEW GUEST DETAILS**
**Action**: Tap on guest card → "Info"

#### **Information Displayed:**
- **Name**: Customer full name
- **Phone Number**: Contact information
- **Status**: Current guest status
- **Grade**: Membership level (Member/Non-Member)
- **Date**: Registration date and time
- **Pax Count**: "Current Pax / Total Pax"
- **Notes**: Special requests (read-only)

#### **No Input Required**: View-only function

### 4. **CANCEL/REMOVE GUEST**
**Action**: Tap on guest card → Delete icon

#### **Required Fields:**
- **Cancellation Reason**: Text explanation for removal (Required)

#### **Process:**
1. Tap delete icon on guest card
2. Enter reason for cancellation
3. Confirm removal
4. Guest status changes to "Cancelled"
5. Guest removed from active waiting list

---

## 🎯 Quick Actions (No Input Required)

### **Search Functions:**
- **Text Search**: Find guests by name or phone number
- **Real-time Filter**: Results update as you type

### **Communication Actions:**
- **Call**: Direct phone call to guest
- **WhatsApp**: Send WhatsApp message
- **Info**: View complete guest details

### **Data Management:**
- **Export**: Download guest list data
- **History**: View past guest records
- **Refresh**: Reload current data

---

## 📊 Guest List Display

### **Header Information:**
- **Total Pax**: Sum of all registered guests
- **Current Pax**: Sum of actual arriving guests
- **Format**: "(Pax: 45 | Current Pax: 38)"

### **Guest Card Information:**
Each guest card displays:
- **Name**: Customer name
- **Phone**: Contact number
- **Status**: Current status with color coding
- **Pax**: "Current/Total" format
- **Table**: Assigned table (if any)
- **Time**: Registration timestamp

### **Color Coding:**
- **Blue**: Waiting status
- **Green**: Seated status
- **Gray**: Completed status
- **Red**: Cancelled status

---

## 🔄 Status Change Workflows

### **WAITING → SEATED**
**Method**: Drag-and-drop in Guest Layout or manual assignment
- **No additional input required**
- **Automatic status update**
- **Table assignment recorded**

### **SEATED → COMPLETED**
**Method**: Manual status update or bill closure
- **No additional input required**
- **Service completion recorded**

### **ANY STATUS → CANCELLED**
**Method**: Delete action with reason
- **Required**: Cancellation reason
- **Immediate removal from active list**

---

## 📱 Action Buttons Summary

### **Header Actions:**
- **Search**: Real-time guest search (no input required to start)
- **History**: View historical guest data (no input required)
- **Export**: Download guest list data (no input required)
- **Add**: Create new guest entry (requires guest information)

### **Guest Card Actions:**
- **Edit Info**: Modify guest details (requires field updates)
- **View Info**: Display complete information (no input required)
- **Delete**: Remove from list (requires cancellation reason)
- **Call/WhatsApp**: Communication (no input required)

---

## 🔐 Permission Requirements

### **Basic Staff:**
- View guest list
- Add new guests
- Edit guest information
- Communication actions

### **Supervisor/Manager:**
- All basic functions
- Cancel/remove guests
- Export data
- View history

---

## 💡 Best Practices

### **Adding Guests:**
- Always verify phone number format
- Confirm actual vs. total pax count
- Add relevant notes for special requests
- Check for existing membership

### **Managing Wait List:**
- Update current pax when guests arrive
- Use table preferences for better service
- Monitor wait times through timestamps
- Keep notes updated for staff communication

### **Data Management:**
- Export data regularly for reporting
- Use search function for quick guest lookup
- Monitor pax counts for capacity planning
- Review history for guest patterns

This guide covers the essential workflows for managing walk-in guests and maintaining an efficient waiting list system in the HolyWings Board application.