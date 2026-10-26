# Power BI project file

Place the Power BI Desktop project (`.pbix`) in this folder. Suggested name:

```text
AI-Automation-Risk-Workforce-Analytics.pbix
```

## Add a smaller file (under 100 MB)

From the repository root, run:

```bash
git add powerbi/AI-Automation-Risk-Workforce-Analytics.pbix
git commit -m "Add Power BI report"
git push
```

You can also use GitHub Desktop: copy the `.pbix` into this folder, commit the change, then push it to GitHub. The GitHub website's browser uploader has a smaller per-file limit than Git; use Git/GitHub Desktop instead of the web uploader if the file is over 25 MB.

## If the `.pbix` is larger than 100 MB

GitHub rejects regular Git files above 100 MB. Use Git Large File Storage (LFS), and check that your GitHub account/repository has enough LFS storage and bandwidth before uploading:

```bash
git lfs install
git lfs track "*.pbix"
git add .gitattributes
git add powerbi/AI-Automation-Risk-Workforce-Analytics.pbix
git commit -m "Add Power BI report with Git LFS"
git push
```

The LFS tracking rule in `.gitattributes` is versioned with the repository. If Git LFS is not installed, install it first from the official Git LFS instructions. Avoid committing backup copies, temporary autosaves, or confidential source extracts.
