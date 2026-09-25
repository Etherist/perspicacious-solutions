# Perspicacious Solutions — GitHub Pages landing site


<!-- engineering-maturity:start -->
## Engineering status

**Estimated implementation completeness: 23% — engineering foundation.**  
**Assessment confidence: medium.**

This repository establishes the engineering foundation and initial working components for the project. The current code demonstrates the intended architecture, while most functional completion remains ahead.

**What is already significant:** a real multi-module implementation rather than a presentation-only repository.

**Remaining engineering work:** add automated verification around the principal execution paths; complete CI automation; strengthen technical and operational documentation; make licensing explicit.

**Production readiness:** Production readiness is not claimed. The repository's value is the implemented architecture, working components and demonstrated engineering approach, with further verification and hardening still required.

| Evidence area | Remote repository evidence |
| --- | --- |
| Implementation | 7 source files; approximately 42 KiB of source code |
| Verification | 0 test files; approximately 0 KiB of test code |
| Automation | 0 GitHub Actions workflow(s) |
| Build/configuration | 0 build/dependency manifest(s); 0 configuration file(s) |
| Deployment | 0 deployment/runtime packaging asset(s) |
| Documentation/examples | 1 documentation file(s); 0 example/demo file(s) |
| Remote code inspection | 7 evidence-rich files read; 0 TODO/FIXME marker(s); 0 explicit unfinished marker(s) |


<sub>Engineering estimate refreshed 2026-09-25 from GitHub repository metadata and remotely read source/test/configuration files. It is an evidence-based maturity estimate, not a claim that every runtime path has been independently executed or externally certified.</sub>
<!-- engineering-maturity:end -->

Static pre-release landing site for Perspicacious Solutions Pty Ltd and RealtyPrompt Pro.

## Recommended repository

Create a **public** repository under the `etherist` account named:

```text
perspicacious-solutions
```

Expected GitHub Pages URL:

```text
https://etherist.github.io/perspicacious-solutions/
```

## Publish with Git

Create the empty public GitHub repository first, then run from this site's directory:

```bash
git init
git branch -M main
git add .
git commit -m "Publish Perspicacious Solutions landing site"
git remote add origin https://github.com/etherist/perspicacious-solutions.git
git push -u origin main
```

Then on GitHub:

1. Open the repository.
2. Open **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select **main** and **/(root)**.
5. Save.
6. When published, visit `https://etherist.github.io/perspicacious-solutions/`.

## Pre-publication review

Review all text, particularly Privacy, Website Terms and Refund Policy.

The package intentionally:
- has no checkout;
- has no analytics;
- has no web contact form;
- contains no secrets;
- describes RealtyPrompt Pro as pre-release.

When Lemon Squeezy onboarding asks for a genuine business website URL, use the published GitHub Pages URL if the site accurately represents the business at that time.
