---

# ITS DTS Inventory Management Database

This project is a comprehensive Inventory Management System developed in Microsoft Access (.accdb). It is designed to help organizations efficiently track and manage inventory, suppliers, products, staff, and locations.

## Features

- **Inventory Tracking:** Monitor stock levels, item details, and movement history.
- **Product Management:** Add, edit, and categorize products and subcategories.
- **Supplier Management:** Maintain a list of suppliers with relevant contact information.
- **Employee/Staff Management:** Track staff responsible for inventory actions.
- **Location Management:** Organize items by storage locations (buildings, rooms, etc.).
- **Reporting:** Generate detailed reports for inventory, staff, suppliers, products, and locations.
- **User Interface:** Easy-to-use forms for data entry and navigation.
- **User Authentication:** Login form to restrict access to authorized users.
- **Macros and Automation:** Automated controls for navigation and reporting.

## Getting Started

### Requirements

- **Microsoft Access 2016 or later** (or Microsoft 365 with Access)
- Windows OS

### Installation

1. **Clone or Download the Repository**
   - Click “Code” > “Download ZIP” or use `git clone` to get the files.

2. **Open the Database**
   - Locate the file `ITS DTS INVENTORY MANAGEMENT DATABASE.accdb`.
   - Double-click to open in Microsoft Access.

3. **Enable Content**
   - If prompted, click “Enable Content” to allow database functionality/Macros.

### Usage

- **Login:** Start with the Login Form. Enter your credentials to access the main menu.
- **Navigation:** Use the main menu to access forms for Inventory, Products, Suppliers, Employees, Locations, Categories, and Subcategories.
- **Reports:** Access various reports from the main menu or dedicated buttons on forms.
- **Data Entry:** Use dedicated forms to add, edit, or remove records.

### Main Components

- **Forms:**  
  - MainMenuForm  
  - InventoryForm  
  - ProductForm  
  - SupplierForm  
  - EmployeeForm  
  - LocationForm  
  - CategoryForm  
  - SubcategoryForm  
  - StaffForm  
  - UserForm  
  - LogInForm  
  - ...and more

- **Reports:**  
  - SupplierReport  
  - StaffReport  
  - ProductReport  
  - LocationReport  
  - InventoryReport  
  - EmployeeReport  

- **Modules:**  
  - ModuleQUITandCONTROLSQL  
  - (For automation and control logic)

### Screenshots

_Add screenshots of your main forms and reports here for better documentation._

### Customization

Modify tables, forms, and reports as needed to fit your organization’s requirements. Use the built-in Visual Basic for Applications (VBA) editor for advanced customization.

## Contributing

1. Fork the repository.
2. Create your feature branch (`git checkout -b feature/YourFeature`).
3. Commit your changes (`git commit -am 'Add some feature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Open a Pull Request.

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.

## Authors

- [Emmanuel Fomundam](https://github.com/emmanuelfomundam)
- [Patrick Ekeu]
- Contributors welcome!

## Support

For issues, use the [GitHub Issues](https://github.com/emmanuelfomundam/Inventory-Management-Database/issues) page.

---

**Note:** This project contains Microsoft Access forms, reports, and modules that are not directly viewable as source code on GitHub. To edit or view form/report designs and VBA code, open the `.accdb` file in Microsoft Access.

---
