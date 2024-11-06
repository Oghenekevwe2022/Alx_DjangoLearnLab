from .models import Book

""" This command updates an instance of an object """

book.title = "Nineteen Eighty-Four"
book.save()
print(book.title)



"""Expected Output"""
Nineteen Eighty-Four