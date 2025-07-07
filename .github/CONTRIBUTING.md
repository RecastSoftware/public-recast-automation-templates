# Contributing to Recast Automation Templates

Thank you for your interest in contributing! Whether it’s a full-blown workflow or a minor fix, your efforts make this repo and the Recast community stronger. Please review the following guidelines before submitting a contribution.

---

## 🧭 Get Started

1. **Fork** the repository and **clone** your fork locally.
2. Keep changes focused and scoped to a single purpose.

---

## 📋 Code & Template Standards
* Maintain consistency in:

  * **Indentation** (spaces, tabs)
  * **Naming** (camelCase or PascalCase as used in current templates)
  * **Comments** — include context for any logic that isn’t immediately clear.
  * **Test** each template workflow in the Builder:
* Document any prerequisites (e.g., specific Recast version).

---

## 🔨 Development Workflow
**Checklist to follow**:

1. Create your template in Builder.
2. Test your Builder automation to ensure it works as intended.
3. Remove any environment specific information from the builder template and replace with placeholders:
    * Domain names
    * Collection IDs/Names
    * Device IDs/Names
    * Other environment specific information
4. Export the builder action and add to your fork.

---

## 🔁 Pull Request Process

1. Submit your PR against the `main` branch.
2. Title it descriptively, e.g., `feat: add Deploy Agent template`.
3. Include the following in your description:

   * What template/workflow was added or changed?
   * How to test it (import, run sequence, expected outcome).
4. Our team will:

   * Review structure, clarity, and consistency.
   * Verify import and execution in Builder.
   * Provide feedback or merge it.

---

## 📘 Documentation

* Add or update comments in the template files themselves.
* If adding a new template, include an example usage in this repo’s README or separate documentation.

---

## 🤝 Contributor Support

For assistance:

* Open an issue for questions or to raise issues with published content.
* Tag your issue with `help wanted` to get our attention.
* Discuss and share ideas for automations over on [Recast’s Discourse forum](https://discourse.recastsoftware.com) or in the #Recast-Software channel on WinAdmins Discord (https://discord.com/channels/618712310185197588/1225493794997272687).

---

## ✅ Summary Table

| Step                  | Details                                    |
| --------------------- | ------------------------------------------ |
| **Branch off `main`** | Use descriptive branch names               |
| **Follow templates**  | Match style, naming, and comments          |
| **Import & test**     | Use Builder & Runner as shown in video     |
| **Submit PR**         | Include description, import steps and expected results |
| **Documentation**     | Inline comments + README updates           |

---

Thank you for helping improve Recast’s automation ecosystem! 
