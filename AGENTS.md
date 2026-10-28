# Mandatory HealingMart font policy

All AI coding sessions and deployments must follow the [HealingMart Open Font Policy](https://github.com/healingmart/healingmart-cloudflare-guide-test/blob/policy/pretendard-20261028/FONT_POLICY.md).
Default for Korean/English: self-hosted **Pretendard Variable (SIL OFL 1.1)**. Other languages: individually license-verified, self-hosted **Noto Sans** variants with preserved license files and a font registry.
**Never introduce paid, unlicensed, or explicitly OS-owned fonts** such as Malgun Gothic (맑은 고딕), Arial, Segoe UI, Apple SD Gothic Neo, Consolas, Georgia or Times New Roman. No remote CDN-only fonts.
Before build/deploy, install and run the repository's font check; a policy document alone is not a gate. Never bypass failing checks, add new GitHub Actions for typography, or deploy production without explicit permission.
