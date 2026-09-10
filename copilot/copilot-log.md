2026-09-10T02:04:21.151Z INFO [settings-**migration**] migrating from v0 to v14
2026-09-10T02:04:21.152Z INFO [byok-migration] no legacy BYOK providers to migrate
2026-09-10T02:04:21.230Z ERROR createChainWithNewModel failed: MissingModelKeyError: No chat model enabled. Enable a model under Settings → Basic → Agents → Quick Chat, or add one on the Models (BYOK) tab.
2026-09-10T02:04:21.230Z INFO configuredModelId: google/gemini-2.5-flash|openrouterai
2026-09-10T02:04:21.255Z INFO VaultDataManager: Initializing with vault event listeners
2026-09-10T02:04:21.263Z INFO [Projects] Initializing ProjectFileManager
2026-09-10T02:04:21.263Z ERROR createChainWithNewModel failed: MissingModelKeyError: No chat model enabled. Enable a model under Settings → Basic → Agents → Quick Chat, or add one on the Models (BYOK) tab.
2026-09-10T02:04:21.263Z INFO configuredModelId: google/gemini-2.5-flash|openrouterai
2026-09-10T02:04:21.263Z ERROR createChainWithNewModel failed: MissingModelKeyError: No chat model enabled. Enable a model under Settings → Basic → Agents → Quick Chat, or add one on the Models (BYOK) tab.
2026-09-10T02:04:21.263Z INFO configuredModelId: google/gemini-2.5-flash|openrouterai
2026-09-10T02:04:21.263Z INFO No legacy userSystemPrompt to migrate
2026-09-10T02:04:21.626Z INFO [Skills] seeded builtin skills: copilot-web-search, copilot-web-fetch, copilot-read-pdf, copilot-youtube-transcript, copilot-fetch-x, openartifacts-publish, obsidian-markdown, obsidian-bases, json-canvas, obsidian-cli
2026-09-10T02:04:21.674Z INFO [skills] Skill set changed for opencode; signature=skills:v1:95f503f6
2026-09-10T02:04:21.674Z INFO [skills] Skill set changed for claude; signature=skills:v1:95f503f6
2026-09-10T02:04:21.674Z INFO [skills] Skill set changed for codex; signature=skills:v1:95f503f6
2026-09-10T02:04:21.674Z INFO [skills] Discovered 10 managed skill(s) under "copilot/skills"
2026-09-10T02:04:22.755Z INFO [skills] Discovered 10 managed skill(s) under "copilot/skills"
2026-09-10T02:04:31.805Z WARN [skills] Gave up waiting for vault events on: .claude/skills/copilot-fetch-x, .agents/skills/copilot-fetch-x, .opencode/skills/copilot-fetch-x, .claude/skills/copilot-read-pdf, .agents/skills/copilot-read-pdf, .opencode/skills/copilot-read-pdf, .claude/skills/copilot-web-fetch, .agents/skills/copilot-web-fetch, .opencode/skills/copilot-web-fetch, .claude/skills/copilot-web-search, .agents/skills/copilot-web-search, .opencode/skills/copilot-web-search, .claude/skills/copilot-youtube-transcript, .agents/skills/copilot-youtube-transcript, .opencode/skills/copilot-youtube-transcript, .claude/skills/json-canvas, .agents/skills/json-canvas, .opencode/skills/json-canvas, .claude/skills/obsidian-bases, .agents/skills/obsidian-bases, .opencode/skills/obsidian-bases, .claude/skills/obsidian-cli, .agents/skills/obsidian-cli, .opencode/skills/obsidian-cli, .claude/skills/obsidian-markdown, .agents/skills/obsidian-markdown, .opencode/skills/obsidian-markdown, .claude/skills/openartifacts-publish, .agents/skills/openartifacts-publish, .opencode/skills/openartifacts-publish
2026-09-10T02:04:32.752Z INFO [skills] Discovered 10 managed skill(s) under "copilot/skills"
2026-09-10T02:04:41.943Z INFO [skills] Discovered 10 managed skill(s) under "copilot/skills"
2026-09-10T02:05:06.844Z INFO [skills] Discovered 10 managed skill(s) under "copilot/skills"
2026-09-10T02:06:22.493Z WARN [AgentMode] claude auth status failed spawn EFTYPE
2026-09-10T02:06:32.624Z ERROR [AgentMode] opencode install failed unable to verify the first certificate\nError: unable to verify the first certificate\n    at TLSSocket.onConnectSecure (node:_tls_wrap:1697:34)\n    at TLSSocket.emit (node:events:519:28)\n    at TLSSocket._finishInit (node:_tls_wrap:1095:8)\n    at ssl.onhandshakedone (node:_tls_wrap:881:12)
2026-09-10T02:06:32.626Z ERROR [AgentMode] inline opencode install failed unable to verify the first certificate\nError: unable to verify the first certificate\n    at TLSSocket.onConnectSecure (node:_tls_wrap:1697:34)\n    at TLSSocket.emit (node:events:519:28)\n    at TLSSocket._finishInit (node:_tls_wrap:1095:8)\n    at ssl.onhandshakedone (node:_tls_wrap:881:12)
2026-09-10T02:07:26.221Z ERROR [AgentMode] opencode install failed unable to verify the first certificate\nError: unable to verify the first certificate\n    at TLSSocket.onConnectSecure (node:_tls_wrap:1697:34)\n    at TLSSocket.emit (node:events:519:28)\n    at TLSSocket._finishInit (node:_tls_wrap:1095:8)\n    at ssl.onhandshakedone (node:_tls_wrap:881:12)
2026-09-10T02:07:26.222Z ERROR [AgentMode] opencode install failed unable to verify the first certificate\nError: unable to verify the first certificate\n    at TLSSocket.onConnectSecure (node:_tls_wrap:1697:34)\n    at TLSSocket.emit (node:events:519:28)\n    at TLSSocket._finishInit (node:_tls_wrap:1095:8)\n    at ssl.onhandshakedone (node:_tls_wrap:881:12)
2026-09-10T02:07:49.732Z ERROR [AgentMode] opencode install failed unable to verify the first certificate\nError: unable to verify the first certificate\n    at TLSSocket.onConnectSecure (node:_tls_wrap:1697:34)\n    at TLSSocket.emit (node:events:519:28)\n    at TLSSocket._finishInit (node:_tls_wrap:1095:8)\n    at ssl.onhandshakedone (node:_tls_wrap:881:12)
2026-09-10T02:07:49.733Z ERROR [AgentMode] opencode install failed unable to verify the first certificate\nError: unable to verify the first certificate\n    at TLSSocket.onConnectSecure (node:_tls_wrap:1697:34)\n    at TLSSocket.emit (node:events:519:28)\n    at TLSSocket._finishInit (node:_tls_wrap:1095:8)\n    at ssl.onhandshakedone (node:_tls_wrap:881:12)
2026-09-10T02:08:01.821Z INFO [skills] Discovered 10 managed skill(s) under "copilot/skills"
2026-09-10T02:08:04.599Z INFO [skills] Discovered 10 managed skill(s) under "copilot/skills"
2026-09-10T02:08:17.081Z ERROR [AgentMode] opencode install failed unable to verify the first certificate\nError: unable to verify the first certificate\n    at TLSSocket.onConnectSecure (node:_tls_wrap:1697:34)\n    at TLSSocket.emit (node:events:519:28)\n    at TLSSocket._finishInit (node:_tls_wrap:1095:8)\n    at ssl.onhandshakedone (node:_tls_wrap:881:12)
2026-09-10T02:08:17.083Z ERROR [AgentMode] opencode install failed unable to verify the first certificate\nError: unable to verify the first certificate\n    at TLSSocket.onConnectSecure (node:_tls_wrap:1697:34)\n    at TLSSocket.emit (node:events:519:28)\n    at TLSSocket._finishInit (node:_tls_wrap:1095:8)\n    at ssl.onhandshakedone (node:_tls_wrap:881:12)
2026-09-10T02:26:13.472Z INFO [skills] Discovered 10 managed skill(s) under "copilot/skills"
2026-09-10T02:26:43.827Z ERROR createChainWithNewModel failed: MissingModelKeyError: No chat model enabled. Enable a model under Settings → Basic → Agents → Quick Chat, or add one on the Models (BYOK) tab.
2026-09-10T02:26:43.827Z INFO configuredModelId: google/gemini-2.5-flash|openrouterai

