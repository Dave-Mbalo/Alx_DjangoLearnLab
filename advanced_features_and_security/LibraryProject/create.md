# Create Operation

## Command
Use the following command to create a new book instance in the Django shell:

```python
from bookshelf.models import Book

new_book = Book(
    title="The Great Gatsby",
    author="F. Scott Fitzgerald",
    publication_year=1925
)

new_book.save()
```

## Output
There is no direct output. If you want to see if the operation was succesful, you can query the database.