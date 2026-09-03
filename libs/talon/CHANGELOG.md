# Changelog

## [0.0.7](https://github.com/AmirulAndalib/deepagents/compare/deepagents-talon==0.0.6...deepagents-talon==0.0.7) (2026-09-03)


### Features

* **code,talon:** require Python 3.12 or greater ([#5603](https://github.com/AmirulAndalib/deepagents/issues/5603)) ([04de43e](https://github.com/AmirulAndalib/deepagents/commit/04de43e05adcbd38f1022f1fafe93f6748c2a032))
* **talon:** add channel debug logging ([#5983](https://github.com/AmirulAndalib/deepagents/issues/5983)) ([1c14626](https://github.com/AmirulAndalib/deepagents/commit/1c14626d068ee5e1724d53dc17927d37987ebe36))
* **talon:** add Discord channel adapter ([#5992](https://github.com/AmirulAndalib/deepagents/issues/5992)) ([67c6c17](https://github.com/AmirulAndalib/deepagents/commit/67c6c17a316c84a6f21eafb95f12e56eedf11e7e))
* **talon:** add opt-in agent activity logging ([#5984](https://github.com/AmirulAndalib/deepagents/issues/5984)) ([3a0f68c](https://github.com/AmirulAndalib/deepagents/commit/3a0f68ccd08166394e02fd736869482be5759f83))
* **talon:** interrupt active turns for new messages ([#6023](https://github.com/AmirulAndalib/deepagents/issues/6023)) ([f93752f](https://github.com/AmirulAndalib/deepagents/commit/f93752f855836b2af358a7c71c35a9f774af58e3))
* **talon:** keep typing indicator alive during long agent turns ([#5993](https://github.com/AmirulAndalib/deepagents/issues/5993)) ([e0d0afa](https://github.com/AmirulAndalib/deepagents/commit/e0d0afa18a3b8209f20c24cfda2ad766e476a102))


### Bug Fixes

* **talon:** drop extract-zip from the WhatsApp bridge dependency tree ([#5924](https://github.com/AmirulAndalib/deepagents/issues/5924)) ([7301d01](https://github.com/AmirulAndalib/deepagents/commit/7301d01e483d0b76745c725134ec09db82f38856))
* **talon:** improve channel reconnect resilience ([#6040](https://github.com/AmirulAndalib/deepagents/issues/6040)) ([54fe91f](https://github.com/AmirulAndalib/deepagents/commit/54fe91fd3745e285899961bfe74380c837674164))
* **talon:** migrate MCP discovery to `discover_mcp_config_sources` ([#5803](https://github.com/AmirulAndalib/deepagents/issues/5803)) ([5cdd977](https://github.com/AmirulAndalib/deepagents/commit/5cdd97730708b0480cb7d32792717dcdcd02f4ea))
* **talon:** preserve WhatsApp quoted message context ([#6025](https://github.com/AmirulAndalib/deepagents/issues/6025)) ([03436b3](https://github.com/AmirulAndalib/deepagents/commit/03436b369c0324498602fe6b7918cf36f3629d76))
* **talon:** restore WhatsApp bridge compatibility ([#5999](https://github.com/AmirulAndalib/deepagents/issues/5999)) ([568b398](https://github.com/AmirulAndalib/deepagents/commit/568b398df9b9f4f3464b4107c0ef9001f530d728))
* **talon:** restrict WhatsApp replies to self-chat ([#6010](https://github.com/AmirulAndalib/deepagents/issues/6010)) ([40359ec](https://github.com/AmirulAndalib/deepagents/commit/40359ec683eaff3a67b39d3f6b3003e70db9ec4d))

## [0.0.6](https://github.com/langchain-ai/deepagents/compare/deepagents-talon==0.0.5...deepagents-talon==0.0.6) (2026-08-28)

### Bug Fixes

- Removed `extract-zip` from the WhatsApp bridge dependency tree. ([#5924](https://github.com/langchain-ai/deepagents/issues/5924))

## [0.0.5](https://github.com/langchain-ai/deepagents/compare/deepagents-talon==0.0.4...deepagents-talon==0.0.5) (2026-08-26)

### Bug Fixes

- Migrated MCP discovery to `discover_mcp_config_sources`. ([#5803](https://github.com/langchain-ai/deepagents/issues/5803))

## [0.0.4](https://github.com/langchain-ai/deepagents/compare/deepagents-talon==0.0.3...deepagents-talon==0.0.4) (2026-08-24)

### Features

- Require Python 3.12 or greater. ([#5603](https://github.com/langchain-ai/deepagents/issues/5603))

## [0.0.3](https://github.com/langchain-ai/deepagents/compare/deepagents-talon==0.0.2...deepagents-talon==0.0.3) (2026-07-06)


### Features

* **sdk:** optional video frame extraction on `read_file` ([#4094](https://github.com/langchain-ai/deepagents/issues/4094)) ([b927147](https://github.com/langchain-ai/deepagents/commit/b927147d026749c6c790bb06c9853515dabf579c))
* **talon:** add Fleet zip import command ([#4493](https://github.com/langchain-ai/deepagents/issues/4493)) ([0289dd0](https://github.com/langchain-ai/deepagents/commit/0289dd0a190e5060e631e840da115dd59c64cf5c))


### Bug Fixes

* **talon:** materialize agents under home ([f2b26a8](https://github.com/langchain-ai/deepagents/commit/f2b26a8915fb70c26d32af6e8240442e5e6118e6))

## [0.0.2](https://github.com/langchain-ai/deepagents/compare/deepagents-talon==0.0.1...deepagents-talon==0.0.2) (2026-06-30)


### Features

* **talon:** `DEEPAGENTS_TALON_RECURSION_LIMIT` env var ([#4354](https://github.com/langchain-ai/deepagents/issues/4354)) ([82d1eac](https://github.com/langchain-ai/deepagents/commit/82d1eac59a43f096096e86849733aa716adb18fc))
* **talon:** add reaction approval routing ([#4345](https://github.com/langchain-ai/deepagents/issues/4345)) ([3fe8c0c](https://github.com/langchain-ai/deepagents/commit/3fe8c0c35536626f583df08573469506b9529706))
* **talon:** add Telegram channel adapter, CLI wiring, and offset persistence ([#4097](https://github.com/langchain-ai/deepagents/issues/4097)) ([7c87cec](https://github.com/langchain-ai/deepagents/commit/7c87ceca069874db8555705efab3973301baa1cb))
* **talon:** add tool approval env override ([#4349](https://github.com/langchain-ai/deepagents/issues/4349)) ([d26481d](https://github.com/langchain-ai/deepagents/commit/d26481da615881bae4401dfa485ad925945e667a))
* **talon:** audit reaction approval attempts ([#4348](https://github.com/langchain-ai/deepagents/issues/4348)) ([d7895c4](https://github.com/langchain-ai/deepagents/commit/d7895c4f9b996ad6fe194936bbeaa8beea21e913))
* **talon:** ingest Telegram approval reactions ([#4346](https://github.com/langchain-ai/deepagents/issues/4346)) ([437af0b](https://github.com/langchain-ai/deepagents/commit/437af0bf79332b20ae0c1883c3cc4d91a98c2457))


### Bug Fixes

* **talon:** default workspace to current directory ([#4099](https://github.com/langchain-ai/deepagents/issues/4099)) ([5e337ae](https://github.com/langchain-ai/deepagents/commit/5e337ae50a76bc174b752be187e62698a389cbe6))

## Changelog

All notable changes to this project will be documented in this file.
