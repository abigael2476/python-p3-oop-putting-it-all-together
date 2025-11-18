# TODO List for Implementing Book and Shoe Classes

- [x] Implement Book class in lib/book.py:
  - Add **init** method to set title and page_count
  - Use property() for page_count with validation (must be int, print message if not)
  - Add turn_page method to print "Flipping the page...wow, you read fast!"
- [x] Implement Shoe class in lib/shoe.py:
  - Add **init** method to set brand and size
  - Use property() for size with validation (must be int, print message if not)
  - Add cobble method to print "Your shoe is as good as new!" and set condition to "New"
- [ ] Run tests to verify implementation:
  - Run pytest on testing/book_test.py
  - Run pytest on testing/shoe_test.py
