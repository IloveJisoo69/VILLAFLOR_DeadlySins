# VILLAFLOR_DeadlySins
VILLAFLOR, LIAM MATTHEW B.

1. create db: deadlysinsdb
2. php artisan migrate
3. php artisan serve

EXPLANATION FOR DEADLY SINS
1.  Using hidden inputs or magic inputs when authenticating
- This deadly sin is prevented by using middleware for authentications.
2. Hard coding queries
- This deadly sin is prevented because Laravel automatically modularizes the code which prevents sql injection and disruption due to user input.
3. Not validating inputs passed by users
- This deadly sin is prevented in the registration form because when a user inputs wrong data (e.g. "hello" under email address), the error is caught and the user is notified that the input is invalid.
