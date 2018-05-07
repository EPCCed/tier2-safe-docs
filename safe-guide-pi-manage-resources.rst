Managing your allocated resources
-------------------

What is "period allocation"?
~~~~~~~~~~~~~~~~~~~~~~~~
A period allocation contains AUs which have been allocated for a project to use within the specified time period. Period allocations are valid for a specific resource pool (machine) and have definitive start and end dates, which usually coincide with the dates of your EPSRC grant or Research Allocation Panel (RAP) project. When the end date of the period allocation passes, any leftover CPUh will automatically expire.

You can view and manage your period allocation via SAFE.

`Login to SAFE <https://www.archer.ac.uk/tier2/>`__. Then:

#.    Go to the Menu Projects managed and select the project you wish to work with
#.    This will display a screen with a variety of options for managing the project.
#.     Click on Manage Project Resources
#.     Click on Manage Group Time Allocations 

You will then see the details of your allocation. *Please check them carefully to make sure you are looking at the correct one.* 

- **Resource Pool (machine). **
- **Amount of CPUh**
- **Dates** It is possible to have multiple successive period allocations, but they can never overlap if they are for the same resource pool. Before carrying out any project management tasks please check the dates and make sure you are managing the correct allocation. You can skip between the period allocations by clicking on the ">>>" (next period) and "<<<" (previous) buttons at the bottom of the page.

You can manage the allocation by setting up project groups and allocating CPUh to project groups. Project management tasks for the period allocation can be carried out at any time, but the allocation will be active, i.e. usable, only between the specified dates. Thus, you can set up project groups in advance.

How can I set up project groups within my project?
~~~~~~~~~~~~~~~~~~~~~~~~
Project groups can be used to administer time and other resources within your project.

#.  `Login to SAFE <https://www.archer.ac.uk/tier2/>`__. Then:
#.    Go to the Menu Projects managed and select the *project* you wish to create the group
#.    This will display a screen with a variety of options for managing the project.
#.     Click *Project Group Administration*
#.     Click *Add new sub-group*
#.    This will take you to the screen for creating new project groups. Fill in a suffix to your project code in the box: for example, if your project code is t01, you might chose t01-a. Project group names cannot be more than eight characters in total.

#. If this group is to be used for **guest budget** users, tick "Guest Budget".

   A *guest budget* is a budget in one project which is set up to permit access requests from users in a different project.
#.  click *Create*

Single user accounts can only belong to one project group.

How can I delete a project group?
~~~~~~~~~~~~~~~~~~~~~~~~
You can only delete a project group if it has no resources or members. You must remove all its members and all its time. 

#.    Go to the Menu *Projects managed* and select the project you wish to delete the sub-group from.
#.    Click on *Project Group Administration*
#.    Select the project sub-group you want to delete. You will only be able to select the groups which have no time, space or members.
#.    Click *Delete*. This will ask for confirmation that you wish to delete the sub-group. Click *Yes*.

Deleting a group involves removing its various directories. 

How can I administer time within my project?
~~~~~~~~~~~~~~~~~~~~~~~~
Time is measured in CPU hours (CPUh), and is held in *budgets*. Every project group has its own budget. There are always at least two project groups in your project:

-    The *general group*, which has the same code as the project itself. Every member of the project is a member of this group, so the time in its budget is available to them all.
-   The *reserve* project group, which has a name of form t01-reserve. It has no members, so no one can use the time in its budget. This budget can be used to hold time which the PI or project manager wishes to hold in reserve for later use.

Initially, all your time is in the general group's budget. If you are happy with all your users using the same budget, you can leave things as they are.

If you wish to divide the time up between groups, you can create a project group for each group. In this case you will probably want to move all the time out the general group, since this can be used by everyone.

You may wish to give time just to a single user. This is a special case of a project group: one with only one member.

The reserve budget is provided so that if you wish you can control the use of time by your project members: you can keep most of the time in your reserve budget, and move it to the other budgets as required. We recommend that you should do this, even if you don't need to create other project groups.

How can I move time between budgets?
~~~~~~~~~~~~~~~~~~~~~~~~

`Login to SAFE <https://www.archer.ac.uk/tier2/>`__. Then:

#.    Go to the Menu Projects managed and select the project you wish to work with. This displays a panel with information for the project.
#.    Click *Manage Project Resources*
#.    Click *Manage Group Time Allocations for Cirrus* 
#.    Click the *Move From* and *Move To* buttons of the project groups you want to change
#.    Enter the number of CPUh you wish to move in the box
#.    Click the *Submit Budget Allocation* Changes button.

Do not forget the last step, or nothing will happen.

How can I allocate time to a single user?
~~~~~~~~~~~~~~~~~~~~~~~~
As all the time in a project group is shared by all its members, the only way to reserve some time for a single user is to create a project group for that user alone.

#.    Create a new project group for the user. For example, if we are in project *t01* and the user is *fred*, you might call the new project group *t01-fred*
#.    Add the user to the new project group
#.    Move the time you wish the user to have into the new project group

Remember that time in the general group's budget is accessible to all, so you will probably want to move all of the project's time away from there.