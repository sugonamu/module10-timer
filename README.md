# Module 10 – Asynchronous Programming (Rust)



## Experiment 1.1: Original Timer from Book

In this experiment, I implemented a custom executor and a `TimerFuture` that completes after a delay. The executor drives the future to completion.

### Result:
- The message `"howdy from Ade’s Komputer!"` is printed.
- After a 2-second pause, `"done!"` is printed.
- This confirms that the future is lazily evaluated and only progresses when polled by the executor.

### Output:
![Experiment 1.1](./Experiment1.1.png)

---

