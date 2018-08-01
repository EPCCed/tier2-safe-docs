SAFE for Project Leaders
========================

Project Leaders can manage the resources and users associated with 
their projects through SAFE.

Getting Started
---------------

Your allocation has been set up as a project on the service. Your first steps.
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Here are some of the things you should consider doing; not all of them
will be needed for every project.

#. Change your own SAFE password
#. Set up an account on appropriate Tier-2 facilities for yourself
#. Make sure other project users get registered
#. Designate one or more users as managers of your project

How to get your own account on the service machine
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

If you are not going to work on the Tier-2 systems yourself, you do not need to
do this. You can administer your project through SAFE alone. But if you
want an account on a Tier-2 system follow the procedure described in
:doc:`safe-guide-users`.

Viewing your allocated resources
--------------------------------

`Login to SAFE <https://www.archer.ac.uk/tier2/>`__. Then:

#. From the Projects managed' menu select the project you want
   to see the resources for.
#. At the bottom of the page you will see a summary of the resources
   remaining for the selected project.
   
 
 
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

- **Resource Pool (Cirrus).**
- **Amount of CPUh**
- **Dates** It is possible to have multiple successive period allocations, but they can never overlap if they are for the same resource pool. Before carrying out any project management tasks please check the dates and make sure you are managing the correct allocation. You can skip between the period allocations by clicking on the ">>>" (next period) and "<<<" (previous) buttons at the bottom of the page.

You can manage the allocation by setting up project groups and allocating CPUh to project groups. Project management tasks for the period allocation can be carried out at any time, but the allocation will be active, i.e. usable, only between the specified dates. Thus, you can set up project groups in advance.

How can I set up project groups within my project?
~~~~~~~~~~~~~~~~~~~~~~~~
Project groups can be used to administer time and other resources within your project.

#.  `Login to SAFE <https://www.archer.ac.uk/tier2/>`__. Then:
#.    Go to the Menu Projects managed and select the *project* you wish to create the group
#.    This will display a screen with a variety of options for managing the project.
#.     Click *Project Groups* to expand this section
#.	Click on the first entry (which will match the project ID)
#.     Click *Add new sub-group*  at the bottom of the section
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

Remember that time in the general group's budget is accessible to all, so you may want to move all of the project's time away from there.

   

Managing Project Users
----------------------

How can project users get registered?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

You must not apply for Tier-2 facility accounts on behalf of other users, or let
others use accounts that belong to you. Account sharing is strictly
forbidden on Tier-2 facilities. Every user must register on
SAFE and then apply for their own machine account.

In order to get an account, a potential user needs to know your project
code. This is included in the email which SAFE sends to you, as PI, when
your project is set up.

Give potential users your project code and then ask them to register
on SAFE and request a Tier-2 system account using the instructions at :doc:`safe-guide-users`.

When a user requests an account in your project then you will receive a 
mail from SAFE asking you to login to approve or reject this request.
To do this:

#. `Login to SAFE <https://www.archer.ac.uk/tier2/>`__.
#. You should see the menu *Projects managed* is highlighted orange,
   then this indicates that there is a request for project membership.
   Now you have to accept (or reject) each user's request.
#. Go to the Menu *Projects managed* and select *project requests* for
   the appropriate project. You will see the details of the user who has applied.
#. Click the button next to the user
#. You will see the user's details, and at the bottom of the page
   buttons to accept or reject them

If you now accept the user, they will get an account. This is the last
chance to stop someone who should not be there! Take a few seconds to
check the user's details, especially their email address, to make sure
that they are who they say they are. Please check their nationality as
well: it's your responsibility to make sure this is right.

When you accept a user, an automatic request is generated to
create the account on the appropriate Tier-2 system. When this has been done, the
user is emailed; allow a working day for this. The user can then login
to SAFE and pick up their initial password for the facility account.

How can I designate a user as a project manager?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

A project manager can do everything in a project that a PI can do,
except designate another project manager. You can designate as many
project managers as you wish.

#. Make sure the user has an account in your project.
#. `Login to SAFE <https://www.archer.ac.uk/tier2/>`__.
#. Go to the Menu *Projects managed* and select the *project* you wish
   to appoint a project manager for. This will display a screen with a
   variety of options for managing the project.
#. Click *Project Group Administration*
#. Click *Add manager*
#. A drop down list will be displayed which contains all the users
   within the project. Select the user you wish to make a manager and
   click *Add*

Tracking your Project Usage
---------------------------

How to check the current state of your project's resources
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Login to SAFE. Then:

#. Go to the Menu *Projects managed* and select the *project* you wish
   to work on.
#. Under *Project groups* you can see the current state of each project.
   If SAFE administers disk quotas on a system, you will also see these, together
   with how much of is in use.

If a project group's use of a quota is getting close to the maximum, it
is highlighted in pink. Note that not all Tier-2 facilities manage disk quotas
through the SAFE so this functionality may not be available for your project.

The budget values displayed are updated every morning, and the values
shown for disk use are updated four times a day. For this reason, these
values may not all be completely up-to-date. If there is a lot of
activity in your project, the numbers shown could be significantly
different from the current ones.

How to track what my project's users and project groups are doing?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

This can be done using the Report Generator

#. Login to SAFE.
#. Go to the Menu *Service information* and select *Report generator*
#. Choose a report and its format: HTML, PDF or CSV (comma-separated values—good
   for input to Excel, *etc.*)
#. Fill in the details required for the report.
#. Click *Generate Report*

