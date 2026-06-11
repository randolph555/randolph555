# randolph555 GitHub Profile Setup

This directory is ready to become the special profile repository for `randolph555`.

Steps:

1. Create a public GitHub repository named exactly `randolph555`.
2. Push these files to that repository.
3. Visit `https://github.com/randolph555`; the README appears at the top of the profile.
4. Open the repository Actions tab and run `Generate contribution snake` once. After that it refreshes every day.
5. Run `Generate 3D contribution profile` once as well. This creates the premium 3D contribution scene.
6. Optional: keep `Daily profile heartbeat` enabled if you want the contribution snake to have regular activity even when you are not pushing code.

Recommended push commands from this directory:

```bash
git init
git add README.md assets .github SETUP.md
git commit -m "Create premium GitHub profile"
git branch -M main
git remote add origin git@github.com:randolph555/randolph555.git
git push -u origin main
```

To tune it later:

- Edit `assets/hero.svg` to change the banner name, tagline, or colors.
- Edit `assets/terminal.svg` to tune the animated terminal panel.
- Replace the two cards under `Featured Builds` with stronger repos if you want.
- Add contact links under the badges when you decide what email, blog, or social links to expose.
- If you dislike automated contribution commits, delete `.github/workflows/heartbeat.yml` and `data/heartbeat.txt`.
