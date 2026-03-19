# Firewalla Public Lists

A community-maintained collection of optional blocklists and other curated datasets for [Firewalla](https://firewalla.com/) devices. This repo exists to provide:

- **Optional** lists for users who want extra filtering or categorization
- **Transparency** around what's included
- **Community contributions** to keep lists accurate and up-to-date
- **A central place** for Firewalla users to share curated, useful datasets

> [!WARNING]
> These lists are community-curated and may not be 100% complete or accurate.
> Use at your own discretion. Firewalla does not guarantee the behavior of third-party domains, nor does it mandate the use of these lists.

These lists are **not required** for Firewalla operation. They are strictly optional tools for users who want them.

## Current Lists

These are NOT the same as the built-in [Target Lists](https://help.firewalla.com/hc/en-us/articles/1500005941962-Firewalla-Feature-Target-Lists#h_01FZ87M2M19TBZG2FS585GZFAC) listed in the Firewalla App. Lists may eventually be synced back to the Firewalla App after proper testing over time.

- [NSFW AI List](https://github.com/firewalla/fw-public-lists/blob/main/nsfw-ai.txt)
- [AI Providers List](https://github.com/firewalla/fw-public-lists/blob/main/ai-provider.txt)
- [uBlockOrigin's Huge AI Blocklist](https://github.com/firewalla/fw-public-lists/blob/main/ublockorigins-huge-ai-blocklist.txt)

## Contributing Guidelines

We welcome all community contributions! To suggest changes, please open a **Pull Request** or create a new **Issue**. Use **one domain per line** and include a brief explanation for each addition, removal, or modification.

We will do our best to review and verify all changes before they are merged into the main branch, but approval is not guaranteed.

### Required Metadata

Each list must include the following metadata at the top of the file:

- **Title**: Name of the list.
- **Description**: Short summary of what the list blocks or allows.
- **Homepage**: Link to the project or repository where the list is maintained.
- **License**: Link to the license for the list.

Example:

```text
# Title: Example Blocklist
# Description: Blocks known malicious domains.
# Homepage: https://github.com/example/blocklist
# License: https://github.com/example/blocklist/blob/main/LICENSE

example.com
...
```

### Additional Metadata for External Lists

We also support pointers to external lists maintained by another party. In this case, the metadata should also include:

- **Original Author**: Company, organization, or GitHub username of the maintainer.

Then, simply add a link to the raw host text file, **preceeded by** `@`.

Example:

```text
# Title: Example Blocklist
# Description: Blocks known malicious domains.
# Homepage: https://github.com/example/blocklist
# License: https://github.com/example/blocklist/blob/main/LICENSE
# Original Author: example-user

@https://example.com/hosts.txt
```

### Contributor Responsibility

By submitting a Pull Request or Issue to this repository, you confirm that you have the right to contribute the content and that it does not violate any third-party copyrights, licenses, or terms of use.

If you include domains or lists sourced from another project, you must ensure the original license permits redistribution and provide proper attribution where required.

Firewalla is not responsible for improperly attributed or unauthorized submissions. We reserve the right to remove or modify any content that may violate licensing or attribution requirements.

> [!NOTE]
> We are not responsible for the content of any submitted list and do not verify whether a list is valid, accurate, compliant, or legally usable. All responsibility for the submitted content rests solely with the submitter. We reserve the right to remove any list at our discretion, including in cases of discrepancies, violations, licensing conflicts, usage restrictions, or quality issues.

## License

For more details, see the [LICENSE](https://github.com/firewalla/fw-public-lists/blob/main/LICENSE).

## Want to Learn More?

Here are more ways to follow us:

- Firewalla homepage: [https://firewalla.com](https://firewalla.com)
- Firewalla community: [https://help.firewalla.com/](https://help.firewalla.com)
- Firewalla Reddit: [https://reddit.com/r/firewalla](https://reddit.com/r/firewalla)
- Firewalla Facebook: [https://facebook.com/firewalla](https://facebook.com/firewalla)
