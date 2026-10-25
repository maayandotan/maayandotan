### Hi, I'm Maayan 👋

Fourth-year B.Sc. Software Engineering student at Ben-Gurion University (graduating March 2028), based in Israel. I like building things that work reliably under real-world mess: concurrent users, flaky third-party sites, and DRM that blocks the obvious approach.

Looking for a **student position in software engineering or backend development**.

---

#### ⚽ [Match Intelligence](https://github.com/maayandotan/premier-league-hackathon): Microsoft × Premier League "Inside the Game" hackathon, team of 2
Live AI football commentary that adapts to the viewer. Two AI agents, a play-by-play caller and a tactical analyst, call the match at your level and answer voice questions mid-match without pausing it. **[Live demo](https://match-intelligence-live.purplesand-eefdeaf2.francecentral.azurecontainerapps.io)**
- Every number the agents say (xG, possession, tactical patterns) comes from a stats engine written in code and exposed to them as tools, and each line is fact-checked before it's spoken.
- An event ranker decides when the commentators talk; a goal cuts in over lower-priority commentary and the broadcast then picks up where it left off.
- Python · FastAPI · React/TypeScript · Microsoft Foundry · Azure AI Speech · Azure Container Apps

#### 🏀 [CourtSide](https://github.com/maayandotan/courtside): personal project
A desktop app that brings sports streaming services (NBA League Pass, DAZN, Premier League, Champions League, NFL, EuroLeague) into one multi-view window, with **spoiler-free skip-to-quarter**.
- Screen capture of DRM video is blocked, so I find quarter boundaries by intercepting and parsing the stream's HLS manifest (via the Chrome DevTools Protocol), then seek through the embedded player's own API.
- Validated against real broadcasts: halftime detection hits exactly; the other quarters are a guess with a one-tap correction.
- Electron · Widevine (castlabs) · CDP · Node.js

#### 🎟️ [TicketPlatform](https://github.com/maayandotan/TicketPlatform): team of 8
An event-ticketing platform with seating maps, purchase policies, checkout, and refunds.
- I built the concurrency test suite that exposed double-booking races in seat reservation, and fixed them with per-event locking and optimistic versioning.
- Also built composite purchase policies, refund rollback, JPA persistence, and the barcode gateway.
- Java 21 · Spring Boot · React/TypeScript · PostgreSQL · 170 merged PRs

#### 🃏 [Blackjack Network](https://github.com/maayandotan/blackjackNetworkProject): team of 3
A multiplayer Blackjack client and server using a custom binary protocol, with UDP server discovery and TCP gameplay.
- Python · sockets · threading

---

**Tech:** Java · Spring Boot · Python · FastAPI · TypeScript · React · JavaScript/Node.js · Electron · SQL/PostgreSQL · Azure · GCP · Docker · Git

📫 [maayan.dotan25@gmail.com](mailto:maayan.dotan25@gmail.com) · [LinkedIn](https://www.linkedin.com/in/maayan-dotan-4a3472406/)
