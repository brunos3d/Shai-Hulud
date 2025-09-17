## 🚨 Not sure if you were affected by the recent npm supply-chain attack? Use Crysknife ⚔️

If you haven't heard about the worm-like malware **Shai-Hulud** or think your account/project might be safe — please check it now.

**What Crysknife does**
- Scans lockfiles, repos and published metadata for known indicators of compromise (IOCs).  
- Decodes suspicious/multi-layer encodings and highlights likely leaked tokens.  
- Flags unauthorized `.github/workflows/*` that could persist exfiltration.  
- Runs client-side in your browser — your secrets never leave your machine.

**Try it now:** https://crysknife.vercel.app/  
**Source & contribute:** https://github.com/brunos3d/crysknife/

**Quick actions if you find something**
1. Delete any repo named `Shai-Hulud` (or similar) immediately if it contains tokens, env vars or other sensitive data.  
2. Rotate all exposed credentials (NPM_TOKEN, GITHUB_TOKEN, cloud keys).  
3. Remove unauthorized GitHub Actions workflows and audit publish activity.  
4. Open an issue or PR on the repo if you need help or want to contribute.

**Privacy note:** Crysknife is privacy-first and runs client-side. We only store hashes/IOCs — never plaintext secrets.  
If you're unsure about results, ask for help on the GitHub repo. Stay safe and spread the word. ⚔️
