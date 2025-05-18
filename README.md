📘 Multiplication Tables Generator

This simple Python script generates multiplication tables from 1 to 20 and saves each table in a separate text file.
📝 Features

    Automatically creates multiplication tables from 1 to 20

    Each table is saved in a separate .txt file

    Files are stored in a folder named Tables

    Example file: table_5.txt contains the 5 times table

🧠 How It Works

The script defines a function tables_gen(n) that:

    Iterates through numbers 1 to 10

    Generates the multiplication table for the given number n

    Writes the table to a file named table_n.txt inside the Tables directory

Then, it runs the function for numbers 1 through 20.
📂 Output Structure

Tables/
├── table_1.txt
├── table_2.txt
├── ...
├── table_20.txt

Each file contains:

n X 1 = n
n X 2 = 2n
...
n X 10 = 10n

🛠 Requirements

    Python 3.x

Make sure the Tables folder exists in the same directory as your script. If not, you can add this snippet to create it automatically:

import os
os.makedirs("Tables", exist_ok=True)

🚀 How to Run

    Save the script as generate_tables.py

    Open a terminal and run:

python generate_tables.py

📌 Author

Developed by Shahed Rahman
