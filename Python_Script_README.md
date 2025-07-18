## Explanation of Python Script Creation and Execution in Google Colab

In Google Colab, I created and ran Python scripts using two approaches:

1. First, I used the `%%writefile my_script.py` magic command to write a Python script directly from a notebook cell, then executed it with `!python my_script.py`.

2. Next, I installed the `nano` text editor using `!sudo apt-get install nano` and enabled a terminal in Colab with the `colab-xterm` extension (`!pip install colab-xterm` and `%load_ext colabxterm`). Inside the terminal, I used `nano` to create and edit another script file, then ran it using `python my_simple_script.py`.

This workflow demonstrates how to write, edit, and run Python scripts both inline in Colab and interactively via the terminal.
