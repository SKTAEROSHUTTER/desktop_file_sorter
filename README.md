<p align="center">
  <a href="" rel="noopener">
    <img width=200px height=200px src="https://i.imgur.com/6wj0hh6.jpg" alt="Project logo">
  </a>
</p>

<h3 align="center">Python File Sorter</h3>

<div align="center">

[![Status](https://img.shields.io/badge/status-active-success.svg)]()
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](/LICENSE)

</div>

---

<p align="center"> A Python program to sort files based on their extensions.
    <br> 
</p>

<h1> 📝 Table of Contents </h1>

- [About](#about)
- [Getting Started](#getting_started)
- [Usage](#usage)
- [Deployment](#deployment)
- [Built Using](#built_using)
- [Contributing](#contributing)
- [Authors](#authors)

<hr/>

<h1>🧐  About <a name="about"></a> </h1>
 
Python File Sorter is a simple command-line program that helps you organize your files by sorting them into folders based on their file extensions.
<hr/>

<h1> 🏁 Getting Started <a name="getting_started"></a></h1>

These instructions will guide you on how to set up and run the Python File Sorter on your local machine.

<h1> Prerequisites </h1>

Make sure you have Poetry installed. You can install it using pip:

```bash
pip install poetry
```

<h1> Installing </h1>


 1. Clone the repository:

```bash
git clone https://github.com/yourusername/file_sorter.git
cd file_sorter

```

2. Set up the virtual environment and install dependencies using Poetry:

```bash
poetry install
```
3. Run the Python File Sorter:

```bash
poetry run python main.py

```
<hr/>

<h1> 🎈 Usage <a name="usage"></a> </h1>

The Python File Sorter sorts files in the current directory into subdirectories based on their file extensions.

<h1> 🚀 Deployment <a name = "deployment"></a></h1>
You can automate the execution of the Python File Sorter on a regular schedule using the Windows Task Scheduler. Here are the steps to set it up:

1. Open the Windows Task Scheduler by searching for "Task Scheduler" in the Windows Start menu.

2. In the Task Scheduler window, click on "Create Basic Task" from the right-hand pane.

3. Follow the wizard to give your task a name and description. Click "Next."

4. Choose the frequency at which you want to run the Python File Sorter (e.g., daily, weekly, or monthly). Click "Next."

5. Specify the start date and time for the task. Click "Next."

6. Select "Start a Program" as the action to perform. Click "Next."

7. Browse and select the `main.py` file from your Python File Sorter project directory as the program/script to run.

8. In the "Add arguments" field, you can specify any command-line arguments your program needs. For example, if you want to sort files in a specific directory, you can use something like:
   ```bash
   -d C:\Path\To\Your\Directory
    ```
   
9. In the "Start in" field, specify the path to your Python File Sorter project directory.

10. Review your task settings and click "Finish" to create the task.

11. To run the task immediately, right-click on it in the Task Scheduler and select "Run."

Your Python File Sorter will now run automatically according to the schedule you defined.


<h1> ⛏️ Built Using <a name = "built_using"></a></h1>

- [Python](https://www.python.com/) - Programming Language
- [Poetry](https://python-poetry.org/) - Dependency Manage

<h1>  ✍️ Authors <a name = "authors"></a></h1>

- [@sadatyussuf](https://github.com/sadatyussuf) - Idea & Initial work


