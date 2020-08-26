# Library-Management-System

This project is based on library management system where the user can issue, return ,renew, search for books, view issued books.
the student sends a request to the admin for issue, return or renew books . The admin can accept or reject request , if admin accepts your request then only you can do issue or return books.
This website is more of interaction between user and admin.


Database tables:

register : sid , fname , lname, email , password, branch   (all varchar)
books : bid, bname, bauthor, copies
issue : sid , bid , issue_date, last_date
issue_request : sid, bid, admin_response
return_request : sid, bid, admin_response
renew_request : sid, bid, admin_response

when a person requests a book it goes into the request table. When admin accepts it , row gets entered into issue table.

