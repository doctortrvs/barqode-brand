# 03 — Design System

> This document defines the principles that govern Barqode's product interface.
>
> It is not a component library or UI kit. It defines how the interface should behave so every screen feels consistent, predictable and operational.

---

# Core Objective

Barqode is designed for operators completing real work under time pressure.

The interface should help them understand what is happening, identify what requires attention and take action without unnecessary delay.

Barqode should not make the operator study the software before they can use it.

The system should feel immediately understandable, even when the operation itself is complex.

Every screen should prioritise:

1. What has gone wrong.
2. What is blocked.
3. What is waiting.
4. What requires a decision.
5. What the operator should do next.
6. What is operating normally.
7. What can be reviewed later.

Barqode never makes the operator guess.

---

# Operator Context

There is no single universal dashboard for every Barqode user.

The information presented should reflect the role, permissions and responsibilities of the operator who has logged in.

A warehouse manager, picker, customer service operator and account administrator may require different views of the same operation.

However, orders remain the centre of the system.

Information should always connect back to the movement, fulfilment, exception or completion of an order.

The interface should adapt to the operator's responsibility without changing the underlying logic of the system.

---

# Grid

Barqode uses a modular grid inspired by the rhythm of a barcode.

Layouts are built from consistent vertical and horizontal intervals that create predictable structure throughout the interface.

Like a barcode, the grid is repetitive, ordered and scalable.

The grid exists to create rhythm, not decoration.

Alignment should make relationships between information immediately visible.

Elements that belong together should align.

Elements that serve different purposes should be clearly separated.

---

# Shape

Barqode uses restrained geometry.

Shapes should feel engineered, precise and dependable.

Corners are softened only where they improve usability and approachability.

The interface should never feel harsh, but it should never feel playful.

Rounded corners exist to reduce visual friction, not to create personality.

Shape may also communicate meaning.

Circles, triangles, squares, rectangles and other recognised forms may be used to distinguish different operational states.

These shapes must be applied consistently and should draw from globally recognised road, safety, emergency and industrial signage wherever possible.

Shape should improve recognition before the operator reads the accompanying text.

---

# Information Architecture

Barqode organises information around operational priority.

Information should not be structured only around product features, database architecture or internal departments.

It should be structured around what the operator needs to know and do.

Critical issues, blocked workflows, pending orders, exceptions and errors take priority because they prevent the warehouse from completing its work.

Analytics, trends and secondary information should never compete with an unresolved operational issue.

Whenever possible, the information required to understand and complete a task should be available within a single view.

The operator should not have to repeatedly move between pages, cards or windows to assemble the context required to make a decision.

Dropdowns, reveals, row expansion and contextual panels may be used to manage complexity without removing the operator from the current task.

The objective is not to show everything at once.

The objective is to make everything necessary immediately accessible.

---

# Information Hierarchy

Information should be prioritised according to its effect on the operation.

The default hierarchy is:

1. Critical issues
2. Blocked orders and workflows
3. Errors and exceptions
4. Actions requiring an operator decision
5. Pending and time-sensitive work
6. Active operational data
7. Completed work
8. Insights, analytics and historical information

This hierarchy may change according to the operator's role, but operational disruption should always receive priority.

Hierarchy should be communicated through:

- Position
- Line weight
- Font weight
- Font size
- Spacing
- Colour
- Shape
- Labels
- Action controls

Important information should be unmistakable without making the entire interface feel urgent.

When everything demands attention, nothing receives it.

---

# Attention System

Barqode uses colour, shape, position and count to direct attention.

Colour inside the product should primarily communicate meaning.

It should not be used decoratively or applied simply to make a screen feel more branded.

Colour may be used for:

- Critical issues
- Errors
- Warnings
- Notifications
- Status
- Direction
- Required actions
- Key operational information

The attention system should draw from globally recognised road signs, emergency signage, safety systems and industrial environments.

As a starting principle:

- Red communicates danger, failure or an operation that must stop.
- Amber or yellow communicates warning, risk or an issue requiring attention.
- Green communicates safe operation, successful completion or a valid direction forward.
- Blue communicates information, instruction or guidance.
- Grey communicates inactivity, unavailability, completion or secondary status.

Colour must never communicate meaning alone.

Every state should also be supported by shape, text, iconography or position.

Notification symbols may contain a number representing the volume of unresolved items.

For example, a warning symbol may display the number of active warnings inside it.

The symbol, colour and number should allow an operator to understand the type and scale of an issue before opening it.

The final definitions for individual symbols will be documented in `07-iconography.md`.

---

# Navigation

Navigation should always provide orientation.

The operator should know:

- Where they are.
- What area of the operation they are viewing.
- How they reached it.
- Where they can go next.

