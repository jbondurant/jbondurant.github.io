# Manifest

A SHA-256 hash proves that a file is, byte for byte, the file it was taken from. The files under served ship with the page, and SHA256SUMS lists them, so shasum -a 256 -c SHA256SUMS checks them. The hashes under recorded were taken of the run files the figures were read from. Those files do not ship with the page, so their hashes cannot be checked from it alone. That these are the files the figures were read from is the publisher's statement. The commit beside each is the one its input names, usually the run that made the figures read from it; it is not always the commit that made the file, and for the ledger it is the git blob of the registration. A hash says nothing about whether the code is right; a bug is hashed just as faithfully. Each file is named from the repository's folder. Files under runs/ are run outputs: they are kept out of the repository and are not published. A name with a branch before a colon, such as custom-count-design:custom-counts.json, is the committed file at that path on that branch. The runs recorded full paths on the computer they ran on, and the part up to the repository's folder is left out here. The input files, listed under inputs in manifest.json, still hold the full paths, so their hashes are those of the files as written.

## Served

| File | Bytes | SHA-256 | Made by |
|---|---|---|---|
| data/results.json | 1565877 | `bf93411c5227562a26147331be522196fbf07ed7acc5b96e9cf019e066c57eec` | SiteBuild |
| data/results.csv | 47172 | `2b13ba953c60dcb10f464c4ad010df76e4b4b6002c6d46052fcdeb8526aa2c26` | SiteBuild |

## Recorded

