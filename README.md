# Astroguru 1.2.0 desktop application

[Download the complete Astroguru 1.2.0 ZIP](https://github.com/menababu-debug/AstroGuru/raw/refs/heads/main/Astroguru-1.2.0.zip)

## Automatic detailed AI reports

- OpenAI and Google Gemini official API adapters with configurable text/image models.
- Detailed or Very detailed generation covering all appropriate life domains and every permitted historical/future year.
- Submit once after reviewing input and recording client consent: generation, checkpoints, report assembly, version saving and automatic PDF export run together.
- Optional voluntary interests/confirmed notes and separately consented aligned palm-photo observations.
- Optional decorative AI cover artwork. Kundali charts and all planetary placements/compatibility scores remain locally calculated.
- Cancellation, saved-section resumption and preserved originals. Optional artwork failure retains the report text and calculated charts.

## Set up API access

1. In Settings select OpenAI or Gemini, an accessible model and your API key. Keys are stored in the OS credential manager.
2. For Gemini, choose Google account · get Gemini API key, sign into Google AI Studio and create a key: https://aistudio.google.com/apikey. Gemini does have an official API.
3. OpenAI keys: https://platform.openai.com/api-keys. Consumer ChatGPT/Gemini subscriptions and website sessions are separate from API authorization/billing.
4. Enable automatic AI generation, select report depth, choose the automatic PDF folder and save Settings.
5. At reading submission, select any optional context/palm/artwork, review the exact inputs and record each person's consent. Full processing then runs automatically.

A Gemini website fallback prepares a reviewed prompt, records consent and opens the website in your own browser. This alternative requires manual copy/paste; it is not an automated Google-login integration. Astroguru does not collect Google passwords or browser session cookies.

Live AI text/image generation requires your credentials, billing/model access and network access. Requests can incur charges. No live billable calls were made during this build; SDK transports were tested with synthetic responses.

## Windows update / launch

1. Close Astroguru and make an encrypted backup in Settings.
2. Extract this ZIP into a new folder.
3. Open the Astroguru folder and run Start-Astroguru.cmd. CPython 3.12 x64 is required; first launch installs dependencies.
4. Use your existing vault password. The default data location and vault format remain compatible. Keep the same ASTROGURU_DATA_DIR if you use a custom location.

The ZIP includes complete desktop application source, Windows setup/build scripts, documentation, calculation rules, dependency/license notices and fictional sample PDF/charts.

To build Astroguru.exe and Astroguru-Setup.exe, install Inno Setup 6 and run build-windows.ps1 on Windows. Windows binaries were not built or tested in the Linux development environment.

## Verification and limitations

62 automated tests passed. Source and frozen Linux offline smoke tests passed. Verification includes detailed job/horizon planning, consent gates, input minimization, both text/image adapter shapes, cancellation/resumption, missing-photo rejection, optional-art failure and real local PDF assembly with a synthetic image. Live API authorization/output quality, Windows Credential Manager, clean-machine installation and physical printing still need target-platform verification.

Interpretations are traditional reflections, not guaranteed outcomes. Review AI-generated reports before sharing. Original calculated tables and scores remain authoritative. Automatic PDFs are unencrypted exported documents; encrypted backups retain report data/artwork, not separate PDF exports.

Read Astroguru/README.md, OPERATOR-GUIDE.md, VERIFICATION.md, LIMITATIONS.md and LICENSING.md.

## Earlier improvements

Modern studio interface, ten-step reading workflow, five-page client information, explicit right/left labels, rectangular palm frames, local background clearing/restoration and offline automatic country lookup remain included.

## License

AGPL-3.0-or-later with included third-party notices; GeoNames data CC BY 4.0. Commercial distribution obligations apply. The ZIP contains no client vault, account session or API credentials.
