## Hi 👋 I'm Hugo Pinto

Software engineering student at **42 Lisboa** and founder of **Hupi Games**, based in Lisbon. I like working close to the machine in C and C++, and building the backend of web applications in TypeScript, with NestJS and PostgreSQL.

## About me

At 42 Lisboa I've completed the common core — a peer-to-peer, project-based curriculum with no classes and no teachers, where every project is reviewed by other students before it counts. It took me from memory management and concurrency in C, through C++ and an HTTP server written from scratch, to Docker infrastructure and a full-stack web platform built by a team of four, where I was also product owner.

Outside 42 I founded **Hupi Games**, an indie studio. Our two puzzle games, [**Out of Moves**](https://www.xbox.com/games/store/out-of-moves/9P7BXDRNXX3H) and [**Out of Moves: Another Try**](https://www.xbox.com/games/store/out-of-moves-another-try/9P5GSPKDSZLN), were signed by the publisher Afil Games and released in 2025 on **PlayStation, Xbox, Nintendo Switch and the Microsoft Store**. I'm now leading production on a third — a pixel-art puzzle game — directing the game design and managing the project with external artists.

## Languages

<img src="https://skillicons.dev/icons?i=c,cpp,py,js,ts,html,css,bash" alt="C, C++, Python, JavaScript, TypeScript, HTML, CSS, Bash" />

## Tools & Technologies

**Backend & data**<br>
<img src="https://skillicons.dev/icons?i=nodejs,nestjs,express,postgres,prisma,mysql,firebase" alt="Node.js, NestJS, Express, PostgreSQL, Prisma, MariaDB, Firebase" />

**Frontend**<br>
<img src="https://skillicons.dev/icons?i=react,nextjs,vite" alt="React, Next.js, Vite" />

**Infrastructure & systems**<br>
<img src="https://skillicons.dev/icons?i=docker,nginx,linux,debian,wordpress" alt="Docker, Nginx, Linux, Debian, WordPress" />

**Testing & workflow**<br>
<img src="https://skillicons.dev/icons?i=jest,git,github,notion,vscode,vim" alt="Jest, Git, GitHub, Notion, VS Code, Vim" />

**Game development**<br>
<img src="https://skillicons.dev/icons?i=godot" alt="Godot" />

## 42 Projects

The common core, in order. The linked repositories each carry a README explaining the design decisions behind them; the unlinked ones have no code to publish — a configured machine and a set of network topologies.

| Project | What it is | Stack |
| --- | --- | --- |
| [**Libft**](https://github.com/Redgtxt/Libft) | The first project: my own C standard library, rewritten function by function — strings, memory, number conversion and linked lists. It grew into the toolbox every later C project links against, with `ft_printf` and `get_next_line` folded in | C |
| [**ft_printf**](https://github.com/Redgtxt/ft_printf) | `printf` without `stdio` — walking a variadic argument list whose types the compiler cannot check, with hand-written base conversion and pointer formatting on top of a bare `write` | C |
| [**get_next_line**](https://github.com/Redgtxt/get_next_line) | Returning a file one line at a time when `read` only hands back fixed-size chunks — a static buffer carries the leftover bytes from one call to the next, and it holds up even at one byte per `read` | C |
| **Born2beRoot** | A Linux server set up inside a virtual machine under strict rules — encrypted LVM partitions, SSH only on port 4242 with root login disabled, a firewall, an enforced password policy, `sudo` that logs every command, and a script that broadcasts the machine's state every 10 minutes | Linux · sysadmin |
| [**so_long**](https://github.com/Redgtxt/So_long) | A tile-based 2D game in MiniLibX that treats its map file as hostile input — it checks the shape, the walls and every tile, then runs a flood fill to prove the level can be won before a window ever opens | C · MiniLibX |
| [**Pipex**](https://github.com/Redgtxt/Pipex) | How a shell runs `< in cmd1 \| cmd2 > out`, rebuilt with `pipe`, `fork`, `dup2` and `execve` — then extended to any number of commands and a `here_doc`, and tested against bash for the same output and exit codes | C · Unix processes |
| [**push_swap**](https://github.com/Redgtxt/push_swap) | Sorting with two stacks and eleven instructions, graded on how few instructions it prints — a greedy algorithm prices every candidate move before each push, averaging 588 instructions for 100 numbers against a limit of 700 | C · algorithms |
| [**Minishell**](https://github.com/ruigoncalves96/Minishell) | A bash-like shell, written in a pair — tokenizing, quote handling and `$VAR` expansion on the language side; pipelines, redirections, heredocs and signals on the systems side, with every file descriptor closed so nothing hangs or leaks | C · readline |
| [**Philosophers**](https://github.com/Redgtxt/Philosophers) | Dijkstra's dining philosophers — one thread per philosopher, one mutex per fork. Asymmetric fork ordering rules out deadlock, and a monitor thread reports a death well within the 10 ms the subject allows, with no data races | C · pthreads |
| **NetPractice** | Ten broken TCP/IP networks to fix by hand — subnet masks, address ranges, routing tables and default gateways — until every host reaches the ones it should | Networking |
| [**miniRT**](https://github.com/Redgtxt/MiniRT) | A ray tracer written from scratch in a pair — intersections with spheres, planes, cylinders and cones, Phong shading, coloured lights, reflection, refraction and antialiasing, plus a live control panel for editing the scene | C · MiniLibX |
| [**CPP Modules 00–04**](https://github.com/Redgtxt/CPP00-04) | The jump from C to C++98 — classes and references, operator overloading on a fixed-point number type, inheritance with the ClapTrap family, and polymorphism with abstract animals that deep-copy their brains | C++ |
| [**Webserv**](https://github.com/Redgtxt/webserv) | An HTTP/1.1 server written from scratch by a team of three, with an NGINX-style config, virtual hosts, file uploads and CGI. I built the network core — non-blocking sockets, a single `poll()` event loop across every port, client timeouts, and CGI scripts that run without blocking the loop | C++98 · sockets |
| [**CPP Modules 05–09**](https://github.com/Redgtxt/CPP05-09) | Exceptions, the four casts, templates and the STL — ending with a Bitcoin price lookup, an RPN calculator, and Ford–Johnson merge-insertion sort timed on `vector` against `deque` | C++ |
| [**Inception**](https://github.com/Redgtxt/Inception) | A WordPress stack in three containers — NGINX with TLS, PHP-FPM and MariaDB — with every image built by hand from Debian instead of pulled, idempotent setup scripts, Docker secrets, and one `make` to bring it all up | Docker · Compose |
| [**ft_transcendence**](https://github.com/Redgtxt/ft_transcendence) | A full-stack multiplayer Connect Four platform with live matches, spectators and an AI opponent, built by a team of four, where I was also product owner. I built the JWT authentication (httpOnly cookies, rate-limited login, protected routes) and account management, the REST API and dashboard for match history and statistics with CSV and PDF export, the match data model in PostgreSQL through Prisma, and a minimax AI with alpha-beta pruning | NestJS · Next.js · PostgreSQL · Prisma |

## Beyond 42

| Project | What it is | Stack |
| --- | --- | --- |
| [**gpt-cli**](https://github.com/Redgtxt/gpt-cli) | Ask a language model from the terminal — a C++ client that sends the question to the Groq API with libcurl, parses the JSON reply and prints a colourised answer, with the API key kept out of the code | C++ · libcurl |
| [**Ping-pong counter**](https://github.com/Redgtxt/ping-pong-counter-games) | An installable web app for settling ping-pong rivalries — scores sync in real time across phones through Firestore, every game has a shareable link, and the full match history is kept | React · Vite · Firebase |

## What I'm working on

- **Hupi Games** — production of our third title, a pixel-art puzzle game.
- **Mini-CRM API** *(work in progress)* — the backend of a small CRM, with companies, contacts, deals and activities, in TypeScript with Express and PostgreSQL. The SQL is written by hand instead of through an ORM, every endpoint gets its test before its code with Jest and Supertest, and it runs on Docker Compose with CI on GitHub Actions.
- **Data science at 42** — the Python for Data Science piscine, and a linear regression trained with gradient descent that I'm writing from scratch.
