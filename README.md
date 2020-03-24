# hasura_enum

### Example migrations used to test hasura enum

```
1.  Create table dinner
2.  Create table vegetable
3.  Insert 'potato' into vegetable table
4.  Change vegetable table to enum
5.  Add foreign key to dinner table

6.  Check Docs: vegetable_enum 
    potato

7.  Insert 'onion' into vegetable table
8.  Press 'Reload Enum Values'
9.  Check Docs: vegetable_enum 
    potato

10. Restart hasura server
11. Check Docs: vegetable_enum
    onion
    potato 
```

