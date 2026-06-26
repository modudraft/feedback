# Modudraft Feedback Repo — Setup TODO

## GitHub Settings (manual — cannot be done via files)

### Branch protection on `main`
Go to: Settings → Branches → Add rule → Branch name pattern: `main`

- [ ] Require a pull request before merging (no direct pushes)
- [ ] Require 1 approving review (when team grows)
- [ ] Dismiss stale reviews when new commits are pushed
- [ ] Do not allow bypassing the above settings (uncheck "Allow administrators to bypass")

### Discussions setup
Go to: Settings → Features → Discussions → Enable

Create these categories (Settings → Discussions → Manage categories):
- [ ] **Announcements** (type: Announcement) — release notes, changelog
- [ ] **Q&A** (type: Q&A) — questions with accepted answers
- [ ] **Ideas** (type: Open-ended discussion) — early-stage ideas
- [ ] **General** (type: Open-ended discussion) — everything else
- [ ] **Show and tell** (type: Open-ended discussion) — share what you built

### Labels
Create these labels (Issues → Labels → New label):
- [ ] `bug` — #d73a4a
- [ ] `enhancement` — #a2eeef
- [ ] `needs-triage` — #e4e669
- [ ] `mcp` — #0075ca
- [ ] `good first issue` — #7057ff
- [ ] `wontfix` — #ffffff
- [ ] `duplicate` — #cfd3d7
- [ ] `in progress` — #0e8a16
- [ ] `shipped` — #6f42c1

### Pinned discussions
Once Discussions are live, pin:
- [ ] A welcome / getting started post
- [ ] The current public roadmap

### Repository description and topics
Settings → General:
- [ ] Description: "Bug reports, feature requests, and community discussions for Modudraft"
- [ ] Website: https://modudraft.com
- [ ] Topics: `system-design`, `architecture`, `mcp`, `ai`, `diagramming`, `developer-tools`

## Automated (done via files in this PR)
- [x] Issue templates (bug, feature request, MCP issue)
- [x] Discussion templates
- [x] CONTRIBUTING.md
- [x] CODE_OF_CONDUCT.md
- [x] SECURITY.md
