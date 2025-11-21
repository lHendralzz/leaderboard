Leaderboard Service

A high-performance leaderboard service supporting:
Update user score
Get top leaderboard
Reset leaderboard

Optimized for high-frequency score updates using Redis sorted sets.

Features
1. Update User Score

Increment or set a user’s score efficiently.
Suitable for real-time games, quizzes, contests, and loyalty systems.

2. Get Top Leaderboard

Retrieve the top N users ranked by score.
Uses Redis ZREVRANGE / ZRANGE for fast ordered queries.

3. Reset Leaderboard

Clear or archive the current leaderboard.
Useful for daily, weekly, or seasonal competitions.

Tech Stack

Go (Golang) — API and business logic
Redis — Stores scores using sorted sets
REST API or gRPC
Optional: Docker, Kubernetes, CI/CD (GitHub Actions, ArgoCD)
