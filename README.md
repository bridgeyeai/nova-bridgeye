# NOVA

### _The World's First Self-Healing CLI Agent._

**nova** is an autonomous junior developer that lives in your terminal. It plans, executes, and — most importantly — **heals** code in a closed loop.

---

## **Why nova?**

In traditional development, AI writes code, but _you_ have to fix the environment and runtime crashes. **nova** closes the loop.

- **Self-Healing Execution:** Run any script with `run`. If it crashes, **nova** analyzes the traceback, finds the local file, and applies a **Surgical Edit** automatically.
- **Auto-Dependency Resolution:** Missing a library? **nova** detects the `ImportError`, installs the package in your active environment, and re-runs the task.
- **Path-Aware Intelligence:** **nova** understands your directory structure. It maps its brain to your local paths for accurate file operations.

---

## **Installation**

**Requires Python 3.10 or newer.**

```bash
pip install nova-bridgeye
```

Then start it:

```bash
nova
```

To upgrade later:

```bash
pip install --upgrade nova-bridgeye
```

All released versions are listed on [PyPI](https://pypi.org/project/nova-bridgeye/).

---

## **Quick Start**

1. **Activate** — type `nova` in your terminal to start the agent.
2. **Login** — follow the authentication prompt to sync your session.

Then talk to it at the prompt:

```
Plan a crypto price tracker in python
Build it
```

And let it run and repair your code:

```
run dashboard.py
```

**The "Magic Moment":** watch as nova detects a crash, locates the exact line in your file, patches the code, and verifies the fix by re-running the script automatically.

---

## **Documentation**

Full documentation: **[nova.bridgeye.com/documentation](https://nova.bridgeye.com/documentation/)**

Changelog: **[nova.bridgeye.com/releases](https://nova.bridgeye.com/releases/)**

Community: **[Discord](https://discord.gg/AHGzRfmWH)**

---

## **Security & Privacy**

1. **Privacy First:** Your code stays local. nova only analyzes errors and context during active "Healing" sessions to provide accurate fixes.
2. **User-in-the-Loop:** No file changes or package installations are made without your explicit permission.
3. **Enterprise Grade:** Built and maintained by Bridgeye Pvt Ltd.

---

© 2026 Bridgeye Pvt Ltd. All rights reserved. Licensed under [MIT](https://github.com/bridgeyeai/nova-bridgeye/blob/main/LICENSE).

Built for the future of autonomous development.
