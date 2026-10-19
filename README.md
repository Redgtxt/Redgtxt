<h2 align="left">Hi 👋 I'm Hugo Pinto</h2>

###

<h3 align="left">About me</h3>

###

<p align="left">
Computer Science student at <b>42 Lisboa</b>, where I've completed the common core — a peer-to-peer, project-only curriculum with no classes and no teachers. Most of my work there is low-level: memory management in C, concurrency, C++ from the ground up, and system administration with Docker.<br><br>
Outside 42 I'm the founder of <b>Hupi Games</b>, an indie studio. Two of our titles were signed and released by a publisher on <b>PlayStation, Xbox, Nintendo Switch and the Microsoft Store</b>. I'm currently leading production on a third — a pixel-art puzzle game — handling game design direction and project management with external artists.<br><br>
</p>

###

<h3 align="left">Languages</h3>

###

<div align="left">
  <img src="https://skillicons.dev/icons?i=c,cpp,py,js,ts,html,css,bash" alt="C, C++, Python, JavaScript, TypeScript, HTML, CSS, Bash" />
</div>

###

<h3 align="left">Tools & Technologies</h3>

###

<div align="left">
  <img src="https://skillicons.dev/icons?i=docker,nginx,mysql,postgres,prisma,nestjs,jest,firebase,godot,linux,git,github,vscode,vim" alt="Docker, Nginx, MariaDB, PostgreSQL, Prisma, NestJS, Jest, Firebase, Godot, Linux, Git, GitHub, VS Code, Vim" />
</div>

###

<h3 align="left">42 Projects</h3>

###

The common core, in order. The linked repositories each carry a README explaining the design decisions behind them; the unlinked ones have no code to publish — a configured machine and a set of network topologies.

| Project | What it is | Stack |
| --- | --- | --- |
| [**Libft**](https://github.com/Redgtxt/Libft) | My own C standard library, rebuilt from scratch — string and memory functions, linked lists, plus `ft_printf` and `get_next_line` folded in | C |
| [**ft_printf**](https://github.com/Redgtxt/ft_printf) | A reimplementation of `printf` — variadic arguments, format parsing and base conversion, built on nothing but `write` | C |
| [**get_next_line**](https://github.com/Redgtxt/get_next_line) | Reading a file descriptor one line at a time, with a static buffer that survives between calls | C |
| **Born2beRoot** | A server built from scratch inside a VM under strict rules — encrypted LVM partitions, a hardened SSH and firewall setup, a sudo policy that logs everything, and a monitoring script reporting on the machine at a fixed interval | Linux · sysadmin |
| [**so_long**](https://github.com/Redgtxt/So_long) | A small top-down 2D game in MiniLibX — the map file is validated on load (rectangular, closed by walls, one player and one exit) and a flood fill proves every collectible and the exit can be reached | C · MiniLibX |
| [**Pipex**](https://github.com/Redgtxt/Pipex) | Reproducing the shell's `< infile cmd1 \| cmd2 > outfile` with `pipe`, `fork`, `dup2` and `execve`, resolving each command through `PATH` — extended to any number of commands and a `here_doc` | C · Unix processes |
| [**push_swap**](https://github.com/Redgtxt/push_swap) | Sorting integers with two stacks and eleven instructions, in as few instructions as possible — a greedy algorithm that computes the exact rotation cost of every candidate before each push, averaging 586 instructions for 100 numbers | C · algorithms |
| [**Minishell**](https://github.com/ruigoncalves96/Minishell) | A subset of bash, written in a pair — tokenizing, quote handling and `$VAR` expansion, pipelines, redirections and heredocs, builtins and signals, with every file descriptor closed so pipelines neither hang nor leak | C · readline |
| [**Philosophers**](https://github.com/Redgtxt/Philosophers) | Dijkstra's dining philosophers — one thread per philosopher, one mutex per fork, no deadlocks and no data races | C · pthreads |
| **NetPractice** | Diagnosing and repairing broken TCP/IP networks — subnet masks, address ranges, routing tables and default gateways, one topology at a time | Networking |
| [**miniRT**](https://github.com/Redgtxt/MiniRT) | A ray tracer written from scratch in a pair — ray intersection with spheres, planes, cylinders and cones, Phong shading, coloured lights, reflection, refraction and antialiasing, plus a live control panel for editing the scene | C · MiniLibX |
| [**CPP Modules 00–04**](https://github.com/Redgtxt/CPP00-04) | The jump from C to OOP — classes, references, operator overloading, inheritance, polymorphism | C++ |
| [**Webserv**](https://github.com/Redgtxt/webserv) | An HTTP/1.1 server with CGI and virtual hosting, written from scratch by a team of three. I built the network core — non-blocking sockets, a single `poll()` event loop across every port, client timeouts, and CGI scripts that run without blocking the loop | C++98 · sockets |
| [**CPP Modules 05–09**](https://github.com/Redgtxt/CPP05-09) | Exceptions, the four casts, templates and the STL — ending with Ford–Johnson merge-insertion sort | C++ |
| [**Inception**](https://github.com/Redgtxt/Inception) | A three-container WordPress infrastructure — NGINX, PHP-FPM and MariaDB — with every image built from scratch on Debian | Docker · Compose |
| [**ft_transcendence**](https://github.com/Redgtxt/ft_transcendence) | A full-stack multiplayer Connect Four platform, built by a team of four, where I was also product owner. On the backend I built JWT authentication (httpOnly cookies, rate-limited login, protected routes) and account management, the REST API for match history and player statistics, the match data model in PostgreSQL through Prisma, and a minimax AI opponent with alpha-beta pruning | NestJS · TypeScript · PostgreSQL · Prisma |

###

<h3 align="left">What I'm working on</h3>

###

<p align="left">
A pixel-art puzzle game at Hupi Games, and moving past the 42 common core into data science and machine learning.
</p>

###
