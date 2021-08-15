# Investigate a Dataset 
 Investigate a medical dataset (No show appointments) using python
In this project, I intend to invistigate "No-show appointments" dataset to answer the question (What are the factors that affecting the attendance of patients?)
 
## Dataset: 
This dataset collects information from 100k medical appointments in Brazil, and containing multiple features illustrated below:
<li>PatientId: Patient file number.</li>
<li>AppointmentID: Id of sceduled appointment.</li>
<li>Gender: F for female, and M for male.</li>
<li>ScheduledDay: The day patients book their appointments.</li>
<li>AppointmentDay: Appointment date.</li>
<li>Age: Patient age vary from 0 to 115 years.</li>
<li>Neighbourhood: Indicates the location of hospital.</li>
<li>Scholarship: Indicates whether or not the patient is enrolled in Brasilian welfare program. It's a binary feature where 0 means patient has no scholarship and 1 means the opposite.</li>
<li>Hipertension: Indicates whether or not the patient has Hipertension.</li>
<li>Diabetes: Indicates whether or not the patient has Diabetes.</li>
<li>Alcoholism: Indicates whether or not the patient diagnosed with alcoholism.</li>
<li>Handcap: Binary label in which 0 means patient has no handcap and 1 otherwise.</li>
<li>SMS_received: Binary label in which 0 means patient doesn't receive SMS for the appointment and 1 if the patient receive the SMS.</li>
<li>No-show: Containing two values "Yes" if the patient miss the appointment and "No" if the patient has attend the appointment.</li>

You can download the data [here](https://www.kaggle.com/joniarroba/noshowappointments)

## Result highlights:
<li>For Age variable, it contains a wide range of data but we can tell there is no dirct relation between Age and showing to the appointment.</li>    
<li>For Scholarship variable, the number of people with scholarship are much less than those with no scholarship. However, we can see the scholarship does not has the big impact on patient showing up to their appointments </li>
<li>Patient with handicap seem more likely to show to their appointment</li> 
<li> Surprisingly, patient who receive SMS and skip their appointments outnumber those who didn't</li>

## Dataset limitations:
There is some limitations in our data:
<li>There is a huge difference between the two groups in the data (no show patients and showed patients) which makes it difficult to infer the relationship between No-show and other independent variables.</li>
<li>All used variables (Except Age) are binary columns which restricts our usage of statistical methods.</li>
<li>Since most of our variables are categorical, we cannot infer a direct and clear relationship between No_show and other independent variables.</li>
<li> Lack of details, like in last result it showed that patients who receive SMS are more likely to skip their appointments, which make us wondering about the hospital policy of sending SMS.
