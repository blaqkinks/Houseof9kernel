# Houseof9kernel
The House of 9 Kernel, a port of the Plan 9 kernel and OS to ARM devices

-------------------------------------------------------------
About the Plan


Plan 9 from Bell Labs is a research system developed at Bell Labs starting in the late 1980s.

Its original designers and authors were Ken Thompson, Rob Pike, Dave Presotto, and Phil Winterbottom. They were joined by many others as development continued throughout the 1990s to the present.

Plan 9 demonstrates a new and often cleaner way to solve most systems problems. The system as a whole is likely to feel tantalizingly familiar to Unix users but at the same time quite foreign.

In Plan 9, each process has its own mutable name space. A process may rearrange, add to, and remove from its own name space without affecting the name spaces of unrelated processes. Included in the name space mutations is the ability to mount a connection to a file server speaking 9P, a simple file protocol. The connection may be a network connection, a pipe, or any other file descriptor open for reading and writing with a 9P server on the other end. Customized name spaces are used heavily throughout the system, to present new resources (e.g., the window system), to import resources from another machine (e.g., the network stack), or to browse backward in time (e.g., the dump file system).

Licensing

The first edition was made available only for use by universities.

The second edition was made available to the general public at a cost of $350 for the distribution, which included a license to use the software throughout the organization.

For the third edition, Lucent agreed to release Plan 9 for free via the Internet, under a new license, the Plan 9 License.

The fourth edition (the current one) is made available under the Lucent Public License version 1.02. Adopted to address shortcomings in the Plan 9 License, the Lucent Public License 1.02 is identical the IBM Public License 1.0 except that it does not require source code to be distributed with derived works; it is non-viral.

The Pi Port also includes Broadcom Corporation license for firmware blobs and binaries. 



A Working IMG file pre-compiled can be found at: 

http://www.plan9fromtheinter.net/

or within this GIT.
