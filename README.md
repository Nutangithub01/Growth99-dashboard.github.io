# Growth99-dashboard.github.io

This file consists of html tags, internal css and jquery/js used within it. The important points used within this project are:- 

Notification Bell & Panel:
•	The structure includes a notification bell icon, a notification counter, and a sliding side panel for notifications.
•	Each notification item in the panel includes a title, message, timestamp, and a delete icon.
•	Onclick of each notification item, popup appears having title, detailed message, timestamp.

Sidebar:
•	The sidebar is positioned on the left side and has a fixed height of 100% of the viewport.
•	It includes four menu items: Dashboard, Reports, Settings, and Logout, each with a corresponding Font Awesome icon.
•	The sidebar also contains a logo at the top and a footer at the bottom for additional information.

Collapsible Sidebar:
•	The sidebar can be collapsed into a narrow version, showing only the icons, to save space on smaller screens or when toggled manually.
•	The collapse feature is handled by adding or removing the collapsed class to the sidebar and adjusting the main content's margin accordingly.

Responsive Design:
•	On smaller screens (max-width: 767px), the sidebar collapses and is hidden off-screen by default. It can be toggled using a hamburger menu button.
•	The hamburger menu appears only on mobile devices, allowing users to show or hide the sidebar.

Custom CSS and Bootstrap:
•	Custom styles are used for the sidebar's appearance, while Bootstrap's grid system and utilities ensure responsive behavior.

