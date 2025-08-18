# Process and Tasking Module

The **Process and Tasking** module provides a reusable framework for managing repeatable business processes, tasks, and automations across your applications. Built on the [Government Data Models](https://github.com/microsoft/gov-datamodels), this module centralizes process configurations so they can be applied consistently to any record type in your system.

With **process templates**, organizations can model anything from a simple one-step action to complex, multi-step, hierarchical workflows. These processes can be tied to specific record types (such as People, Cases, Requests, or Investigations), ensuring users are presented with the right processes at the right time. Each process execution is tracked through **action items**, which record assignments, progress, approvals, and automation outcomes.

Key features include:

* **Reusable process templates** – Define and manage structured workflows once and apply them to many record types.
* **Action item tracking** – Automatically create task records to capture progress, notes, and completion status.
* **Approval support** – Enable structured approval steps with options to integrate Microsoft Teams approvals for notifications and decision tracking.
* **Automation steps** – Configure process steps to create Teams collaboration channels, generate documents from templates, or trigger other common actions.
* **Ad hoc flexibility** – Create standalone or supplemental action items at any point to adapt to real-world scenarios.

By combining these capabilities, the module helps standardize implementation plans, increase accountability, and provide visibility into process progress across teams. This turns apps into **actionable, process-driven tools** that support mission outcomes with efficiency and repeatability.

