Mintamir Mengistu 1602148 section B



installation of Ubuntu24.04.1


**Ubuntu 24.04.1 LTS** is a stable and secure Linux distribution developed by Canonical, designed for desktops, servers, and cloud environments.  
As a Long-Term Support (LTS) release, it receives security updates and maintenance for five years, making it ideal for production use.  
Ubuntu 24.04.1 features the latest GNOME desktop environment, improved performance, and updated software packages.  
It emphasizes ease of use, with a user-friendly interface and strong community support.  
Ubuntu is open source and freely available, encouraging innovation and collaboration worldwide.

munlock () systemcall



The `munlock()` system call is used in Unix-like operating systems to unlock memory pages that were previously locked using `mlock()`.  
It allows the operating system to swap the specified memory region back to disk if needed, reversing the effect of `mlock()`.  
This is important for managing system resources and ensuring memory is not unnecessarily kept in RAM.  
The function takes a pointer to the memory region and the length (in bytes) as arguments.  
Proper use of `munlock()` helps maintain system performance and memory availability, especially in applications that temporarily need locked memory.



