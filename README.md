# Coupon-System
- RESTful Application with MVC Architecture.
- Uses CRUD operations.
- 3 different interfaces/facades:
Admin- Can create/view/delete/update companies and custmoers.
Company - Can create/view/delete/update only it's own coupons.
Customer- Can purchase/view coupons.  
The main thread is a singltone.
An extra thread for auto deletion to out-of-date coupons.
