# AddressBloc

This simple Ruby address book app runs on the command line, presenting the user with a set of text-based menu items to:

View entries
Create an entry
Search for an entry
Import entries from a CSV file
There are just two models (address book and entry) and one controller, and the TDD development process uses RSpec.

This was essentially an exercise for becoming familiar with Ruby development. Even though CRUD functions are provided to create, read, update, and destroy individual records, there is no database support nor even an option to export the records to a new CSV file. So the CRUD actions occur only in memory and when one quits the app all data is lost, so it has no practical value beyond being a learning exercise.
