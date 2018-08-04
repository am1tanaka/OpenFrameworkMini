# OpenFrameworkMini
Unity用の必要最小限のゲームのひな形。

# 環境
- Unity2018.2.1で動作確認

# 最初の準備
このリポジトリーではTextMesh Proのリソースを利用しています。最初に読み込む必要があります。

- Unityの*Window*メニューから、*TextMeshPro* -> *Import TMP Essential Resources*を選択して、読み込みます
- 同じく、*Window*メニューから、*TextMeshPro* -> *Import TMP Examples and Extras*を選択いｓて、読み込みます

リソースを読み込んでもエラーが発生する場合があるので、プロジェクトを読み込み直します。

- *File*メニューから*Save Project*を選択して保存しておきます
- *File*メニューから*Open Project*を選択して、**OpenFrameworkMini**を読み込みます

以上で完了です。

# プロジェクトの開始方法
- *Project*ビューから、*Scenes*フォルダーの左の三角をクリックして開きます
- *Title*シーンをダブルクリックして開きます

以上で、*Play*すればデモが始まります。

# 警告について
ゲームオーバーやクリアシーンになると、ライトに関する警告が表示されます。これは、ライトのベイクを*Auto Generate*にしていて、シーンの切り替わり時にライトが無効になって、画面が暗くなる症状についての警告です。

シーンが切り替わった時に、ライティングが暗くなる症状を解決する場合は、ライトの調整が完了したあとに、*Window*メニューから*Rendering* -> *Lighting Settings*を開いて、*Auto Generate*のチェックを外して、ライトを*Generate*してください。
