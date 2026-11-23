# stone

**Inferno suite用のビデオファイル専用ブラウザ。日本語・英語対応。**  
**A dedicated video file browser for the Inferno suite, with Japanese and English interfaces.**

[ダウンロード / Download](https://github.com/newfrontierstudio/stone/releases/latest)

stone is a dedicated video file browser for Windows, built for people who work with footage. Open a folder and your clips are simply there, as thumbnails — no importing, no library database to maintain.

Hover over a thumbnail and it grows into a large preview. Move the pointer sideways and the preview scrubs through the clip, so you can check the content of a shot without opening a player. Resolution, frame rate and duration are shown for every file.

Blackmagic RAW (.braw) files belong in the same list. When a Blackmagic RAW runtime is installed — DaVinci Resolve or Blackmagic RAW Player — BRAW clips get thumbnails and metadata like any other format. Nothing is bundled; without the runtime, the files still list, without a thumbnail.

A LUT can be assigned to each clip from the right-click menu. Pick a .cube file and the thumbnail is shown with that LUT applied. The assignment is remembered per clip, and when the clip is opened in Inferno, the same LUT goes with it.

stone is part of the Inferno suite. Selected clips open directly in Inferno for editing, and ordinary playback uses your default Windows player. Thumbnails are generated on the GPU and cached — the cache is shared with Inferno, so a folder browsed in one is fast in the other.

The everyday file work is covered too: search by file name, rename, move, and send to the Recycle Bin, without leaving the browser.

- Windows 10 / 11, 64-bit
- Interface in Japanese and English, following your Windows language, switchable in the app
- The installer is about 2.1 MB; the components it needs are fetched on first install, and shared components already on the PC are reused
- [Inferno](https://github.com/newfrontierstudio/inferno-studio/releases/latest) is required only for the Inferno editing shortcut

---

stone は、映像を扱う人のための Windows 専用ビデオファイルブラウザです。フォルダを開けば、クリップがサムネイルでそのまま並びます。取り込みも、ライブラリの管理もありません。

サムネイルにマウスを置くと大きくプレビューされ、左右に動かすと映像をスクラブできます。プレーヤーを開かなくても、中身を確認できます。解像度・フレームレート・長さは、すべてのファイルに表示されます。

Blackmagic RAW (.braw) も同じ一覧に並びます。Blackmagic RAW ランタイム (DaVinci Resolve / Blackmagic RAW Player) がインストールされていれば、他の形式と同じようにサムネイルとメタ情報が表示されます。同梱はしません。ランタイムが無い環境では、サムネイルなしの一覧表示になります。

LUT は右クリックでクリップごとに割り当てられます。.cube ファイルを選ぶと、サムネイルにその LUT が適用されて表示されます。割り当てはクリップごとに記憶され、Inferno で開いたときにも同じ LUT が引き継がれます。

stone は Inferno スイートの一員です。選んだクリップは Inferno で直接開いて編集でき、通常の再生には Windows で設定したプレーヤーを使います。サムネイルは GPU で生成してキャッシュし、そのキャッシュは Inferno と共有されます。片方で見たフォルダは、もう片方でも速く開きます。

ファイル名検索、名前変更、移動、ゴミ箱への移動といった日常のファイル操作も、ブラウザを離れずに行えます。

- Windows 10 / 11、64bit
- 表示言語は Windows に合わせて自動選択。「日本語 / English」で切り替えられます
- インストーラーは約2.1MB。必要な実行環境・動画部品は初回に取得し、導入済みの共通部品は再利用します
- Inferno 連携にのみ [Inferno](https://github.com/newfrontierstudio/inferno-studio/releases/latest) のインストールが必要です

This repository hosts downloads and documentation. The application source code is not published.
