---
name: test-bad-skill
version: 1
description: A skill that accidentally includes internal fields.
owner_team: some-internal-team
owner_cti: AWS/SomeService/InternalPath
stages: [preprod]
---

# Test Bad Skill

This skill has internal frontmatter fields that should be caught.
