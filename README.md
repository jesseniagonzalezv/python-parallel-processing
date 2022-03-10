# Multiprocessing and multithreading examples.

- **Multitasking** --> division of the execution time of processes. This taks is performed by the kernel of the operating system (scheduler).

- **Multithreading** --> task division inside the same process. Example: Android program (single process, 1 core exec.) --> GUI (1 thread) + Downloading (1 thread)

- **Multiprocessing** --> multi core processor. Each process is independent and assign it own memory space and hardware resources.

# Concurrency and parallelism
Images are taken from [https://towardsdatascience.com/multithreading-multiprocessing-python-180d0975ab29]{https://towardsdatascience.com/multithreading-multiprocessing-python-180d0975ab29}

- **Concurrency:** A condition that exists when at least two threads are making progress. A more generalized form of parallelism that can include time-slicing as a form of virtual parallelism - Sun’s Multithreaded Programming Guide.
![Alt text](https://assets.digitalocean.com/articles/alligator/boo.svg "a title")

- **Parallelism:** A condition that arises when at least two threads are executing simultaneously - Sun’s Multithreaded Programming Guide.
![Alt text](https://assets.digitalocean.com/articles/alligator/boo.svg "a title")