Every page should have a clear place within the system.

Navigation should feel like a well-organised warehouse.

Everything has an address.

Nothing feels lost.

Navigation provides structure and orientation.

Search provides speed.

The interface should never leave an operator asking:

> "Where am I?"

---

# Search

Search is a primary method of operating Barqode.

The system may contain large volumes of orders, shipments, products, clients, integrations and operational records.

The operator should not be expected to manually navigate through multiple sections to find a known item.

Search should be prominent, fast and available from the areas where it is most useful.

Where possible, search should recognise different forms of operational information, including:

- Order numbers
- Tracking numbers
- Customer names
- Product names
- SKUs
- Barcodes
- Client accounts
- Store names
- Carrier references
- Shipment references

Search results should preserve context and make the next relevant action clear.

The operator should be able to find information without first remembering where the system stores it.

---

# Filters and Saved Views

Filters are fundamental to Barqode.

Operators need control over large quantities of data and must be able to isolate exactly what is relevant to their current task.

Tables and operational views should provide the widest practical range of useful filters.

Filters may include:

- Status
- Date and time
- Client
- Warehouse
- Store
- Carrier
- Service
- Destination
- Order type
- Exception type
- Assigned operator
- Priority
- Integration
- Fulfilment stage

Filters should be visible or immediately accessible.

Common filters should not be hidden behind unnecessary menus.

Operators should be able to combine filters without losing clarity.

Frequently used combinations should be saved as named views.

Saved views allow the system to reflect how an individual operator or team works.

The operator should not have to rebuild the same working view every day.

Active filters must always be clearly visible.

The interface should never leave the operator unaware that a filtered view is being displayed.

---

# Actions

Actions should reflect priority.

Only the most important action within a view should appear as the primary action.

Secondary actions should be visually quieter.

Tertiary actions should appear as links, contextual controls or menu items.

The interface should not present multiple competing primary actions.

Actions should be placed close to the information they affect.

The operator should not have to leave the current context to perform a straightforward task.

Barqode should minimise the number of interactions required to complete an action.

A common action should not require five clicks when it can be completed safely in one or two.

The system may provide recommendations, guidance and automated support.

However, the operator remains responsible for the final decision.

Barqode assists the operator.

It does not silently make operational decisions on their behalf.

---

# Confirmation

Confirmation exists to prevent mistakes, not to slow the operator down.

An action should require confirmation when it:

- Changes important operational information.
- Affects multiple orders or records.
- Cannot be easily reversed.
- Could interrupt an integration or workflow.
- Creates financial, customer or fulfilment consequences.
- Has been triggered accidentally before.
- Is unusual within the current context.

A confirmation should clearly summarise:

- The action being performed.
- What will be affected.
- The immediate consequence.
- Whether the action can be reversed.

The confirmation should use specific language.

Avoid generic questions such as:

> "Are you sure?"

Instead, state exactly what the operator is confirming.

Routine, reversible and low-risk actions should not require unnecessary confirmation.

Where practical, an undo option is preferable to an additional confirmation step.

The objective is minimum friction with maximum operational certainty.

---

# Destructive Actions

Destructive actions require greater visual and written seriousness.

Examples include:

- Deleting an integration.
- Disconnecting a Shopify store.
- Removing a warehouse.
- Deleting inventory data.
- Cancelling an active shipment.
- Removing a client account.
- Deleting a saved configuration.
- Performing a permanent bulk action.

The interface must make it clear when an action cannot be undone.

Destructive confirmations should identify exactly what will be removed, disconnected or cancelled.

The destructive action should be visually distinct from the safe alternative.

The operator should never confirm a destructive action through an ambiguous button such as:

> "Continue"

The button should name the action directly, for example:

> "Disconnect Shopify store"

Where the operational consequence is severe, Barqode may require an additional verification step.

This should be reserved for genuinely high-risk actions.

Serious confirmation should protect the operation without turning every action into a process.

---

# Density

Density should match the task.

Operational interfaces should maximise useful information density where speed, monitoring and throughput are critical.

Decision-making interfaces may provide more space where comprehension and comparison require it.

Barqode should favour compact, organised views over unnecessarily spacious layouts.

Operators should be able to understand the state of their work without scrolling through large empty areas.

Whenever practical, the critical information for a task should fit within one view.

The ideal operational flow requires:

- No unnecessary scrolling.
- No unnecessary page changes.
- No unnecessary clicks.
- One clear action where possible.

This is an objective rather than an inflexible technical rule.

Content must never be compressed to the point that it becomes difficult to scan, understand or operate.

High density is useful only when the structure remains clear.

Line weight, spacing, typography, colour and grouping should separate information without wasting space.

Every unnecessary click introduces friction.

