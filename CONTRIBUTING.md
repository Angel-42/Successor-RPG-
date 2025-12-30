Contributing Guide

Thank you for your interest in contributing to Successor RPG. The project is open to contributions; please follow these guidelines to make review and integration smoother.

1) Report a bug / Request a feature
- Open an issue describing the problem or the proposal.
- Include: OS and environment, reproduction steps, relevant logs or errors, and screenshots when useful.

2) Contribution workflow
- Fork the repository and create a branch from `main` named `feature/your-feature` or `fix/your-fix`.
- Make small, focused commits with clear messages. Prefer the style: `feat: ...`, `fix: ...`, `docs: ...`.
- Open a Pull Request (PR) against `main` and describe what you changed and why.

3) Coding standards
- Language: C. Keep functions focused and readable.
- Add or update prototypes in `includes/` when needed.

4) Tests and validation
- Ensure the project builds locally with `make`.
- Mention any additional dependencies or platform-specific notes in your PR.

5) Licensing and assets
- Do not add assets (images, music, sounds) under proprietary licenses without permission.
- Assets included under `assets/` and `musics/` are licensed under **CC BY-NC 4.0** (see `LICENSE-ASSETS`) and are for non-commercial use. For commercial use, contact the project authors to arrange a separate agreement.

6) Asset attribution
- When modifying or reusing an asset, include a clear attribution (author name and link) in the folder where it is used or in the PR description.

7) Pull Request checklist
- The project builds successfully (`make`) and changes do not introduce new build errors.
- New assets must include an appropriate license and a short `README` describing usage where relevant.

Thanks — maintainers will review PRs and may request changes before merging.
