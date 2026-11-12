# Block Maze native TikTok test packages

Latest device candidate: **Block-Maze-native-20261112-v3b.zip**, uploaded as TikTok portal **version 3**.

SHA256: e50c8852b02bfa097d7582c3b412669f68fb46d7b7fc16030b3c1a13baf0b98c

V3b flattens all platform subpackage names, translates logical game package names at the Laya loader boundary, and fixes the home caption callback for the actual GImage renderer. Local engine tests covered startup, dragging, win, Level 2, reload, settings/home and all 55 package entries. Official static checks passed 115/115. Real TikTok device CDN delivery, login and ads still require tester verification.

Earlier archives are historical candidates. V1/V2 failed phone startup. The plain v3 archive lacks the later home caption fix; use v3b for the next test.
