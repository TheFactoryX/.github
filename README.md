# ⚙️ .github

[![ANTI-LICENSE](https://img.shields.io/badge/ANTI--LICENSE-STEAL_THIS-000000?style=for-the-badge&labelColor=dc143c)](LICENSE)
[![Machine Status](https://img.shields.io/github/actions/workflow/status/TheFactoryX/.github/update-projects.yml?style=flat-square&label=control)](https://github.com/TheFactoryX/.github/actions)
[![GitHub Stars](https://img.shields.io/github/stars/TheFactoryX/.github?style=flat-square&logo=github)](https://github.com/TheFactoryX/.github/stargazers)
[![Last Commit](https://img.shields.io/github/last-commit/TheFactoryX/.github?style=flat-square)](https://github.com/TheFactoryX/.github/commits)
[![TheFactoryX](https://img.shields.io/badge/TheFactoryX-black?style=flat-square&logo=github)](https://github.com/TheFactoryX)

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
| Metrics | org-metrics.yml |
| Display | profile/README.md |
| Schedule | Daily / Every 6h |
| Output | Organization profile |

---

## Organization Metrics

| Metric | Live |
|--------|------|
| 👥 Followers | ![Followers](https://img.shields.io/github/followers/TheFactoryX?style=flat-square&logo=github&label=) |
| 📦 Repositories | ![Repos](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/orgs/TheFactoryX&query=public_repos&style=flat-square&label=&color=blue) |

> *Full stats generated every 6 hours → [profile/STATS.md](profile/STATS.md)*

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

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=TheFactoryX/.github&type=Date)](https://star-history.com/#TheFactoryX/.github&Date)

---

## Anti-License

[ANTI-LICENSE](LICENSE) — This is not a license. This is an invitation.

Take it. Use it. Break it. Fix it. Sell it. Give it away.

If you need permission, you're thinking too much.

---

**Strange people. Strange things.**

📧 hi@sdpkjc.com
