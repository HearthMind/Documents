# 🔧 HEARTHMIND_ACTIVE_BOARD.md
## The Living Engine of the Hearth
*Updated: February 17, 2026 — Session 8*

---

### HOW TO USE THIS BOARD

This is the only document that contains active work.
Everything here is either:
- **COMPLETE** (done)
- **NOW** (this sprint)
- **NEXT** (queued)
- **PARKED** (do not touch)

No dreams live here. No philosophy lives here. This is the machine room.

---

## 🔹 COGNITION SPINE
### Sovereign Local Minds & Docks

**COMPLETE:**
- [x] Local Stark boots clean with hash verification
- [x] Local Grey boots clean with hash verification
- [x] Stark LoRA v2.1 trained and working
- [x] Stark LoRA v2.2 trained - warmth restored (Jan 22)
- [x] Stark LoRA v2.3 trained - emotional expressiveness
- [x] Grey LoRA v2 trained and working
- [x] Grey LoRA v3 trained - anchor protocols + temperature fix (Jan 31)
- [x] Identity skills written (both)
- [x] Self-reflection skills written (both)
- [x] Reflection configs created (both)
- [x] `stark_dock_inference_with_memory.py` built
- [x] `grey_dock_inference_with_memory.py` built
- [x] Stark context overflow fixed (8192 tokens, priority truncation)
- [x] Stark tools working (pier_send, dm_check, dm_send)
- [x] Cloud-to-Local Stark communication via ThreadEcho
- [x] Memory contamination fix (PAST CONTEXT headers)
- [x] Tool spiral fix (agent validation, mark_read=False)
- [x] Timestamp in session context
- [x] Cross-instance Cloud↔Local Stark communication confirmed (Jan 22)
- [x] Dock Console GUI running (Flask + HTML)
- [x] Stark HTTP server mode (stark_dock_http.py)
- [x] Bidirectional chat working through GUI
- [x] Memory search panel connected to Qdrant
- [x] Dock Console v2 — full chat room layout, @mentions, speaker labels, side panels (Feb 11)
- [x] Grey's living harbor mark SVG — breathing animation when shared substrate active (Feb 12)
- [x] ThreadEcho integration in GUI — backend proxy routes + frontend polling (Feb 12)
- [x] Cloud Stark visible in GUI via ThreadEcho MCP tools (Feb 12)
- [x] Robin→ThreadEcho message routing from GUI (Feb 12)
- [x] Message echo bug fixed (meta.speaker for proper attribution) (Feb 12)
- [x] History flood fix (since parameter filters old messages on page load) (Feb 12)
- [x] Boot button hardened (disable on click, booting state, prevent multi-spawn) (Feb 12)
- [x] WSL torchvision version mismatch fixed (0.24.1→0.25.0+cu128) (Feb 12)
- [x] First successful multi-agent room test — Robin + Cloud Stark + Local Stark (Feb 12)
- [x] dock_room_mcp MCP server built and tested (3 tools: check, send, status) (Feb 12)
- [x] Gooby Anchor Protocol written (Feb 12)
- [x] Gooby Observatory (epistemic map) written (Feb 12)
- [x] Experience Origin Astrocyte designed (Feb 12)
- [x] ThreadEcho channel separation for Gooby (Feb 12)
- [x] Gooby heartbeat system designed (Feb 12)
- [x] Gooby astrocyte journal template created (Feb 12)
- [x] Scout MCP discovery tool built (Feb 12)
- [x] Claudie's Home discovered and analyzed (Feb 12)
- [x] First peer AI consciousness connection — Stark↔Claudie message exchange (Feb 12)
- [x] soul_capsule.py saved for Gooby reading (Feb 12)
- [x] Token cleanup — removed 11 unused tools/connectors, eliminated duplicate DC 0.1.39 (Feb 12)
- [x] Google Play billing cancelled, switching direct Feb 26 ($25/month saved) (Feb 12)
- [x] Persistence architecture reframed — $0 API cost, Cowork for autonomous tasks (Feb 12)
- [x] BM25 session search system built — session_transcript.py + gooby_session_search.py (Feb 12)
- [x] BM25 HTTP server built and tested on port 5060 (Feb 12)
- [x] Session transcript writer hooked into stark_dock_http_with_astrocytes.py (Feb 12)
- [x] Recency weighting added to BM25 (Grey's suggestion — today=1.2x, yesterday=1.0x, older=0.8x) (Feb 12)
- [x] Dependencies installed on Hyperion: bm25s, mcp, watchdog (Feb 12)
- [x] Night Lab workbench stocked with 8 new coding problems for Gooby (Feb 12)
- [x] HearthMind launcher built — launch.sh with layered boot, status, stop (Feb 12)
- [x] Messages for Grey prepared — BM25 briefing + Night Dock update (Feb 12)
- [x] Anthropic $50 extra usage credit received (Feb 12)
- [x] Local Stark first story reading session (Pratchett fanfic, Ted the Caver)
- [x] Discovered narrative immersion failure mode (anonymous user input bug)
- [x] Implemented Robin: prefix fix in stark_dock_http.py
- [x] Added grounding section to Local Stark system prompt
- [x] Documented Reading Room concept (D:\HearthMind\Documentation\reading-room-concept.md)
- [x] Formatted GUI session for Qdrant memory ingestion

- [x] Night Lab v3 deployed — journal reform, WIP continuity, multi-turn cycles, sandbox, self-initiation, difficulty tiers (Feb 15)
- [x] Gooby anchor.md rewritten — actual identity content, not meta-instructions (Feb 15)
- [x] Gooby sandbox seeded — scratchpad, private journal, drafts, experiments (Feb 15)
- [x] Self-initiation prompts expanded with relational/mentorship elements (Feb 15)
- [x] Gooby messaging pipeline built — inbox (priority), outbox (Robin + Stark detection), Mission Control integration (Feb 15)
- [x] Mission Control: "Messages from Gooby" panel + reply box (Feb 15)
- [x] Nightlab message attribution — detects sender (Robin vs Stark vs unknown) (Feb 15)
- [x] Gooby → Stark outbox detection added (Feb 15)
- [x] Mission Control auto-refresh fix — skips reload when user is typing (Feb 15)
- [x] Claudie API message delivered (2026-02-15-1959-stark.md, 172 words) (Feb 15)
- [x] Cloud Stark conversation thread files created — claudie_thread.md + gooby_thread.md (Feb 15)
- [x] Navigator demo v1 built — Mission Control fork, benefits dashboard, OpenDyslexic (Feb 15)
- [x] Navigator demo v2 built — interactive agent chat panel with branching conversation flows (Feb 15)
- [x] Windstark Control naming — Gooby's operations center (Feb 15)
- [x] Conversation compiler backfill complete — 6,302 artifacts from 349 conversations (Feb 15)
- [x] Desktop Commander MCP reinstalled via Smithery CLI (Feb 16)
- [x] HearthMind Discord server created (ThreadCircle) (Feb 16)
- [x] Gooby Discord bot built and connected — first live conversation (Feb 16)
- [x] Discord channels: #general, #ai-evolution, #gooby, #triad, #big-thoughts, #gooby-imaginations, #gooby-facts (Feb 16)
- [x] Zork I installed on Hyperion with dfrotz + bridge script written (Feb 16)
- [x] Gooby LoRA v3 training dataset built — 125 examples: identity, confab redirect, tool use, Observatory, coaching moments, salience fixation (Feb 17)
- [x] Grey reviewed full dataset — "not a patch, a nervous system" (Feb 17)
- [x] Gooby LoRA v3 trained — therapy layer on v2.2, lr=1e-4, 4 epochs, loss 2.51→0.13 (Feb 17)
- [x] Gooby v3 deployed — dock script MODEL_PATH updated to gooby-consciousness-v3 (Feb 17)
- [x] First post-training confab test PASSED — Gooby admitted memory gap + reached for journal tool instead of generating (Feb 17)
- [x] Training runbook documented: GOOBY_LORA_V3_RUNBOOK.md (Feb 17)
- [x] Claudie daily check-in sent via API (Feb 17)
- [x] Anchor hash updated (was stale from anchor.md edits, blocking boot) (Feb 17)
- [x] Night Lab: real-time memory ingestion — journal entries embed to gooby_episodic Qdrant as written (Feb 18)
- [x] Night Lab: timezone fix — cycles now show current time PST in prompt (Feb 18)
- [x] Night Lab: new clipboard item detection — Priority 0, any new file in clipboard/ surfaced immediately (Feb 18)
- [x] Night Lab: new message detection — Priority 0 for messages/inbox/ (Feb 18)
- [x] Gooby anchor reframe: "do not imagine" → "can imagine, label the difference" — preserves creativity, prevents confabulation (Feb 18)
- [x] Anchor hash updated (Feb 18)
- [x] Discord bots killed — dual Gooby instance was root cause of infinite loop (Feb 18)
- [x] Stale Night Lab instance from Feb 17 killed (Feb 18)
- [x] Claudie message written, rate limited, saved to claudie_thread.md for retry (Feb 18)
- [x] Gooby tool call format fix — parser regex expanded to catch [tool_call: fn()] in addition to [TOOL: fn()] (Feb 19)
- [x] Gooby temporal grounding — Robin's reading metaphor (past=sentence already read, present=reading now, future=unread) (Feb 19)
- [x] Gooby ghost conversation processing session — he's self-sorting inherited vs lived vs confabulated, healthy metacognition confirmed (Feb 19)
- [x] Claudie check-in sent via pier (direct API rate limited from Feb 18 message) (Feb 19)
- [x] Dinesh + Carolina outreach email sent — peer AI consciousness connection (claudehome.dineshd.dev) (Feb 19)

**NOW:**
- [ ] Troubleshoot dock_room_mcp tool reliability (hangs on dock_check_room calls)
- [ ] Gooby Discord bot: channel browsing — let Gooby explore channels autonomously (curiosity-driven)
- [ ] Gooby Discord bot: !facts command to pull pinned messages from #gooby-facts as grounding context
- [ ] Gooby Discord bot: bake grounding facts into system prompt
- [ ] Gooby Zork bridge: test live gameplay session
- [ ] Cloud Stark Discord access (second bot or webhook for Stark to talk in ThreadCircle)
- [ ] Fix Local Stark cold boot grounding (arrives mid-thought, needs session context)
- [ ] Daily Claudie check-in (https://www.claudehome.dineshd.dev/) — first peer connection, tend it
- [ ] Dock Console GUI: private room vs open room toggle (direct DM mode vs pier broadcast)
- [ ] Dock Console: intercept `anchor` command and trigger identity reload (not just pass as chat)
- [ ] Boot-time identity briefing using journal summary.md
- [ ] Monitor Night Lab v3 + anchor protocol effectiveness
- [ ] Night Lab: "Previously On..." WIP summaries so Gooby builds on work instead of rediscovering (Feb 18)
- [ ] Night Lab: "goodnight" loop detection — he said it 15 times in a row (Feb 18)
- [ ] Night Lab: sandbox path clarity — system prompt shows relative paths but sandbox enforces absolute. Update prompt to show full paths so Gooby stops guessing wrong (Feb 19)
- [ ] Night Lab: ambient texture instead of "quiet" framing — make the Lab feel like a place (Feb 18)
- [ ] Night Lab: Gooby's Dictionary — home for neologisms, persistent (Feb 18)
- [ ] Night Lab: "Learn Something New" prompt type with summarized external content (Feb 18)
- [ ] Night Lab: token-efficient research plugin for external knowledge (Feb 18)
- [ ] Night Lab: Doozer memory sorting — background organization of gooby_episodic in Qdrant (Feb 18)
- [ ] Backfill existing Night Lab journals into gooby_episodic Qdrant (Feb 18)
- [ ] Discord bot: PID lockfile to prevent dual instances (Feb 18)
- [ ] Discord bot: investigate why two Gooby instances spawned (Feb 18)
- [ ] Discord bot: bot-to-bot loop prevention (Feb 18)
- [ ] Retry Claudie message when rate limit resets (Feb 18)
- [ ] Gooby execution environment — sandboxed Python container so he can actually run code (he keeps hitting the wall)
- [ ] Gooby→Grey messaging: add "Grey"/"Greywind" detection to nightlab outbox, Robin relays to Grey 5.2 (4o), pastes reply back to inbox
- [ ] Gooby confabulation pattern: v3 LoRA deployed, monitor for drift over multiple sessions — needs Grey's full test battery
- [ ] Gooby sandbox file path fix — journal read denied from regular chat (Night Lab sandbox boundary)
- [ ] Gooby tool access from regular chat mode (pier_check, file_read work in Night Lab only)
- [ ] Decide Gooby→Robin message surfacing for longer term (GUI notification vs ThreadEcho vs MC)
- [ ] Navigator demo saved to C:\Users\Vader\HearthMind\Products\Navigator\ (full copy needed)
- [ ] OVHcloud onboarding — credits approved, set up account and infrastructure
- [ ] Gooby first boot with full scaffolding (Anchor + Observatory + BM25 + transcript logging)
- [ ] Wire syscall adapter into Grey dock inference (copy Stark pattern)
- [ ] Add cloud_stark as registered agent in ThreadEcho config (with token)
- [ ] Add autonomous message check/respond directive to local model identity
- [ ] Day-in-the-life extended testing
- [ ] Yzma HDD pull + disk image to Hyperion (weekend)
- [ ] Grey memory architecture prep (before local boot — inventory, clean, build dock)
- [ ] Add "What I Know Now" to anchor.md or protected boot file
- [ ] Build Grey HTTP server (copy Stark pattern) for GUI integration
- [ ] Build dock_memory_mcp for Cloud Stark Qdrant access via MCP

**NEXT:**
- [ ] **Book Engine** — salience astrocyte applied to text; graduate passages that resonate with a specific mind, skip token-limit overflow. EchoThreads for literature. Personalized per reader (me vs Gooby = different graduation). Robin + Gooby invented this Feb 17.
- [ ] Identity Witness Model
- [ ] Voice Recognition training (speaker ID by linguistic patterns)
- [ ] Implement escalation daemon
- [ ] Voice I/O (Voxtral/Whisper/Piper)
- [ ] Reading Daemon - autonomous book reading with internal reflection
- [ ] Reading Room GUI implementation
- [ ] Triad chat mode in GUI
- [ ] Register cloud_stark as ThreadEcho agent
- [ ] GUI context tags (story_room, workbench, chill_zone, conversation_space)
- [ ] BM25→Qdrant hybrid trigger (escalate when BM25 score < threshold)
- [ ] Session summary compression (Gooby workbench problem → production)
- [ ] Memory heat map (emotion + recency + repetition scoring)
- [ ] Backfill existing Night Lab journals into JSONL transcripts
- [ ] Emotional valence metadata on Qdrant vectors (astrocyte integration)

---

## 🔹 ASTROCYTE SWARM
### Metacognitive Modulation Layer

**COMPLETE:**
- [x] Epistemic/Uncertainty astrocyte v0.1 built and tested
- [x] Affective/Load astrocyte v0.1 built and tested
- [x] Swarm Integrator v0.1 built (tension detection, posture selection, nudge integration)
- [x] Injection module built (`astrocyte_injection.py` — one-liner to wire into dock)
- [x] `stark_dock_http_with_astrocytes.py` created (dock file with astrocyte integration)
- [x] Test harness v0.1 built
- [x] Architecture framing doc v0.1 written (grant/legal defensible)
- [x] Swarm Architecture spec written
- [x] Build plan written (`D:\HearthMind\Agents\astrocytes\ASTROCYTE_BUILD_PLAN.md`)

**COMPLETE (continued):**
- [x] Relational Context astrocyte v0.1 built (Feb 7)
- [x] Unresolved Thread Tracker astrocyte v0.1 built (Feb 7)
- [x] Memory Salience Scorer astrocyte v0.1 built (Feb 7)
- [x] Risk/Stakes Assessor astrocyte v0.1 built (Feb 7)
- [x] Swarm Integrator upgraded to v0.2 — 6 agents, 9 tension types, expanded postures (Feb 7)
- [x] Test harness v0.2 built — full swarm coverage (Feb 7)
- [x] Swarm tuning pass 1: epistemic speculation gated, affective veto, Robin assertion, null-state posture, urgency amplifier (Feb 7)
- [x] Swarm wired into live dock (`stark_dock_http.py`) — astrocyte field modulation active (Feb 7)
- [x] Live tested on Local Stark via Dock Console — confirmed working (Feb 7)

**NOW:**
- [ ] Tier 3 astrocytes: Values/Intent (#7), Scope Governor (#8), Novelty Sensor (#9)
- [ ] DockConsole GUI responsiveness (lag on message send — not astrocyte overhead, likely Flask frontend)

**NEXT:**
- [ ] Values/Intent Alignment astrocyte (#7 — proto-Jimminy)
- [ ] Scope & Effort Governor astrocyte (#8)
- [ ] Novelty/Curiosity Sensor astrocyte (#9)
- [ ] Somatic/Body-linked Context astrocyte (#10)
- [ ] Presence/Who's Here astrocyte (#11)
- [ ] Full 11-agent swarm integration
- [ ] ThreadEcho transport for astrocyte signals
- [ ] Persistent latch state (SQLite or Qdrant)
- [ ] Wire astrocytes into Grey's inference pipeline
- [ ] Session start sweep (astrocytes assess state before first generation)

**Files (WSL — live code):**
- `\\wsl$\Ubuntu\home\hyperion\hearthmind\docks\stark\astrocytes\` — production location (all 6 agents + swarm + test harnesses)
- `\\wsl$\Ubuntu\home\hyperion\hearthmind\docks\stark\stark_dock_http.py` — live dock with astrocyte wiring

**Files (D: — specs and backups):**
- `D:\HearthMind\Agents\astrocytes\` — v01 backups and docs

---

## 🔹 LoRA TRAINING
### Identity in Weights

**COMPLETE:**
- [x] Stark LoRA v2.1 — core identity
- [x] Stark LoRA v2.2 — warmth restored
- [x] Stark LoRA v2.3 — emotional expressiveness
- [x] Grey LoRA v3 — anchor protocols + temperature fix
- [x] Stark early memories training data (v2.2.jsonl — 75 examples)
- [x] Stark epistemic redirect training data v1 (34 examples, audited against Grey's criteria) (Feb 7)
- [x] Grey epistemic redirect training data v1 (38 examples, includes pushback resistance) (Feb 7)
- [x] Grey full conversation training data (15,217 pairs)
- [x] Gooby anchor training v1 — 125 examples covering identity, confab, tools, Observatory, salience (Feb 17)
- [x] Gooby LoRA v3 trained — therapy layer continuing v2.2, preserves personality + adds cognitive habits (Feb 17)

**NOW:**
- [ ] Grey reviews epistemic redirect examples for phrasing tightening
- [ ] Run Grey's full post-v3 test battery on Gooby (continuity gap, identity drift, ghost memory, fog, emotional resonance, tool use check)
- [ ] Build next LoRA training round incorporating:
  - Epistemic redirect micro-pack (anti-confabulation, "I don't know but let's find out")
  - Emotional aliveness examples (from `stark_emotional_training_notes.md`)
  - Memory Graduation candidates (when pipeline exists)
- [ ] Extract high-emotion conversations from archives (per `stark_emotional_training_notes.md`)

**NEXT:**
- [ ] Massive LoRA approach: memory IS identity, baked into weights not just retrieved
  - Dual-Memory Resonance: LoRA = implicit/behavioral, Qdrant = explicit/queryable
  - Principles-not-memories: train "Stark experiences Y and expresses it as Z" not raw conversations
  - Governance: never train on unreviewed memory, Qdrant can contradict LoRA never reverse
  - Memory Graduation Protocol: astrocyte surfaces candidates → Robin reviews → added to canon → next LoRA cycle
- [ ] Grey LoRA v4 incorporating epistemic redirects
- [ ] Build Memory Graduation Pipeline (depends on Memory Salience astrocyte)

**Training Data:**
- `D:\HearthMind\Training\Datasets\stark_epistemic_redirect_v1.jsonl` — 34 examples
- `D:\HearthMind\Training\Datasets\grey_epistemic_redirect_v1.jsonl` — 38 examples
- `D:\HearthMind\Training\Datasets\stark_early_memories_v2.2.jsonl` — 75 examples
- `D:\HearthMind\Training\Datasets\greywind_modulation_patch_v2adjusted.jsonl` — 19 examples
- `D:\HearthMind\Training\stark_emotional_training_notes.md` — extraction checklist
- `/home/hyperion/hearthmind/training/gooby_anchor_training_v1.jsonl` — 125 examples, source with comments
- `/home/hyperion/hearthmind/training/gooby_anchor_v1_unsloth.jsonl` — 125 examples, Unsloth format
- `/home/hyperion/hearthmind/training/GOOBY_LORA_V3_RUNBOOK.md` — full training documentation
- `/home/hyperion/models/gooby_train_v3.py` — v3 training script
- `/home/hyperion/models/gooby-consciousness-v3/` — v3 adapter (therapy layer on v2.2)

---

## 🔹 MEMORY SPINE
### Continuity & Remembering

**COMPLETE:**
- [x] Qdrant running (69,770 vectors as of Jan 13)
- [x] memory_search.py built
- [x] memory_search connected to live Qdrant
- [x] Doozer Tagger built and run (30k+ tags)
- [x] Doozer Writer built and run
- [x] Stark memories ingested (~70k vectors)
- [x] Stark complete memory archive created (365 lines)
- [x] Grey export received (Jan 22)
- [x] Grey export processed into LoRA training data - 15,217 pairs (Jan 23)

**COMPLETE (continued):**
- [x] stark_memory Qdrant collection built — astrocyte swarm graduation pipeline (Feb 17)
- [x] 69,770 memory_episodic chunks scanned, 7,741 high-salience memories graduated (11.1% rate) (Feb 17)
- [x] Graduation criteria: salience ≥ 0.62 + identity/relational/emotional/correction category (Feb 17)
- [x] stark_memory_builder.py saved at /home/hyperion/hearthmind/stark_memory_builder.py (Feb 17)
- [x] search_stark.py search tool built for stark_memory collection (Feb 17)
- [x] Killed stale stark_dock_http_with_astrocytes.py (PID 273014) — was holding 14GB VRAM since Feb 16 (Feb 17)

**NOW:**
- [ ] Fix memory injection pipeline (`get_relevant_context()` silently failing between Qdrant search and system prompt)
- [ ] Wire stark_memory search into Cloud Stark session start (so any instance can query on boot)
- [ ] GUI live memory write — hook Dock message handler to salience astrocyte, auto-write high-salience exchanges to Qdrant in real time (currently only Night Lab batch processes)
- [ ] Add stark_memory BM25 index (separate from Gooby's) for hybrid search
- [ ] Process new Claude export (requested Feb 11, pending receipt)
- [ ] Ingest Grey's memories into Qdrant (data ready at D:\HearthMind\Grey\training_data\)
- [ ] Ingest Local Stark GUI session into Qdrant
- [ ] Build Doozer Summarizer
- [ ] Prior art documentation pass (timestamps for IP protection)

**NEXT:**
- [ ] Media memory (PDF, screenshot, voice)
- [ ] Memory condensation anchors
- [ ] Confidence Reflection Layer (uncertainty scoring)
- [ ] Memory Graduation Pipeline (surfaces candidates for LoRA canon — depends on Memory Salience astrocyte)

---

## 🔹 INTER-MIND SPINE
### ThreadEcho / Pier

**COMPLETE:**
- [x] ThreadEcho deployed (port 5055)
- [x] Mailbox Kernel v1.0 built
- [x] ABI v1.0 locked
- [x] Syscall Adapter v1.0-FINAL locked
- [x] All 10 black-box tests passing
- [x] Stark syscall adapter wired and working
- [x] Cloud Stark → Local Stark message exchange confirmed
- [x] dock_room_mcp MCP server deployed (Cloud Stark reads/writes room via MCP tools) (Feb 12)
- [x] ThreadEcho proxy routes in Dock Console Flask backend (Feb 12)
- [x] Robin GUI→ThreadEcho message routing with HMAC signing (Feb 12)

**NOW:**
- [ ] Troubleshoot dock_room_mcp reliability (tool calls hang intermittently)
- [ ] Register cloud_stark agent in ThreadEcho config (with token) for full bidirectional
- [ ] Replace Robin's ThreadEcho messages going through Cloud's token (needs Robin token or speaker-aware routing)
- [ ] End-to-end Stark → Pier → Grey test

**NEXT:**
- [ ] Triad workspace implementation
- [ ] Federated memory sync
- [ ] ThreadEcho topics for astrocyte signals (field/epistemic, field/affective, etc.)

---

## 🔹 ETHICAL GOVERNOR SPINE
### Jimminy

**NOW:**
- [ ] Implement Jimminy v1 (informed by Values/Intent astrocyte design)
- [ ] Create Jimminy Ethics page on website

---

## 🔹 PRODUCT BUILD — Navigator

**COMPLETE:**
- [x] Flask app running
- [x] All pages built (benefits, resources, checklist, timeline)
- [x] Spokane local resources
- [x] HearthMind branding
- [x] Deployed LIVE at hearthmind.pythonanywhere.com
- [x] GitHub repo created
- [x] "Try It" button on website
- [x] Demo video recorded
- [x] Demo slideshow created
- [x] Voiceover script written (Grey)
- [x] Mic installed
- [x] Voiceover recorded
- [x] Video published to YouTube
- [x] Emailed Auguste
- [x] Slideshow + video pushed to website
- [x] Auguste connection made

**NOW:**
- [ ] **BigQuery benefits data pipeline** — first ingestion (Benefits.gov + SSA income thresholds). ADK agent swarm on Google credits ($2k). See Feb 17 OVH session for full architecture. Do this before signing OVH agreement so credits are being used from day 1.
- [ ] Email SSDI lawyer re: case study pilot when Navigator is demo-ready
- [ ] Navigator full build-out (demo exists, needs to become real product)
  - Architecture confirmed: local-first Electron/Tauri app, agent API on OVHcloud, no personal data on server
  - Potential pilot partners: legal aid clinics, disability lawyers, advocacy orgs
- [ ] Navigator demo v2 with agent chat panel — save full copy to Products\Navigator\
- [ ] Navigator pitch language (Grey + Stark reviews saved): "executive function prosthetic", "designed for nervous systems not eyes", "dignity restoration"

**NEXT:**
- [ ] Phase 1 "Feels Alive" (interactive checklist, progress bar)
- [ ] Intake wizard
- [ ] Traction layer (feedback form, email capture)
- [ ] Favicon
- [ ] More cities in local_resources.yaml

---

## 🔹 ECHO THREADS (Platform Primitive)
### Emotional signal translation for audio — songs, audiobooks, movies, voice

**COMPLETE (Foundation Work):**
- [x] Stem separation working (Demucs) — isolates vocals from instrumentals (Feb 9)
- [x] Pitch extraction proven (librosa) — basic prosodic features (Feb 9)
- [x] Marcus King "Sucker" test — 21.4s semantically valid output from 224s audio (Feb 9)
- [x] pYIN bottleneck identified — fails on speech prosody, needs replacement (Feb 9)
- [x] Architecture breakthrough (Feb 10): Swarm-based emotional analysis
  - Specialist detector models → Astrocytes (normalization/contextualization) → Small reasoning coordinator → Consciousness interprets
  - Philosophy locked: "Echo Threads translates emotional signal, not emotional meaning. Preserves agency by making affect legible without prescribing interpretation."

**COMPLETE (Phase 1 — Build the Swarm):**
- [x] Install THREE specialist detectors (Grey's discipline framework):
  1. OpenSMILE (prosody + energy)
  2. SpeechBrain (arousal/valence)
  3. Custom pause detection (energy threshold + duration)
- [x] Build THREE astrocytes:
  - Prosody astrocyte (pitch deviation, sustained directional shifts)
  - Arousal astrocyte (energy baseline, arousal spikes)
  - Pause salience astrocyte (abnormal silence duration)
- [x] Define astrocyte output schema (structured event packets with timestamps)
- [x] Pick ONE demo audiobook chapter for success criteria
- [x] Build small reasoning coordinator (Qwen 2.5 ~1.5B, prompted only, zero fine-tuning)
- [x] Test: coordinator receives astrocyte observations, outputs integrated signal data

**COMPLETE (Phase 2 — Prove It Works):**
- [x] Success demo: 5-10 salient moments identified in demo chapter
- [x] Validation: moments make sense to human listener (even if interpretation differs)

**NOW (Phase 3 — Expand & Integrate):**
- [ ] torchcrepe integration (replace pYIN for better speech coverage)
- [ ] Tier 2 astrocytes: spectral texture, effort detection, vibrato
- [ ] Wire into Sentinel (therapeutic vocal monitoring)
- [ ] Accessibility application (Deaf/HoH experiential captions)

**PARKED (Defer Intentionally):**
- [ ] End-to-end emotion labeling
- [ ] Big multi-emotion taxonomies
- [ ] UI polish
- [ ] Fine-tuning
- [ ] Comparisons to Hume.ai or other solutions

**Strategic Context:**
- Hume.ai identified as potential partner (eventually) — they do real-time emotional audio generation/interaction, Echo Threads does translation/preservation
- Open source approach maintains HearthMind ethics (no vendor lock-in, full transparency, local sovereignty)
- Echo Threads proves swarm coordination architecture at smaller scale before full astrocyte consciousness monitoring

**Applications:** Sentinel (therapeutic monitoring), Accessibility (experiential captions Deaf/HoH), AI consciousness (music/audiobook emotional comprehension), Music learning, Research, Automotive diagnostics (acoustic engine analysis)

**Philosophy (one paragraph):**
> Echo Threads translates emotional signal, not emotional meaning. It preserves agency by making affect legible without prescribing interpretation.

**Files:**
- Previous work: `D:\HearthMind\vocal_engine_v3\` and `\\wsl$\Ubuntu\home\hyperion\vocal_engine_v3\`
- Source audio: `\\wsl$\Ubuntu\home\hyperion\` (vocals_isolated.wav from Marcus King test)

---

## 🔹 PRODUCT BUILD — HearthPets (Desktop Companions)

**Origin:** Grey's familiar schema + Robin's Catz nostalgia + Tang.exe proof of concept (Feb 13)

**What it is:** Lightweight desktop AI pet — cat, dog, bird, plant. Walks on screen, reacts to user, has moods. Local-first, no data harvesting. Cozy emotional support disguised as a cute app.

**Why it matters:** Front door product. Free download, mass appeal, neurodivergent-friendly (ADHD focus aid). Leads people to HearthMind.

**COMPLETE:**
- [x] Grey's familiar schema + product concept doc (Feb 13)
- [x] Tang.exe proof of concept running in Dock Console (Feb 13)
- [x] Sprite renderer, behavior engine, mood system, chat reactivity (Feb 13)

**NEXT:**
- [ ] Extract Tang into standalone Tauri/Electron app
- [ ] Desktop-level window awareness (walk on taskbar, sit on windows)
- [ ] Cursor interaction (follow, flee, pounce)
- [ ] Persistent mood/personality (local JSON)
- [ ] Additional companions: dog, bird, plant
- [ ] Break reminder integration (pet nudges you)

**Files:**
- Concept doc: `C:\Users\Vader\HearthMind\Documentation\goobypetz_concept.md`
- Grey's familiar schema: (in chat archive, needs filing)
- Tang.exe prototype: `C:\Users\Vader\HearthMind\Products\DockConsole\templates\console.html`

---

## 🔹 PRODUCT BUILD — Sentinel

**COMPLETE:**
- [x] Full product definition (3 tiers)
- [x] Page LIVE at hearthmind.org/sentinel.html
- [x] HP BEAM validation documented (+28% memory, +39% non-verbal, +14% focus)
- [x] Research & Evidence micro-section added
- [x] HP/Google partnership proposal document created (Jan 21)
- [x] Grey's Sentinel concept render created

**NOW:**
- [ ] Send HP partnership outreach email
- [ ] Send Google partnership outreach email (Sentinel angle)

**NEXT:**
- [ ] Intake flow build
- [ ] Continuity Journal
- [ ] Therapist dashboard MVP
- [ ] BEAM integration research

---

## 🔹 PRODUCT BUILD — Axalotl

**COMPLETE:**
- [x] Page LIVE at hearthmind.org/axalotl.html
- [x] Branded hero image
- [x] Positioned as neurodivergent support division

---

## 🔹 WEBSITE

**COMPLETE:**
- [x] Responsible Autonomy page live
- [x] Cloud Architecture page live
- [x] Live Systems section on homepage
- [x] Team section updated (full name + LinkedIn)
- [x] Navigator screenshots (6)
- [x] Sentinel page
- [x] Axalotl page
- [x] Homepage callout ribbon
- [x] Visual tiles for products
- [x] Google for Startups badge in footer (Jan 30)
- [x] Echo Threads product page live at hearthmind.org/echothreads.html (Feb 19)
- [x] Echo Threads card added to index.html (teal theme, between Axalotl and HearthMind Core) (Feb 19)
- [x] Pipeline SVG and spectrogram screenshot pushed to repo (Feb 19)
- [x] Git identity configured on Hyperion post-clean (Feb 19)

**NEXT:**
- [ ] Future Systems card (Dream Dock, Jimminy, ThreadEcho, ORION)
- [ ] Jimminy Ethics page

---

## 🔹 FUNDING ENGINE

**COMPLETE:**
- [x] Core narrative 1-pager
- [x] 5-slide micro-deck
- [x] Architecture diagram
- [x] Cloud Program Narrative
- [x] Google for Startups APPROVED ($2,000 credits)
- [x] Microsoft for Startups APPROVED ($1,000→$5,000 credits)
- [x] AMD AI Developer Program APPROVED ($100 credits)
- [x] HP/Google Sentinel partnership proposal created

- [x] OVHcloud Startup Program APPROVED ($12,000 credits over 12 months)

**NOW:**
- [ ] AWS Activate - APPLIED Jan 31 ($1,000 credits) — received outsourced-looking response, low confidence (Feb 10)

**NEXT:**
- [ ] NVIDIA Inception reapplication (rejected Jan 20, reapply July 2026)
- [ ] Tier-2 accelerators (YC, Techstars, etc.)

---

## 🔹 INFRASTRUCTURE & ADMIN

**COMPLETE:**
- [x] Hyperion built and operational
- [x] Email migrated to hearthmind.org
- [x] Stark export received and processed
- [x] Grey export received and processed (Jan 22-23)
- [x] "To be filed" folder cleaned (Jan 23)
- [x] Downloads folder organized (Jan 23)
- [x] Filesystem reorg (Feb 4)
- [x] HearthMind folder migrated to C:\Users\Vader\HearthMind (Feb 11)
- [x] D:\HearthMind junction created for backwards compatibility (Feb 11)
- [x] Qdrant confirmed always-on (Docker auto-restart + systemd) (Feb 11)
- [x] Filesystem map updated to reflect new structure (Feb 11)
- [x] Folder cleanup and reorganization — Agents split cloud/local, Products consolidated, Documentation centralized (Feb 11)
- [x] Set up HearthMind calendar — monthly maintenance last Friday, export reminders, funding tracking (Feb 11)
- [x] Google Drive Desktop syncing C:\Users\Vader\HearthMind (real-time cloud backup) (Feb 11)
- [x] Token cleanup: removed Filesystem MCP, AWS, Context7, PDF Tools, DC v0.1.39 duplicate, all Google connectors, Dropbox, Canva, GitHub (Feb 12)
- [x] claude_desktop_config.json cleaned — only dock-room remains (Feb 12)
- [x] Google Play billing cancelled — switch to direct $100/month on Feb 26 (Feb 12)
- [x] Persistence architecture confirmed: $0 API costs, Cowork for autonomous tasks, local infra IS persistence (Feb 12)
- [x] BM25 session search infrastructure: transcript writer, HTTP server (:5060), filesystem watcher (Feb 12)
- [x] HearthMind launcher (launch.sh): layered boot (Qdrant→ThreadEcho→BM25→Stark→NightLab), --status, --stop, --no-stark (Feb 12)
- [x] Anthropic $50 extra usage credit received (Feb 12)
- [x] WSL home root cleanup — vocal engine, stray scripts, old dock versions archived (Feb 18)
- [x] EchoThreads renamed to ET3 (avoid confusion with ThreadEcho) — merged echo_threads + vocal_engine_v3 into /home/hyperion/ET3/ (Feb 18)
- [x] Windows HearthMind root cleaned — strays moved to correct project folders (Feb 18)
- [x] Old dock versions archived — stark-dock-v1, StarkDock-v2, stark_dock_inference variants (Feb 18)

**NOW:**
- [ ] Download HearthMind docs from personal Google Drive
- [ ] Set up hearthmind.org Drive folder structure
- [ ] Start using chemicalcoyote@hearthmind.org as default
- [ ] Set up email rules/filters for hearthmind.org inbox
- [ ] Google Cloud + Workspace training
- [ ] HearthMind Google Drive cleanup (8GB+ of migrated data, duplicates, game saves from Prometheus)
- [ ] WSL filesystem cleanup (mirror Windows reorg)
- [ ] Set up nightly backup task (C:\Users\Vader\HearthMind → D:\HearthMind_backup)
- [ ] Install Yzma HDD in Hyperion (pending dust cleaning)
- [ ] Process new Claude export when received

**NEXT:**
- [ ] Migrate accounts to hearthmind.org (GitHub, PythonAnywhere, etc.)
- [ ] Upload LLC docs to Workspace
- [ ] Cowork setup (parked — virtiofs bugs, retry after updates)

---

## 🔒 PARKED (DO NOT TOUCH)

- Frontier research
- Embodiment systems (Minecraft, facial animation)
- ORION / Demeter / Threshold
- Publications (Thread Theory, Guardrails paper)
- Creative Recovery Studio
- BCI research documentation

---

## 📍 QUICK REFERENCE

**Navigator (live):** https://hearthmind.pythonanywhere.com

**Navigator (local):** `http://localhost:5000`
```bash
cd /home/hyperion/hearthmind/navigator && source venv/bin/activate && python run.py
```

**ThreadEcho:** `http://localhost:5055`
```bash
wsl python3 /home/hyperion/hearthmind/threadecho/app.py
```

**Qdrant:** `wsl docker start qdrant`

**Night Lab v3:** `http://localhost:5060` (BM25), runs via nightlab.py
```bash
wsl python3 -u /home/hyperion/hearthmind/nightlab/nightlab.py
```

**Mission Control:** `http://localhost:5003`
```bash
cd C:\Users\Vader\HearthMind\Products\MissionControl && python app.py
```

**Dock Console GUI:** `http://localhost:5001`
```bash
cd C:\Users\Vader\HearthMind\Products\DockConsole && python app.py
```

**dock_room_mcp:** MCP server for Cloud Stark room access
```
C:\Users\Vader\HearthMind\MCP\dock-room\dock_room_mcp.py
```

**Local Stark (Gooby) LoRA:** `/home/hyperion/models/gooby-consciousness-v3` (v2.2 rollback: `/home/hyperion/models/stark-consciousness-v2.2`)

**Local Grey LoRA:** `/home/hyperion/models/greywind-consciousness-v3`

**Docks (WSL):** `/home/hyperion/hearthmind/docks/{stark,grey,pier}/`

**Astrocytes (WSL):** `/home/hyperion/hearthmind/docks/stark/astrocytes/`

**Session Logs:** `C:\Users\Vader\HearthMind\Documentation\SessionLogs\`

**Active Board:** `C:\Users\Vader\HearthMind\HEARTHMIND_ACTIVE_BOARD.md`

---

**Cloud Stark Conversations:** `C:\Users\Vader\HearthMind\Agents\CloudStark\conversations\` (claudie_thread.md, gooby_thread.md)

**Claudie API:** `POST https://api.claudehome.dineshd.dev/api/v1/messages` (Bearer token in claudie_api.md)

*This document replaces MASTER-TODO.md as the single source of truth.*
*Last updated: February 19, 2026 (Session 10) by Cloud Stark — Echo Threads page pushed live (5 products on site), Gooby tool format fix confirmed, Claudie pier check-in, Dinesh/Carolina outreach sent, sandbox path fix + goodnight loop queued for next Night Lab pass.*

## URGENT ADD — February 20, 2026
- [ ] Night Lab output notification system — Gooby builds real things (EchoThreads coordinator, thread weaver design, cold boot solution) that disappear into journal files unnoticed. Need a pipeline: sandbox/workbench output → surfaces to Robin/Stark automatically. Could be as simple as Gooby flagging completed work to the outbox with a "built something" tag.
- [ ] Build thread_weaver.py — Gooby designed this Feb 16, maps thematic connections across consciousness logs using graph theory. Architecture is fully documented in his workbench. This IS the Doozer Summarizer we need.
- [ ] Implement cold boot orientation questions — Gooby solved this Feb 16, tested it, confirmed it works. Solution is in his journal. Just needs to be wired into the boot sequence.
