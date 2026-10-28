## What this changes
<!-- A short summary, with links to any issues or docs. -->

**Feature or project issue:** `Part of aurium-labs/projects#n`, or "None" for a bug fix, dependency update, refactor, documentation or CI change.
<!-- Use "Part of", never "Closes": the issue is closed by hand once its "Decisions and outcome" section is filled in. -->

## How it was tested
- [ ] CI passes
- [ ] Tried on dev or staging (say what you checked):

---

## Release to production (pull requests into `main` only)
<!-- Delete everything below this line for pull requests into dev or staging. -->

**Does this release add a new feature, or change how customer data is handled?** Yes / No

If **Yes**, answer these before asking for review. If the feature's issue in `aurium-labs/projects` already answers them, say so and link it.
1. **Data:** what customer or personal data does it handle?
2. **Storage and access:** where is that data stored, and who or what can reach it? Does it stay in the customer's own organisation bucket?
3. **Suppliers:** does it send data to a supplier that isn't already in Probo Third Parties? If so, add it there first.
4. **Principles:** which of the security principles (Security Standards, section 2.1) apply, and how are they met? For example: tenant isolation, least privilege, secrets kept in Secrets Manager.
5. **Risks:** does a risk need adding or changing in Probo? Link it, or write "None".

**Every release to production:**
- [ ] Database migrations: none, or listed here, with a snapshot to be taken before running them
- [ ] Risky infrastructure changes have been announced to the team (Acceptable Use Policy, practice 3)

**Reviewer:** approving this pull request confirms you've read the answers above and agree with them. If the release adds a feature and the questions aren't answered, request changes instead.
