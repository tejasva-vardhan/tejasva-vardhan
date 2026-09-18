# Tejasva Vardhan Sharma

Information Science undergraduate at Dayananda Sagar College of Engineering, Bengaluru.

I write backends in Go and Python (HTTP APIs, SQL, background workers) and contribute to open-source transit software.

## Open source

[OneBusAway/maglev](https://github.com/OneBusAway/maglev) is a Go rewrite of the OneBusAway REST API (GTFS import, stops, trips, real-time vehicles, SQLite). I have merged pull requests there on transactions for GTFS bulk import, N+1 query fixes, concurrency, HTTP behaviour, and tests.

## Selected work

**[OBA-ReviewEval](https://github.com/tejasva-vardhan/oba-revieweval)** — Student study on 33 merged Maglev PRs: human review comments labelled into a gold set (198 comments → 266 atomic findings, 75 defect/design), plus a pinned golangci-lint baseline on the same merge commits. Language-model scoring is not finished.

**[Chandrayaan-2 image correspondence](https://github.com/tejasva-vardhan/Chandrayan-Lunar)** — Team pipeline that registers Chandrayaan-2 OHRC images against LROC NAC reference imagery (ingest → match → subpixel refine → warp). Scientific core is separate from a thin FastAPI + React layer. TMC-2 / IIRS are not live yet.

**[ContentDesk](https://github.com/tejasva-vardhan/ContentDesk)** — Write-once publisher: React/Tiptap editor, Go Echo API, PostgreSQL, RabbitMQ worker. Medium uses the write API first then headless Chrome; Dev.to uses the browser path.

**[AI Neta](https://github.com/tejasva-vardhan/AI-netaa)** — Civic-complaint chat app (Go, React, MySQL). Rule-based department routing and a time-based L1–L3 SLA worker. Demo phone OTP. Public case page without personal fields.

## Elsewhere

[Codeforces](https://codeforces.com/profile/TEJASVAvardhan)
