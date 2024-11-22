
# ServiceNow Incident Monitoring Report

## Project Overview
This project aims to create a report in the ServiceNow platform to monitor the states of incidents. The report provides insights into incidents in the "New," "On Hold," and "In Progress" states, helping assignment group managers prioritize and resolve issues efficiently.

## Steps to Implement

### Step 1: Access ServiceNow Developer Instance
1. Open your ServiceNow Developer Instance.
2. Click on 'All' in the navigation menu.

### Step 2: Create a New Report
1. Search for 'Reports' and click on 'Create New'.
2. Provide a suitable name for the report.
3. Set the 'Source Type' to 'Table'.
4. Select the 'Incident' table as the data source.
5. Click 'Next'.

### Step 3: Configure Report Settings
1. Choose 'Type' as 'Pie Chart' for visualization.
2. Click on the funnel icon to add a filter condition:
   - **Field:** State
   - **Operator:** isoneof
   - **Value:** New, On Hold, In Progress
3. Click 'Next'.

### Step 4: Group and Save Report
1. Group the data by 'Assignment Group'.
2. Click 'Next' and then 'Save' to save the report.
3. Run the report to verify the results.

### Step 5: Add Report to Dashboard
1. Open the ServiceNow Dashboard.
2. Provide a title for the dashboard.
3. Add the newly created report to the dashboard.
4. Save the dashboard in the 'Incident Overview' folder.

## Benefits
- Enables efficient incident prioritization and resolution.
- Improves team performance tracking.
- Enhances service quality through timely issue management.

## License
This project is licensed under the MIT License. See the LICENSE file for details.
