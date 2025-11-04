# Leave Period

**A Leave Period is a duration of time for which leaves are allocated.**

Most companies manage leaves based on a Leave Period, corresponding to a calendar year or the fiscal year. To access Leave Period, go to:

> Home \> Human Resources \> Leaves \> Leave Period

## 1. Prerequisites

Before creating a Leave Period, it is advisable to create the following:

1.  [Company](https://docs.frappe.io/erpnext/v13/user/manual/en/setting-up/company-setup)
2.  [Holiday List](https://docs.frappe.io/erpnext/v13/user/manual/en/human-resources/holiday-list)

## 2. How to create a Leave Period

1.  Go to Leave Period list, click on New.
2.  Enter the From Date and To Date of the Leave Period.
3.  Select the Company name for which the Leave Period is applicable.
4.  Save.

The Leave Period also allows you to select a [Holiday List for Optional Leaves](https://docs.frappe.io/erpnext/v13/user/manual/en/human-resources/holiday-list) (optional) which will be considered for allocating Optional Leaves for the period.

> **Note: The 'Holiday List for Optional Leaves' is not the same as the usual 'Holiday List'. This list will contain a list of optional holidays only. 'Holiday List for Optional Leaves' can be created from the [Holiday List](https://docs.frappe.io/erpnext/v13/user/manual/en/human-resources/holiday-list) document. You can create two Holiday Lists for a Leave Period; one containing the usual set of holidays and the other for optional holidays.**

Additionally, you can check the 'Is Active' checkbox if you want to enable this particular Leave Period.

<img src="./media/leave-period.png" class="screenshot" alt="Leave Period" />

## 3. Granting leave using Leave Period

> In version 12, leaves could be granted via Leave Period through the "Grant Leaves" button. In version 13, leaves will be granted using [Leave Policy Assignment](https://docs.frappe.io/erpnext/v13/user/manual/en/human-resources/leave-policy-assignment).

Once the information is saved, the Leave Period will also be used as a tool to help you grant leaves for a category of employees.

The **Grant** button will generate Leave Allocations based on the [Leave Policy](https://docs.frappe.io/erpnext/v13/user/manual/en/human-resources/leave-policy) applicable to each Employee. You can allocate leaves based on [Employee Grade](https://docs.frappe.io/erpnext/v13/user/manual/en/human-resources/employee-grade), [Department](https://docs.frappe.io/erpnext/v13/user/manual/en/human-resources/department) or [Designation](https://docs.frappe.io/erpnext/v13/user/manual/en/human-resources/designation) as shown below.

<img src="./media/grant-button.gif" class="screenshot" alt="Leave Period" />

## 3. Related Topics

1.  [Leave Allocation](https://docs.frappe.io/erpnext/v13/user/manual/en/human-resources/leave-allocation)
2.  [Leave Policy](https://docs.frappe.io/erpnext/v13/user/manual/en/human-resources/leave-policy)
3.  [Leave Type](https://docs.frappe.io/erpnext/v13/user/manual/en/human-resources/leave-type)