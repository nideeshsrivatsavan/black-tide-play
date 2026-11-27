# Sea monster bodies

`*.bin` here are the bodies of the sea monsters, baked by `tools/monsters/bake.py` from the models below
(each file's header lists its own sources under `sources`). Every model keeps its own licence.

| File | Built from |
|---|---|
| `leviathan.bin` | High-Poly Humpback Whale (body, flukes, flippers) + Black caiman (head, jaws, neck) |
| `isonade.bin`, `lusca.bin` | Indonesian Whaler Shark |
| `serpent.bin`, `bakunawa.bin` | Daian Sea Eel |
| `kraken.bin` | North Pacific Giant Octopus (head and mantle) |

## High-Poly Humpback Whale

- Author: K9239 (https://sketchfab.com/K9239)
- Source: https://sketchfab.com/3d-models/high-poly-humbpack-whale-5a6a09f1c27e4d0f890f2a30c10d7a81
- Licence: Creative Commons Attribution 4.0 International (CC BY 4.0),
  https://creativecommons.org/licenses/by/4.0/ (legal code: https://creativecommons.org/licenses/by/4.0/legalcode)
- Attribution: "High-Poly Humpback Whale" by K9239, licensed under CC BY 4.0. Modified: cut into the body and
  the flippers, straightened, rescaled (the body stretched to 55 m, the flippers to 12 m), joined to a
  caiman's head, decimated, bound to the game's rig and its colours reduced to a pattern. No endorsement by
  the author is implied.

## Black caiman (Melanosuchus niger)

- Author: State Darwin Museum, Moscow (https://sketchfab.com/darwinmuseum.ru)
- Source: https://sketchfab.com/3d-models/black-caiman-fe345a7b30a7452b976fd1f43262dbea
- Licence: CC0 1.0 Universal (public domain dedication), https://creativecommons.org/publicdomain/zero/1.0/

## Indonesian Whaler Shark; Daian Sea Eel (Conger erebennus); North Pacific Giant Octopus

- Author: ffish.asia / floraZia.com (https://sketchfab.com/ffishAsia-and-floraZia)
- Sources:
  - https://sketchfab.com/3d-models/cc0-indonesian-whaler-shark-c8c0853a047e4fefa0ce98be353bcf6a
  - https://sketchfab.com/3d-models/cc0-daian-sea-eel-conger-erebennus-a9ebd0c2970449ce80fa3a9b99ba66c3
  - https://sketchfab.com/3d-models/cc0-north-pacific-giant-octopus-7fb48f6cbcd54149bb23837a3ac09b2e
- Licence: CC0 1.0 Universal (public domain dedication), https://creativecommons.org/publicdomain/zero/1.0/

The files were downloaded from the Objaverse 1.0 mirror of these Sketchfab models
(https://huggingface.co/datasets/allenai/objaverse), which redistributes each object under its own licence;
`tools/monsters/fetch.py` names the exact files (sha256).
