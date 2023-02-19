# Truck Rental Management Project
A .NET 5.0 responsive desktop application created with WPF, XAML, C#, Entity Framework, MVC framework, and connected to MySQL database to perform CRUD operations divided into 3 major components:
* Stock management - add, display, search, and update truck information
* Employee and Customer management - add, view, and update information
* Rental management - display, rent, and return trucks based on selected customer or dates. 

Login Validation was also implemented to access specific functionalities reserved only for Administrator use.

Packages installed using Tools> Nuget Package Manager > Manage Nuget Packages for Solution
* Microsoft.EntityFrameworkCore (7.0)
* Microsoft.EntityFramework.SqlServer (7.0)
* Microsoft.EntityFramework.Tools (7.0)

Scaffold-Command for Package Manager Console
```
Scaffold-DbContext "Server=citizen.manukautech.info,6306;Initial Catalog=DAD_Nicole;Persist Security Info=True;User ID=DAD_Nicole;Password=DAD_1935;MultipleActiveResultSets=False;Encrypt=True;TrustServerCertificate=True;Connection Timeout=30;" Microsoft.EntityFrameworkCore.SqlServer -Tables IndividualTruck-PB, TruckModel-PB, TruckFeature-PB, TruckRental-PB, TruckPerson-PB, TruckCustomer-PB, TruckEmployee-PB, Truck_Feature_Association-PB -OutputDir Models/DB
```

## Installation
* Clone repository using this link:
```
 https://github.com/nicolefabian/Truck-Rental-Management-Reports.git
 ```
 * Run MainWindows.xaml to start the application

## Database Diagram
![image](https://user-images.githubusercontent.com/102332600/219917689-acf2d933-7e05-4dfd-b0a2-a312dd91ea1f.png)

## Login page
<img width="660" height="400" src="https://user-images.githubusercontent.com/102332600/219915112-cfc5961d-a91a-443a-8917-d42b2049832c.png">

## Admin Dashboard
<img width="760" height="500" src="https://user-images.githubusercontent.com/102332600/219916380-21bd6478-53d7-4990-abb4-3e7596d0c670.png">

## Stock Management
#### Add New Truck
<img width="760" height="500" src="https://user-images.githubusercontent.com/102332600/219916628-cadba5e5-957b-4653-9894-c6ba69529a6e.png">

#### Update Truck Information
<img width="760" height="500" src="https://user-images.githubusercontent.com/102332600/219921737-500893ff-96ad-4fc0-b5ff-08514c5f81b0.png">

#### Display All Trucks 
<img width="760" height="500" src="https://user-images.githubusercontent.com/102332600/219921834-fcacdea1-d5fd-47d2-b0f9-41738082291a.png">

#### Display All Available for Rent Trucks
<img width="760" height="500" src="https://user-images.githubusercontent.com/102332600/219921915-659a9c1c-4bce-4117-8a1d-0c6cf82f8502.png">

#### Search By Specific Truck Model
<img width="760" height="500" src="https://user-images.githubusercontent.com/102332600/219918939-8f8e483d-f5ab-4fcd-af2c-6f823392b734.png">

## Employee and Customer Management
#### Add Employee
<img width="760" height="500" src="https://user-images.githubusercontent.com/102332600/219921984-b89dcd5c-1cee-44fc-87b1-1bf6f62a4731.png">

#### Update Employee
<img width="760" height="500" src="https://user-images.githubusercontent.com/102332600/219922002-caac4123-2c64-4bd3-b577-10fe6196c5e2.png">

#### Add Customer
<img width="760" height="500" src="https://user-images.githubusercontent.com/102332600/219922026-ea8b39ef-3fa3-4119-bdb9-75a8acdedd17.png">

#### Update Customer 
<img width="760" height="500" src="https://user-images.githubusercontent.com/102332600/219922040-47e7f272-9dd6-4ab1-aa5a-d494f42fb219.png">



