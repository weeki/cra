# CRA Notification Simulator

Static HTML simulator for CRA vulnerability / incident notification readiness across 24h, 48h, 72h and final summary steps.

## GitHub Pages deployment

1. Create a new GitHub repository, for example `cra-notification-simulator`.
2. Upload these files at the root of the repository:
   - `index.html`
   - `.nojekyll`
   - `README.md`
3. Commit the files to the `main` branch.
4. Open the repository **Settings**.
5. Go to **Pages**.
6. Under **Build and deployment**, choose:
   - Source: **Deploy from a branch**
   - Branch: **main**
   - Folder: **/root**
7. Save. GitHub Pages will publish the site after the deployment completes.

The site URL is usually:

```text
https://<github-username>.github.io/<repository-name>/
```

For example:

```text
https://papyweeki.github.io/cra-notification-simulator/
```

## Notes

- This is a static client-side HTML application.
- No backend is required.
- Data saved by the simulator is stored locally in the user's browser via local storage.
