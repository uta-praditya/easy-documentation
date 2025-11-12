# HolyWings Board - User Guide

## 🎯 Overview
HolyWings Board is a comprehensive hospitality management system designed for both restaurants and clubs. The platform enables staff to efficiently manage reservations, guest lists, table layouts, ticketing, and daily operations through an intuitive interface.

### **Venue Types Supported:**
- **Restaurants**: Traditional dining with table reservations and course selection
- **Clubs**: Entertainment venues with ticketing, VIP areas, and event management
- **Hybrid Venues**: Combined restaurant-club operations with flexible configurations

### **Key Benefits:**
- Real-time reservation and guest management
- Visual table layout with drag-and-drop functionality
- Ticketing system for events and club operations
- Comprehensive reporting and analytics
- Multi-user access with role-based permissions
- Mobile-optimized interface for on-the-go management

### **System Requirements:**
- Modern web browser (Chrome, Safari, Firefox, Edge)
- Stable internet connection
- Mobile device or tablet for optimal experience

---

## 🏭 Venue Types & Operations

### **Restaurant Mode**
**Focus**: Dining experience with table service and course management

#### **Key Features:**
- **Table Reservations**: Time-based bookings with party size
- **Course Selection**: Menu-driven dining experiences
- **Service Flow**: Arrival → Seating → Ordering → Service → Payment
- **Table Turnover**: Optimized seating for multiple seatings

#### **Typical Operations:**
- Breakfast, lunch, and dinner service
- Private dining events
- Special occasion bookings
- Walk-in management

### **Club Mode**
**Focus**: Entertainment and event management with ticketing

#### **Key Features:**
- **Event Ticketing**: Entry-based admissions with capacity limits
- **VIP Management**: Premium areas with bottle service
- **Capacity Control**: Real-time headcount and area limits
- **Event Flow**: Ticket Purchase → Entry → Area Assignment → Service

#### **Typical Operations:**
- Evening entertainment events
- DJ performances and live shows
- VIP bottle service
- Private party bookings

### **Hybrid Operations**
**Flexibility**: Switch between restaurant and club modes

#### **Common Scenarios:**
- **Day/Night Transition**: Restaurant during day, club at night
- **Event Nights**: Special club events in restaurant space
- **VIP Dining**: Premium restaurant service within club environment
- **Flexible Layouts**: Reconfigure space based on operational needs

---

## 🏠 Main Navigation

### **Dashboard**
- **Purpose**: Overview of outlet information and daily notifications
- **Features**: Outlet details, operating hours, contact info, announcements
- **Actions**: View outlet status, check notifications

### **Side Menu Navigation**
Access different modules through the side menu:
- **Reservation Management**: Handle all booking types and statuses
- **Guest List**: Manage walk-in guests and seating
- **Guest Layout**: Visual table management with drag-and-drop
- **Manager Operations**: Administrative functions and daily tasks
- **Guest History**: Historical data and analytics
- **Settings**: User preferences and system configuration

### **Top Navigation Bar**
- **Outlet Selector**: Switch between multiple outlets (if applicable)
- **Date Picker**: Navigate to specific dates
- **Notifications**: System alerts and updates
- **User Profile**: Account settings and logout

---

## 📋 Core Features

### 1. **Reservation Management** → [📋 Detailed Guide](RESERVATION_BUSINESS_FLOW.md)
**Purpose**: Handle all types of customer bookings

#### **Types Available:**
- **Regular Reservations**: Standard table bookings for dining
- **Ticket Reservations**: Event-based reservations with entry tickets for clubs
- **Restaurant V2**: Enhanced dining experience with course selection
- **Standing Reservations**: Recurring VIP bookings for regular guests
- **Club Events**: Special event bookings with capacity management
- **VIP Packages**: Premium experiences with bottle service and reserved areas

#### **Main Actions:**
- **Search**: Find reservations by name, phone, or ID
- **QR Search**: Scan QR codes for quick lookup
- **Export**: Download reservation data
- **Filter**: View by date and status
- **Status Updates**: Change reservation status through swipe actions

#### **Status Flow:**
```
Pending → Confirmed → Arrived → Seated → Completed
         ↓
    Cancelled/No Show
```

#### **Quick Actions:**
- **Swipe Right**: Primary actions (Confirm, Arrive, Complete)
- **Swipe Left**: Communication (Call, WhatsApp, View Details)
- **Long Press**: Additional options menu