Every unnecessary scroll costs time.

Density is a tool for productivity, not a visual style.

---

# Data Presentation

Data should be presented in the format best suited to the task.

Tables are used for operational data.

Cards are used for insights and summaries.

Charts are used only when they reveal a pattern, comparison or change that would be difficult to understand through direct values.

We do not replace tables simply because cards or charts appear more modern.

The operator should not be required to interpret an abstract visual when a direct value would communicate the answer more quickly.

Data presentation should help the operator:

- Find the relevant record.
- Understand its current state.
- Compare it with other records.
- Identify an exception.
- Take the next action.

The correct format is the one that allows the work to be completed with the least uncertainty.

---

# Tables

Tables are Barqode's primary operational interface.

They are designed for scanning, filtering, sorting, comparing and acting on large volumes of information.

A Barqode table should support:

- Sticky column headers.
- A sticky first column where row identity must remain visible.
- Zebra striping where it improves row tracking.
- Movable columns through drag and drop.
- Adjustable column order.
- The ability to add or remove columns.
- Relevant filters.
- Sorting.
- Batch selection.
- Batch actions.
- Saved views.
- Clear row status.
- Contextual actions.
- Row expansion where additional information is required.

The most important identifying information should remain visible while the operator moves horizontally or vertically through the data.

Columns should reflect operational priority rather than database order.

Operators should be able to adapt a table to the task they are performing.

The system should remember an operator's table preferences where appropriate.

Batch actions should make repetitive work faster, but they must clearly state how many records will be affected.

Tables should remain readable at high density.

Compact does not mean cramped.

The operator should be able to scan a row, understand its status and find the relevant action without decoding the interface.

---

# Cards

Cards are used for insights, summaries, KPIs and clearly defined groups of related information.

They should not be used as the default container for every piece of content.

Cards are appropriate when the operator needs to understand:

- A total.
- A trend.
- A summary.
- A comparison.
- A contained operational insight.
- A small group of related actions.

Cards should not replace tables when the operator needs to scan or compare multiple records.

A card must have a clear purpose.

Decorative cards that exist only to divide the screen should be avoided.

Information can be separated through spacing, lines, typography and layout without placing every section inside a floating container.

Cards explain.

Tables operate.

---

# Charts

Charts should be used sparingly.

Operators should not have to decipher a chart to discover a fact that could have been stated directly.

Pie charts and other abstract visualisations should not be used when the relationship between values is difficult to judge accurately.

A chart is appropriate when it helps the operator identify:

- A trend over time.
- A sudden change.
- A recurring pattern.
- A meaningful comparison.
- A developing operational risk.

Every chart should answer a specific question.

The title, labels and surrounding information should make that question clear.

Important values should also be available as direct numbers.

Charts should not hide the underlying operational data.

Where action is required, the operator should be able to move from the chart to the relevant records.

Charts explain trends.

Tables complete work.

---

# Status

Status should be visible, consistent and immediately recognisable.

An operator should not have to open a record to understand its current state.

Status may be communicated through:

- Colour
- Shape
- Icon
- Label
- Position
- Line treatment
- Supporting text

Status labels should use clear operational language.

Avoid vague labels such as:

- Processing
- Pending
- Issue
- Failed

Where possible, make the status more specific, for example:

- Awaiting stock
- Label generation failed
- Carrier response pending
- Payment review required
- Ready to dispatch
- Dispatched

The same status should look and behave consistently throughout the system.

Colour should follow the principles defined by the attention system.

Status must never rely on colour alone.

---

# Alerts and Notifications

Alerts should be prioritised by operational consequence.

Critical issues should not be buried beneath informational notifications.

The system should distinguish between:

- Critical issues requiring immediate action.
- Errors preventing work from continuing.
- Warnings that may become operational problems.
- Decisions awaiting operator input.
- Informational updates.
- Completed or resolved events.

Each category should have a recognisable combination of colour, shape, icon and label.

Where multiple alerts of the same type exist, the interface may display their unresolved count within the relevant symbol.

Alerts should lead directly to the records or actions required to resolve them.

Opening an alert should not simply repeat the message.

It should provide the context and next action.

Resolved alerts should no longer compete for attention, but their history should remain available where operational accountability requires it.

---

# Loading and Progress

Loading states should communicate progress.

An indefinite spinning circle provides no useful operational information and should not be the default for actions that take measurable time.

Where possible, Barqode should display:

- A progress bar.
- Percentage completed.
- Current stage.
- Estimated time remaining.
- Number of items completed.
- Number of items remaining.

For example:

> 640 of 1,000 orders imported  
> 64% complete  
> Approximately 2 minutes remaining

The operator should know whether the system is working, how much work remains and whether they can safely continue with another task.

