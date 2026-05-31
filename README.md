# Eddie's Claude Code Plugins

A personal collection of Claude Code plugins.

## Installation

### 1. Add marketplace

```bash
claude plugin marketplace add git@github.com:edditz/claude-plugins-marketplace.git
```

### 2. Install plugin

```bash
claude plugin install claude-notify-plugin@edditz-plugins
```

### 3. Setup

Run the setup command in Claude Code:

```
/claude-notify-plugin:setup
```

This will guide you through configuring ntfy notifications.

## Available Plugins

### claude-notify-plugin

Push notifications for Claude Code events via ntfy.

**Features:**
- 🔔 Permission alerts when Claude needs approval
- ✅ Task completion notifications
- 📱 Mobile push notifications
- 🖥️ Smart terminal detection
- 🏠 Self-hosted server support

**Commands:**
- `/claude-notify-plugin:setup` — Interactive setup wizard
- `/claude-notify-plugin:config` — Configure notification settings
- `/claude-notify-plugin:toggle` — Toggle notifications on/off

## License

See individual plugin licenses.
