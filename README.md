# clipboard_automaton
Ready text file and copy to clipboard

### **Procedure to Use the Code**

1. **Prepare the Input File (`user_data.txt`):**
   - Create a plain text file named `user_data.txt` (or any name, but update the `file_path` in the code accordingly).
   - Add user credentials in the following format:
     ```
     user1|pwd1
     user2|pwd2
     ***random***
     abcdasdfkj234234|asdfasdfas8979889
     kjsldfkjsa98798798927|aljl234234234
     asdfasdf234234243|lkjljljljlkasdfdf;lkasfd
     ```

2. **Set Up the Environment:**
   - Install the required Python modules:
     ```bash
     pip install pyperclip
     ```
   - `tkinter` comes pre-installed with Python, so no need for additional installation.

3. **Save and Run the Script:**
   - Save the code as a `.py` file, e.g., `credential_manager.py`.
   - Open a terminal or command prompt and run the script:
     ```bash
     python credential_manager.py
     ```

4. **Interact with the GUI:**
   - A GUI window will appear with buttons for each user and a `cif_trans` button.
   - Click on any user button to copy their **username** immediately and their **password** after 6 seconds.
   - Click on the `cif_trans` button to copy a random **CIF ID** immediately and its corresponding **Trans ID** after 6 seconds. This will cycle through the random credentials.

---

### **Benefits of the Code**

1. **Improved Efficiency:**
   - Quickly copy credentials to the clipboard without manually searching the file or typing them.
   - Ideal for repetitive tasks requiring rapid credential retrieval.

2. **Automation of Delayed Copy:**
   - Automatically handles time gaps for sensitive operations like sequentially pasting credentials in applications.

3. **User-Friendly GUI:**
   - Simplifies interaction with credentials through an easy-to-navigate interface.
   - Keeps the window always on top, ensuring availability during multitasking.

4. **Secure Clipboard Management:**
   - Ensures credentials are copied to the clipboard only when needed.
   - Reduces the risk of accidental misuse by managing delays and messages.

5. **Flexibility with Random Data:**
   - Supports handling a separate set of credentials under the `***random***` marker.
   - Enables cycling through less frequently used or special-purpose credentials.

6. **Great for Professionals:**
   - Useful for testers, administrators, or developers who need to handle multiple accounts and credentials efficiently.

Feel free to customize the script further to match your specific needs! 😊
