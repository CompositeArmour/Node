Callback is an asynchronous equivalent for a function. A callback function is called at the
completion of a given task. Node makes heavy use of callbacks. All the APIs of Node are
written in such a way that they support callbacks.
For example, a function to read a file may start reading a file and return the control to the
execution environment immediately so that the next instruction can be executed. Once
file I/O is complete, it will call the callback function while passing the callback function,
the content of the file as a parameter. So there is no blocking or wait for File I/O. This
makes Node.js highly scalable, as it can process a high number of requests without waiting
for any function to return results.

Express is a minimal and flexible Node.js web application framework that provides a robust
set of features to develop web and mobile applications. It facilitates the rapid development
of Node-based Web applications. Following are some of the core features of Express
framework: