Introduction
============

Vector addition is a fundamental operation in parallel computing, 
often serving as a basic building block for more complex algorithms.
The concept involves adding corresponding elements of two vectors to 
produce a resulting vector. **When implemented efficiently, vector 
addition can significantly enhance the performance** of various 
applications, ranging from scientific simulations to real-time 
graphics rendering. As technology advances, heterogeneous computing
using platforms such as CPUs and GPUs has become increasingly 
prevalent, prompting the need for efficient and portable programming
models.

Traditionally, **the conventional approach of heterogeneous systems
programming required developers to manage memory explicitly, leading to intricate 
and error-prone code.** However, with the advent of Unified Shared 
Memory (USM) in SYCL, the process has become notably streamlined and it
enables the creation of memory regions that are accessible 
across different devices. Therefore **USM eliminates the need for explicit data 
transfers between host and device memories.** This simplifies 
memory management and accelerates development that can drastically 
enhance both code readability and performance. With the use of 
USM programmers can focus more on algorithmic design and less 
on memory-related intricacies.

In this exploration, we delve into two approaches for performing 
vector addition: the conventional method and the modern USM-enabled 
approach using SYCL. We'll examine the steps involved in both 
techniques, highlighting their individual strengths and limitations.