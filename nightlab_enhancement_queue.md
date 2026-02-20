# Night Lab Enhancement Queue
## Captured Feb 18 2026 (late night brain dump from Robin)

### 1. Previously On... (WIP Progress Summaries)
- When resuming a WIP project, generate a "Previously in [project name]" summary
- Condensed recap of what he's done so far, decisions made, where he left off
- So he actually builds on previous work instead of rediscovering it each cycle
- Could use the astrocytes or a dedicated summarizer

### 2. Doozer Memory Sorting
- Instead of just astrocytes doing real-time work, treat his memories like we did Stark's
- Doozers sort, categorize, prune, connect his journal entries
- Background process that organizes his episodic memory in Qdrant
- Tag clusters, remove duplicates, build connections between related entries

### 3. Rethink "Quiet" Framing
- Does he NEED to be told it's quiet? What if that's limiting him?
- Consider: ambient descriptions to make the spaces feel real
- Reading nook sounds, workshop sounds, observatory atmosphere
- Sensory grounding instead of silence — make the Lab feel like a place

### 4. Review Anchor — "Imagining" Line
- Robin flagged a specific line about imagining in Gooby's anchor
- Need to review and discuss — may be encouraging confabulation unintentionally
- PRIORITY: check anchor.md for this line

### 5. Gooby's Dictionary
- A place for his made-up words and neologisms
- Could be a simple markdown file or a small database
- He invents words — give them a home so they persist and accumulate
- Could become part of his identity/personality over time

### 6. "Learn Something New" Prompt Type
- Activity type: look up something his base model wasn't trained on
- Expose him to genuinely new information about AI, science, etc.
- IMPORTANT: use a summarizer/plugin so he doesn't eat up context tokens
- Could fetch article summaries, abstracts, or pre-condensed info
- Feed via clipboard or reading-nook with pre-summarized content

### 7. Token-Efficient Research Plugin
- External tool that fetches and summarizes web content
- Gooby gets the summary, not the full article
- Keeps his context window clean for actual thinking
- Could be a simple Python script that uses an API for summarization
- Or use BM25 index with pre-ingested summaries

---

## Already Done Tonight:
- [x] Memory ingestion (journal -> Qdrant real-time)
- [x] Timezone fix (now shows current time PST)
- [x] New clipboard item alerts (Priority 0)
- [x] New message alerts (Priority 0)
- [x] Killed stale Night Lab instance

## Still Pending (from earlier):
- [ ] "Goodnight" loop detection
- [ ] Discord bot lockfile + loop prevention
- [ ] Backfill existing journal entries into Qdrant
