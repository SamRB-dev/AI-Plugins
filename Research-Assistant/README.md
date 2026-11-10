# Research Assistant export

**Plugin version:** 1.1.0  
**Portable skill file version:** 1.2 (10 November 2026)

This export contains the complete academic research assistant instructions and the original plugin manifests. The portable `SKILL.md` is the main file to reuse across AI assistants.

## Files

- `SKILL.md`: complete reusable instructions, all seven modes, HELP guide, authorship permissions, source verification, locators, issue log and appendices.
- `HELP.md`: quick command guide and example prompts.
- `plugin.json`: portable Agent Plugin manifest.
- `.codex-plugin/plugin.json`: ChatGPT/Codex-style plugin metadata.
- `agents/openai.yaml`: assistant interface defaults.
- `skills/research-assistant/SKILL.md`: skill in its plugin-native location.

## Reuse in other AI assistants

### Claude
Create a Project for each academic project. Add `SKILL.md` to the Project Knowledge or paste it into project instructions if supported. Upload the draft and source PDFs to that Project. Start with the prompt in `HELP.md`.

### Gemini
Use a Gem or a dedicated conversation. Add the content of `SKILL.md` to the Gem's instructions where the instruction limit permits, or attach it as a reference file. Upload the actual research papers separately.

### ChatGPT
Use a dedicated Project or research conversation. Add `SKILL.md` to Project instructions/files, or paste it as the first message. Avoid global custom instructions if you do not want these rules to affect unrelated chats.

### Other assistants
If the platform supports skills, agent instructions, system prompts or knowledge files, import `SKILL.md`. If there is a context limit, use **Appendix C: Compact version** at the end of `SKILL.md` as a fallback. The compact version is less detailed, so use the full file whenever possible.

## Important portability note

The ZIP includes the plugin manifests for compatible plugin/agent runtimes. Other platforms may not accept these manifests directly. Even when the ZIP cannot be installed as a plugin, the standalone Markdown skill remains reusable.

## Working rules

- Upload the actual papers. A bibliography or filename is not source evidence.
- The assistant must not invent citations, quotes, DOIs, statistics or page numbers.
- Level 0 is review-only. Writing requires explicit, scoped permission.
- Verify quoted anchors in the original paper.
- Keep the issue log and master draft under your control.
- Follow your institution's rules on AI use and disclosure.
