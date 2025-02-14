# Kotlin Mutable Collection removeIf Pitfalls

This example demonstrates a potential issue when using the `removeIf` function with mutable lists and maps in Kotlin.  The issue arises from the concurrent modification of the collection during iteration.

The `bug.kt` file shows the problematic code, while `bugSolution.kt` offers a safer approach using iterators or copying for modification.