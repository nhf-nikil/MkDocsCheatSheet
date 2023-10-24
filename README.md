# Purpose

MkDocs is a software that can create a full website out multiple plain text files written in 'Markdown'.
Markdown is formatting language similar to HTML.
It allows us to embed code snippets, equations, diagrams, charts, and tables into our plain text files.
It even allows us to embed Jupyter Notebooks, videos, images, and external links.
Since all of this is done using plain text files, no propietary software is needed to render the documentation.
Instead, everything can be viewed with only a web browser. that allows us to embed the diagrams, tables, etc into our plain text files.

MkDocs is a good way to provide most other types of documentation for the following reasons
- Installing it on a server only requires Python PIP
- Writing in 'Markdown' allows for ability to create docs/diagrams/etc without a high learning curve 
- Reading from it on the company network only requires a web browser and URL
- Because it is a 'website', there is no need to download additional software on your PCs/Phones
- Because it is a 'website', there is no need to search for individual .doc files 
- It allows for centralization and document version control
- It has full text search and wikilinks 

# Contents

Documentation for the Robotics Architecture needs to be stored in the following formats:
- Plain Text combined with Code Snippets (useful for installation, configuration, and tutorial instructions)
- Jupyter Notebooks, Math Equations, and Tables for code simulation, experimentation, and algorithm walkthroughs
- Diagrams and Charts for Architecture Layouts/Explanations, Design notes, and 
- Links to external resources (other websites, source code, dashboards)

# Installation

``` py title="bubble_sort.py"
def bubble_sort(items):
    for i in range(len(items)):
        for j in range(len(items) - 1 - i):
            if items[j] > items[j + 1]:
                items[j], items[j + 1] = items[j + 1], items[j]
``


