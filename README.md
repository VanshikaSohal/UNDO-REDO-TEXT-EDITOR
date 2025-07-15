# 📝 Undo-Redo Text Editor using Stacks and Queues

This project is a simple text editor that supports 🧭 Undo and 🔁 Redo operations. It is implemented using the **Stack** and **Queue** data structures to simulate basic text editing functionality.


## 💡 Concept

🔹 Stack stores the previous states of text (Undo)  
🔹 Another stack or queue stores the undone states (Redo)  
🔹 When the user types or deletes, the state goes to the Undo stack  
🔹 Undo retrieves the last state and pushes current to Redo  
🔹 Redo restores a previously undone state


## 🛠️ Technologies Used

🔹 C++ (or your preferred language)  
🔹 Standard Template Library (Stack, Queue)  
🔹 Console-based interface


## ✨ Features

🔹 Add new text  
🔹 Undo the last operation  
🔹 Redo the undone operation  
🔹 Clear editor  
🔹 Display current text content


## 🚀 How to Run

1. Compile the code:
   ```bash
   g++ main.cpp -o editor
Run the program:

No additional setup required. The editor runs in the terminal.


##Author
VANSHIKA SOHAL

