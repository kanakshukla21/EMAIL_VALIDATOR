GUI-based email validator using Tkinter and regular expressions (regex)
1️⃣ Importing Required Modules
re → Used for regex-based email validation
tkinter → Used to create a graphical user interface (GUI)
messagebox → Used to show pop-up messages for valid/invalid emails

2️⃣ Function to Validate Email
How it Works?
Regex Pattern for Basic Email Validation

Ensures the email follows the format: username@domain.com
Allows alphabets, numbers, dots (.), underscores (_), and hyphens (-) in the username
Ensures a valid domain with a top-level domain (e.g., .com, .org, .net)
Domain Filtering for Specific Providers

Only allows Gmail, Outlook, Hotmail, Live, and Yahoo domains
If the domain isn't in the allowed list, it's considered invalid

3️⃣ Function to Handle Button Click
 How it Works?
Gets Email Input from User

entry_email.get() → Retrieves email entered in the input field
strip() → Removes extra spaces
lower() → Converts to lowercase to ensure case insensitivity
Checks if the Input is Empty

If no email is entered, shows a warning message
Calls is_valid_email() Function

Returns a boolean (True/False) and a message
Displays Validation Result

messagebox.showinfo("Valid", message) → Shows a success message
messagebox.showwarning("Invalid", message) → Shows an error message

4️⃣ Creating the GUI
tk.Tk() → Creates the main window
title("Email Validator") → Sets window title
geometry("400x200") → Sets window size (400x200 pixels)

5️⃣ Adding UI Components
tk.Label() → Creates a text label
pack(pady=10) → Adds some padding (spacing)
tk.Entry() → Creates an input field for the email
width=30 → Sets field width
pack(pady=5) → Adds padding
tk.Button() → Creates a button
text="Validate Email" → Button label
command=on_validate_click → Calls the function when clicked

6️⃣ Running the Application
Starts the GUI event loop
Keeps the application running until the user closes it
