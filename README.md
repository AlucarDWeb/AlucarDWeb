<pre>
  1 -- AlucarDWeb
  2 -- Agentic era maximalist and accelerationist
  3
  4 local me = {
  5   name            = "Ferdinando",
  6   role            = "iOS~AI engineer at Wallapop",
  7   location        = "Barcelona",
  8   nvim_enthusiast = true,
  9   builds          = "tools for coding agents",
 10   runs            = "open models, locally",
 11 }
 12
 13 me.agent_tooling = {
 14   -- Code review in Neovim with a headless coding agent next to the diff.
 15   -- It explains the hunk under the cursor or reviews the whole change, and
 16   -- your comments go to a pending GitHub review. It drives Claude Code, pi
 17   -- or any other headless CLI.
 18   { "<a href="https://github.com/AlucarDWeb/agentic-review.nvim">AlucarDWeb/agentic-review.nvim</a>" },
 19
 20   -- The compiler's code graph of a Swift or Objective-C project, plus the
 21   -- commit history with PR descriptions and the repo's docs, as MCP tools.
 22   -- In the repo's benchmarks agents use 20 to 48% fewer tokens with it, at
 23   -- about the same accuracy.
 24   { "<a href="https://github.com/AlucarDWeb/codebase-brain">AlucarDWeb/codebase-brain</a>" },
 25
 26   -- A Claude Code plugin that finds the skills and memories you've stopped
 27   -- using and archives the ones you pick. Archived items can be restored.
 28   { "<a href="https://github.com/AlucarDWeb/claude-curator">AlucarDWeb/claude-curator</a>" },
 29
 30   -- Native Android and iOS clients for a self-hosted Hermes agent. They
 31   -- speak the same WebSocket protocol as the Hermes TUI and desktop app.
 32   { "<a href="https://github.com/AlucarDWeb/hermo">AlucarDWeb/hermo</a>" },
 33 }
 34
 35 return me
~
~
<b> NORMAL </b>│ main │ AlucarDWeb.lua                          lua │ utf-8 │ Bot │ 35:1 
</pre>
