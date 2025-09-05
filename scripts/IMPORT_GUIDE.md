# Import Guide (Web UI Only)

1. Open your forked GitHub repository.
2. Click **Add file → Upload files**.
3. Drag all files/folders from this ZIP into the upload area and click **Commit changes**.
4. Go to **Settings → Secrets and variables → Actions → New repository secret** and add keys from `.env.sample`.
5. In your app, register these prompt IDs:
   - prompts/onboarding_cn_v1.json → id: prompt_onboarding_cn_v1
   - prompts/polish_cn_v1.json → id: prompt_polish_cn_v1
   - prompts/jd_align_cn_v1.json → id: prompt_jd_align_cn_v1
6. Enable the features in your admin/config page (or environment flags).
