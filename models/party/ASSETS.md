# Birthday Party room assets

Runtime copies for `/party`. Do not edit here; change the source and copy again.

## Asset Studio exports (`D:\Asset Studio\exports\<id>\<id>.glb`)

| File | Studio version | sha256 (prefix) |
| --- | --- | --- |
| railwood-table.glb | 2 | 25fde3a6fb432828 |
| railwood-chair.glb | 2 | 32d1aaf51f714c03 |
| mv2-round-cafe-table.glb | 1 | 80365658f2b11b76 |
| double-sofa.glb | 1 | 24b2d7f752348bcc |
| single-sofa.glb | 1 | dc4abe332cc17143 |
| coffee-table.glb | 1 | fd4db413fec750fc |
| school-art-narrow-console-table.glb | 1 | 7ddad3f1e7e82cb3 |
| school-canteen-rect-table.glb | 1 | 6bef216a30055ab3 |
| mv2-leafy-floor-planter.glb | 1 | 9b1d01a0c7636df6 |
| campus-music-speaker.glb | 1 | fba7ff45c84b1d44 |
| mv2-table-snack-riser.glb | 1 | 2e53ff81254ce9d8 |
| bonk-coke.glb | 1 | 842b7cd0d885d0d0 |
| solprite.glb | 1 | 22dbb37877c1e862 |
| pump-juice.glb | 1 | 84e17a219e510dd0 |
| pepetos.glb | 1 | 36e21c60de05a161 |
| dogeitos.glb | 1 | 843ba4693735feae |

## Character

`photo-guy.glb` (sha256 4b9eb8ac2898a3c4) is
`artifacts/toony-tiny-research/photo-face/photo-face-toony-tiny.glb` v004
(sha256 022ca4723ba5…) repacked by `scripts/party/pack-character.mjs`: the
embedded PNG textures are re-encoded as JPEG; geometry, skins, morphs and all
24 clips are byte-identical. `portrait.jpg` is the same project's source
portrait, resized for the framed photos.

## Third party

`strawberry-cake.glb` — "Strawberry Cake" by Strawbie
(https://sketchfab.com/strawbie133), CC BY 4.0,
https://sketchfab.com/3d-models/strawberry-cake-0b5e74462cac4869b6cfb64c325b6d89.
Unmodified file; the page re-skins the flame material at runtime and shows the
credit in its footer.

Music is not stored here: the TV plays two YouTube videos through YouTube's
embedded player (`src/party/music.ts`).
