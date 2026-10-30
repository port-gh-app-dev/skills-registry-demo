<!-- PAGE_ID: skills-registry-demo_02_skills-catalog -->
<details>
<summary>📚 Relevant source files</summary>

The following files were used as context for generating this wiki page:

- [README.md:17-167](https://github.com/port-gh-app-dev/skills-registry-demo/blob/4140e5ec64a5bdbd04a267fd6b8aeb022f52fb33/README.md#L17-L167)
- [SKILL.md:1-30](https://github.com/port-gh-app-dev/skills-registry-demo/blob/4140e5ec64a5bdbd04a267fd6b8aeb022f52fb33/skills/infrastructure/adding-docker/SKILL.md#L1-L30)
- [helpers.py:1-31](https://github.com/port-gh-app-dev/skills-registry-demo/blob/4140e5ec64a5bdbd04a267fd6b8aeb022f52fb33/skills/port-specific/run-self-service/helpers.py#L1-L31)

</details>

# Skills Catalog

> **Related Pages**: [[Plugins and Marketplace|03_plugins.md]]

---

<!-- BEGIN:AUTOGEN skills-registry-demo_02_skills-catalog_categories -->
## Categories

Skills live under `skills/<category>/`. The README lists these categories, with counts as stated there (the README's counts are not verified against the file tree here).

| Category | Folder | README count |
|----------|--------|--------------|
| Port-Specific | `port-specific` | 6 listed ([README.md:19-30](https://github.com/port-gh-app-dev/skills-registry-demo/blob/4140e5ec64a5bdbd04a267fd6b8aeb022f52fb33/README.md#L19-L30)) |
| Cursor-Native | `cursor-native` | 27 ([README.md:32](https://github.com/port-gh-app-dev/skills-registry-demo/blob/4140e5ec64a5bdbd04a267fd6b8aeb022f52fb33/README.md#L32)) |
| Analytics & Tracking | `analytics-tracking` | 3 ([README.md:46](https://github.com/port-gh-app-dev/skills-registry-demo/blob/4140e5ec64a5bdbd04a267fd6b8aeb022f52fb33/README.md#L46)) |
| Testing | `testing` | 6 ([README.md:54](https://github.com/port-gh-app-dev/skills-registry-demo/blob/4140e5ec64a5bdbd04a267fd6b8aeb022f52fb33/README.md#L54)) |
| Infrastructure | `infrastructure` | 4 ([README.md:65](https://github.com/port-gh-app-dev/skills-registry-demo/blob/4140e5ec64a5bdbd04a267fd6b8aeb022f52fb33/README.md#L65)) |
| Code Quality | `code-quality` | 6 ([README.md:74](https://github.com/port-gh-app-dev/skills-registry-demo/blob/4140e5ec64a5bdbd04a267fd6b8aeb022f52fb33/README.md#L74)) |
| Frontend & UI | `frontend-ui` | 5 ([README.md:85](https://github.com/port-gh-app-dev/skills-registry-demo/blob/4140e5ec64a5bdbd04a267fd6b8aeb022f52fb33/README.md#L85)) |
| Workflow | `workflow` | 5 ([README.md:95](https://github.com/port-gh-app-dev/skills-registry-demo/blob/4140e5ec64a5bdbd04a267fd6b8aeb022f52fb33/README.md#L95)) |
| Planning & Architecture | `planning-architecture` | 2 ([README.md:105](https://github.com/port-gh-app-dev/skills-registry-demo/blob/4140e5ec64a5bdbd04a267fd6b8aeb022f52fb33/README.md#L105)) |
| Documentation | `documentation` | 2 ([README.md:112](https://github.com/port-gh-app-dev/skills-registry-demo/blob/4140e5ec64a5bdbd04a267fd6b8aeb022f52fb33/README.md#L112)) |
| Utilities | `utilities` | 5 ([README.md:119](https://github.com/port-gh-app-dev/skills-registry-demo/blob/4140e5ec64a5bdbd04a267fd6b8aeb022f52fb33/README.md#L119)) |

Port-specific skills integrate with Port's service catalog and MCP, e.g. `triage-incident`, `investigate-incident`, `service-health-check` and `run-self-service` ([README.md:21-30](https://github.com/port-gh-app-dev/skills-registry-demo/blob/4140e5ec64a5bdbd04a267fd6b8aeb022f52fb33/README.md#L21-L30)). The skills tree also contains a `cursor-native` directory with many more skills than the README table lists individually ([README.md:44](https://github.com/port-gh-app-dev/skills-registry-demo/blob/4140e5ec64a5bdbd04a267fd6b8aeb022f52fb33/README.md#L44)).

Sources: [README.md:17-127](https://github.com/port-gh-app-dev/skills-registry-demo/blob/4140e5ec64a5bdbd04a267fd6b8aeb022f52fb33/README.md#L17-L127)
<!-- END:AUTOGEN skills-registry-demo_02_skills-catalog_categories -->

---

<!-- BEGIN:AUTOGEN skills-registry-demo_02_skills-catalog_format -->
## SKILL.md Format

Each skill is a folder containing a `SKILL.md` ([README.md:131](https://github.com/port-gh-app-dev/skills-registry-demo/blob/4140e5ec64a5bdbd04a267fd6b8aeb022f52fb33/README.md#L131)). The documented format is YAML frontmatter (`name`, `description`, `user-invocable`) followed by "When to Use", "Process" and "Quality Checklist" sections ([README.md:148-167](https://github.com/port-gh-app-dev/skills-registry-demo/blob/4140e5ec64a5bdbd04a267fd6b8aeb022f52fb33/README.md#L148-L167)).

A real example, `adding-docker`, uses `name`, `description` and `version` frontmatter instead of `user-invocable` ([SKILL.md:1-5](https://github.com/port-gh-app-dev/skills-registry-demo/blob/4140e5ec64a5bdbd04a267fd6b8aeb022f52fb33/skills/infrastructure/adding-docker/SKILL.md#L1-L5)). It then gives a "Use this skill when…" trigger and numbered steps ([SKILL.md:9-15](https://github.com/port-gh-app-dev/skills-registry-demo/blob/4140e5ec64a5bdbd04a267fd6b8aeb022f52fb33/skills/infrastructure/adding-docker/SKILL.md#L9-L15)). So frontmatter varies between skills.

Sources: [README.md:129-167](https://github.com/port-gh-app-dev/skills-registry-demo/blob/4140e5ec64a5bdbd04a267fd6b8aeb022f52fb33/README.md#L129-L167), [SKILL.md:1-15](https://github.com/port-gh-app-dev/skills-registry-demo/blob/4140e5ec64a5bdbd04a267fd6b8aeb022f52fb33/skills/infrastructure/adding-docker/SKILL.md#L1-L15)
<!-- END:AUTOGEN skills-registry-demo_02_skills-catalog_format -->

---

<!-- BEGIN:AUTOGEN skills-registry-demo_02_skills-catalog_helpers -->
## Helper Scripts

A few skills ship supporting files next to SKILL.md, such as `setup.sh` (adding-docker), `run-tests.sh` (writing-tests), `scripts/generate_image.py` (generating-images) and `helpers.py` (run-self-service). I did not read the shell scripts or `generate_image.py`.

`run-self-service/helpers.py` wraps the Port REST API (`https://api.port.io/v1`) using only the standard library ([helpers.py:1-7](https://github.com/port-gh-app-dev/skills-registry-demo/blob/4140e5ec64a5bdbd04a267fd6b8aeb022f52fb33/skills/port-specific/run-self-service/helpers.py#L1-L7)):

| Function | Behavior |
|----------|----------|
| `get_headers()` | Builds a Bearer header from the `PORT_CLIENT_TOKEN` env var ([helpers.py:10-12](https://github.com/port-gh-app-dev/skills-registry-demo/blob/4140e5ec64a5bdbd04a267fd6b8aeb022f52fb33/skills/port-specific/run-self-service/helpers.py#L10-L12)) |
| `get_entity(blueprint, identifier)` | GETs a blueprint entity ([helpers.py:15-19](https://github.com/port-gh-app-dev/skills-registry-demo/blob/4140e5ec64a5bdbd04a267fd6b8aeb022f52fb33/skills/port-specific/run-self-service/helpers.py#L15-L19)) |
| `upsert_entity(...)` | POSTs with `?upsert=true` ([helpers.py:22-31](https://github.com/port-gh-app-dev/skills-registry-demo/blob/4140e5ec64a5bdbd04a267fd6b8aeb022f52fb33/skills/port-specific/run-self-service/helpers.py#L22-L31)) |

Sources: [helpers.py:1-31](https://github.com/port-gh-app-dev/skills-registry-demo/blob/4140e5ec64a5bdbd04a267fd6b8aeb022f52fb33/skills/port-specific/run-self-service/helpers.py#L1-L31)
<!-- END:AUTOGEN skills-registry-demo_02_skills-catalog_helpers -->

---
