Design a modern, clean, and responsive Admin Panel UI for a laundry and tailoring service application, strictly following the Ant Design (antd) design system. The UI should cater to the following requirements based on provided Admin User Stories, using antd components and styling:

1. **View All Orders**:

   - Create a dashboard with an antd `Table` component to display all orders.
   - Table columns: Client Name, Service Type (e.g., Laundry, Tailoring), Description (text summary), Status (e.g., Pending, In Progress, Completed), Pickup/Delivery Time.
   - Implement antd `Table` features: sorting for each column, pagination, and a filter dropdown for Status and Service Type.
   - Add an antd `Input.Search` component above the table for searching orders by client name or order ID.
   - Ensure the table is responsive for desktop (1920x1080) and mobile (375x667) screens, using antd’s responsive design principles.
   - Apply antd’s hover effects and row selection styling for interactivity.

2. **Update Order Status**:

   - Design an antd `Modal` for updating the status of a selected order.
   - Inside the modal, include an antd `Select` component with options for status (e.g., Pending, In Progress, Completed, Cancelled).
   - Add an antd `Button` (type="primary") to confirm status changes.
   - Include a preview of an antd `Notification` or `message` component to indicate that a user notification will be triggered after status update.
   - Ensure the modal is centered, with antd’s standard animations and styling.

3. **Set Pickup/Delivery Time**:
   - Within the same antd `Modal` or a separate antd `Form` section, include fields to set pickup and delivery times.
   - Use antd `DatePicker` components (with time selection enabled) for picking pickup and delivery times.
   - Add validation (using antd `Form` rules) to ensure delivery time is after pickup time.
   - Include an antd `Button` (type="primary") to save changes.
   - Use antd `Form.Item` for clear labeling and error messages.

**Design Guidelines**:

- **Style**: Strictly adhere to Ant Design’s design system, using its component library (e.g., Table, Modal, Form, Select, DatePicker, Button, Input.Search).
- **Color Palette**: Use antd’s default colors (Primary: rgb(82, 142, 111), Success: #52c41a, Error: #ff4d4f, Warning: #faad14) with a neutral background (#f0f2f5).
- **Typography**: Use antd’s recommended fonts (e.g., -apple-system, BlinkMacSystemFont, ‘Segoe UI’, Roboto) with antd’s typography hierarchy (Title, Text, Link).
- **Icons**: Use antd’s `Icon` components (e.g., SearchOutlined, EditOutlined, SaveOutlined) from `@ant-design/icons`.
- **Layout**: Use antd’s `Layout` component with `Sider` (for navigation, if needed) and `Content` for the main dashboard. Ensure a clean, grid-based layout with antd’s `Row` and `Col`.
- **Responsiveness**: Follow antd’s responsive design guidelines, ensuring components adapt to desktop and mobile screens using antd’s `Grid` system.
- **Interactivity**: Apply antd’s default animations for modals, buttons, and table interactions. Use antd’s `Spin` component for loading states.
- **Accessibility**: Ensure compliance with antd’s accessibility features (e.g., keyboard navigation, ARIA labels) and WCAG 2.1 contrast standards.
- **Branding**: Include a placeholder logo and app name in the antd `Header` or `Sider`, customizable later.

**Output**:

- Provide a high-fidelity UI mockup for the Admin Panel, including:
  - A dashboard with an antd `Table` for orders.
  - A modal with an antd `Select` for status updates and `Notification` preview.
  - A form with antd `DatePicker` for setting pickup/delivery times.
- Include desktop and mobile views, following antd’s responsive design.
- Export the design in a format compatible with Figma or PNG for easy integration.

**Inspiration**:

- Draw inspiration from Ant Design’s official component library examples (e.g., antd Pro, antd Admin dashboards) and other antd-based dashboards, focusing on simplicity and functionality.
