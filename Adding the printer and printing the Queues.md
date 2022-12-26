# ADDING PRINTERS & CREATING PRINT QUEUES
I used the lpadmin command to create the printer named as DummyPrint and can be changed according to our need.
```
lpadmin -p DummyPrint -E -v file:/dev/null
```
Then, I used the lp command to generate print jobs for the printing purpose.
```
lp -d  test <file_name>
```
