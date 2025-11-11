# Layout Manager System - Business User Guide

## 🎯 Overview
The Layout Manager System allows administrators to create, edit, and manage restaurant floor plans. This visual editor enables drag-and-drop table positioning, category management, and layout configuration for different outlet areas or events.

---

## 🏗️ Layout Editor Interface

### **Main Components:**
- **Visual Canvas**: Interactive floor plan editing area
- **Table Categories Panel**: Draggable table types at bottom
- **Control Buttons**: Edit, Copy, Reset, Cancel, Save actions
- **Outlet Selector**: Choose different outlet layouts
- **Zoom Controls**: Pan and zoom functionality

### **Editor Modes:**
- **View Mode**: Display-only layout viewing
- **Edit Mode**: Full editing capabilities with drag-and-drop

---

## 🔄 Layout Management Workflows

### 1. **ENTER EDIT MODE**
**Action**: Click "Edit Layout" button (top right)

#### **Process:**
1. Click "Edit Layout" button
2. Interface switches to edit mode
3. Table categories panel appears at bottom
4. Tables become draggable
5. Control buttons become active

#### **No Input Required**: Simple mode switch

### 2. **ADD NEW TABLE**
**Action**: Drag table category from bottom panel to canvas

#### **Required Fields:**
- **Table Name**: Unique table identifier (Required)
  - Format examples: "A-1", "VIP-3", "Bar-5"
- **Table Status**: Select table availability (Required)
  - **Available for Walk-in**: Open for walk-in guests
  - **Available for Reservation**: Open for reservations
  - **Available for Both**: Open for both types
  - **Not Available**: Temporarily closed

#### **Process:**
1. Select table category from bottom panel
2. Long-press and drag to desired position on canvas
3. Release to place table
4. Dialog opens for table configuration
5. Enter table name and select status
6. Save to add table to layout

### 3. **EDIT EXISTING TABLE**
**Action**: Click on existing table in edit mode

#### **Editable Fields:**
- **Table Name**: Modify table identifier
- **Table Status**: Change availability settings

#### **Available Actions:**
- **Save**: Apply changes to table
- **Delete**: Remove table from layout

#### **Process:**
1. Click on table in edit mode
2. Modify table name or status
3. Choose Save or Delete
4. Changes apply immediately

### 4. **MOVE TABLE POSITION**
**Action**: Drag existing table to new position (edit mode)

#### **Process:**
1. Click and hold table
2. Drag to new position
3. Release to place
4. Position updates automatically
5. Ruler guides appear during drag

#### **Features:**
- **Snap to Grid**: Tables align to invisible grid
- **Boundary Limits**: Cannot drag outside canvas area
- **Visual Guides**: Ruler lines show positioning

---

## 🎛️ Layout Control Actions

### 1. **COPY LAYOUT**
**Action**: Click "Copy Layout" button

#### **Required Selection:**
- **Source Layout**: Choose layout to copy from dropdown

#### **Process:**
1. Click "Copy Layout" button
2. Select source layout from dropdown
3. Layout copies immediately
4. All tables from source appear on current layout
5. Save to make changes permanent

### 2. **RESET LAYOUT**
**Action**: Click "Reset" button

#### **Process:**
1. Click "Reset" button
2. All unsaved changes are discarded
3. Layout returns to last saved state
4. No confirmation required

#### **No Input Required**: Immediate reset action

### 3. **CANCEL CHANGES**
**Action**: Click "Cancel" button

#### **Required Confirmation:**
- **Confirm Cancellation**: Verify intent to discard changes

#### **Process:**
1. Click "Cancel" button
2. Confirmation dialog appears
3. Confirm to discard all unsaved changes
4. Return to view mode
5. Layout reverts to saved state

### 4. **SAVE LAYOUT**
**Action**: Click "Save" button

#### **Required Confirmation:**
- **Confirm Save**: Verify intent to save changes

#### **Process:**
1. Click "Save" button
2. Confirmation dialog appears
3. Confirm to save all changes
4. System uploads table positions and configurations
5. Success message appears
6. Return to view mode

---

## 📋 Table Categories

### **Available Categories:**
Different table types available for placement:
- **Standard Tables**: Regular dining tables
- **VIP Tables**: Premium seating areas
- **Bar Seating**: Counter-style seating
- **Booth Seating**: Enclosed seating areas
- **Outdoor Tables**: Patio or terrace seating

### **Category Properties:**
Each category has predefined:
- **Size**: Visual representation size
- **Capacity**: Default guest capacity
- **Minimum Cost**: Default spending requirement
- **Type**: Per Pax or Per Table charging

---

## 🎯 Layout Selection & Management

### **Outlet Selector:**
**Action**: Dropdown menu (if multiple layouts available)

#### **Function:**
- **Select Layout**: Choose different floor plan
- **Switch Areas**: Change between dining areas, floors, or event layouts
- **No Input Required**: Simple dropdown selection

### **Layout Types:**
- **Regular Layout**: Standard dining configuration
- **Event Layout**: Special event arrangements
- **Seasonal Layout**: Holiday or seasonal setups
- **Private Event**: Custom arrangements for private functions

---

## 🔧 Advanced Features

### **Zoom and Pan:**
- **Zoom In/Out**: Pinch or scroll to zoom
- **Pan View**: Drag to move around large layouts
- **Fit to Screen**: Auto-adjust zoom level

### **Grid Alignment:**
- **Snap to Grid**: Tables automatically align
- **Consistent Spacing**: Maintains professional appearance
- **Precise Positioning**: Ruler guides for accuracy

### **Visual Feedback:**
- **Drag Indicators**: Visual cues during table movement
- **Boundary Warnings**: Prevents invalid placements
- **Status Colors**: Different colors for table states

---

## 💾 Save and Version Control

### **Auto-Save Features:**
- **Draft Mode**: Changes saved locally during editing
- **Version History**: Previous layouts preserved
- **Rollback Option**: Revert to previous versions

### **Validation:**
- **Duplicate Names**: System prevents duplicate table names
- **Overlap Detection**: Prevents table overlapping
- **Boundary Checking**: Ensures tables stay within canvas

---

## 🔐 Permission Requirements

### **Admin Only:**
- Access to Layout Manager System
- Create and edit layouts
- Save layout changes
- Copy between layouts

### **Manager:**
- View layouts only
- No editing capabilities
- Can switch between existing layouts

---

## 💡 Best Practices

### **Layout Design:**
- Use consistent naming conventions (A-1, A-2, B-1, B-2)
- Maintain clear pathways between tables
- Group similar table types together
- Consider service flow and staff movement

### **Table Placement:**
- Leave adequate space between tables
- Position VIP areas strategically
- Ensure emergency exit accessibility
- Consider noise levels and privacy

### **Configuration Management:**
- Test layouts before saving
- Keep backup of working layouts
- Document layout purposes (regular, event, etc.)
- Regular review and updates

---

## 🚨 Important Notes

### **System Requirements:**
- Admin permissions required
- Stable internet connection for saving
- Modern browser for optimal performance

### **Limitations:**
- Cannot edit layouts currently in use
- Changes require save to take effect
- Some table categories may be outlet-specific

### **Troubleshooting:**
- Refresh if drag-and-drop becomes unresponsive
- Save frequently to prevent data loss
- Contact support for layout recovery issues

This guide covers the essential workflows for creating and managing restaurant layouts through the visual Layout Manager System, enabling efficient floor plan configuration and table management.