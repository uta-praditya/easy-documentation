# Guest Layout Management - Business User Guide

## 🎯 Overview
The Guest Layout Management system provides a visual, interactive floor plan for managing table assignments and guest seating. Staff can drag-and-drop guests to tables, view real-time table status, and manage seating efficiently through a visual interface.

---

## 🗺️ Visual Layout Interface

### **Main Components:**
- **Interactive Floor Plan**: Visual representation of restaurant layout
- **Table Status Colors**: Real-time color-coded table status
- **Guest Waiting List**: Side panel with waiting guests
- **Pax Counter**: Live guest count display
- **Layout Selector**: Multiple floor plan options (if available)

### **Table Status Color Coding:**
- **🔴 Red (Filled)**: Table occupied with guests
- **🟢 Green (Empty)**: Table available for assignment
- **🟡 Yellow (Reservation)**: Table reserved for upcoming reservation
- **🟣 Purple (Empty Walk-in)**: Table available for walk-in guests
- **🔵 Blue (Waiting Payment)**: Table assigned, waiting for payment confirmation
- **🟠 Orange (On Hold)**: Table temporarily held
- **⚫ Gray (Filler)**: Non-assignable table space

---

## 🔄 Table Interaction Workflows

### 1. **EMPTY TABLE ASSIGNMENT**
**Action**: Tap on green (empty) table

#### **Guest Type Selection:**
**Required Selection**: Choose guest type from options:
- **Walk-in Guest**: Regular walk-in customer
- **Reservation Guest**: Customer with existing reservation
- **Ticket Guest**: Customer with event ticket (if applicable)

#### **Process Flow:**
1. Tap empty table
2. Select guest type
3. Choose specific guest from waiting list
4. Configure assignment details
5. Confirm assignment

### 2. **ASSIGN GUEST TO TABLE**
**Action**: After selecting guest type → Choose from waiting list

#### **Required Fields:**
- **Guest Selection**: Choose from dropdown of waiting guests (Required)
- **Number of Guests (Pax)**: Actual arriving guests (Required, numbers only)
- **Minimum Charge Amount**: Spending requirement (Required, numbers only)
- **MC Type**: Select "Per Pax" or "Per Table" (Required)

#### **Process:**
1. Select guest from dropdown list
2. Enter actual number of arriving guests
3. Set minimum charge amount and type
4. System calculates total MC automatically
5. Confirm assignment
6. Guest moves from waiting list to table
7. Table color changes to red (filled)

### 3. **VIEW OCCUPIED TABLE INFO**
**Action**: Tap on red (filled) table

#### **Information Displayed:**
- **Guest Name**: Customer name
- **Phone Number**: Contact information
- **Membership**: Member status/level
- **Pax Count**: Current/Total guests
- **Minimum Charge**: Amount and calculation
- **Notes**: Special requests or information
- **Seating Time**: When guest was seated

#### **Available Actions:**
- **Edit Info**: Modify guest details
- **Close Table**: Complete service and free table
- **Duplicate Table**: Copy guest to another table
- **Change Guest**: Replace with different guest
- **Move Table**: Transfer guest to different table

### 4. **EDIT GUEST INFORMATION**
**Action**: Tap occupied table → "Edit Info"

#### **Editable Fields:**
- **Current Pax**: Update actual guest count (numbers only)
- **Total MC**: Modify minimum charge amount (currency format)
- **Notes**: Update special requests or information

#### **Process:**
1. Tap "Edit Info" button
2. Modify required fields
3. Save changes
4. Information updates immediately

### 5. **CLOSE TABLE**
**Action**: Tap occupied table → "Close Table"

#### **Required Fields:**
- **Confirmation**: Confirm service completion

#### **Process:**
1. Tap "Close Table" button
2. Confirm action
3. Guest marked as completed
4. Table becomes available (green)
5. Guest removed from active seating

