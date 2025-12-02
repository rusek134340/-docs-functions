1. Register Patient

Function Name: Register Patient  
Input: Personal data (name, DOB, contact, insurance)  
Process: Validate input → create Patient object → store in persistence laye  
Output: Patient ID  
Feedback: “Patient successfully registered”  
KPIs: Registration time, data completeness, input error rate

2. Schedule Appointment

Function Name: Schedule Appointment  
Input: Patient ID, Staff ID, datetime, reason  
Process: Check staff availability → detect conflicts → store appointment  
Output: Appointment ID  
Feedback: “Appointment scheduled”  
KPIs: Conflict rate, scheduling success rate, staff availability utilization

3. Record Clinical Visit

Function Name: Record Clinical Visit  
Input: Appointment ID, visit notes, diagnosis, prescriptions  
Process: Create clinical record → attach to patient → update appointment status  
Output: Updated patient medical record  
Feedback: “Clinical visit recorded”  
KPIs: Record completeness, record update time, documentation accuracy

4. Generate Invoice

Function Name: Generate Invoice  
Input: Services rendered, pricing info  
Process: Calculate totals → apply insurance rules → generate invoice entry  
Output: Invoice ID  
Feedback: “Invoice generated”  
KPIs: Billing accuracy, invoice generation time, unpaid invoice rate

5. Process Payment

Function Name: Process Payment  
Input: Invoice ID, payment amount, payment method  
Process: Verify invoice → apply payment → update billing status  
Output: Payment confirmation  
Feedback: “Payment processed”  
KPIs: Payment success rate, outstanding balance, transaction time
