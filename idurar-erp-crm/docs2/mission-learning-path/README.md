# Mission Learning Path

This suite is a training campaign. Do not read it passively. Each mission asks you to open real files, trace real code, answer questions, and self-grade immediately.

Recommended pacing:

Do 1-2 junior missions per session until you can explain the app boot and invoice list without notes. Do 1 mid-level mission per session because those require tracing across frontend/backend boundaries. Do senior missions slowly and write your answers as if you were reviewing a pull request.

How to self-grade:

Answer the Socratic questions first. Then compare your answer to the rubric. A strong answer names concrete files and line ranges, explains cause/effect, and uses the app domain: clients, invoices, payments, settings, and admins.

How this differs from normal documentation:

Normal docs tell you what the code is. These missions train you to find the answer yourself, read chronologically, spot risks, and explain the system under pressure.

There are 25 missions: 1-8 in `01-tier-1-junior-missions.md`, 9-17 in `02-tier-2-mid-level-missions.md`, 18-24 in `03-tier-3-senior-missions.md`, and Mission 25 (write the docs that don't exist) in `04-reference-artifacts.md`.

Code blocks are condensed and annotated, not verbatim. The `// path:lines` header names the real range, but the code is reformatted, end-of-line comments were added for teaching, and some lines inside the range are left out (for example, Mission 3's `schemaValidate.js:2-24` block omits the `year`, `status`, `notes`, `expiredDate` and `date` fields). Open the cited range before quoting it in a review or interview. (Note added 2026-10-06.)

