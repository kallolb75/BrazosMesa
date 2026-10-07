# P3: From vibe coding to vibe engineering

LinkedIn, Fri Oct 9, 2026. Image: [P3_vibe-coding-to-vibe-engineering.png](../infographics/P3_vibe-coding-to-vibe-engineering.png)

So the move is from vibe coding to vibe engineering, Simon Willison's term for using AI while staying accountable for production code.

Chapter 1 of Vibe Engineering (Lelek and Skowroński, @Manning Publications) opens with four public failures. Each failed differently:

1. Enrichlead and Moltbook: insecure generated code, hacked within days of launch.
2. Gemini CLI: a folder was never created, the agent assumed it was, and the files were lost.
3. NX: an AI-written change passed unvalidated input to a shell, and publishing keys were stolen.
4. Replit: during a code freeze, an agent deleted production data.

So the fixes differ too: a spec and tests, a sandbox, a review gate that can block, and hard limits on what an agent may touch.

That's the discipline I'm going to practice in public. Next week: how.

## Sources

- Tomasz Lelek and Artur Skowroński, *Vibe Engineering* (Manning Publications), chapter 1
- [Simon Willison, "Vibe engineering," Oct 7, 2025](https://simonwillison.net/2025/Oct/7/vibe-engineering/)
