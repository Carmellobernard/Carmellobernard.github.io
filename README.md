# Carmellobernard.github.io
- name:carmello Upload a Build Artifact
  uses: actions/upload-artifact@v3.1.2
  with:
    # Artifact name Carmello
    name: # optional, default is artifact
    # A file, directory or wildcard pattern that describes what to upload
    path: 
    # The desired behavior if no files are found using the provided path.
Available Options:
  warn: Output a warning but do not fail the action
  error: Fail the action with an error message
  ignore: Do not output any warnings or errors, the action does not fail

    if-no-files-found: # optional, default is warn
    # Duration after which artifact will expire in days. 0 means using default retention.
Minimum 1 day. Maximum 90 days unless changed from the repository settings page.
remote_theme: pages-themes/architect@v0.2.0
plugins:
- jekyll-remote-theme