## Settings
```json
{
  "userId": "ffb8fc83-7b1e-487d-9c63-f17c82cbb909",
  "isPaidUser": false,
  "isPlusUser": false,
  "entitlementExpiresAt": 0,
  "defaultChainType": "llm_chain",
  "defaultModelKey": "google/gemini-2.5-flash|openrouterai",
  "contextTurns": 15,
  "userSystemPrompt": "",
  "openAIProxyBaseUrl": "",
  "stream": true,
  "copilotFolder": "copilot",
  "copilotRootHistory": [
    "copilot"
  ],
  "upgradedToV8FromLegacy": false,
  "defaultSaveFolder": "copilot/copilot-conversations",
  "defaultConversationTag": "copilot-conversation",
  "autosaveChat": true,
  "autoAddActiveContentToContext": true,
  "defaultOpenArea": "view",
  "defaultSendShortcut": "enter",
  "customPromptsFolder": "copilot/copilot-custom-prompts",
  "qaExclusions": "copilot",
  "qaInclusions": "",
  "chatNoteContextPath": "",
  "chatNoteContextTags": [],
  "debug": false,
  "maxSourceChunks": 30,
  "enableInlineCitations": true,
  "activeModels": [
    {
      "name": "copilot-plus-flash",
      "provider": "copilot-plus",
      "enabled": true,
      "isBuiltIn": true,
      "core": true,
      "plusExclusive": true,
      "capabilities": [
        "vision"
      ]
    },
    {
      "name": "google/gemini-2.5-flash",
      "provider": "openrouterai",
      "enabled": true,
      "isBuiltIn": true,
      "core": true,
      "capabilities": [
        "vision"
      ]
    },
    {
      "name": "gpt-5.5",
      "provider": "openai",
      "enabled": true,
      "isBuiltIn": true,
      "core": true,
      "capabilities": [
        "vision"
      ]
    },
    {
      "name": "gpt-5.4-mini",
      "provider": "openai",
      "enabled": true,
      "isBuiltIn": true,
      "core": true,
      "capabilities": [
        "vision"
      ]
    },
    {
      "name": "google/gemini-3.5-flash",
      "provider": "openrouterai",
      "enabled": true,
      "isBuiltIn": true,
      "capabilities": [
        "vision",
        "reasoning"
      ]
    },
    {
      "name": "claude-sonnet-4-6",
      "provider": "anthropic",
      "enabled": true,
      "isBuiltIn": true,
      "capabilities": [
        "vision",
        "reasoning"
      ]
    },
    {
      "name": "gemini-3.5-flash",
      "provider": "google",
      "enabled": true,
      "isBuiltIn": true,
      "capabilities": [
        "vision",
        "reasoning"
      ]
    },
    {
      "name": "gemini-3.1-flash-lite",
      "provider": "google",
      "enabled": true,
      "isBuiltIn": true,
      "capabilities": [
        "vision"
      ]
    },
    {
      "name": "gemini-2.5-flash",
      "provider": "google",
      "enabled": true,
      "isBuiltIn": true,
      "capabilities": [
        "vision"
      ]
    },
    {
      "name": "google/gemini-3.1-pro-preview",
      "provider": "openrouterai",
      "enabled": true,
      "isBuiltIn": true,
      "capabilities": [
        "vision",
        "reasoning"
      ]
    },
    {
      "name": "google/gemini-2.5-pro",
      "provider": "openrouterai",
      "enabled": true,
      "isBuiltIn": true,
      "core": false,
      "capabilities": [
        "vision"
      ]
    },
    {
      "name": "openai/gpt-5.5",
      "provider": "openrouterai",
      "enabled": true,
      "isBuiltIn": true,
      "core": false,
      "capabilities": [
        "vision"
      ]
    },
    {
      "name": "openai/gpt-5.4-mini",
      "provider": "openrouterai",
      "enabled": true,
      "isBuiltIn": true,
      "core": false,
      "capabilities": [
        "vision"
      ]
    },
    {
      "name": "grok-4.3",
      "provider": "xai",
      "enabled": true,
      "isBuiltIn": true,
      "core": false,
      "capabilities": [
        "vision"
      ]
    },
    {
      "name": "x-ai/grok-4.3",
      "provider": "openrouterai",
      "enabled": true,
      "isBuiltIn": true,
      "core": false,
      "capabilities": [
        "vision"
      ]
    },
    {
      "name": "gpt-4.1",
      "provider": "openai",
      "enabled": true,
      "isBuiltIn": true,
      "core": false,
      "capabilities": [
        "vision"
      ]
    },
    {
      "name": "gpt-4.1-mini",
      "provider": "openai",
      "enabled": true,
      "isBuiltIn": true,
      "core": false,
      "capabilities": [
        "vision"
      ]
    },
    {
      "name": "claude-opus-4-7",
      "provider": "anthropic",
      "enabled": true,
      "isBuiltIn": true,
      "capabilities": [
        "vision",
        "reasoning"
      ]
    },
    {
      "name": "claude-haiku-4-5",
      "provider": "anthropic",
      "enabled": true,
      "isBuiltIn": true,
      "capabilities": [
        "vision",
        "reasoning"
      ]
    },
    {
      "name": "gemini-3.1-pro-preview",
      "provider": "google",
      "enabled": true,
      "isBuiltIn": true,
      "capabilities": [
        "vision",
        "reasoning"
      ]
    },
    {
      "name": "gemini-2.5-pro",
      "provider": "google",
      "enabled": true,
      "isBuiltIn": true,
      "capabilities": [
        "vision"
      ]
    },
    {
      "name": "deepseek-chat",
      "provider": "deepseek",
      "enabled": true,
      "isBuiltIn": true
    },
    {
      "name": "deepseek-reasoner",
      "provider": "deepseek",
      "enabled": true,
      "isBuiltIn": true,
      "capabilities": [
        "reasoning"
      ]
    },
    {
      "name": "deepseek-ai/DeepSeek-V3",
      "provider": "siliconflow",
      "enabled": true,
      "isBuiltIn": false,
      "baseUrl": "https://api.siliconflow.com/v1"
    },
    {
      "name": "deepseek-ai/DeepSeek-R1",
      "provider": "siliconflow",
      "enabled": true,
      "isBuiltIn": false,
      "baseUrl": "https://api.siliconflow.com/v1",
      "capabilities": [
        "reasoning"
      ]
    }
  ],
  "lexicalSearchRamLimit": 100,
  "promptUsageTimestamps": {},
  "promptSortStrategy": "timestamp",
  "chatHistorySortStrategy": "recent",
  "projectsFolder": "copilot/projects",
  "defaultConversationNoteName": "{$topic}@{$date}_{$time}",
  "inlineEditCommands": [],
  "projectList": [],
  "lastDismissedVersion": null,
  "passMarkdownImages": true,
  "enableAutonomousAgent": true,
  "enableCustomPromptTemplating": true,
  "enableSelfHostMode": false,
  "enableMiyo": false,
  "enableMiyoSearchSkill": false,
  "miyoSearchAll": false,
  "relevantNotesLiveUpdate": true,
  "miyoServerUrl": "",
  "selfHostSearchProvider": "firecrawl",
  "docProcessorBackend": "plus",
  "enableLexicalBoosts": true,
  "suggestedDefaultCommands": false,
  "autonomousAgentMaxIterations": 4,
  "autonomousAgentEnabledToolIds": [
    "localSearch",
    "readNote",
    "webSearch",
    "pomodoro",
    "youtubeTranscription",
    "writeFile",
    "editFile",
    "updateMemory"
  ],
  "reasoningEffort": "low",
  "verbosity": "medium",
  "memoryFolderName": "copilot/memory",
  "enableRecentConversations": true,
  "maxRecentConversations": 30,
  "enableSavedMemory": true,
  "quickCommandIncludeNoteContext": true,
  "autoIncludeTextSelection": false,
  "autoAddSelectionToContext": false,
  "autoAcceptEdits": false,
  "diffViewMode": "split",
  "userSystemPromptsFolder": "copilot/system-prompts",
  "defaultSystemPromptTitle": "",
  "autoCompactThreshold": 128000,
  "convertedDocOutputFolder": "",
  "agentMode": {
    "byok": {},
    "activeBackend": "opencode",
    "backends": {},
    "debugFullFrames": true,
    "notificationSound": true,
    "notificationSoundId": "piano",
    "welcomeDismissed": false,
    "skills": {
      "folder": "copilot/skills"
    }
  },
  "providers": {},
  "configuredModels": [],
  "backends": {},
  "_keychainVaultId": "67580ff9",
  "settingsVersion": 14
}
```
