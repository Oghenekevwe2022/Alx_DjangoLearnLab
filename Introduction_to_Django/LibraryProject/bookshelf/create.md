from .models import Book

""" This command creates an instance of an object """

book = Book.objects.create(title = "1984", author = “George Orwell”, publication_year = 1949)
book.save()

"""Expected Output"""
If outcome is successful, it will be empty