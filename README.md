# -Login-Page-Using-NetBeans-IDE-Main-Flow-Task-3-
A GUI-based Login Page built using Java Swing in NetBeans IDE. It includes username/password fields, show/hide password option, input validation, and basic login logic. Designed for a Java full stack task to demonstrate GUI design and authentication using NetBeans tools.
This project is a graphical user interface (GUI) based Login Page developed using Java Swing components in NetBeans IDE. It is part of a full stack Java development task that focuses on building basic desktop applications using NetBeans' built-in GUI builder (Design View) and Swing toolkit.

📌 Key Features:
Username & Password Input Fields: Accepts user login details.

Login Button: Validates credentials with a hardcoded username and password (Muskan / 123456).

Show/Hide Password: A checkbox lets users toggle password visibility for convenience.

Exit Button: Allows users to close the application gracefully.

Input Validation: Prompts the user if either the username or password field is left empty.

Error Handling: Displays a warning dialog if incorrect credentials are entered.

🛠 Development Process Using NetBeans IDE
The login interface was created using NetBeans' JFrame Form via drag-and-drop components:

JLabel for field labels and title

JTextField for username input

JPasswordField for secure password entry

JButton for login and exit actions

JCheckBox for showing/hiding the password

The layout used is AbsoluteLayout, with all components properly positioned and aligned. Tooltips were added to guide the user when entering credentials.

In the constructor, setSize() and setLocationRelativeTo(null) were used to size and center the window on launch. The login button’s ActionListener handles credential validation and feedback using JOptionPane.
