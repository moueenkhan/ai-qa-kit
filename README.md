# ai-qa-kit 🧪

Practical tools for testing **non-deterministic AI systems** from a **QA perspective**.

Traditional tests expect:
- same input → same output

AI systems don’t behave like that:
- outputs vary
- correctness is fuzzy
- models drift
- infra and latency make tests flaky

`ai-qa-kit` helps QAs write *stable*, *realistic* tests for AI features.

---

## ✨ Goals

- Make it easy for QAs to:
  - assert AI responses without strict string matching
  - run dataset-based tests against AI APIs
  - get a quick pass/fail + metrics (accuracy, failures)

- Be **framework-friendly**:
  - works with Jest / Vitest / Playwright
  - can be used in any Node/TypeScript project

---

## 📦 Installation (planned)

```bash
npm install ai-qa-kit
# or
yarn add ai-qa-kit
# or
pnpm add ai-qa-kit
