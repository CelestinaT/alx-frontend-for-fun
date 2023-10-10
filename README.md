
Markdown to HTML
---------------------------------------------
Requirements: All files will be interpreted/compiled on Ubuntu 18.04 LTS using python3 (version 3.7 or higher), The first line of all files should be exactly #!/usr/bin/python3, A README.md file, at the root of the folder of the project, is mandatory, Code should use the PEP 8 style (version 1.7.*), All files must be executable, All modules should be documented: python3 -c 'print(__import__("my_module").__doc__)' Code should not be executed when imported (by using if __name__ == "__main__":)

Tasks
-----------------------------------------------------------------------
0. Start a script: Write a script markdown2html.py that takes an argument 2 strings: First argument is the name of the Markdown file Second argument is the output file name Requirements: If the number of arguments is less than 2: print in STDERR Usage: ./markdown2html.py README.md README.html and exit 1, If the Markdown file doesn’t exist: print in STDER Missing <filename> and exit 1, Otherwise, print nothing and exit 0 Repo: GitHub repository: alx-frontend-for-fun File: markdown2html.py
1. Headings: Improve markdown2html.py by parsing Headings Markdown syntax for generating HTML Repo: GitHub repository: alx-frontend-for-fun File: markdown2html.py
2. Unordered listing Improve markdown2html.py by parsing Unordered listing syntax for generating HTML Repo: GitHub repository: alx-frontend-for-fun File: markdown2html.py
3. Ordered listing Improve markdown2html.py by parsing Ordered listing syntax for generating HTML Repo: GitHub repository: alx-frontend-for-fun File: markdown2html.py
4. Simple text: Improve markdown2html.py by parsing paragraph syntax for generating HTML Repo: GitHub repository: alx-frontend-for-fun File: markdown2html.py
5. Bold and emphasis text: Improve markdown2html.py by parsing bold syntax for generating HTML Repo: GitHub repository: alx-frontend-for-fun File: markdown2html.py
6. ... but why?? Improve markdown2html.py by parsing bold syntax for generating HTML Repo: GitHub repository: alx-frontend-for-fun File: markdown2html.py
