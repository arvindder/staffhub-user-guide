# Compensatory Leave Request

</div>

<div class="wiki-content">

**Compensatory Leave is a leave that is granted to an Employee as compensation for working overtime or on holidays.**

ERPNext allows Employees to request for Compensatory Leaves through the Compensatory Leave Request document. It is necessary that the dates mentioned in the Compensatory Leave Request should be in default Holiday List and also that the Employee should have their attendance marked Present.

> **Note:** Only Leave Types which are marked as 'Is Compensatory' can be selected in the Compensatory Leave Request.

To access Compensatory Leave Request, go to:

> Home \> Human Resources \> Leaves \> Compensatory Leave Request

## 1. Prerequisites

Before creating a Compensatory Leave Request, it is necessary to create the following documents:

- [Employee](https://docs.frappe.io/erpnext/v13/user/manual/en/human-resources/employee)
- [Leave Period](https://docs.frappe.io/erpnext/v13/user/manual/en/human-resources/leave-period)
- [Leave Type](https://docs.frappe.io/erpnext/v13/user/manual/en/human-resources/leave-type)
- [Leave Policy](https://docs.frappe.io/erpnext/v13/user/manual/en/human-resources/leave-policy)
- [Leave Allocation](https://docs.frappe.io/erpnext/v13/user/manual/en/human-resources/leave-allocation)
- [Holiday List](https://docs.frappe.io/erpnext/v13/user/manual/en/human-resources/holiday-list)
- [Attendance](https://docs.frappe.io/erpnext/v13/user/manual/en/human-resources/attendance)

## 2. How to create a Compensatory Leave Request

1.  Go to Compensatory Leave Request list, click on New.

2.  Select the Employee ID. Once selected, The Employee Name and Department will get automatically fetched.

3.  Select Leave Type.

4.  Select Work From Date and Work End Date. This is the date of the day(s) the Employee has worked on, during a Holiday.

5.  Enter the Reason.

6.  Save and Submit.

    <img src="./media/compensatory-leave.png" class="screenshot" alt="Compensatory Leave Request" />

On submitting the Compensatory Leave Request, ERPNext updates the Leave Allocation record for the Compensatory leave type, allowing the Employee to apply for leaves of this type later on depending upon the number of leaves left.

## 3. Related Topics

1.  [Leave Application](https://docs.frappe.io/erpnext/v13/user/manual/en/human-resources/leave-application)
2.  [Leave Encashment](https://docs.frappe.io/erpnext/v13/user/manual/en/human-resources/leave-encashment)
3.  [Leave Block List](https://docs.frappe.io/erpnext/v13/user/manual/en/human-resources/leave-block-list)