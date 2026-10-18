# Axolotl-Cachix

预构建 [美西螈启动器](https://github.com/Mystic-Stars/Axolotl) 产物由 [工作流](./.github/workflows/nix-cache.yml) 自动推送至 [Cachix](https://axlmc.cachix.org)。\
请将 `"https://axlmc.cachix.org"` 加入 `extra-substituters`，\
并将 `"axlmc.cachix.org-1:dmsRJqFQqLMfvRveerHV3DxDCW1wq1N+TX1+dryYWZU="` 加入 `extra-trusted-public-keys`。

Prebuilt [Axolotl Launcher](https://github.com/Mystic-Stars/Axolotl) artifacts are pushed automatically by the [workflow](./.github/workflows/nix-cache.yml) to [Cachix](https://axlmc.cachix.org).\
Please add `"https://axlmc.cachix.org"` to `extra-substituters`,\
then add `"axlmc.cachix.org-1:dmsRJqFQqLMfvRveerHV3DxDCW1wq1N+TX1+dryYWZU="` to `extra-trusted-public-keys`.

<!-- BEGIN CACHED-COMMITS -->

| Ref | Commit | x86_64-linux | aarch64-linux |
| --- | --- | :---: | :---: |
| `v1.9.8` | [`c77ce76c19224df6cfe4cc2c1b362e07db22a0fd`](https://github.com/Mystic-Stars/Axolotl/commit/c77ce76c19224df6cfe4cc2c1b362e07db22a0fd) | ✅ | ✅ |
| `v1.10.0-beta.2` | [`f20f2cc4c2910713c91ff2071bc307ef8c1ca564`](https://github.com/Mystic-Stars/Axolotl/commit/f20f2cc4c2910713c91ff2071bc307ef8c1ca564) | ✅ | ✅ |
| `main` | [`7996bdadfc60cf965af25b5c235a5fe0705f2f5a`](https://github.com/Mystic-Stars/Axolotl/commit/7996bdadfc60cf965af25b5c235a5fe0705f2f5a) | ✅ | ✅ |

<!-- END CACHED-COMMITS -->

| 图例  Legend |      描述      | Description |
|:------------:|:--------------:|:----------------:|
|     `✅`     | 缓存成功       | `Successfully cached` |
|   `❔❓❌`   | 构建失败1/2/3+ | `Build failed 1/2/3+` |
|     `💤`     | 无可用的flakes | `No available flakes` |
|     `⏳`     | 未知故障       | `Undetermined issues` |
