# MongoDB Relationships (Week 5 Day 4)

## What is a virtual property?

Additional fields for models in the database. However, the properties of virtuals do not persist in the DB.

## When might you use a virtual property?

You could use virtuals to get properties from models without needing them to be stored in the database independently. One way to use this would be setting up first and last name virtuals to get user's names from auth data.

## How do you search by a virtual properties value?

You can use a "get" method to return the virtual's value.

Project Link: https://github.com/john87barker/ReadIt