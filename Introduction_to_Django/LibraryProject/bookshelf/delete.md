### Delete a Book Instance

book = Book.objects.get(title="Nineteen Eighty-Four")
book.delete()
