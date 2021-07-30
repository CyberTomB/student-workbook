# Subdocuments (Week 5 Day 3)

## In simple terms what is a sub-document?

Subdocuments are documents nested inside of other documents. A document is something like a Schema or Model, and a nested object or Schema would be a subdocument.

## When might you use a sub-document?

It makes sense to use a subdocument when a Schema might need to have child data contained within it and references to the child data are required or expected where the parent data is called.
     

## How do you add to a collection of sub-documents? What about editing them?

You can add to them typically using the findOne method first, and then adding new information or updating the called information as needed and then running save.