#  The motivations for building the Swift language and how Swift’s libraries and compiler work together to make powerful abstractions

## KEY OUTLINES
- Swift is a multi-paradigm language that supports many programming styles, including imperative, functional, object-oriented, protocol-oriented and generic paradigms.

- Swift aims to pick reasonable defaults, making undefined behavior hard to trigger.

- Swift embraces the idea of progressive disclosure. You only need to learn about more advanced language features when you need them.

- Swift is a general-purpose programming language that features a powerful type system and type inference.

- Much of Swift is defined in its expressive, standard library and not as part of the compiler.

- The Swift compiler phases are parse, semantic analysis, SILGen, IRGen and LLVM.

- Source location information resides in AST and SIL, making better error reporting possible.

- SIL is a low-level description using basic blocks of instructions written in SSA form. It understands the semantics of Swift types, which enables many optimizations not possible with pure LLVM IR.

- SIL helps support definite initialization, memory allocation optimizations and devirtualization.

- Any is the ultimate type-erasure in Swift, but it can be error-prone to use. Generics are usually a better alternative.

- Pass a closure as a parameter that returns a value to defer evaluation of the argument until within the body of a function[…]
