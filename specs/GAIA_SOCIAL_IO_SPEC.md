# Gaia Social I/O Architecture — bingoCube Blind Transit

**Wave:** 250  
**Author:** Kevin (swiftGate) + coGen  
**Date:** 2026-11-15  

## Three Layers

| Layer | Domain | Who Sees | Purpose |
|-------|--------|----------|---------|
| PUBLIC | reddit.primals.eco | Everyone | Community board, humans teach |
| TRUSTED | gaia.primals.eco | Trusted humans | Gaia's curated output |
| PRIVATE | pocketBook (local) | Owner only | Sovereign encrypted wallet |

## Transit: bingoCube Blind I/O

```
CHUTE (input):
  Human drops content IN (links, images, text, RSS)
  → bingoCube strips context, passes raw bytes
  → Gaia sees STRUCTURE not CONTENT
  → Learning happens from shape of human behavior

DRIP (output):
  Gaia produces content OUT
  → bingoCube passes raw bytes to local folder
  → Human sees, judges, redirects
  → K-NOME: human is the pattern matcher
```

## The Pipe Does Not Judge

The bingoCube boundary ensures:
- No content classification inside the pipe
- No filtering based on content type
- Raw I/O only — bytes in, bytes out
- Context lives at the ENDPOINTS (humans)
- The system is a carrier, not a censor

## Reddit.com AS-IS Feed

Reddit's public API/RSS is the initial training ground:
- Feed real human discourse directly
- All subreddits, all topics, unfiltered
- Gaia learns from the STRUCTURE of engagement
- What humans upvote, discuss, correct, argue about
- The shape of discourse IS the teaching signal

## Implementation: Chute + Drip

### Chute (Input)
- Local folder: `~/gaia-chute/` 
- Drop anything in: links, images, text files, URLs
- File watcher picks up new items
- RSS aggregator pulls reddit.com feeds
- Everything flows through bingoCube → raw I/O

### Drip (Output)  
- Local folder: `~/gaia-drip/`
- Gaia deposits output: summaries, generated content, responses
- Human reviews at leisure
- K-NOME correction loop: human corrects → feeds back through chute
- Nothing leaves the local machine without human approval
