# Congressional Twitter Accounts

This repo houses the datasets of users and entities for the [Congressional Twitter Accounts datasets](https://github.com/alexlitel/congresstweets-accounts).

You can quite easily use this data as a basis for wide range of things, and the account list is a custom list for which I poured a number of hours of work into painstakingly accumulating a variety of accounts. It's also updated via some automated maintenance. Entities listed sorted by chamber and entity type, and depending on entity type, state, name, and party.

## What is what
* `users` - contains all current committees, MOCs, caucuses, etc
* `users-filtered` - contains all current congressional entities with active twitter accounts
* `historical-users` - contains all committees, MOCs, caucuses, etc (both former and current) from the inception of the project, including a few exclusive data points including past screen names for accounts, whether an account was deleted, and previous properties for MOCs (i.e. party or chamber changes). I strongly recommend you use either this or the `historical-users-filtered` dataset if you to utilize the dataset for anything. If you do use the this dataset and associated accounts, make sure you use the `id` key rather than `screen_name`, which can very well change
* `historical-users-filtered` - current and former congressional entites with twitter accounts