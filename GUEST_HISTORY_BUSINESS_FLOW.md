# Guest History - Business User Guide

## 🎯 Overview
The Guest History module provides comprehensive tracking and analysis of past guest visits and reservations. Staff can view historical data, search past records, export reports, and manage guest status changes for analytical and operational purposes.

---

## 📊 History Types

### **Two Main History Views:**

1. **Guest History (Master)**
   - **Purpose**: Complete historical guest data with date range selection
   - **Access**: Main side menu navigation
   - **Features**: Full search, export, date filtering, status management

2. **Guest History (Today)**
   - **Purpose**: Today's rejected/cancelled guests only
   - **Access**: From Guest List → History button
   - **Features**: Limited to current day, status change capability

---

## 🔍 Guest History Interface

### **Main Components:**
- **Date Range Selector**: Choose start and end dates (Master view only)
- **Search Function**: Find guests by name or phone
- **Grid Layout**: Card-based guest information display
- **Export Function**: Download historical data
- **Status Management**: Change guest status (specific conditions)

### **Guest Card Information:**
Each guest card displays:
- **Date & Time**: Visit date and time stamp
- **Guest Name**: Customer name
- **Phone Number**: Contact information
- **Pax Information**: Current/Total guest count and table assignment
- **Minimum Charge**: Spending amount
- **Notes**: Special requests or information
- **Status**: Current guest status with color coding

---

## 🔄 Core Functions & Workflows

### 1. **VIEW HISTORICAL DATA**
**Action**: Access Guest History from side menu

#### **Process:**
1. Navigate to Guest History from main menu
2. System loads default date range (today)
3. Historical guest data displays in grid format
4. Scroll through guest cards to view information

#### **No Input Required**: Automatic data loading

### 2. **DATE RANGE SELECTION** (Master View Only)
**Action**: Click on date picker interface

#### **Interface Components:**
- **Start Date Picker**: "Start From" date selection
- **End Date Picker**: "Until" date selection
- **Visual Connector**: Line connecting date ranges

#### **Process:**
1. Click on either date picker
2. Date range picker dialog opens
3. Select start and end dates from calendar
4. Confirm selection
5. System reloads data for selected range
6. Updated guest history displays

#### **Date Constraints:**
- **Maximum Range**: Up to 2 years in the past
- **End Date**: Cannot exceed current date
- **Format**: Calendar-based selection interface

### 3. **SEARCH HISTORICAL GUESTS**
**Action**: Use search function in header

#### **Search Capabilities:**
- **Guest Name**: Search by full or partial name
- **Phone Number**: Search by contact number
- **Real-time Filtering**: Results update as you type

#### **Process:**
1. Click search icon in header
2. Enter search term (name or phone)
3. Results filter automatically
4. Clear search to return to full list

#### **No Additional Input Required**: Simple text search

### 4. **VIEW GUEST DETAILS**
**Action**: Click "See Info" button on guest card

#### **Information Displayed:**
- **Complete Guest Profile**: Name, phone, membership status
- **Visit Details**: Date, time, pax count, table assignment
- **Financial Information**: Minimum charge and payment details
- **Service Notes**: Special requests and staff notes
- **Status History**: Current and past status information

#### **No Input Required**: View-only function

### 5. **CHANGE GUEST STATUS** (Specific Conditions Only)
**Action**: Click status change icon (X) on eligible guest cards

#### **Eligibility Criteria:**
- **Status**: Must be "Rejected" (status 5)
- **Table Assignment**: Must be assigned to "GA-" tables
- **History Type**: Available in Master view only

#### **Required Fields:**
- **Reason**: Detailed text explanation for status change (Required)
- **Confirmation**: Verify intent to change status

#### **Process:**
1. Click X icon on eligible guest card
2. Dialog opens for status change
3. Enter detailed reason for change
4. Confirm status change to "Cancel After Close Bill"
5. Status updates immediately

#### **Status Change:**
- **From**: Rejected
- **To**: Cancel After Close Bill
- **Purpose**: Administrative correction for billing purposes

### 6. **EXPORT HISTORICAL DATA**
**Action**: Click "Export" button in header (Master view only)

#### **Export Features:**
- **Date Range**: Exports data for selected date range
- **Complete Data**: All guest information included
- **File Format**: Excel (.xlsx) format
- **Automatic Naming**: Includes outlet name and date range

#### **Process:**
1. Set desired date range
2. Click "Export" button
3. System generates Excel file
4. Download progress tracked
5. File saved with automatic naming

#### **File Naming Format:**
`[OutletName]_GUESLIST_HISTORY_[StartDate]_[EndDate].xlsx`

#### **No Additional Input Required**: Automatic export process

---

## 🎯 Quick Actions Summary

### **No Input Required:**
- **View History**: Automatic data loading
- **Search**: Real-time text filtering
- **View Details**: Complete guest information display
- **Export**: One-click data download
- **Refresh**: Reload current data

### **Input Required:**
- **Date Range Selection**: Calendar-based date picking
- **Status Change**: Reason explanation (specific conditions only)

---

## 📊 Data Analysis Features

### **Historical Insights:**
- **Visit Patterns**: Track guest frequency and timing
- **Table Utilization**: Monitor table assignment history
- **Service Quality**: Review notes and status changes
- **Financial Tracking**: Minimum charge and spending patterns

### **Operational Benefits:**
- **Guest Recognition**: Identify returning customers
- **Service Improvement**: Learn from past interactions
- **Capacity Planning**: Understand peak periods
- **Staff Training**: Review service quality indicators

---

## 🔐 Permission Requirements

### **Basic Staff:**
- View guest history
- Search historical records
- View guest details

### **Manager/Supervisor:**
- All basic functions
- Export historical data
- Change guest status (where applicable)
- Access extended date ranges

---

## 💡 Best Practices

### **Data Analysis:**
- Regularly review guest history for patterns
- Use date ranges to analyze specific periods
- Export data for detailed analysis and reporting
- Monitor guest satisfaction through status tracking

### **Search Efficiency:**
- Use partial names for broader search results
- Search by phone number for exact matches
- Clear search filters to return to full dataset
- Combine search with date filtering for precision

### **Status Management:**
- Only change status when administratively necessary
- Provide detailed reasons for all status changes
- Verify guest information before making changes
- Document reasons clearly for audit purposes

### **Export and Reporting:**
- Export data regularly for backup purposes
- Use appropriate date ranges for analysis
- Share reports with management for insights
- Maintain data privacy and security standards

---

## 🚨 Important Notes

### **Data Limitations:**
- Historical data availability depends on system implementation date
- Some older records may have limited information
- Export file size may be large for extended date ranges

### **Status Change Restrictions:**
- Status changes only available for specific conditions
- Changes are permanent and tracked for audit
- Requires appropriate permissions and justification

### **Performance Considerations:**
- Large date ranges may take longer to load
- Search functions work on currently loaded data
- Export operations may take time for large datasets

This guide covers the essential functions for accessing, analyzing, and managing historical guest data in the HolyWings Board system, enabling effective guest relationship management and operational insights.