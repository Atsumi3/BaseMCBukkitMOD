# BaseMCBukkitMOD  
自分が Minecraft Bukkit のMODを作成するためのテンプレです。  
IntelliJ IDEA で gradle を使ってビルドします。  
  
## ビルドの覚書
ビルドする時は  gradlew build  を使う  
すると /build/libs/ にプラグインが排出される。  
このプロジェクトなら BaseMCBukkitMOD-0.0.1.jar かな

## 現在の環境
JRE 1.8.0_45 64bit  
JDK 1.8.0_31 64bit  
IntelliJ IDEA Community Edition 14.1.4   
Bukkit LatestVersion (1.8.7-R0.1)  
  
## 自分の環境に合わせる時
(どれか意味のない事をしてる気がする)  
* パッケージの変更  
 * Shift-Ctrl-R を押して  info.nukoneko.mine を置換
 * あとディレクトリ構造も info.nukoneko.mine から変更
* プラグイン名の変更
 * Shift-Ctrl-R を押して  TestPlugin を置換
* バージョンの変更
 * src/main/resources/plugin.yml の0.0.1を変えよう
 * build.gradle の version も変えよう
