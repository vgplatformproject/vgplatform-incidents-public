VGPlatform Public Incident Knowledge Base

# Example Incident

Problem:

permission denied write file

VGPlatform analysis:

Root cause:
missing write permission on export directory

Fix:
grant write permission

Result:
incident resolved in 2 minutes

## How VGPlatform turns incidents into knowledge

```mermaid
flowchart TD
  A[Failure / anomaly] --> B[Capture: logs + context]
  B --> C[Sanitize + package]
  C --> D[Analyze: similarity + root cause hints]
  D --> E[Knowledge base (this repo)]
  E --> F[Prevent recurrence: gates + checks]
```
