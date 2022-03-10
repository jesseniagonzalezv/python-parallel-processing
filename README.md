# Multiprocessing and multithreading examples.

- **Multitasking:** division of the execution time of processes. This taks is performed by the kernel of the operating system (scheduler).

- **Multithreading:** task division inside the same process. Example: Android program (single process, 1 core exec.): GUI (1 thread) + Downloading (1 thread)

- **Multiprocessing:** multi core processor. Each process is independent and assign it own memory space and hardware resources.

![Multithreading and multiprocessing](./imgs_repo/multith_multiproc_1.jpg 'Multithreading and multiprocessing')
![Multithreading and multiprocessing](./imgs_repo/multith_multiproc_2.jpg 'Multithreading and multiprocessing')
![Multithreading and multiprocessing](./imgs_repo/multith_multiproc_3.jpg 'Multithreading and multiprocessing')

# Concurrency and parallelism

- **Concurrency:** A condition that exists when at least two threads are making progress. A more generalized form of parallelism that can include time-slicing as a form of virtual parallelism - Sun’s Multithreaded Programming Guide.

[![Concurrency](./imgs_repo/concurrency.png 'Concurrent execution')](https://towardsdatascience.com/multithreading-multiprocessing-python-180d0975ab29)

- **Parallelism:** A condition that arises when at least two threads are executing simultaneously - Sun’s Multithreaded Programming Guide.

[![Parallelism](./imgs_repo/parallelism.png 'Parallel execution')](https://towardsdatascience.com/multithreading-multiprocessing-python-180d0975ab29)

## References: 
Images are taken from: 
- ![Giorgos Myrianthous' Blog](https://towardsdatascience.com/multithreading-multiprocessing-python-180d0975ab29).
- ![Varun Kumar G's Blog](https://levelup.gitconnected.com/diy-multithreading-vs-multiprocessing-in-python-fb93698ca7f3).
- ![Learning Python Network Programming](https://subscription.packtpub.com/book/networking_and_servers/9781784396008/8/ch08lvl1sec69/multithreading-and-multiprocessing).
- ![Carlos Salas's Blog](https://www.lightbringercap.com/blog/neuromancer-blues-threading-vs-multiprocessing-part-2).




