
basic structure



Data Side
    - Contains a table of "User data" 
    - Customer table:
        - User location (ex. users zip) 
        - User gender
        - User age
    - Client table: 
        - Username
        - Password
    - Program table:
        - program length (dates)
        - program budget
        - ˜
                


Server Side
(Ruby/Sinatra)
    - server take in information regarding user info
        (age, gender, shoping habits)
    - based on client side requirements an add is directed to a specific user
        - if over lap in segments user will be served the add with the highest priority
        * if overlap user could get adds sequentially based on priority 



Client UI
    - A client should be able to build a program
        - input total budget (monitary),
        - CPM (cost per 1k views)
        - CPCV (cost per completed view)
        -  Program runtime
    - A client should be able to upload a media assett
        - MP4 or PNG
    - A client shoud be able to set up multiple programs at once
(React)


STRETCH GOALS
    - Production UI
    - a small data intake survey that would allow a front end user to put themself in an audience and be served the appropriate ad
    - possible integration on 3rd party API data
    
    
