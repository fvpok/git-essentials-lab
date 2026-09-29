# Library demo run guide

## Prerequisites

- Git 2.23 or later.
- Python 3.9 or later, available as python3.
- JDK 17 or later, with both java and javac available.

No Maven, Gradle, or third-party Java dependencies are required.

## Run the demo

Open a terminal in the root directory of this exercise repository and run:

```bash
python3 run.py demo
```

## What the demo does

The demo creates a small library catalog and registers a student and a faculty
member. It displays borrowing limits and a title search result, then borrows
a book for the student and prints a receipt and the due date. Finally, it
returns the book and displays the return fee and remaining active loans.

A fixed date makes the demonstration reproducible.
