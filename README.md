# ML Book, Edition 1
## Book Information
The contents are prepared by __Salma Emara__ and __Ali Bereyhi__ and is consistent with the course materials for __ECE 1513: Introduction to Machine Learning__
The book has been typeset by __Saeed Jafari__
The current edition has been last revised on __January 2026.__

## Next Editions
The source book can be cloned at `https://github.com/salma-emara/ml-book` and will be updated regularly. For sake of maintenance this edition is forked and deployed separately. 

## Building the Book Locally
If you are trying to build the book locally, you can follow the instructions below.

1- Clone this GitHub repo. In your terminal, type the following command:

```
git clone https://github.com/AlBerey/ml-book-ed1
cd ml-book
```

2- Install jupyter-book and other dependencies by running the following command in the terminal

```
pip install -r requirements.txt
```

3- To build everything for the first time 

```
jupyter-book build --all textbook
```
and to build after updating a markdown file:
```
jupyter-book build textbook
```

4- To view the book, you have two options:

To open directly, type the following command in the terminal:

```
open textbook/_build/html/index.html
```

To know more check [Tutorials](https://jupyterbook.org/en/stable/start/create.html)


