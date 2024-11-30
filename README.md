# Inventory Management System App

## Overview
The Inventory Management System App is a custom-built solution using Microsoft PowerApps to simplify inventory management. This app enables users to efficiently track stock levels, automate reorder processes, and maintain transparency across departments. It integrates seamlessly with SharePoint or other data sources, ensuring centralized data management and compatibility with Office 365 tools.

---

## Features
- **User-Friendly Interface**:
  - Intuitive navigation for adding, viewing, editing, and deleting inventory items.
- **Inventory Management**:
  - Manage inventory with key data fields such as Item Name, SKU, Quantity, Category, Location, and Reorder Level.
- **Reorder Alerts**:
  - Receive alerts when inventory levels fall below the reorder threshold.
  - Option to send notifications to the procurement team using Power Automate.
- **Barcode/QR Code Integration** (Optional):
  - Quickly update inventory with barcode or QR code scanning.
- **Search and Filter**:
  - Search and filter items by name, category, location, or other criteria.
- **Role-Based Access**:
  - Admin users have full control, while staff users can view and update stock levels based on assigned permissions.
- **Mobile and Desktop Accessibility**:
  - Optimized for use on both mobile devices and desktops.

---

## Technology Stack
- **Microsoft Power Apps**:
  - User Interface and Logic
- **Microsoft Power Automate**:
  - Notifications and process automation for reorder alerts
- **SharePoint/Excel/Dataverse**:
  - Backend for storing and retrieving inventory data
- **Office 365 Integration**:
  - Ensures compatibility with existing tools
- **Barcode/QR Code Integration**:
  - For fast inventory updates

---

## Key Features in Detail
1. **Home Screen**:
   - Quick navigation options for managing inventory.
   - Visual alerts for low-stock items needing reordering.
2. **Inventory List**:
   - A gallery A displaying all items with details like name, code, quantity, and reorder status.
   - Filter and sort inventory by categories such as item type or supplier.
3. **Add/Edit Inventory Item**:
   - A form for adding or updating items, including details like SKU, quantity, supplier, and reorder levels.
4. **Reorder Alerts**:
   - Low-stock items are flagged with color-coded indicators.
   - Option to integrate with Power Automate for notifications.
5. **Search and Filter**:
   - Easily locate items with a search bar and advanced filter options.
6. **Role-Based Access**:
   - Admins have full permissions, while staff access is limited to specific functionalities.

---

## Data Source
The app supports multiple data storage options:
- **SharePoint List**:
  - Ideal for medium-sized inventories and Office 365 integration.
- **Excel**:
  - Suitable for simpler setups and smaller inventories.
- **Dataverse**:
  - Recommended for larger inventories or advanced integration needs.

---

## Benefits
- Streamlines inventory tracking and management processes.
- Automates reorder alerts to reduce manual effort.
- Enhances accuracy with barcode/QR code integration.
- Provides centralized data access across mobile and desktop platforms.

---

## Future Enhancements
- Integration with Power BI for advanced analytics and reporting.
- Support for multi-warehouse inventory management.
- Predictive analytics for inventory forecasting.

---

