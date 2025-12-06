# Contributing to Free Tools Friday

Thank you for your interest in contributing to Free Tools Friday (#FTF) by Peach Security.

---

## Contribution Types

### Tools

Tools with real code live in their own repositories under the [Peach-Security GitHub organization](https://github.com/Peach-Security).

**To contribute to a tool:** Submit PRs directly to that tool's repository.

### Resources

Resources include templates, checklists, and client-ready materials.

**To contribute a resource:** Submit a PR to this repository under `/releases/resources/`.

### Guides

Guides include practical documentation, playbooks, and how-to content.

**To contribute a guide:** Submit a PR to this repository under `/releases/guides/`.

### Ideas

Have an idea for a future release?

**To suggest an idea:** Submit and vote on ideas at the FTF ideas board: https://www.peachsecurity.io/ftf

---

## File Naming Conventions

### Resources

```
/releases/resources/{type}/{name}.md
```

**Types:** `templates`, `checklists`, `assessments`

**Examples:**
- `/releases/resources/templates/ai-aup.md`
- `/releases/resources/checklists/ai-security-discovery.md`

### Guides

```
/releases/guides/{category}/{name}.md
```

**Categories:** `ai-security`, `endpoint-security`, `compliance`, `operations`

**Examples:**
- `/releases/guides/ai-security/hardening-guide.md`
- `/releases/guides/compliance/audit-prep.md`

---

## Linking External Repos

When a tool lives in its own repository:

1. Add an entry to the README.md tools table
2. Add an entry to `/tools/tools.manifest.yml`
3. Include the full GitHub URL

**Example manifest entry:**

```yaml
- name: ToolName
  description: Short description of what it does.
  repo: https://github.com/Peach-Security/ToolName
  release_date: YYYY-MM-DD
  category: category-name
  tags:
    - tag1
    - tag2
  status: released
```

---

## Tone Requirements

All FTF content must be:

- **Useful** — Solves a real problem MSPs face
- **Practical** — Ready to use, not theoretical
- **Clear** — No jargon, no fluff
- **Neutral** — No marketing language or sales pitches

### Do

- Write for busy MSPs who need solutions
- Be direct and concise
- Include actionable steps
- Test everything before submitting

### Don't

- Add marketing fluff or promotional language
- Use vague or aspirational statements
- Overcomplicate simple concepts
- Submit untested content

---

## PR Requirements

### Before Submitting

1. **Test your contribution** — Verify it works as documented
2. **Follow naming conventions** — Use the file structure defined above
3. **Write clear descriptions** — Explain what problem it solves
4. **Check for duplicates** — Search existing releases first

### PR Checklist

- [ ] Follows file naming conventions
- [ ] Includes clear description of problem solved
- [ ] Content is tested and verified
- [ ] No marketing language or fluff
- [ ] Links are valid and working
- [ ] Spelling and grammar checked

### PR Description Template

```markdown
## What this adds

[Brief description of the contribution]

## Problem it solves

[What MSP problem does this address?]

## Type

- [ ] Tool
- [ ] Resource
- [ ] Guide

## Testing done

[How did you verify this works?]
```

---

## Code of Conduct

- Be respectful and constructive
- Focus on helping MSPs solve real problems
- Keep discussions on-topic
- No spam or self-promotion

---

## Questions?

- Open an Issue for questions about contributing
- [Join the FTF Slack Community](https://join.slack.com/t/peachsecurity-qhl2413/shared_invite/zt-3ka9yzhf9-LvvIYQqC5SXWbCNRJfJGRw) for discussions

🔗 **FTF Home:** https://www.peachsecurity.io/ftf

