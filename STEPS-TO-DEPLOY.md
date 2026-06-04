# Steps to Deploy GitHub Profile README

## Prerequisites

- GitHub account: **supernovaprime**
- Repository created: `supernovaprime/supernovaprime` (public)
- Git installed locally
- GitHub CLI (`gh`) optional but recommended

---

## 1. Clone Your Repository

```bash
git clone git@github.com:supernovaprime/supernovaprime.git
cd supernovaprime
```

---

## 2. Copy Project Files

Copy all files from this directory to your cloned repo:

```bash
# From this project directory
cp -r * /path/to/cloned/supernovaprime/
# Or manually copy:
# - README.md
# - .github/workflows/*.yml
# - assets/*.svg
```

---

## 3. Customize the README

Edit `README.md` and replace placeholder values:

| Placeholder | Replace With |
|-------------|--------------|
| `supernovaprime` (in badge URLs) | Your actual GitHub username |
| Project URLs (`project-alpha`, `project-beta`, etc.) | Your actual repo names |
| Live demo URLs | Your actual deployed URLs |
| Social links (LinkedIn, Twitter, Email) | Your actual profiles |
| Company/role info | Your actual details |
| Skills/proficiency levels | Your actual skills |
---

## 4. Enable GitHub Actions

1. Go to your repo: `https://github.com/supernovaprime/supernovaprime`
2. Settings → Actions → General
3. **Actions permissions**: "Allow all actions and reusable workflows"
4. **Workflow permissions**: "Read and write permissions"
5. Save

---

## 5. Commit and Push

```bash
git add .
git commit -m "feat: add complete profile README with automation

- Hero with typing animation
- GitHub stats cards (auto-updated)
- Tech stack with skill icons
- Featured projects with live badges
- Contribution activity graphs
- Achievements trophies
- Social connect buttons
- GitHub Actions for daily/weekly updates"
git push origin main
```

---

## 6. Verify Deployment

1. Visit `https://github.com/supernovaprime`
2. Check all sections render correctly
3. Wait for Actions to run (or trigger manually via Actions tab)
4. Verify badges show live data

---

## 7. Optional: Custom Domain (for portfolio site)

If you later build a standalone portfolio at `supernovaprime.dev`:

1. Add `CNAME` file with your domain
2. Configure DNS: CNAME → `supernovaprime.github.io`
3. Enable GitHub Pages in repo settings

---

## File Structure

```
supernovaprime/
├── README.md                    # Main profile (renders on github.com/supernovaprime)
├── .github/
│   └── workflows/
│       ├── update-stats.yml     # Daily: refreshes contribution stats
│       ├── update-repos.yml     # Weekly: updates featured project data
│       └── update-metrics.yml   # Every 6hrs: updates timestamp
├── assets/
│   ├── banner.svg               # Animated gradient banner
│   └── divider.svg              # Theme-aware section dividers
└── STEPS-TO-DEPLOY.md           # This file
```

---

## Troubleshooting

| Issue | Fix |
|-------|-----|
| Actions not running | Check repo Settings → Actions permissions |
| Badges not loading | Verify username in badge URLs; check shields.io status |
| SVG not animating | GitHub strips some CSS animations; use GIF fallback |
| Stats not updating | Trigger workflow manually from Actions tab |
| 404 on assets | Ensure assets committed to repo root |

---

## Updating Content

- **Projects**: Edit the Featured Projects section in README.md
- **Skills**: Update the skillicons.dev URL in Tech Stack section
- **Social links**: Update badge URLs in Connect section
- **Bio**: Edit the About Me YAML block

All external badges (stats, stars, forks, etc.) update automatically on page load via their CDN.

---

## Resources

- [GitHub Profile README Guide](https://docs.github.com/en/account-and-profile/setting-up-and-managing-your-github-profile/customizing-your-profile/managing-your-profile-readme)
- [shields.io Badge Generator](https://shields.io)
- [skillicons.dev](https://skillicons.dev)
- [github-readme-stats](https://github.com/anuraghazra/github-readme-stats)
- [readme-typing-svg](https://github.com/DenverCoder1/readme-typing-svg)