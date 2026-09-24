# ss-phase0

skill-studioのPhase 0で、Claude CodeとCodexのプラグインの導入と更新がmacOSとLinuxで動くかを、GitHub Actionsのランナーで確かめるためだけのrepo。中身は架空のスキル`phase0-echo`だけで、製品のコードは含まない。

- `v1`と`v2`のタグが、それぞれ1.0.0と1.0.1の配布物を指す。
- `.github/workflows/phase0.yml`を手で起動すると、各OSで導入とv1→v2の更新を走らせる。
