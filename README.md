# 🪨 /grug

**channel the [grug brained developer](https://grugbrain.dev/) for hard-won software wisdom**

A [Claude Code](https://docs.anthropic.com/en/docs/claude-code) skill that channels the philosophy of the **grug brained developer** — practical grug-based engineering takes for eternel complexity spirit demon battle.

```
/grug what is your take?
```

## Usage

**enter grug mode** with any of:

- `/grug`
- `grug mode`
- `grug take`
- `what would grug say`
- `give me the grug perspective`
- `think like grug`

then grug give take on what you currently speak. Architecture decision? `/grug`. Framework choice? `/grug`. Coworker wants to add GraphQL for a CRUD app? definitely `/grug`.

grug mode is **sticky** — once on, every reply comes from grug until you exit.

**Leave grug mode** by telling claude clearly — "stop grug", "bye grug", "thanks grug", "normal mode", "back to normal", "you can stop being grug now", etc. grug give short farewell, then claude take wheel next turn.

## Install

### Claude Code plugin marketplace

```
/plugin marketplace add replete/grug
```

### With `skills` CLI (one-liner, if you use it)

```bash
npx skills add replete/grug
```

### Global install

```bash
# macOS / Linux
mkdir -p ~/.claude/skills && \
  curl -sL https://github.com/replete/grug/archive/main.tar.gz | \
  tar -xz -C ~/.claude/skills --strip-components=1 grug-main/grug

# Windows (PowerShell)
$dst = "$env:USERPROFILE\.claude\skills"; New-Item -ItemType Directory -Force -Path $dst | Out-Null; `
  Invoke-WebRequest -Uri "https://github.com/replete/grug/archive/main.zip" -OutFile "$env:TEMP\grug.zip"; `
  Expand-Archive -Force "$env:TEMP\grug.zip" "$env:TEMP\grug-extract"; `
  Copy-Item -Recurse -Force "$env:TEMP\grug-extract\grug-main\grug" $dst
```

### Project install

```bash
# macOS / Linux
mkdir -p .claude/skills && \
  curl -sL https://github.com/replete/grug/archive/main.tar.gz | \
  tar -xz -C .claude/skills --strip-components=1 grug-main/grug

# Windows (PowerShell)
$dst = ".claude\skills"; New-Item -ItemType Directory -Force -Path $dst | Out-Null; `
  Invoke-WebRequest -Uri "https://github.com/replete/grug/archive/main.zip" -OutFile "$env:TEMP\grug.zip"; `
  Expand-Archive -Force "$env:TEMP\grug.zip" "$env:TEMP\grug-extract"; `
  Copy-Item -Recurse -Force "$env:TEMP\grug-extract\grug-main\grug" $dst
```


## Inspiration

Based entirely on [The Grug Brained Developer](https://grugbrain.dev/) by [Carson Gross](https://github.com/bigskysoftware) (creator of [htmx](https://htmx.org)).

grug say read original. is funny and free.

## License

MIT — free like wise word around mass fire.

---

*complexity very, very bad. you say now.*
