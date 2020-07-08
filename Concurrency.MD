Process -> Program or application running in an environment
Thread -> Single task of Execution is a Thread
Daemon thread -> A daemon thread runs in background and doesn’t prevent JVM from terminating, child thread created from daemon thread is also a daemon thread.
multi-threaded programming -> Improves the performance and reduces CPU idle time
Thread creation -> Implement runnable and extending thread	class
Life cycle of thread -> New,Runnable,Running,Waiting,Blocked,Dead
Run method-> will act like normal function call
Start method-> creates a thread
sleep()-> pauses the thread
priority->based on this scheduler will pick a runnable thread
Context switching -> process of storing and restoring of CPU state so that Thread execution can be resumed from the same point at a later point of time
join()-> u make sure all the threads created by the program is dead before finishing the main function.
wait(), notify() and notifyAll()-> methods allows threads to communicate about the lock status of a resource.
thread safety  ->synchronization, atomic concurrent classes, implementing concurrent Lock interface, using volatile keyword, using immutable classes
volatile->always reads from memory not from cache
Synchronized block is better as it won't block object like snchronized method
Deadlock->programming situation where two or more threads are blocked forever
thread pool ->manages the pool of worker threads, it contains a queue that keeps tasks waiting to get executed.
Sleep method-> will not release the lock. Wait method releases lock.
Wait method ->defined in Object class, whereas Sleep method defined in Thread class.
