# Debt-Collection-Plan-Tracker
Debt Recovery Plan Tracker is a purpose-built, single-page web application designed for debt collection call centres to efficiently log and manage client payment arrangements in real time.

It provides:

Transaction Type Handling: Supports three main transaction types —
• PIF (Payment in Full)
• SIF (Settlement in Full)
• Payment Plans (Scheduled Repayments)
Each type dynamically updates the form controls to fit the data needed.

Down Payment Management: If a Payment Plan is selected, users can record whether a down payment was taken and capture its amount separately.

Real-Time Tracking:

Automatically records the exact timestamp of each transaction.

Displays live counters for the number of PIFs, SIFs, and Plans achieved during a shift.

Continuously updates the total amount of money collected for the day.

Transaction Log Table:

Lists all entries with transaction type, amount, and timestamp.

Offers a one-click delete option for incorrect entries.

Export Capability:

Agents can download the day's transaction log as a CSV spreadsheet.

Includes custom filename input for easier record management and upload to internal systems.

User Interface:

Built with a dark mode, neon-themed design to reduce eye strain over long shifts.

Clean, simple layout for quick entry between calls.

Fully responsive, ensuring usability across desktops, tablets, or call centre kiosks.

Technical Stack:

HTML5 for structure

CSS3 (including modern gradients and neon effects) for styling

Vanilla JavaScript for all dynamic behaviour

No external dependencies — lightweight, fast loading, fully offline-capable if needed.
