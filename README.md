# Hi, I'm Matthew 👋

Computing Science student at Simon Fraser University. I like low-level systems programming, networking, and figuring out why code runs as fast (or slow) as it does. I also enjoy full stack development, building everything from the database to the user interface.

- 🌱 Currently learning: system security and privacy, database systems, data structures and algorithms
- 📫 Reach me: [mat28@sfu.ca](mailto:mat28@sfu.ca) · [LinkedIn](https://www.linkedin.com/in/matthew-tortolano-aa2387383/)

## Tech I use

![C](https://img.shields.io/badge/-C-A8B9CC?logo=c&logoColor=black)
![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white)
![Java](https://img.shields.io/badge/-Java-ED8B00?logo=openjdk&logoColor=white)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?logo=javascript&logoColor=black)
![C++](https://img.shields.io/badge/-C++-00599C?logo=cplusplus&logoColor=white)
![Node.js](https://img.shields.io/badge/-Node.js-339933?logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/-Express-000000?logo=express&logoColor=white)
![HTML](https://img.shields.io/badge/-HTML-E34F26?logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/-CSS-1572B6?logo=css3&logoColor=white)
![Spring Boot](https://img.shields.io/badge/-Spring_Boot-6DB33F?logo=springboot&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/-Linux-FCC624?logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/-Git-F05032?logo=git&logoColor=white)
![CMake](https://img.shields.io/badge/-CMake-064F8C?logo=cmake&logoColor=white)
![Gradle](https://img.shields.io/badge/-Gradle-02303A?logo=gradle&logoColor=white)
![x86-64 Assembly](https://img.shields.io/badge/-x86--64_Assembly-555555)
![Bash](https://img.shields.io/badge/-Bash-4EAA25?logo=gnubash&logoColor=white)
![Wireshark](https://img.shields.io/badge/-Wireshark-1679A7?logo=wireshark&logoColor=white)
![Postman](https://img.shields.io/badge/-Postman-FF6C37?logo=postman&logoColor=white)

## Featured projects

### 🔧 [Mechanic Client Manager](https://github.com/Tortz123/Mechanic-Client-Manager)
`Node.js` `Express.js` `PostgreSQL` `REST API`

A full-stack app where mechanics manage clients, cars, and service records. Features a 4-table PostgreSQL schema with foreign keys, 10 REST endpoints verified with 17 Postman test cases, and cookie-based session authentication so each mechanic only sees their own clients.

### 🟩 [Multiplayer Wordle Game](https://github.com/cgutwin/CMPT371_A3_PythonSocketWordle)
`Python` `TCP Sockets`

A networked two-player Wordle built with a partner; I built the client. Uses a 6-command enum-based protocol over TCP, with client-side guess validation, state rollback when the server rejects a guess, and a colour-coded terminal UI.

### ⚡ [Matrix Multiplication Performance Study](https://github.com/Tortz123/Matrix-Multiplication-Performance-Study)
`C++` `x86-64 Assembly` `AVX`

A hand-written AVX SIMD matrix multiplication running 6× faster than a naive C++ version. Profiling with `perf` showed it cut L1 cache misses from 66% to 24%, and that Eigen's cache-blocked algorithm explained its remaining 4.7× lead. Assembly inspection showed the naive loop only partially vectorized with 128-bit `xmm` registers.

### 💬 Synchronised Group Chat Server
`C` `TCP Sockets` `Multithreading` `Linux`

A multi-client group chat server using one thread per client, handling up to 100 clients at once. Messages are tagged with the sender's IP and port, and a two-step handshake keeps shutdown synchronised across the server and every client. Passed all 12 server and client test cases from a fuzzing tool.






## Education

**Simon Fraser University**, B.Sc. Computing Science (expected December 2027)

