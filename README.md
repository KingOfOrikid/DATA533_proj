**Subpackeage: Library_Base**

#### Module Library_Book_System
| Book_System | Desceription |
| ------ | ------ |
| search_book  |  Use this ISBN number or book name to search book |
| all_book | get infromation of all books information |
| search_position | use the postion of the book to search the inforamtion  |

| Book_admin | Desceription |
| ------ | ------ |
|  input_book | input the book information  |
|  borrow_book_info |display all the borrowed book information  |
|  borrow_book_log | admin use the ISBN to record the book information when it's lend out  |
|  return_book_log | admin use the ISBN to record info when the book was return  |

|Book_User | Desceription |
| ------ | ------ |
| borrow_book  | user use ISBN to check if the book is available to borrow and borrow the book |
|  return_book |  user use the ISBN number to return the book |
|  number_book_log | total number of books that was borrowed out  |

#### Module Library_Person
| Person | Desceription |
| ------ | ------ |
|  get_username |  retrieve user name of the person |
|  get_name | retrieve name of the person  |
|  get_category |  retrieve the category of the person |


| Admin | Desceription |
| ------ | ------ |
| menu  |  choose to take 3 different actions: i)user management, ii)book management, iii) lend/borrow management |
|  user_info |  show all the user’s information |
|  edit_user_info | enable to edit person’s information|


| Module: User | Desceription |
| ------ | ------ |
|  menu  | 3 actions: i)center, ii)borrow return center, iii) book search  |
| my_info  | retrieve the person’s information  |
|  change_username | change the user id |
|  change_name |  change user’s name |
 
**Subpackeage: Library_Opera**

#### Module Data_
| Data | Desceription |
| ------ | ------ |
|  get_person_name | retrieve the person's name  |
|  get_person_info | get and print the person's information  |
|  get_person_info_num | retrieve the person's information for future use  |
|  get_book_info |  reteive the book information |
|  get_book_borrow_info | retrieve the borrowed book information with ISBN  |
|  get_all_book_borrow_info | get all borrowed book's information  |
|  get_all_book | get all books' information  |
|  get_book_info_from_pos | retrieve the book information by the position  |
|  get_user_borrow_list |  retrieve the list of borrowed book for certain users |
|  check_user_pass |  check user's password |
|  check_cate | check the user's category  |
|  input_user| input a user's information  |
|  input_book |  input a book's inforamtion |
|  change_book_borrow_status  | change the book's status to lend out |
|  change_book_return_status  |  change the book's status to returned |
|  check_book | check whether the book exists or not |
|  change_user |  change the user's username |
|  change_name | change the user's name  |
|  show_user_info | display the user information  |
|  save_file | update the information to a json file  |

#### Module Library_
| Library  | Desceription |
| ------ | ------ |
|  library_menu  | 3 actions to choose to choose: i)sign in; ii) register; iii) quit|
|  sign_in |  sign in to account |
|  register |  register a new account |

