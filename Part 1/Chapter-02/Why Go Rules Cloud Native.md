
## Problems in Cloud Native

- Low program comprehensibility
- Slow builds
- Inefficient
- High cost to update


> Don't communicate by sharing memory, share memory by communicating

See Communication Sequential Processes- the formal language that describes patterns of interactions in systems with concurrency.

**Concurrency is not Parallelism**
	Parallelism is simultaneous execution
	concurrency is the *composition of independently executing elements*

Go has very very fast builds, and is the structure of the language has not changed a lot (it is linguistically stable)

It is very memory safe. Doesn't let you touch pointers much at all. However it does have a garbage collector which can introduce overhead not present when working with C++ or Rust.

Static linking - The binaries contain everything on their own

Static typing
