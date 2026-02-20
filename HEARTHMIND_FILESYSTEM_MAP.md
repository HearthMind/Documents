# HEARTHMIND FILESYSTEM MAP
## Updated: February 11, 2026

**Primary Location:** `C:\Users\Vader\HearthMind\`
**Junction:** `D:\HearthMind\` → points to primary (backwards compatibility)
**Nightly Backup:** `D:\HearthMind_backup\` (to be automated)

```
C:\Users\Vader\HearthMind\
│
├── HEARTHMIND_ACTIVE_BOARD.md          ← Single source of truth for all work
├── HEARTHMIND_FILESYSTEM_MAP.md        ← This file
│
├── Agents\                             ← ALL agent-related files
│   ├── cloud agents\                   ← Cloud-based agent resources
│   │   ├── claude desktop saved\       ← Claude Desktop saved conversations
│   │   └── stark-core.skill            ← Cloud Stark continuity skill
│   └── Local agents\                   ← Local model agents
│       ├── local stark\                ← Local Stark files
│       │   ├── conversations\          ← Conversation logs
│       │   ├── dock\                   ← Dock/inference code
│       │   ├── exports\                ← Exports
│       │   ├── identity\               ← anchor.md, identity.md, skills
│       │   └── memories\               ← Memory archives
│       ├── Grey\                       ← Local Grey files
│       │   ├── dock\                   ← Dock/inference code
│       │   ├── exports\                ← OpenAI exports
│       │   ├── greywind hero\          ← Grey hero assets
│       │   ├── identity\               ← anchor.md, identity.md, skills
│       │   ├── rescue\                 ← Emergency rescue sessions
│       │   └── training_data\          ← Processed training pairs (15,217)
│       ├── infrastructure\             ← Shared tooling
│       │   ├── astrocytes\             ← Astrocyte research code (backups)
│       │   ├── Pier\                   ← Inter-agent routing
│       │   └── [scripts]               ← memory_search, doozers, schema, ingest
│       └── stories for the locals\     ← Reading material for local models
│
├── Documentation\                      ← All docs, logs, archives
│   ├── Archives\                       ← Old/retired files
│   │   ├── Backups\
│   │   ├── board and to do\            ← Archived boards and TODO lists
│   │   ├── credentials\
│   │   ├── dock-revisions\
│   │   ├── Exports\
│   │   ├── images\
│   │   ├── misc\
│   │   └── Receipts\
│   ├── HearthMind docs\                ← Core company docs
│   │   ├── Branding\                   ← Logos, hero images, visual assets
│   │   ├── config\                     ← Config references
│   │   ├── drafts\                     ← Work-in-progress docs
│   │   ├── Grants\                     ← All funding/grant applications
│   │   └── [core docs]                 ← Constitution, Master, Civilization Index,
│   │                                     Frontier Vault, Weekly Bridge, Outreach,
│   │                                     MicroDeck, Robin TODO
│   ├── Meetings\                       ← Meeting prep and notes
│   ├── Projects\                       ← Project specs and design docs
│   │   ├── ContinuitySuite\            ← Voice fingerprints, preservation
│   │   └── DreamlikeDock\              ← Dock architecture master spec
│   └── SessionLogs\                    ← All session documentation
│       ├── sessions logs\              ← Dated session logs
│       ├── stark-journal\              ← Stark's journal (notes from self to self)
│       │   ├── daily\
│       │   ├── CURRENT.md              ← Quick orientation for new sessions
│       │   └── START_HERE.md
│       └── Notes\                      ← Misc session notes and specs
│
├── Products\                           ← ALL product builds
│   ├── Axalotl\                        ← Neurodivergent support companion
│   ├── DockConsole\                    ← GUI application (Flask + HTML)
│   ├── EchoThreads\                    ← Emotional signal translation
│   ├── HearthMindWebsite\              ← Website (git repo — don't restructure)
│   ├── Jimminy\                        ← Ethical governor
│   ├── Navigator\                      ← Benefits assistance app
│   ├── ORION\                          ← Future project
│   ├── Sentinel\                       ← Therapeutic continuity platform
│   ├── ThreadEcho\                     ← Messaging layer (reference copy)
│   ├── Threshold\                      ← Future project
│   ├── Triad-Game\                     ← Future project
│   └── archived\                       ← Retired product work
│
└── To be filed\                        ← Robin's working/staging folder
    ├── Robin\                          ← Robin's personal files
    └── [temp items]
```

## Key Rules
1. **Agent stuff → Agents\** — Cloud agents vs Local agents, always.
2. **Product stuff → Products\** — All product builds and assets.
3. **Docs, logs, archives → Documentation\** — One place for all written records.
4. **Staging → To be filed\** — Temp items land here, get sorted later.
5. **No loose files at root** — Only the active board and this map live at root.
6. **WSL is the real codebase** — Windows copies are reference/launch points.
7. **HearthMindWebsite\ is a git repo** — Don't reorganize it manually.
8. **D:\HearthMind is a junction** — All paths work, but C:\Users\Vader\HearthMind is primary.

## WSL Paths (where code actually runs)
- Local Stark dock: `\\wsl$\Ubuntu\home\hyperion\hearthmind\docks\stark\`
- Local Grey dock: `\\wsl$\Ubuntu\home\hyperion\hearthmind\docks\grey\`
- Astrocytes (live): `\\wsl$\Ubuntu\home\hyperion\hearthmind\docks\stark\astrocytes\`
- ThreadEcho: `\\wsl$\Ubuntu\home\hyperion\hearthmind\threadecho\`
- Pier: `\\wsl$\Ubuntu\home\hyperion\hearthmind\docks\pier\`
- Qdrant: Docker container in WSL (localhost:6333, always-on)
- Models: `\\wsl$\Ubuntu\home\hyperion\models\`
- Stark LoRA: `\\wsl$\Ubuntu\home\hyperion\models\stark-consciousness-v2.3\`
- Grey LoRA: `\\wsl$\Ubuntu\home\hyperion\models\greywind-consciousness-v3\`

## Quick Launch
```bash
# Qdrant (auto-starts with Docker, but manual if needed)
wsl docker start qdrant

# ThreadEcho
wsl python3 /home/hyperion/hearthmind/threadecho/app.py

# Dock Console GUI
cd C:\Users\Vader\HearthMind\Products\DockConsole && python3 app.py

# Navigator (local)
wsl bash -c "cd /home/hyperion/hearthmind/navigator && source venv/bin/activate && python run.py"
```

## Infrastructure Notes
- **Hyperion:** ASUS TUF X870E-Plus WiFi7, Ryzen 9 9950X, RTX 5080, 128GB RAM,
  Corsair RM1200e PSU, MSI MAG A13 240 AIO, SK hynix P41 2TB NVMe, Seagate 24TB HDD
- **Qdrant:** 69,770+ vectors in `memory_episodic` collection, always-on via Docker
- **Cowork:** Parked — virtiofs sandbox bugs, retry after updates