### 2. **Guest List Management** → [📋 Detailed Guide](GUEST_LIST_BUSINESS_FLOW.md)
**Purpose**: Track walk-in guests and manage seating

#### **Core Functions:**
- **Add Guests**: Register new walk-in customers
- **Track Pax**: Monitor total and current guest count
- **Status Management**: Update guest status (Waiting, Seated, Completed)
- **Search**: Find guests by name or details

#### **Main Actions:**
- **Search**: Find guests quickly
- **History**: View past guest visits
- **Export**: Download guest data
- **Add**: Register new guests

### 3. **Guest Layout Management** → [📋 Detailed Guide](GUEST_LAYOUT_BUSINESS_FLOW.md)
**Purpose**: Visual venue management with drag-and-drop functionality

#### **Core Functions:**
- **Interactive Layout**: Visual representation of venue floor (restaurant/club)
- **Drag-and-Drop**: Assign guests to tables or areas by dragging
- **Real-time Updates**: Live table/area status changes
- **Space Assignment**: Allocate specific tables, booths, or VIP areas to guests

#### **Features:**
- Visual venue representation (tables, bars, dance floors, VIP areas)
- Live status updates across all areas
- Guest assignment via drag-and-drop
- Capacity tracking for different zones
- Special area management (VIP sections, private rooms)

### 4. **Layout Manager System** → [📋 Detailed Guide](LAYOUT_MANAGER_BUSINESS_FLOW.md)
**Purpose**: Configure and edit venue layouts for restaurants and clubs

#### **Core Functions:**
- **Layout Editor**: Visual positioning tool for tables, bars, and areas
- **Area Categories**: Organize spaces by type (dining, bar, VIP, dance floor)
- **Layout Controls**: Copy, Reset, Cancel, Save changes
- **Multi-Layout Support**: Different configurations for day/night operations

#### **Main Actions:**
- **Edit Layout**: Modify table/area positions
- **Copy Layout**: Duplicate existing layouts
- **Save Changes**: Commit layout modifications
- **Reset**: Restore previous layout
- **Switch Modes**: Toggle between restaurant and club layouts

### 5. **Manager Operations** → [📋 Detailed Guide](MANAGER_OPERATIONS_BUSINESS_FLOW.md)
**Purpose**: Administrative functions and daily operations

#### **Available Functions:**
- **Daily Checklists**: Opening and closing procedures
- **Table Management**: Lock tables, configure settings
- **Financial Operations**: Handle reschedules and refunds
- **Off Schedule**: Manage non-operational periods

#### **Menu Options:**
- Daily Operational Lists (Opening/Closing)
- Lock Table Management
- Off Schedule Management
- Reschedule List
- Refund List
- Outlet Layout (Admin only)
- Table Settings (Admin only)

### 6. **Guest History** → [📋 Detailed Guide](GUEST_HISTORY_BUSINESS_FLOW.md)
**Purpose**: View historical guest and reservation data

#### **Core Functions:**
- **Historical Data**: Past guest visits and reservations
- **Analytics**: Guest behavior tracking
- **Export**: Download historical reports
- **Search**: Find past records

### 7. **Settings & Configuration**
**Purpose**: System configuration and user preferences

#### **Available Settings:**
- **User Profile**: Personal information and preferences
- **Notification Settings**: Alert preferences and timing
- **Display Options**: Theme, language, and layout preferences
- **Venue Configuration**: Operating hours, contact details, venue type
- **Operational Mode**: Switch between restaurant/club/hybrid modes
- **Integration Settings**: Third-party service connections

### 8. **Ticketing System** (Club Mode)
**Purpose**: Manage event tickets and admissions

#### **Core Functions:**
- **Ticket Sales**: Process ticket purchases and payments
- **Entry Management**: Check-in guests with tickets or guest lists
- **Capacity Monitoring**: Track venue capacity in real-time
- **Guest List Management**: VIP and complimentary entry lists

#### **Features:**
- QR code ticket scanning
- Real-time capacity tracking
- VIP and general admission tiers
- Group booking management
- Door staff interface for quick check-ins

---

## 🚀 Getting Started

### **First Time Setup:**
1. **Login**: Use provided credentials to access the system
2. **Select Outlet**: Choose your working outlet (if multiple available)
3. **Review Dashboard**: Familiarize yourself with today's overview
4. **Check Settings**: Verify notification and display preferences

### **Daily Workflow:**

