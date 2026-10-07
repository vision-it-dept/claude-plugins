# Vision Inc. Claude Code Plugins

English | [日本語](README.ja.md)

Claude Code plugins published by Vision Inc.

## Plugins

| Plugin | Description |
|---|---|
| [security-audit](plugins/security-audit/) | Standard-procedure vulnerability assessment for websites and APIs you own or are authorized to test: a comprehensive assessment (OWASP Top 10, APIs, configuration) and a rapid triage of critical issues. |

## Installation

Add this marketplace to Claude Code:

```sh
claude plugin marketplace add vision-it-dept/claude-plugins
```

Then install a plugin by name, for example `claude plugin install security-audit@vision-net`. Each plugin's README explains its requirements, usage, and how to update it.

## Support

Support is provided on a best-effort basis. We do not guarantee a response to any issue or a fix for any problem.

- Bugs, false positives, and questions: [open an issue](https://github.com/vision-it-dept/claude-plugins/issues/new/choose). You may write in English or Japanese.
- Vulnerabilities in the plugins themselves: report them privately as described in [SECURITY.md](SECURITY.md). Do not open a public issue.

## Contributing

We do not accept external code contributions. Please send suggestions as [issues](https://github.com/vision-it-dept/claude-plugins/issues/new/choose).

## License

[MIT](LICENSE)
