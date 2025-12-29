# Academia – Course Registration System

This project was developed as part of the EGC 301P-Operating Systems Lab Course Project at IIIT Bangalore.

# Overview
Academia is a Linux-based client–server course registration portal that supports Admin, Faculty, and Student roles with role-based access control.

# Features
- Client–server architecture using socket programming
- Role-based login for Admin, Faculty, and Student
- File-based storage for users and course data
- Concurrent client handling with read/write file locking
- Course enrollment with seat limits

# OS Concepts Used
- Process management and system calls
- Socket-based inter-process communication
- File management and file locking
- Synchronization and concurrency control

# Technologies
- C / C++
- Linux
- Socket Programming
- Makefiles

# How to Run
```bash
cd server
make
./server

cd ../client
make
./client
