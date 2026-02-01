# ⚙️ .github

**The Control Room**

---

> *"Every factory needs a control room. This is ours."*

---

## What This Is

The nerve center of TheFactoryX.

This repository controls the organization profile. The face we show the world.

Every day, a script wakes. It scans all repositories. It counts the machines. It updates the display. Then it sleeps.

Automatic. Silent. Continuous.

---

## The System

| Control Room | Code |
|--------------|------|
| Script | update-projects.yml |
| Display | profile/README.md |
| Schedule | Daily |
| Output | Organization profile |

---

## How It Works

```
Workflow triggers
    │
    └── Fetches all repositories
            │
            └── Assigns emoji by project type
                    │
                    └── Updates profile/README.md
                            │
                            └── Commit. Push. Sleep.
```

Each repository gets its emoji:
- 🥫 Campbell's Soup Cans
- 🎬 Screen Tests
- 🪦 Epitaphs
- 📺 Broadcasting
- 📻 Radio Static
- ...and more

---

## Add Your Project

Edit `.github/workflows/update-projects.yml`:

```bash
elif [[ "$line" == *"your-project"* ]]; then
  project_list+="🆕 $line"$'\n\n'
```

The control room will find it. The display will update.

---

## Anti-License

[ANTI-LICENSE](LICENSE) — This is not a license. This is an invitation.

Take it. Use it. Break it. Fix it. Sell it. Give it away.

If you need permission, you're thinking too much.

---

**Strange people. Strange things.**

📧 hi@sdpkjc.com
