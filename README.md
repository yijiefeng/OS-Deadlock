
(1) get input from the user (name of input file) ***
(2) Create an Activity class ***
(3) Create a Task class ***


(4) implement FIFO FIFO ***
        
(5) handle deadlocks for FIFO 
        
(6) handle delays for FIFO         
                
(*) fix FIFO for:
        > input-02 (deadlock)
        > input-03 (deadlock)
        > input-04 (deadlock)
        > input-05 
        > input-06 (deadlock)
        > input-07 (deadlock)
        > input-10 (deadlock)
        > input-12 
        > input-13 
        
        






(*) account for case where inputs for two tasks are interleaved (input 8)

(*) account for malformed input (multiple activities on one line; ignore whitespace) 

(*) set arbitrary limits for T and R values 

(*) put the required comments in your code 

---------------------------------------------------------------

>> if there are R resource types there are R initiate requests? 

>> The manager can process one activity (initiate, request, or release) for each task in one cycle.
   However, the terminate activity does NO T require a cycle.
   
>> The delay value represents the number of cycles between the completion of the previous activity for this
   process and the beginning of the current activity. 
   