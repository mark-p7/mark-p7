# Hi, I'm Mark

I build backend services and network security tools, mostly in C, Python, and C#. Lately that means covert channels, password crackers, steganography, and supply-chain attack detection.

## Security & networking projects

| Project | What it does | Stack |
|---|---|---|
| [**KNOCC**](https://github.com/mark-p7/KNOCC) | Commander/victim backdoor simulation that stays dark until a port-knock sequence, then hides all traffic in UDP length and checksum fields. Go-back-N on top keeps delivery reliable over a few bytes per packet. The README covers how an IDS and `/proc` cross-checks catch it. | Python, raw UDP |
| [**CHASM**](https://github.com/mark-p7/CHASM) | Distributed `crypt(3)` hash cracker. The server hands out keyspace blocks over TCP, tracks checkpoints, and reissues unfinished work when a client dies. Blocks are computed from an index with base-79 math, so no wordlist is stored. | C, pthreads, sockets |
| [**Sentinel**](https://github.com/mark-p7/Sentinel) | GNN that flags malicious npm packages from 41 features per package across the dependency graph. Includes registry crawlers, simulated supply-chain attacks for training data, and a monitor that re-scans packages when a dependency updates. | Python, PyTorch Geometric, Neo4j, Redis |
| [**SHADE**](https://github.com/mark-p7/SHADE) | Hides any file in a PNG's blue-channel LSBs after encrypting it with Fernet, so a wrong key or modified payload fails authentication instead of producing garbage. | Python, `cryptography` |
| [**CoDefend**](https://github.com/mark-p7/CoDefend) | Chrome extension that intercepts downloads and fans them out to VirusTotal, Cloudmersive, and Bytescale through a Node backend before the download completes. Also checks URL reputation on click. | JavaScript, Node.js |

> [!WARNING]
> KNOCC and CHASM are offensive security research projects, built to study how these attacks work and how to detect them. Run them only in isolated labs, on systems you own or are explicitly authorized to test.

## Other projects

- [**Melloww**](https://github.com/mark-p7/Melloww): journaling and mood-tracking web app built with a small team. Next.js, TypeScript, Tailwind, Express, MongoDB.
- [**EngineerInTech**](https://github.com/mark-p7/EngineerInTech): matches engineers by the skills they want to teach and learn. TypeScript client and Node server.
- [**NoteTed**](https://github.com/mark-p7/NoteTed): server-rendered note-taking app with cross-device sync. Next.js, MUI, Firebase.

## Tools I reach for

C · C# / .NET · Python · TypeScript · Kafka · Docker · Kubernetes · PostgreSQL · Neo4j · Wireshark · tcpdump

[markdeguzman.com](https://www.markdeguzman.com)
