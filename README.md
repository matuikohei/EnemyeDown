# Minecraft プラグイン EnemyDown


**開発背景**
---
私は現在、未経験からのエンジニア転職に向けてプログラミングスクールでJavaを学習しています。
このプラグインは、Javaの条件分岐やループ処理、入出力処理を学習するために作成しました。

**プラグイン概要**
---
プライヤーが制限時間内に敵を倒してスコア（合計点数）を競うミニゲームです。ゲームの難易度をeasy、nomal、hardから選択することができます。ゲーム終了後に、スコアが表示されます。


**機能要件**
---
* 体力や空腹ゲージは最大化されること
* 一定のエリア内でしか敵は発生しないこと
* 敵の種類はランダムであること
* 装備や武器はプレイする度に同じになること
* 敵を倒すと点数が手に入ること
* 時間制限を設定できること
* スコア（合計点数）ボードが表示できること
* 敵の種類によって手に入る点数が異なること
* 時間制限が来たらエリア内の敵は消滅すること
* 特殊効果や状態異常はゲーム開始時に無効化されること / ゲーム終了後にも無効化されること
* 時間制限が来たら合計の点数が表示されること
* 保存する情報はスコアとプレイヤー名と日時
* 新しい情報が入った場合は、上書きではなく、全て保存すること


**プラグイン実装方法**
---
* Javaのインストール(Javaのバージョンは17.0.11です)
* Spigotのインストール（Spigotのバージョンは1.19.3）
* Minecraftのインストール（Minecraftのバージョンは1.19.3です）
* URLのファイルをダウンロード
  https://drive.google.com/file/d/1zSzhI3lvb3SLPQZYdc9UaBRbffX-Ap8W/view?usp=drive_link
* Minecraftフォルダのpluginsフォルダの中に、ダウンロードしたファイルを移動することで、プラグインを実装できます

**使用技術**
---
* Java　17.0.11
* Spigot 1.19.3
* MySQL　8.0
