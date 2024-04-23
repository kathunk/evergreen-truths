Here lies a hodgepodge of specific best practices when programming. 

## Tests

### Write failing tests before logging off

Tests are a great way to regain context when you log back on. So when you're about ready to log off for the day, write some failing tests for all the work you need to do. Then it will be much easier to get started the next day (or for someone else to pick up where you left off).

## Pivot tables, always

When a feature requires a relationship between two objects, it's usually right to make a pivot table. Creating a 1-to-1 relationship between objects frequently creates rigid limitations. Real life frequently demands more flexible relationships. So start with the pivot table, and avoid painful refactors later.