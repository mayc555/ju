# Block Maze native TikTok test packages

Latest device candidate: **Block-Maze-native-20261113-v4.zip**, uploaded as TikTok portal **version 4**.

SHA256: 5aafedca2e2b4d084c920bebf180e19a434a8b4084bb70ceffcd787dbcc8d647

V3b flattens all platform subpackage names, translates logical game package names at the Laya loader boundary, and fixes the home caption callback for the actual GImage renderer. Local engine tests covered startup, dragging, win, Level 2, reload, settings/home and all 55 package entries. Official static checks passed 115/115. Real TikTok device CDN delivery, login and ads still require tester verification.

Earlier archives are historical candidates. V1/V2 failed phone startup. The plain v3 archive lacks the later home caption fix; use v3b for the next test.

V4 restores the original indexed side-game data and 34 asset-only remote bundles on the developer HTTPS CDN, and separates them from executable native subpackages. Actual local engine tests entered Sand Spin and Block Puzzle and exercised drag operations. Real TikTok phone login, ad delivery and device acceptance remain pending.
