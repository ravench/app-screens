# app-screens

Screenshots that the CI of [ravench/kaliberfinder](https://github.com/ravench/kaliberfinder),
[ravench/schiesstagebuch](https://github.com/ravench/schiesstagebuch) and
[ravench/kaliberkatalog-android](https://github.com/ravench/kaliberkatalog-android) takes. They live
here so the app repositories' history stays small.

- `kaliberfinder/pr-screens`, `schiesstagebuch/pr-screens`, `kaliberkatalog-android/pr-screens`: one
  folder per pull request with the screens that look different, before and after. The *PR screens*
  comment on each pull request links them by commit.
- `schiesstagebuch/ipad-screens`: the latest run of the *iPad screens* workflow.
- `archive/kaliberfinder-pr-screens`, `archive/schiesstagebuch-pr-screens`: the old `pr-screens`
  branches of the app repositories (until 6 November 2026), same commits. Older comments link here.

The images are plain files, not Git LFS: newer comments link them as
`https://github.com/ravench/app-screens/raw/<commit>/…`, older ones through raw.githubusercontent.com,
which does not serve LFS files. Do not delete or rewrite these branches, or the images in old
comments break. The workflows push with the deploy key stored in each app repository's
`SCREENS_DEPLOY_KEY` secret.
