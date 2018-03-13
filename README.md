Learns as you fill forms, you will never have to type the same thing twice.

CHANGELOG  v1.1
---------------

1- Avoid filling of search inputs                                           DONE
2- Detect if the field is inside a search/chat form, if so, dont fill it    DONE
3- Make sure that for each website there is 
4- Select elements inside iframe
6- If form comes already filled, do not overwrite it


Form fill performance metrics
-----------------------------

7- Detect when the user has to type the same thing twice and send error
8- Measure the amount of changes he has to do before submit the form


Instructions
------------

- Load the project folder on the chrome://extensions page . 
- There switch to developer mode and then you will see the button appearing next to the address bar. 
- When a page loads, it lookups all existing entries stored in the taffy javascript client database, and calculates the most accurate, based on levenshtein distance, or the minimum amount of operations needed for a string to become another.
- When you submit a form, all entries are stored. As simple as that, no profiles, no previously input data to make the form filler work, no cloud, no registration, no nothing.. just works.. so.. 


HAPPY FORM FILLING !
