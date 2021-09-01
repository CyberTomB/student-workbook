# C# Data Types (Week 10 Day 1)

## What are the three categories of data types? How are they different?

Value, Reference, and Pointer. Values store their data in the address in memory they are assigned. Reference store a data address that "refers" to data in memory, and Pointers which holds the memory address of value types and arrays.

## What are the Value-type data types? What differences do you notice from JavaScript?

* Bool
* Enum
* Short
* Byte
* Float
* Struct
* Char
* Int
* Uint
* Decimal
* Long
* Ulong
* Double
* Sbyte
* Ushort

There are more data types than seem to be in javascript, especially when it comes to number types (int, short, and long as opposed to just "Number").

## How do Reference types work?

Reference types point to a location in memory. When these variables are passed, the location that the reference type is pointing to stays the same, and thus the data contained inside that address in memory is changed.

### [Project Link](https://github.com/CyberTomB/csharp-rock-paper-scissors)