When the total duration cannot be calculated, the interface should still explain what the system is doing.

Loading language should be specific.

Avoid:

> "Please wait"

Prefer:

> "Generating 48 shipping labels"

Long-running processes should continue safely in the background where possible.

The operator should be able to leave the view and return without losing progress.

Completion and failure should be communicated clearly.

---

# Empty States

Empty states should guide operators towards becoming operational.

They are not opportunities for entertainment.

They are operational checklists.

Every empty state should explain:

- Why the view is empty.
- Whether the empty state is expected.
- What the operator needs to do next.
- The fastest path to becoming operational.

An empty result caused by active filters should be clearly distinguished from a system containing no data.

Progress should be clear, actionable and measurable.

An empty system should never feel broken.

It should feel ready.

---

# Errors

Errors should help operators recover, not simply report failure.

Every error should answer three questions:

1. What happened?
2. Why did it happen?
3. What should the operator do next?

Technical implementation details should never replace operational guidance.

Technical references may be made available for support or troubleshooting, but they should not be the primary message.

Errors should identify what has been affected.

For example:

- One order
- A group of orders
- A carrier connection
- An integration
- A warehouse
- The entire account

The interface should distinguish between an error that has stopped the operation and an error that affects only part of it.

Where possible, Barqode should provide a direct recovery action.

Examples include:

- Retry
- Reconnect
- Correct address
- Select another service
- Review affected orders
- Contact administrator

The operator should always leave an error with a clear path forward.

The objective is not to explain the system.

The objective is to get the operation moving again.

---

# AI Operators

Barqode's AI should be agentic and task-specific.

AI should not exist as a general-purpose feature placed on every screen.

Barqode may provide specialist agents designed to perform clearly defined operational tasks.

Each agent should:

- Have a specific area of responsibility.
- Operate within defined limits.
- Use the context required for that task.
- Explain what it has done.
- Identify decisions that still require the operator.
- Avoid acting outside its assigned responsibility.

An agent should behave like an expert in one operational task, not a chatbot pretending to understand everything.

The operator should always know when an agent is acting, what information it is using and what changes it proposes or completes.

High-risk decisions must remain with the operator.

AI should reduce repetitive work and surface relevant information.

It should not reduce accountability.

---

# Desktop and Mobile

Desktop is the primary Barqode operating environment.

Complex tasks that require significant context, comparison or operational control should be completed on a desktop interface.

These may include:

- Resolving complex exceptions.
- Configuring integrations.
- Reviewing large tables.
- Performing high-risk actions.
- Managing warehouse settings.
- Investigating multi-step operational issues.

Mobile is a companion to the desktop system.

It should focus on:

- Notifications.
- Critical issue awareness.
- Simple approvals.
- Basic status checks.
- Time-sensitive acknowledgements.
- Straightforward operational actions.

For example, an operator may accept a new delivery from mobile where the action is clear and low risk.

Mobile should not attempt to reproduce every desktop capability within a smaller screen.

Information or actions requiring substantial context should direct the operator to the desktop system.

Mobile keeps the operator connected.

Desktop provides full operational control.

---

# Accessibility

Accessibility is fundamental to operational reliability.

Barqode may be used by people of different ages, abilities, experience levels and working conditions.

The interface must account for:

- Colour blindness.
- Reduced vision.
- Low-light environments.
- Poor-quality displays.
- Glare.
- Distance from monitors.
- Different screen sizes.
- Motor limitations.
- Time pressure.
- Cognitive load.
- Operators wearing gloves or other equipment.

Colour must never be the only way information is communicated.

Text and interactive controls must maintain sufficient contrast.

Important controls should have clear and practical target sizes.

Labels should be understandable without relying only on icons.

Focus states should be visible.

Core controls should support keyboard access where practical, even though keyboard-only operation is not assumed to be the primary workflow.

Accessibility is not an additional layer applied after the interface has been designed.

It is part of making the system dependable for every operator.

---

# Final Principle

> **Barqode never makes the operator guess.**

A successful Barqode interface communicates the critical and necessary information an operator needs within one clear view.

It does not create an information dump.

It uses hierarchy, line weight, typography, spacing, colour, shape and action controls to make complex operations understandable.

It minimises unnecessary scrolling, navigation and interaction.

It keeps additional context available without forcing the operator into a chain of new windows, cards or screens.

The operator should know:

- What is happening.
- What requires attention.
- What is blocked.
- What decision must be made.
- What will happen next.
- Whether an action has succeeded.

A great operational interface is not measured by how beautiful it looks.

It is measured by how quickly operators can complete their work with confidence.

Every design decision should reduce uncertainty, minimise friction and help the operation move forward.
