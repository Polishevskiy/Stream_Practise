# Stream_Practise
Stream in Java is a sequence of elements that can be processed in a declarative way. It is a new feature introduced in Java 8 that allows for functional-style operations on collections of objects. Streams can be used to perform operations such as filtering, mapping, and reducing on collections of data.

A Stream is not a data structure, but rather a view of a data source such as an array, a collection, or an I/O channel. Streams are designed to be used with lambda expressions to perform operations on the elements of a sequence in a declarative way. The operations performed on a Stream are executed only when a terminal operation is invoked.

Streams have two types of operations: intermediate operations and terminal operations. Intermediate operations are operations that return a Stream, allowing for chaining of operations. These operations include filtering, mapping, sorting, and others. Terminal operations are operations that return a non-Stream result, such as a List, a boolean value, or a single value. These operations include forEach, collect, reduce, and others.

One of the benefits of Streams is that they can be processed in a parallel manner, which can improve performance on multi-core systems. When a Stream is processed in parallel, the elements are divided into multiple chunks and processed by multiple threads simultaneously.

Overall, Streams provide a powerful tool for processing collections of data in a declarative and functional way. They allow for chaining of operations and can be processed in parallel, improving performance on multi-core systems.
