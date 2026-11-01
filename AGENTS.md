# Backend Topics contributor rules

This is a public backend knowledge and reusable-module repository. Use synthetic examples. Never commit private project paths, internal domains, real account lists, credentials, production records, database dumps or customer logs. Do not import another checkout at runtime.

This repository is initially a knowledge scaffold. Do not invent backend modules, deploy services, connect production databases or change consumer projects merely to fill directories. Future modules need an explicit responsibility boundary, error/resource ownership, a version and meaningful isolated tests for their claimed behavior. Keep credentials and business policy in consumer adapters.

Knowledge distinguishes verified contracts, contextual recommendations and unresolved questions. Record reproduction, cause, evidence, failure/recovery boundaries and conditions; prefer extending an existing topic over duplicating rules. Do not promote a single implementation choice into a universal mandate.

Use native validation appropriate to changed code plus npm run check for documentation. A document/link check does not prove API, concurrency, storage, backup or operational behavior. Verify each claim at the layer it concerns. Public functions need concise API documentation; tests must not use production services or data.

Before commit/push scan secrets and public content, stage intentional changes only and confirm actual remote visibility. End tasks with an evidence-backed retrospective; genuine open items require cause, owner role and falsifiable closure criteria. Main agent owns publication. This AGENTS.md is the sole local instruction source; do not create a competing CLAUDE.md.
