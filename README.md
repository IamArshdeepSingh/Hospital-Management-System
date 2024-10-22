# Description :
It's a web application for managing hospitals rooms and determining the patient's priority for isolation. The app provides a centralised hub for managing the patients and planning their distribution across hospital’s rooms. 

It allows nurses to keep track of the patients and their diseases in real time and to have an overview over the patients and rooms, and better manage the rooms assignment across patients.

1. Install the dependencies

   ```bash
   npm install
   ```

2. Run in the Ternimal 
   ```bash
   node start
   ```
3. Open the url `http://localhost:3000` in browser for seeing the result

### Dashboard

Data about patients and rooms is available here. The page is split into three tables. 

To clear the red warning sign you need to go on the patient’s personal page. To do that, you have to double click on his name. By clicking on the ‘Update button’ on the bottom of the page, the patient’s diagnosis in updated for the next 24 hours (consequently, the red warning sign disappears).

### Add patient page

You can add a new patient in the system with his personal details and his diseases. The application automatically computes the score of the patient based on the entered diseases

### Patient page

Double click on a patient name on the dashboard to get here.

### System settings

The control center of the application. It allows users to manage the diseases & rooms of the Hospital and create new accounts


