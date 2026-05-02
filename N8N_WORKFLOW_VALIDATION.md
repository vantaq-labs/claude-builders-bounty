# Local validation

- JSON parses successfully.
- Contains an importable n8n workflow object with `nodes` and `connections`.
- Includes weekly schedule trigger.
- Includes GitHub API requests for commits, issues, and PRs.
- Includes Anthropic Messages API request with `claude-sonnet-4-20250514`.
- Includes email delivery via n8n email node.
- Configurable values are read from env vars: `GITHUB_REPO`, `DESTINATION_EMAIL`, `SUMMARY_LANGUAGE`.

Limit: no live credentialed n8n screenshot was included because this environment does not have a configured n8n instance with GitHub/Anthropic/SMTP secrets.