### 6. **RESERVED TABLE INFO**
**Action**: Tap on yellow (reservation) table

#### **Information Displayed:**
- **Reservation Details**: Customer and booking information
- **Reservation Time**: Scheduled arrival time
- **Table Assignment**: Reserved table details
- **Status**: Current reservation status

#### **No Input Required**: View-only for reservation information

---

## 🎯 Drag-and-Drop Operations

### **DRAG GUEST TO TABLE**
**Action**: Drag guest from waiting list to empty table

#### **Process:**
1. Locate guest in waiting list panel
2. Drag guest card to desired empty table
3. System automatically opens assignment dialog
4. Complete assignment details (same as manual assignment)
5. Confirm placement

#### **Validation:**
- Can only drag to empty (green) tables
- System prevents invalid assignments
- Automatic conflict checking

---

## 📊 Guest Waiting List Panel

### **Panel Information:**
- **Guest Cards**: Individual guest information
- **Pax Counter**: Total waiting guests
- **Search Function**: Find specific guests
- **Status Indicators**: Guest status colors

### **Guest Card Actions:**
- **Tap to Select**: Choose for table assignment
- **View Details**: See complete guest information
- **Edit Info**: Modify guest details
- **Remove**: Cancel from waiting list

---

## 🔧 Layout Controls

### **Layout Selector** (if multiple layouts available):
**Action**: Dropdown menu at top of screen

#### **Function:**
- **Select Layout**: Choose different floor plan
- **No Input Required**: Simple selection from dropdown
- **Automatic Refresh**: Layout updates immediately

### **Pax Counter Display:**
**Location**: Header area
**Information**: 
- **Total Pax**: All registered guests
- **Current Pax**: Actual arriving guests
- **Format**: "Pax: 45 | Current Pax: 38"

---

## 🎯 Quick Actions (No Input Required)

### **Communication:**
- **Call Guest**: Direct phone call from guest card
- **WhatsApp**: Send message to guest
- **View Info**: Display complete guest details

### **Navigation:**
- **Zoom**: Pinch to zoom in/out on layout
- **Pan**: Drag to move around large layouts
- **Refresh**: Reload current data

### **Search:**
- **Find Guest**: Search waiting list by name/phone
- **Real-time Filter**: Results update as you type

---

## 🔄 Status Change Workflows

### **TABLE STATUS CHANGES:**
```
Empty (Green) → Assigned (Red) → Closed (Green)
     ↓
Reserved (Yellow) → Arrived (Red) → Closed (Green)
```

### **GUEST STATUS CHANGES:**
```
Waiting List → Assigned to Table → Service Complete
```

---

## 💡 Best Practices

### **Efficient Table Management:**
- Use drag-and-drop for quick assignments
- Monitor table colors for status overview
- Keep waiting list organized and updated
- Use search function for busy periods

### **Guest Assignment:**
- Verify pax count before assignment
- Set appropriate minimum charges
- Add relevant notes for staff communication
- Confirm guest details before seating

### **Layout Navigation:**
- Use zoom for detailed table selection
- Switch layouts for different areas/events
- Monitor pax counters for capacity planning
- Keep layout view updated with refresh

---

## 🔐 Permission Requirements

### **Basic Staff:**
- View layout and table status
- Assign guests to tables
- Edit basic guest information
- View guest details

### **Supervisor/Manager:**
- All basic functions
- Close tables and complete service
- Move guests between tables
- Access all layout options

---

## 📱 Mobile vs Desktop Usage

### **Mobile Features:**
- Touch-friendly drag-and-drop
- Pinch-to-zoom navigation
- Side drawer for guest list
- Optimized button sizes

### **Desktop Features:**
- Mouse-based interactions
- Persistent side panels
- Keyboard shortcuts
- Larger information display

This guide covers the essential workflows for managing guest seating through the visual layout interface, enabling efficient table management and guest assignment in the HolyWings Board system.