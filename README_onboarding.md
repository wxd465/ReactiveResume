# Resume AI Starter Pack (for Reactive Resume base)

**Who is this for?** Non-coders. You only upload these files into your forked project.
If you have not forked yet, open the Reactive Resume GitHub page and click **Fork**.
After forking, in your new repo click **Add file → Upload files** and drag the contents of this ZIP.
No command line is required.

## What this pack gives you
1. **.env.sample** — environment variables you can copy to your project settings (GitHub → Settings → Secrets and variables → Actions → New repository secret).
2. **prompts/** — AI prompts for two modes: onboarding (conversation) and polish (one-click optimization), plus JD alignment.
3. **questions/** — question bank for the chatbot to collect resume data.
4. **templates/** — a minimalist resume template JSON with layout rules aligned to ATS-friendly output.
5. **exporter/config.json** — filename rules for exported resumes.
6. **scripts/IMPORT_GUIDE.md** — step-by-step instructions (web UI only).

## Minimal steps (web only)
1) Fork the base project on GitHub (Reactive Resume is recommended).
2) In your forked repo: **Add file → Upload files**, then upload the ZIP contents.
3) Go to **Settings → Secrets and variables → Actions** and add these secrets:
   - OPENAI_API_KEY (optional)
   - CLAUDE_API_KEY (optional)
   - GEMINI_API_KEY (optional)
   - DEEPSEEK_API_KEY (optional)
   - GROQ_API_KEY (optional)
   - DATABASE_URL (required by backend if you deploy full stack)
   - BROWSERLESS_KEY (for server-side PDF if used)
4) Open the app’s admin/config page (or environment config page) and paste prompt JSON IDs.
5) Done. The app can run with onboarding chat and one-click polish using these prompts.

## Note on licenses
If you use Reactive Resume (MIT), you can keep your fork closed-source for business use as long as you retain the license file.
If you use AGPL projects, you must open-source your modified service when deployed over a network.
