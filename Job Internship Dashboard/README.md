# Job & Internship Dashboard

Interactive Tableau dashboard for exploring global job and internship postings.

## 📊 Features
- **Multi-worksheet design** (6 sheets) showing company size, job roles, country comparisons, maps, etc.
- **Advanced filters**: qualification, job title, experience, salary, company size, job portal, gender preference, country/continent lists.
- **Time-based visibility**: specific charts render **only between 3 PM–5 PM (or 3 PM–6 PM) IST** using calculated fields.
- **Dynamic “No Data” message** when filters return zero records.
- **Map integration**: click latitude/longitude to open Google Maps.

## 🛠 Setup
1. Clone this repo and download the Tableau workbook (`.twbx` or `.twb`).
2. Open in **Tableau Desktop** (or publish to **Tableau Server/Online**).
3. Connect to the provided dataset (CSV/DB) containing fields such as  
   `Country`, `Job Title`, `Qualification`, `Work Type`, `Experience`,  
   `Salary`, `Company Size`, `Latitude`, `Longitude`, `Job Posting Date`,  
   `Preference`, `Job Portal`, etc.
4. Make sure calculated fields (e.g., `TimeFilter`, `IsAsianCountry`, `IsAfricanCountry`) are included.

## 🚀 Usage
- Use filter cards on the dashboard to interact with data.  
- Charts governed by `TimeFilter` display only during the defined IST window.  
- Click map points to open the exact location in Google Maps.


