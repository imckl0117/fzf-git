# fzf-git

A dead simple git helper script for automating some of my git commands. The _install_ script places _fzf-git_ under _~/.local/bin_ and names it _g_.

## Some notes for myself

- In `git_log_preview()`, `pbcopy` is only available on macOS.
- For `xargs` invocations, consider adding the `-r` flag to handle empty input for the GNU version of `xargs`.
