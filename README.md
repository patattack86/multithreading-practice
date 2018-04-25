# multithreading-practice
Training to be able to implement multithreading techniques into practical programs

writing some notes to myself.
There cannot be simultaneous shared memory of a common variable when multithreading.  Each task must access the shared variable at different times. This is where sleep comes in

When sharing a variable or database that is shared, there needs to be a lock put in place so that when a function gains access to a variable it locks the variable.  This means that only one function can access the database or variable at one time. 

When two functions access a variable or database at once when threading you'll experience data corruption


