# Build Plan: Car Rental CRM System

**Client:** DriveEase Rentals
**Total action points:** 8

This plan was generated from the approved action points. Items are ordered by build dependency — start at the top and work down.

---

### 1. Develop Fleet Management Module

_Category: `feature` · Priority: `high`_

Create a module where every car in the fleet has a profile with registration, model, year, current location, status, and service history.

**Acceptance criteria:**
- Module allows adding, editing, and viewing car profiles.
- Status can be updated and reflects availability, rented, in service accurately.
- Service history can be logged and viewed for each vehicle.

---

### 2. Implement Booking System with Availability Calendar

_Category: `feature` · Priority: `high`_

Develop a booking system that allows staff to check car availability by date range and lets them create new bookings while preventing double bookings.

**Acceptance criteria:**
- Staff can view car availability by selecting date ranges.
- System prevents double bookings for the same car within overlapping dates.
- Successful booking creation confirms and logs the booking.

---

### 3. Create Customer Management Module

_Category: `feature` · Priority: `high`_

Build a CRM to store customer profiles with documents like CNIC and license, rental history, and notes.

**Acceptance criteria:**
- Customer profiles can be created with required documents uploaded (CNIC, license).
- Rental history is automatically logged against customer profiles.
- Notes can be added and viewed for each customer.

---

### 4. Develop Payments and Invoicing Module

_Category: `feature` · Priority: `high`_

Record payments against bookings, generate invoices, and produce daily/monthly collection reports.

**Acceptance criteria:**
- Staff can log payments received via cash, bank transfer, and Easypaisa for each booking.
- Invoices can be generated for completed bookings.
- Daily and monthly payment collection reports are automatically generated and accessible.

---

### 5. Setup Branch-level Access Control

_Category: `feature` · Priority: `high`_

Ensure that staff at each branch only see their location's data while the owner has access to all branches.

**Acceptance criteria:**
- System users can be assigned branch-level permissions.
- Accessible data is limited to the user's assigned branch, except for the owner.
- Owner account can view and manage data across all branches.

---

### 6. Design Public Booking Inquiry Form

_Category: `ui` · Priority: `medium`_

Create a simple booking page on the website where customers can check car availability and submit booking inquiries.

**Acceptance criteria:**
- Booking inquiry form is accessible via the website.
- Customers can check availability and submit inquiries without creating an account.
- Submitted inquiries appear in the CRM for staff follow-up.

---

### 7. Build Vehicle Handover/Return Checklist

_Category: `feature` · Priority: `medium`_

Develop a checklist for vehicle handover and return, allowing staff to record fuel level, mileage, and condition with photo uploads.

**Acceptance criteria:**
- Staff can fill out a digital checklist during handover and return processes.
- Photos can be uploaded and attached to the booking record.
- Data captured includes fuel level, mileage, and vehicle condition, which are accessible for review.

---

### 8. Create Owner Dashboard with Reports

_Category: `feature` · Priority: `low`_

Implement a dashboard for the owner to monitor fleet activity and daily/week/monthly performance metrics.

**Acceptance criteria:**
- Dashboard displays daily operational metrics such as cars rented, cash collected, and overdue bookings.
- Weekly reports include revenue per branch, and monthly reports show overall revenue, expenses, and top customers.
- Reports are visually accessible and exportable.

