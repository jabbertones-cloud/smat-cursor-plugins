# Cursor submission evidence and restrictions (2026-11-17)

Source: https://cursor.com/marketplace-publisher-terms ; https://cursor.com/docs/reference/plugins

- Cursor Publisher Terms section 3.1 prohibits charging users directly or indirectly to access or use a marketplace plugin.
- Original SMAT Designs application was acknowledged in M2 Safari ('Thanks for applying'). This is not marketplace acceptance.
- This repository adds five independent skill-only plugins with zero hosted MCP dependency and no billing. They require no seller, Apple, legal or POS authorization to analyze local user-supplied files.
- AppDev Atlas remains a free read-only hosted 45-tool MCP; live initialize and tools/list were verified.
- EzSeller, AiSCent, CashCrop and Unloopr MCP endpoints respond with OAuth-required. USIPE initializes and lists 13 tools publicly. This is separate from Cursor listing authorization.
- EzSeller has a $0 metered tier but paid additional features and Amazon beta grant limits; AiSCent advertises a free first ship with paid continuation.
- Unloopr metadata currently advertises a workers.dev issuer rather than its custom MCP host. Do not claim live Cursor OAuth acceptance.
- Existing commercial service policy, backend entitlement and production code remain unchanged.
- Re-index and Cursor local installed-client smoke are separate required acceptance gates. No automatic Cursor listing is implied.
