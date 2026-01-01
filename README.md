# canteen-management-system-in-c
This C program is a simple canteen management system that allows the owner to add, view, and delete food items using file handling. Customers can view the menu, place orders, and receive an automatically calculated bill.
Explanation of Canteen Management and Billing System

1. This project is developed using the C programming language to manage a canteen’s menu and billing process efficiently.

2. The program uses a structure (struct Menu) to store food item details such as item ID, item name, and price.

3. File handling is used to store data permanently. The menu is saved in canteen.txt, while customer order details are saved in orders.txt.

4. The system has two main sections: Owner Section and Order Section.

5. The Owner Section is protected by a password to ensure security and prevent unauthorized access.

6. After login, the owner can add new food items, view existing items, or delete items from the menu.

7. While adding an item, the program checks for duplicate item IDs to avoid repetition and sorts the items by ID before saving them.

8. The View Items function displays all food items in a tabular format with ID, name, and price.

9. The Delete Item function removes a selected item by ID and updates the file accordingly.

10. The Order Section is designed for customers to interact with the system.

11. Customers can view the menu and place orders by entering item ID and quantity.

12. The program calculates the total bill automatically based on selected items and quantities.

13. All order details and the final bill amount are stored in the orders.txt file.

14. The program uses functions, loops, conditionals, arrays, and file operations for proper program flow.

15. Overall, this project demonstrates a simple, user-friendly, and practical application of C programming concepts for real-world use.
16. Practice on your own to get better results and also do your best in reading books of c
