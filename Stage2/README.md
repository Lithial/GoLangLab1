# GoLangLab stage 2
### Import and look-up information from a json source

You will adopt and continue working on your application constructed in Stage 1. You need to hand in the complete and extended application including the following:


- A function that provides an overview (in text format) of the average staff size per company per suburb, sorted on staff size from high to low
##### Status: Complete
Proof that no average is out of bounds
 .- *All i did for this one is put in a check that makes sure the value isn't below 0. I could probably do a check for the upper bounds as well but I think this is fine*
##### Status: Complete
- Measurements that show the time required to produce the requested overview. Aim for and explain the solution that is most efficient. Explain how the time relates to the size of the data set
 .- *I used quick sort. Its big o is o(log n) and depending on how its implemented it can be 2-3 times faster than heap or merge sort. This is a best case scenario and if its implement wrong it could end up being O(n2)*
##### Status: Complete