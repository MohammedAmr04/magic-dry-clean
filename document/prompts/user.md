Design a modern, clean, and responsive User Interface for a laundry and tailoring service application, strictly following the Ant Design (antd) design system. The UI should cater to the following requirements based on provided User Stories, plus additional Home and Feedback pages, using antd components and styling:

1. **Create Account**:

   - Design a signup page using an antd `Form` component.
   - Include fields for Name, Email, Phone, and Address (using antd `Input` and `Form.Item`).
   - Add an antd `Button` (type="primary") for submitting the form.
   - Include form validation (e.g., required fields, valid email format) using antd `Form` rules.
   - Ensure the form is centered and responsive for desktop (1920x1080) and mobile (375x667) screens.

2. **Login/Signin**:

   - Design a login page using an antd `Form` component.
   - Include fields for Email and Password (using antd `Input` and `Input.Password`).
   - Add an antd `Button` (type="primary") for login submission.
   - Include a link (antd `Typography.Link`) for password recovery and signup redirection.
   - Ensure the form is responsive and follows antd’s clean layout.

3. **Create Order**:

   - Design an order creation page within the user dashboard using an antd `Form` component.
   - Include an antd `Select` for choosing service type (e.g., Laundry, Tailoring).
   - Add an antd `InputNumber` for number of items and an antd `Input.TextArea` for description.
   - Include an antd `Radio.Group` for selecting pickup/delivery method (e.g., Pickup, Delivery).
   - Add an antd `Button` (type="primary") to submit the order.
   - Show a confirmation message using antd `message` component after submission.
   - Ensure the form is responsive and integrated into the dashboard layout.

4. **Order Status**:

   - Design a user dashboard with an antd `Table` or `List` component to display the user’s orders.
   - Show columns/fields: Service Type, Description, Status (e.g., Pending, In Progress, Completed), Pickup/Delivery Time.
   - Implement real-time status updates with antd `Spin` for loading states or antd `Tag` for status colors.
   - Ensure the dashboard is responsive, with a clean layout for desktop and mobile views.

5. **Home Page**:

   - Design an engaging landing page to introduce the laundry and tailoring service.
   - Use an antd `Carousel` or `Card` components to showcase services (e.g., Laundry, Tailoring, Express Delivery).
   - Include a prominent antd `Button` (type="primary") for “Get Started” that links to signup/login.
   - Add an antd `Typography.Title` for a catchy headline (e.g., “Fast and Reliable Laundry & Tailoring Services”).
   - Include placeholder images or icons (using antd `Image` or `@ant-design/icons`) for visual appeal.
   - Ensure a responsive grid layout using antd `Row` and `Col` for desktop and mobile.

6. **Feedback Page**:
   - Design a feedback submission page using an antd `Form` component.
   - Include an antd `Input.TextArea` for feedback text and an optional antd `Rate` component for star ratings.
   - Add an antd `Button` (type="primary") to submit feedback.
   - Show a confirmation message using antd `message` component after submission.
   - Ensure the form is centered, responsive, and follows antd’s clean design.

**Design Guidelines**:

- **Style**: Strictly adhere to Ant Design’s design system, using its component library (e.g., Form, Input, Select, Table, List, Button, Carousel, Rate, message).
- **Color Palette**: Use antd’s default colors (Primary: #1890ff, Success: #52c41a, Error: #ff4d4f, Warning: #faad14) with a neutral background (#f0f2f5).
- **Typography**: Use antd’s recommended fonts (e.g., -apple-system, BlinkMacSystemFont, ‘Segoe UI’, Roboto) with antd’s typography hierarchy (Title, Text, Link).
- **Icons**: Use antd’s `Icon` components (e.g., UserOutlined, LockOutlined, SearchOutlined, StarOutlined) from `@ant-design/icons`.
- **Layout**: Use antd’s `Layout` component with `Header`, `Content`, and optional `Footer` for consistent structure. Use antd `Row` and `Col` for grid-based layouts.
- **Responsiveness**: Follow antd’s responsive design guidelines, ensuring components adapt to desktop (1920x1080) and mobile (375x667) screens using antd’s `Grid` system.
- **Interactivity**: Apply antd’s default animations for buttons, modals, carousels, and form submissions. Use antd `Spin` for loading states and `message` for notifications.
- **Accessibility**: Ensure compliance with antd’s accessibility features (e.g., keyboard navigation, ARIA labels) and WCAG 2.1 contrast standards.
- **Branding**: Include a placeholder logo and app name in the antd `Header`, customizable later.

**Output**:

- Provide a high-fidelity UI mockup for the User Interface, including:
  - Signup and Login pages with antd `Form`.
  - User dashboard with antd `Table` or `List` for orders.
  - Order creation form within the dashboard.
  - Home page with antd `Carousel` or `Card` and “Get Started” button.
  - Feedback page with antd `Form` and `Rate` components.
- Include desktop and mobile views, following antd’s responsive design.
- Export the design in a format compatible with Figma or PNG for easy integration.

**Inspiration**:

- Draw inspiration from Ant Design’s official component library examples (e.g., antd Pro, antd-based user dashboards) and modern consumer apps like Uber or Airbnb, adapted to antd’s style.