| File | Bytes | SHA-256 | Input's commit |
|---|---|---|---|
| counting-systems.json |  | `d63b01b967efdd6690752f56e1ffa9004432d89c36b7cef9e016ac80b0a03f66` | 1946b3dc1182c86f59d88b115edcd601a64e9cfd |
| custom-count-design:custom-count-ledger.tsv | 922 | `8dfb83d169d2bc1684cf7a083ea158aef5135ac6edc2aef4f511b3869c696794` | 39bd6d4a17f168c8906bce219db2eb95de67d856 |
| custom-count-design:custom-counts.json | 9693 | `87e56e7e3862308aae2d1db2c9be6da61301d3f4b69173c6f8af134ae8f18e5b` | 1946b3dc1182c86f59d88b115edcd601a64e9cfd |
| runs/ceiling/ceiling-1946b3d.json | 66496 | `5f5ff31a619d2b8db56fde910cb8a921be0e3874ea52cda1f085dd07b57ef820` | 1946b3dc1182c86f59d88b115edcd601a64e9cfd |
| runs/custom-count/fullplay-main-97bf834/results.ser | 113431766 | `6a456558649bf3d01ad7cd543856e8312fe6913c533788e7435501400d8c5302` | c06c061c21445d0c3c32752b4e8906390fb670ad |
| runs/full-index/full-c06c061/results.ser | 430694877 | `8ba1412b64c8b0276ee988440172737277b36aebec4ab63da94c77536ec93285` | c06c061c21445d0c3c32752b4e8906390fb670ad |
| runs/full-index/pilot-1417-100.txt | 53657 | `0018be90d8ec6103345cf6f52e81a0a350656863e25f4f45a7c39713cfbb7f76` | c06c061c21445d0c3c32752b4e8906390fb670ad |
| runs/key-edges/key-edges-1946b3dc1182c86f59d88b115edcd601a64e9cfd.json | 56333649 | `0ee6a39672ddfda7896759ed69e5dfb48671f78a07edec1b6709bd9ed6bdf65c` | 1946b3dc1182c86f59d88b115edcd601a64e9cfd |
| runs/report-ceiling-97bf834.md |  | `18763003e667aab5f4b9eb4d38eec65231511bbb0e34449e556868db20c06c19` | 1946b3dc1182c86f59d88b115edcd601a64e9cfd |
| runs/report-ceiling-97bf834.ser |  | `c854767f4d72e4124f7d465c40f9207347e477bda54878848dab754563de6511` | 1946b3dc1182c86f59d88b115edcd601a64e9cfd |
| runs/report-final-26f0724.md |  | `718a8e232a21901aa0addd745a7990034cf8a66c2ca9353c57927501293d495d` | 1946b3dc1182c86f59d88b115edcd601a64e9cfd |
| runs/risk/risk-1946b3d.json | 62241 | `69369629562bb534ff3b8fc6dc5f613a02f14371149c9f07df5759ef15a1fe4b` | 1946b3d |
| runs/sim/part1-0e0920d-plant-bet-key-plus-one/summary-p2.json | 24030 | `4dfb3b001403740f07352458fe498520b267edd81dba9644ffdbb98d9f766435` | fe9a91ea88f49b73c86278eec075d2b17e4bd4bd |
| runs/sim/part1-0e0920d-plant-bet-key-plus-one/summary-p3.json | 30487 | `5e193530cbd496a18f75ffce1cd0ecf234be07a26116e143128bc98b60d80d83` | fe9a91ea88f49b73c86278eec075d2b17e4bd4bd |
| runs/sim/part1-0e0920d-plant-hole-card/summary-p2.json | 24121 | `f6adf9e709bcbb402d2d305fbc3ab409dfd8c38b274047500cc612d57535fc2c` | fe9a91ea88f49b73c86278eec075d2b17e4bd4bd |
| runs/sim/part1-0e0920d-plant-hole-card/summary-p3.json | 30493 | `b8abe715d9d45f2ca61ae5a1c7a0d03c05e5827b215c6297159d458a9bda40c4` | fe9a91ea88f49b73c86278eec075d2b17e4bd4bd |
| runs/sim/part1-0e0920d-plant-insure-whole-bet/summary-p2.json | 23989 | `f1abf473957326b1fef9e8dc96a2de8898a05af519aa9b1443beb2911a3d4487` | fe9a91ea88f49b73c86278eec075d2b17e4bd4bd |
| runs/sim/part1-0e0920d-plant-insure-whole-bet/summary-p3.json | 30460 | `7c3783a5710bbe99c940383027fe61df35500812120a0909cb2d7deadda38d99` | fe9a91ea88f49b73c86278eec075d2b17e4bd4bd |
| runs/sim/part1-0e0920d-plant-no-das/summary-p2.json | 24126 | `8a616a6a0df647467429e4b769e443a47e63bfd7def865932a2eb57e9cee9b7a` | fe9a91ea88f49b73c86278eec075d2b17e4bd4bd |
| runs/sim/part1-0e0920d-plant-no-das/summary-p3.json | 30540 | `c471bd1aa44e896b4fa27db53990b9c04a1f5ec3d371609049806a820d544d01` | fe9a91ea88f49b73c86278eec075d2b17e4bd4bd |
| runs/sim/part1-0e0920d-plant-none/summary-p2.json | 24055 | `12c7096fb25a30ae990d9b03f98654e32bb619968b88f2fd67d77d32059741b9` | fe9a91ea88f49b73c86278eec075d2b17e4bd4bd |
| runs/sim/part1-0e0920d-plant-none/summary-p3.json | 30482 | `e436cbf20c8c43821ffd8449ff177c7d0ba407469345875858d8bb9cbbfad8bb` | fe9a91ea88f49b73c86278eec075d2b17e4bd4bd |
| runs/sim/part1-0e0920d-plant-other-fold/summary-p2.json | 24061 | `95fd3010e21de264b3ceb3ee205f7ad6cceea14cf86f4fb2cc923ebff94d2b71` | fe9a91ea88f49b73c86278eec075d2b17e4bd4bd |
| runs/sim/part1-0e0920d-plant-other-fold/summary-p3.json | 30489 | `5be95658acd354207fb29d9f4d7c7ad5d72a6bc33f7d887156f66dc991f25e19` | fe9a91ea88f49b73c86278eec075d2b17e4bd4bd |
| runs/sim/part1-0e0920d-plant-s17/summary-p2.json | 24046 | `04906d53bcc9ed99004a17cf71c693ad61739e0a76cac489f35e94d797d5d8a7` | fe9a91ea88f49b73c86278eec075d2b17e4bd4bd |
| runs/sim/part1-0e0920d-plant-s17/summary-p3.json | 30419 | `c52b699dd5f3e6b01678cef29d5808ab9938874c2c007a305812e9b8c388891d` | fe9a91ea88f49b73c86278eec075d2b17e4bd4bd |
| runs/sim/part1-0e0920d-plant-split-aces-hit/summary-p2.json | 24031 | `8f1e9632b41cde857f4d7559412a06b642948a8b56eae358655c4d5f1e7bd6fb` | fe9a91ea88f49b73c86278eec075d2b17e4bd4bd |
| runs/sim/part1-0e0920d-plant-split-aces-hit/summary-p3.json | 30416 | `6a1546c1d3164f047724daaab9af531005e0a4da310e00731d28e4cc49cd8d6d` | fe9a91ea88f49b73c86278eec075d2b17e4bd4bd |
| runs/sim/part1-0e0920d-plant-truncate/summary-p2.json | 24084 | `29a098d913ba68c57beddadf918c459fb0032e17fa1915345b896d426656463f` | fe9a91ea88f49b73c86278eec075d2b17e4bd4bd |
| runs/sim/part1-0e0920d-plant-truncate/summary-p3.json | 30505 | `3092763bbe571141a97d1589f54f6371de8db1b9d356585ee88c0aa431a319c6` | fe9a91ea88f49b73c86278eec075d2b17e4bd4bd |
| runs/sim/part1-0e0920d/depth.tsv | 1756 | `f6e1b90de1d9b0a9fd51787c73cffc595fa50ac654af0bba572e5e0344fa1104` | fe9a91ea88f49b73c86278eec075d2b17e4bd4bd |
| runs/sim/part1-0e0920d/ev-by-key.tsv | 12942 | `62dc22bbabd5ee29e023def0f02993196c69d47a38ff786793b24f37581a3b1f` | fe9a91ea88f49b73c86278eec075d2b17e4bd4bd |
| runs/sim/part1-0e0920d/summary-p2.json | 24100 | `d4be5f5201647a9cf56d764c72398c8c3ee24e7d5c5428f6d32e98c5e95cf909` | fe9a91ea88f49b73c86278eec075d2b17e4bd4bd |
| runs/sim/part1-0e0920d/summary-p3.json | 30398 | `1eb13d783bc2b500868694b279f925d65e07a75226406428c52c928ab0e0a8d5` | fe9a91ea88f49b73c86278eec075d2b17e4bd4bd |
| runs/sim/part2-0f087c4-plant-bet-key-plus-one/summary-p2.json | 12401 | `7f76012c7aaad3e06f3ec3c7d9d3273d52fbfdcb3908e6dcc76476f5fe3bb2a2` | fe9a91ea88f49b73c86278eec075d2b17e4bd4bd |
| runs/sim/part2-0f087c4-plant-bet-key-plus-one/summary-p3.json | 28445 | `05b03bdb36c218b14980370c4aef312042052750a58ceb9fc67e20ac076a4b2d` | fe9a91ea88f49b73c86278eec075d2b17e4bd4bd |
| runs/sim/part2-0f087c4-plant-hole-card/summary-p2.json | 12433 | `3fcb64f2e2cd174c6b3d56e2fc3ec0ffba94466353df275dc520a2606ec8f4a7` | fe9a91ea88f49b73c86278eec075d2b17e4bd4bd |
| runs/sim/part2-0f087c4-plant-hole-card/summary-p3.json | 28525 | `19dbb2a56e858aded65164b881ade606dd41cc9e9c9514ef33708c9b7e7f6600` | fe9a91ea88f49b73c86278eec075d2b17e4bd4bd |
| runs/sim/part2-0f087c4-plant-insure-whole-bet/summary-p2.json | 12382 | `df4462b549a1e779317cd664892a48abd1876a8d9ce668701170214934efb291` | fe9a91ea88f49b73c86278eec075d2b17e4bd4bd |
| runs/sim/part2-0f087c4-plant-insure-whole-bet/summary-p3.json | 28495 | `e9195f908beec883aa8c3e40acefd86c3403bdd11d7cc7c308451d9e7f1319ff` | fe9a91ea88f49b73c86278eec075d2b17e4bd4bd |
| runs/sim/part2-0f087c4-plant-no-das/summary-p2.json | 12425 | `7e9c998ffb8dd1236bd66305d5b2b6420e6ecb2634b43385a9ad0e84eed4b889` | fe9a91ea88f49b73c86278eec075d2b17e4bd4bd |
| runs/sim/part2-0f087c4-plant-no-das/summary-p3.json | 28543 | `9d8407ae454cc30b55002c5b33c423c855a916fdda6369e09086b9275354dd77` | fe9a91ea88f49b73c86278eec075d2b17e4bd4bd |
| runs/sim/part2-0f087c4-plant-none/summary-p2.json | 12406 | `aa0196fde157042c2b286cf47ceb3529e56d5b6826258bf4043a786e9aa2a6dc` | fe9a91ea88f49b73c86278eec075d2b17e4bd4bd |
| runs/sim/part2-0f087c4-plant-none/summary-p3.json | 28488 | `ccdff324f83babf79aed66ea90fd307f444b03dbac972732ff6dc09c741b3659` | fe9a91ea88f49b73c86278eec075d2b17e4bd4bd |
| runs/sim/part2-0f087c4-plant-other-fold/summary-p2.json | 12415 | `18e77d03001830bcb7707a80069e2fb87f17c1344f6403d03624bc8d8e0d0623` | fe9a91ea88f49b73c86278eec075d2b17e4bd4bd |
| runs/sim/part2-0f087c4-plant-other-fold/summary-p3.json | 28490 | `a412adcfadba8c550dcb26875031f9a8b0839c35ccd3320b47ac2cfcb526f9c4` | fe9a91ea88f49b73c86278eec075d2b17e4bd4bd |
| runs/sim/part2-0f087c4-plant-s17/summary-p2.json | 12398 | `d08e59647365ab1f9a7b54e0c7f8d66a954e38addeb6442a6da6334894a7915e` | fe9a91ea88f49b73c86278eec075d2b17e4bd4bd |
| runs/sim/part2-0f087c4-plant-s17/summary-p3.json | 28450 | `41875e82f768f84243f8cdcf58a51ae5d7fc6060c8512fb0242b26ebe7ed46ba` | fe9a91ea88f49b73c86278eec075d2b17e4bd4bd |
| runs/sim/part2-0f087c4-plant-split-aces-hit/summary-p2.json | 12402 | `b27762ad892156ebe18295495575083a00dd22bdf5189d0841e390fa747dc88e` | fe9a91ea88f49b73c86278eec075d2b17e4bd4bd |
| runs/sim/part2-0f087c4-plant-split-aces-hit/summary-p3.json | 28456 | `f24638aa9b7dd8284d4e2ca1be4fb8b9692c93718d1b446d3d5ef7d49bfeaf6f` | fe9a91ea88f49b73c86278eec075d2b17e4bd4bd |
| runs/sim/part2-0f087c4-plant-truncate/summary-p2.json | 12424 | `ef06fed05e6b2432609097e5479051c938dff5e0149082cb7a720d3d0107eddc` | fe9a91ea88f49b73c86278eec075d2b17e4bd4bd |
| runs/sim/part2-0f087c4-plant-truncate/summary-p3.json | 28512 | `7499d32054352e93f9c7d63547c574240abe8ea728fd4f9d4c78825f59e9272a` | fe9a91ea88f49b73c86278eec075d2b17e4bd4bd |
| runs/sim/part2-0f087c4/ev-by-key.tsv | 15078 | `0376792ee56e56d125625b30c814405524c90b106a541723eabeb1ce1cf7d23e` | fe9a91ea88f49b73c86278eec075d2b17e4bd4bd |
| runs/sim/part2-0f087c4/summary-p2.json | 12414 | `6fc9c73a44795c31d211d3ffdd0377c35c9c99bd92e8f89e529e2ab91f7d97dd` | fe9a91ea88f49b73c86278eec075d2b17e4bd4bd |
| runs/sim/part2-0f087c4/summary-p3.json | 28420 | `95316ce03f887aafb629d7e678d368b3e798ef89f6e99f19565f58fa954d1f51` | fe9a91ea88f49b73c86278eec075d2b17e4bd4bd |
| runs/sim/part2-0f087c4/summary-variants.json | 3892 | `f6b94c6d4437f816d22b4077c76b3e6c2b58a14da91fa399c4b948eed8394e61` | fe9a91ea88f49b73c86278eec075d2b17e4bd4bd |
| runs/sim/part2-look-first-0f087c4/ev-by-key.tsv | 43 | `bbef6559755a0f0769c3cb4e674af029050f3b2e08345977a870297ff273c46a` | fe9a91ea88f49b73c86278eec075d2b17e4bd4bd |
| runs/sim/part2-look-first-0f087c4/summary-p2.json | 2250 | `7d6e43489d00d4c3693d75a563e87f0cadcb10b5a1ec86cb0b5cd8a5caac4f9c` | fe9a91ea88f49b73c86278eec075d2b17e4bd4bd |
| runs/sim/part2-look-first-0f087c4/summary-p3.json | 3659 | `7ec740584bbf9c1afcc298d8946f221d4d97706b06e462bd8354adea328234f4` | fe9a91ea88f49b73c86278eec075d2b17e4bd4bd |
| runs/sim/part2-look-full-0f087c4/ev-by-key.tsv | 43 | `bbef6559755a0f0769c3cb4e674af029050f3b2e08345977a870297ff273c46a` | fe9a91ea88f49b73c86278eec075d2b17e4bd4bd |
| runs/sim/part2-look-full-0f087c4/summary-p2.json | 2295 | `21c5e83e7de00842405929fa066ff96dad1c8700ebfb07092cec907d5581bdf7` | fe9a91ea88f49b73c86278eec075d2b17e4bd4bd |
| runs/sim/part2-look-full-0f087c4/summary-p3.json | 3702 | `8ba98219a557f5312c0c3b37bb255176e3dfbd0aeccf7db35a76d35313f904c8` | fe9a91ea88f49b73c86278eec075d2b17e4bd4bd |
| runs/wide/spreads-1946b3d.json | 8402452 | `ffb91cc95b72dbcfe9e2e19b896a8bb2940ec3720a4f553563b6cc024b049576` | 1946b3d |
| site-integration:literature/claims.json |  | `da7b74fe71dcebbe2b5dc4c840d61510473c7da49fa1c5dfda50b6e3b9a119e3` | 1946b3dc1182c86f59d88b115edcd601a64e9cfd |
| site-integration:verification/evidence.tsv | 6383 | `fa8771cb7e3b8c3347ed51100cd260336e09779ef137bf3b18cc1ca800e7aef7` | 34d2959441bc7069009303ad8403477dd73fd99b |
