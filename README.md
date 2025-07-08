

This is a simple Java-based online bookstore system built for the **Quantum Internship Challenge**.



- Supports multiple book types:
  - **PaperBook**: Has stock, ships to address.
  - **EBook**: Has file type, sent via email.
  - **ShowcaseBook**: Not for sale.
- Easily extensible by adding new book types via inheritance.
- Basic purchase functionality using ISBN and quantity.
- Remove outdated books based on publish year.
- All messages are prefixed with `Quantum book store`.



- `Book.java` – Abstract base class for all book types.
- `PaperBook.java` – Concrete class for physical books with stock and shipping.
- `EBook.java` – Concrete class for digital books with filetype and email delivery.
- `ShowcaseBook.java` – Book not for sale.
- `Inventory.java` – Handles all operations like add, remove, and buy books.
- `QuantumBookstoreFullTest.java` – A complete test class demonstrating how everything works.



1. Clone the repo or unzip the folder.
2. Compile all `.java` files:
   ```bash
   javac *.java
