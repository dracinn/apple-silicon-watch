# Apple Silicon Watch

Automated daily digest of Apple Silicon Linux ecosystem activity feeding
[bazzite-asahi](https://github.com/dracinn/bazzite-asahi) development.

The `apple-silicon-watch` workflow scans the repos in `WATCH_REPOS` for
merged PRs and releases, plus project checks (Fedora manifest pin drift,
@asahi COPR Fedora 46 chroot), and opens one issue per active day.
Edit `WATCH_REPOS` in `.github/workflows/apple-silicon-watch.yml`.
