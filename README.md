Phonebook Documentation
This documentation provides an overview of the phonebook functions implemented in pseudocode. The phonebook allows users to manage contacts through various operations, including adding, searching, displaying, deleting, updating, sorting, and analyzing search efficiency.

Table of Contents
 1.Insert Contact
 2.Search Contact
 3.Display All Contacts
 4.Delete Contact
 5.Update Contact
 6.Sort Contacts (optional)
 7.Analyze Search Efficiency

1. Insert Contact
Description
Allows the addition of a new contact to the phonebook.

FUNCTION InsertContact(head, newContact)
Parameters
head: The head of the linked list representing the phonebook.
newContact: The contact to be added.
Returns
The updated head of the contact list.

2. Search Contact
Description
Finds a contact by name.

FUNCTION SearchContact(head, name)
Parameters
head: The head of the linked list representing the phonebook.
name: The name of the contact to search for.
Returns
The contact if found; otherwise, "Contact not found".

contact = SearchContact(head, "John Doe")
3. Display All Contacts
Description
Displays all contacts in the phonebook.

FUNCTION DisplayContacts(head)
Parameters
head: The head of the linked list representing the phonebook.

4. Delete Contact
Description
Removes a contact from the phonebook.

FUNCTION DeleteContact(head, name)
Parameters
head: The head of the linked list representing the phonebook.
name: The name of the contact to be deleted.
Returns
The updated head of the contact list.

5. Update Contact
Description
Changes the details of an existing contact.

FUNCTION UpdateContact(head, name, newContact)
Parameters
head: The head of the linked list representing the phonebook.
name: The name of the contact to be updated.
newContact: The new contact details.

6. Sort Contacts (optional)
Description
Organizes the contacts in alphabetical order by name.

FUNCTION SortContacts(head)
Parameters
head: The head of the linked list representing the phonebook.
Returns
The head of the sorted contact list.

7. Analyze Search Efficiency
Description
Measures the time taken to perform a search operation.

FUNCTION AnalyzeSearchEfficiency(head, name)
Parameters
head: The head of the linked list representing the phonebook.
name: The name of the contact to search for.

Conclusion
This phonebook implementation allows users to effectively manage contacts with operations for insertion, search, display, deletion, updating, sorting, and performance analysis. The structure is based on a linked list, providing flexibility in managing the contacts.


CONTRIBUTIONS: Lucio Serafim 224095048, TK Hambira 220997755 AND Martin Nginyengwa 223038245 -LEAD DEVELOPERS: RESPONSIBLE FOR IMPLEMENTING THE CORE FUNCTIONALITIES OF THE APPLICATION,AND DESIGNED THE USER INTERFACE and java codes to run the application.

Kauarive Katjaita 223077267 , Amilkar Manuel 224090232 AND Vitjiukua Kaereho 223053317 - DOCUMENTATION SPECIALISTS: CREATED A DETAILED DOCUMENTATION FOR THE APPLICATION following each modules pseudocode and flowchart and other project resources.

