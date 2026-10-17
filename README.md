# Enzora web application

Static frontend deployment for the Enzora research workspace.

Open https://enzora-agent.com/ . The private model API requires a workspace access code. Demo mode replays a saved real 1,000-candidate case and lets visitors repeat the workflow and inspect tools. Its MiniMax Assistant answers questions about the case without submitting model tasks.

Application source and deployment documentation: https://github.com/YuzhangLi2281/Enzora.

The authenticated API uses a dedicated Cloudflare Tunnel at https://api.enzora-agent.com/api. The CPU service runs in time-limited cluster allocations with a queued successor; availability remains subject to cluster scheduling and maintenance. This repository contains no model weights or API keys.
