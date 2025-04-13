Release Checklist:

1.  **Update `package.json` version:**

    - Open `package.json`.
    - Set the `version` field to the new version number (e.g., `1.0.0`).
    - Commit the change.

2.  **Update `CHANGELOG.md`:**

    - Open `CHANGELOG.md`.
    - Add a new section for the release with the version number and date.
    - Detail the changes, fixes, and new features included in this release.
    - Commit the change.

3.  **Package the extension:**

    - Open a terminal in the project root directory.
    - Run `vsce package`.
    - Verify that the `.vsix` file is created in the project directory.

4.  **Test the package (Optional):**

    - In VS Code, go to the Extensions view (Ctrl+Shift+X or Cmd+Shift+X).
    - Click the "..." menu in the Extensions view.
    - Choose "Install from VSIX...".
    - Select the `.vsix` file you created.
    - Test the extension to ensure it works as expected.

5.  **UPLOAD TO AZURE DEVOPS/MARKETPLACE - REMEMBER: YOU DO THIS!**
    - Log in to the [VS Code Marketplace](https://marketplace.visualstudio.com/manage/publishers/matzar).
    - Navigate to the extensions management section.
    - Upload the `.vsix` file.
    - Follow the prompts to publish the new version.
    - Announce the new release to your team/users.
