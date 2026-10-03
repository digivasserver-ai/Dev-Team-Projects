# Dev-Team-Projects

Working projects from the Digivas dev team. Each sub-project has its own README with its own notes;
this repo is the index.

| project | what it is |
|---|---|
| `projects/usb_boot_system/` | Bootable USB workflow built on **Ventoy**, with an `ai_llm_boot/` sub-project — an LLM-assisted boot assistant (`src/boot_assistant.py`) |
| `projects/devstation_optimizer/` | Workstation optimisation notes and a session log |

## Why Ventoy + an LLM boot assistant

Ventoy already solves "one USB stick, many ISOs". The interesting part is the boot layer above it:
letting a model reason about boot failures and pick the right boot entry, instead of the operator
reading the log. `projects/usb_boot_system/ai_llm_boot/` is where that lives.

See the individual project READMEs for detail.

MIT licensed.
