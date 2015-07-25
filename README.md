<code>
$ gradle uploadArchives
</code>

を実行することで、ローカルMavenリポジトリにインストールされ、他プロジェクトから参照できるようになります。

build.gradle の dependencies に以下のコードを追記してください。

<code>
compile 'com.github.yukihane.android:support-v4-preferencefragment:1.0.0'
</code>

クラス名は<code>android.support.v4.preference.PreferenceFragment</code>
となっており、あたかもAndroidプロジェクト公式のものであるかのように見えますが、
そうではないので注意してください。
(可視性の問題などでこのようなパッケージ名にせざるを得ないのかもしれません)

以下、オリジナルのREADME:


android-support-v4-preferencefragment
=====================================

Unofficial PreferenceFragment compatibility layer for Android 1.6 and up. Includes resources so add this as a library project to your project.
