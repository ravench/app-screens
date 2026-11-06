# app-screens

Screenshots that the CI of [ravench/kaliberfinder](https://github.com/ravench/kaliberfinder) and
[ravench/schiesstagebuch](https://github.com/ravench/schiesstagebuch) takes. They live here so the
app repositories' history stays small.

- `kaliberfinder/pr-screens`, `schiesstagebuch/pr-screens`: one folder per pull request with the
  screens that look different, before and after. The *PR screens* comment on each pull request
  links them by commit.
- `schiesstagebuch/ipad-screens`: the latest run of the *iPad screens* workflow.
- `archive/kaliberfinder-pr-screens`, `archive/schiesstagebuch-pr-screens`: the old `pr-screens`
  branches of the app repositories (until 6 November 2026), same commits. Older comments link here.

The images are plain files, not Git LFS: the comments link them through raw.githubusercontent.com,
which does not serve LFS files. Do not delete or rewrite these branches, or the images in old
comments break. The workflows push with the deploy key stored in each app repository's
`SCREENS_DEPLOY_KEY` secret.
