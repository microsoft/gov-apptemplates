
# Release 1.0.2.0 (Jun-06, 2025)

- **Major Update: Action Items Overhaul**
	- Replaced the legacy Action Assignments feature with a new Action Items table and custom page, providing a more flexible and scalable approach to tracking actions and assignments. The Action Assignments component will be deprecated in a future release.

- **New "Action Tracker" Model-Driven App**
	- Introduced the Action Tracker app, designed as a low-entry, departmental solution for basic action and assignment tracking. This app streamlines task management and improves visibility for teams.

- **Action Items Enhancements**
	- Added Action Items to the Process and Tasking model-driven app, including a baseline Action Item form for consistent data entry and management.
	- Added a Primary Action Item field to the Person table, enabling direct association of individuals with their key tasks or responsibilities.
	- Developed a new Action Item custom page to replace the previous Action Assignment page, improving user experience and functionality.
	- Added a new Action Items custom page to support both record-specific visualization and top-down hierarchical management of action items.
	- Updated the All Action Items view by moving the Parent Action Item to the first column, making parent/child relationships more intuitive and easier to navigate.

- **Process Steps and Templates**
	- Added a Process Templates - All Items view, supporting better organization and management of reusable process templates.

- **Document Management Improvements**
	- Replaced the Document Information form with a new "Document - Process and Tasking" form, eliminating co-dependency with the MS Fed - Core Document component and improving modularity.
	- Added a Document "Quick Create - Process and Tasking" form for rapid document creation and association within process workflows.

---

This release delivers significant improvements to action tracking, process management, and document handling within the Process and Tasking module. Implementors can leverage these updates to enhance departmental task coordination, streamline process automation, and maintain clear records of actions and supporting documents. The new features are designed for extensibility and can be integrated with other modules to support broader enterprise scenarios.