#### **Restaurant Operations:**
1. **Opening**: Complete [daily checklist](MANAGER_OPERATIONS_BUSINESS_FLOW.md#daily-operational-list-opening)
2. **Reservations**: Check [today's bookings](RESERVATION_BUSINESS_FLOW.md)
3. **Walk-ins**: Manage [guest list](GUEST_LIST_BUSINESS_FLOW.md) and [seating](GUEST_LAYOUT_BUSINESS_FLOW.md)
4. **Closing**: Complete [closing procedures](MANAGER_OPERATIONS_BUSINESS_FLOW.md#daily-operational-list-closing)

#### **Club Operations:**
1. **Setup**: Configure [event layout](LAYOUT_MANAGER_BUSINESS_FLOW.md)
2. **Tickets**: Process [ticket reservations](RESERVATION_BUSINESS_FLOW.md#ticket-reservations)
3. **Entry**: Manage [guest check-ins](GUEST_LIST_BUSINESS_FLOW.md)
4. **VIP Service**: Handle [premium areas](GUEST_LAYOUT_BUSINESS_FLOW.md)

---

## 📚 Quick Reference

### **Feature Guides:**
- [📋 Complete Reservation Management](RESERVATION_BUSINESS_FLOW.md) - All booking types and workflows
- [👥 Guest List Management](GUEST_LIST_BUSINESS_FLOW.md) - Walk-in guests and waiting lists
- [🗺️ Visual Layout Control](GUEST_LAYOUT_BUSINESS_FLOW.md) - Drag-and-drop table management
- [⚙️ Manager Operations](MANAGER_OPERATIONS_BUSINESS_FLOW.md) - Admin functions and daily tasks
- [🏗️ Layout Configuration](LAYOUT_MANAGER_BUSINESS_FLOW.md) - Floor plan editor (Admin only)
- [📊 Guest History & Analytics](GUEST_HISTORY_BUSINESS_FLOW.md) - Historical data and reports

### **🎯 Common Tasks:**

#### **Reservations:**
- **New Booking**: [Reservation → Add New → Fill Details](RESERVATION_BUSINESS_FLOW.md#create-reservation)
- **Check-in Guest**: [Find Reservation → Swipe Right → Arrived](RESERVATION_BUSINESS_FLOW.md#confirmed--arrived)
- **Cancel Booking**: [Find Reservation → Swipe Right → Cancel](RESERVATION_BUSINESS_FLOW.md#any-status--cancelled)

#### **Walk-in Management:**
- **Add Walk-in**: [Guest List → Add → Fill Details](GUEST_LIST_BUSINESS_FLOW.md#add-new-guest)
- **Assign Table**: [Guest Layout → Drag Guest to Table](GUEST_LAYOUT_BUSINESS_FLOW.md#drag-guest-to-table)
- **Complete Service**: [Guest Layout → Tap Table → Close](GUEST_LAYOUT_BUSINESS_FLOW.md#close-table)

#### **Daily Operations:**
- **Opening Setup**: [Manager Operations → Daily Checklist](MANAGER_OPERATIONS_BUSINESS_FLOW.md#daily-operational-list-opening)
- **Lock Tables**: [Manager Operations → Lock Table Management](MANAGER_OPERATIONS_BUSINESS_FLOW.md#lock-table-management)
- **View Reports**: [Guest History → Set Date Range → Export](GUEST_HISTORY_BUSINESS_FLOW.md#export-historical-data)

#### **Layout Management:**
- **Edit Layout**: [Layout Manager → Edit Mode → Drag Tables](LAYOUT_MANAGER_BUSINESS_FLOW.md#enter-edit-mode)
- **Add Tables**: [Layout Manager → Drag Category → Configure](LAYOUT_MANAGER_BUSINESS_FLOW.md#add-new-table)
- **Save Changes**: [Layout Manager → Save → Confirm](LAYOUT_MANAGER_BUSINESS_FLOW.md#save-layout)

---

## 🔗 Feature Integration

### **Connected Workflows:**
- **Reservation → Layout**: [Confirmed reservations](RESERVATION_BUSINESS_FLOW.md) appear as [yellow tables](GUEST_LAYOUT_BUSINESS_FLOW.md#table-status-color-coding)
- **Guest List → Layout**: [Walk-in guests](GUEST_LIST_BUSINESS_FLOW.md) can be [dragged to tables](GUEST_LAYOUT_BUSINESS_FLOW.md#drag-and-drop-operations)
- **Manager Operations → Layout**: [Locked tables](MANAGER_OPERATIONS_BUSINESS_FLOW.md#lock-table-management) show as [reserved](GUEST_LAYOUT_BUSINESS_FLOW.md#reserved-table-info)
- **All Activities → History**: Every action is tracked in [Guest History](GUEST_HISTORY_BUSINESS_FLOW.md)

---

## 🆘 Quick Troubleshooting

### **Common Issues:**
- **Can't assign table**: Check if table is [available (green)](GUEST_LAYOUT_BUSINESS_FLOW.md#table-status-color-coding)
- **Missing reservation**: Use [QR search](RESERVATION_BUSINESS_FLOW.md#qr-search) or check [different dates](RESERVATION_BUSINESS_FLOW.md#filter-actions)
- **Layout not saving**: Ensure [admin permissions](LAYOUT_MANAGER_BUSINESS_FLOW.md#permission-requirements)
- **Export not working**: Check [date range limits](GUEST_HISTORY_BUSINESS_FLOW.md#date-constraints)

---

## 📱 Mobile vs Desktop

### **Mobile Optimized:**
- Touch-friendly [drag-and-drop](GUEST_LAYOUT_BUSINESS_FLOW.md#mobile-vs-desktop-usage)
- [Swipe actions](RESERVATION_BUSINESS_FLOW.md#quick-actions) for reservations
- Pinch-to-zoom on [layouts](GUEST_LAYOUT_BUSINESS_FLOW.md#layout-controls)

### **Desktop Features:**
- Larger data displays
- Keyboard shortcuts
- Multi-panel views
- Enhanced [export capabilities](GUEST_HISTORY_BUSINESS_FLOW.md#export-historical-data)

---

## 🎓 Training Path

### **New Staff (Start Here):**
1. Read this overview guide
2. Practice with [Guest List Management](GUEST_LIST_BUSINESS_FLOW.md)
3. Learn [Guest Layout](GUEST_LAYOUT_BUSINESS_FLOW.md) basics
4. Master [Reservation Management](RESERVATION_BUSINESS_FLOW.md)

### **Advanced Users:**
1. [Manager Operations](MANAGER_OPERATIONS_BUSINESS_FLOW.md) for daily tasks
2. [Guest History](GUEST_HISTORY_BUSINESS_FLOW.md) for analytics
3. [Layout Manager](LAYOUT_MANAGER_BUSINESS_FLOW.md) for admins

---

## 📞 Support & Resources

### **Need Help?**
- Check specific feature guides for detailed steps
- Review [permission requirements](MANAGER_OPERATIONS_BUSINESS_FLOW.md#permission-requirements) if access is denied
- Contact system administrator for layout or configuration issues

### **Best Practices:**
- Follow the [workflows](RESERVATION_BUSINESS_FLOW.md#status-flow) for consistent operations
- Use [cross-references](#feature-integration) to understand connected features
- Regular [data exports](GUEST_HISTORY_BUSINESS_FLOW.md#export-historical-data) for backup and analysisns:**
1. **Morning Setup**: Review opening checklist and today's reservations
2. **Active Management**: Handle dining reservations and walk-ins
3. **Real-time Updates**: Monitor table status and guest flow
4. **End of Day**: Complete closing procedures and export reports

#### **Club Operations:**
1. **Event Preparation**: Review event details and ticket sales
2. **Guest Management**: Handle VIP reservations and general admission
3. **Capacity Monitoring**: Track venue capacity and area utilization
4. **Event Closure**: Complete event procedures and financial reconciliation

---

## 🎯 Common Actions

### **Search Functions:**
- **Text Search**: Find by name, phone, or ID
- **QR Search**: Scan QR codes for quick access
- **Filter**: Date and status-based filtering

### **Export Functions:**
- **Excel Export**: Download complete data
- **Date Range**: Select specific periods
- **Status Filter**: Export by status

### **Status Updates:**
- **Swipe Actions**: Left/right swipe for quick actions
- **Button Actions**: Tap buttons for status changes
- **Confirmation**: Some actions require confirmation or additional input
- **Bulk Actions**: Select multiple items for batch operations

### **Communication Tools:**
- **Call**: Direct phone calls to guests
- **WhatsApp**: Send messages via WhatsApp
- **SMS**: Text message notifications
- **Email**: Automated confirmation emails

---

## 🔄 Status Management

### **Reservation Statuses:**
- **Blue**: Pending, Waiting Payment
- **Green**: Confirmed, Waiting Seat  
- **Dark Green**: Arrived, Assigned
- **Red**: Cancelled, No Show, Walkout

### **Guest Statuses:**
- **Waiting**: Guest registered, waiting for table
- **Seated**: Guest assigned to table
- **Completed**: Service finished

### **Table/Area Statuses:**
- **Available**: Ready for new guests
- **Occupied**: Currently in use
- **Reserved**: Held for specific reservation
- **Locked**: Temporarily unavailable
- **VIP Reserved**: Premium area held for VIP guests
- **Event Setup**: Area being prepared for special events

---

## 🔐 User Permissions

### **Role-Based Access Control:**

#### **Staff Level:**
- View and update reservation status
- Add walk-in guests and ticket holders
- Basic search and filter functions
- View venue layout (read-only)
- Check-in guests for events

#### **Supervisor Level:**
- All Staff permissions
- Cancel reservations with reason
- Modify guest details
- Access to daily reports
- Lock/unlock tables

#### **Manager Level:**
- All Supervisor permissions
- Access manager operations
- Handle refunds and reschedules
- Modify venue layouts (restaurant/club modes)
- User management (add/remove staff)
- Event management and capacity control
- Full reporting and analytics

#### **Admin Level:**
- Full system access
- Outlet configuration
- System settings management
- Integration management
- Audit logs and system monitoring

---

## 📱 Quick Tips

### **Efficient Navigation:**
- Use search functions to find records quickly
- Swipe left/right on cards for quick actions
- Use filters to focus on relevant data
- Export data for reporting needs

### **Status Updates:**
- Swipe right for main actions (Confirm, Arrive, etc.)
- Swipe left for communication (Call, WhatsApp, Info)
- Some actions require additional input (PIN, reason, pax count)

### **Data Management:**
- Export data regularly for backup
- Use date filters to manage large datasets
- Search by multiple criteria (name, phone, ID)

---

## 🔧 Troubleshooting

### **Common Issues:**

#### **Login Problems:**
- Verify internet connection
- Check username/password accuracy
- Clear browser cache if needed
- Contact admin for password reset

#### **Sync Issues:**
- Refresh the page
- Check internet connectivity
- Log out and log back in
- Report persistent issues to support

#### **Performance Issues:**
- Close unnecessary browser tabs
- Clear browser cache
- Use recommended browsers
- Check device storage space

### **Error Messages:**
- **"Access Denied"**: Insufficient permissions for action
- **"Connection Lost"**: Internet connectivity issue
- **"Session Expired"**: Need to log in again
- **"Data Not Found"**: Record may have been deleted or moved

---

## 📞 Support & Contact

### **Getting Help:**
- **In-App Help**: Click the help icon for contextual assistance
- **User Manual**: Refer to detailed business flow guides
- **Training Videos**: Access video tutorials (if available)
- **Support Team**: Contact technical support for urgent issues

### **Reporting Issues:**
1. Note the exact error message
2. Record steps that led to the issue
3. Include screenshot if possible
4. Contact support with details

### **Feature Requests:**
- Submit suggestions through the feedback form
- Discuss with your manager for evaluation
- Participate in user feedback sessions

---

## 📊 Reports & Analytics

### **Available Reports:**

#### **Restaurant Reports:**
- **Daily Summary**: Reservations, walk-ins, revenue overview
- **Table Utilization**: Occupancy rates, peak dining hours
- **Menu Performance**: Popular dishes, course selection trends

#### **Club Reports:**
- **Event Summary**: Ticket sales, attendance, revenue
- **Capacity Analytics**: Peak hours, area utilization
- **VIP Performance**: Bottle service, premium area usage

#### **Universal Reports:**
- **Guest Analytics**: Repeat customers, preferences, trends
- **Staff Performance**: Booking efficiency, response times
- **Financial Reports**: Revenue tracking, payment methods
- **Cross-Venue Analysis**: Performance across different operational modes

### **Export Options:**
- **Excel Format**: Detailed data for analysis
- **PDF Reports**: Formatted summaries
- **CSV Files**: Raw data for external processing
- **Email Reports**: Automated daily/weekly summaries

---

## 🔄 Updates & Maintenance

### **System Updates:**
- Updates are deployed automatically
- New features announced via notifications
- Training provided for major changes
- Downtime scheduled during off-peak hours

### **Data Backup:**
- Automatic daily backups
- Export important data regularly
- Historical data retained per company policy
- Recovery procedures available if needed

---

This comprehensive guide covers HolyWings Board's main features and operations. For detailed workflows and specific procedures, refer to the individual business flow guides for each module.