本日は、Python で開発したプログラムの多言語化について調べていました。調査の結果、gettext を使用するのが一般的な方法であることがわかりました。gettext では、翻訳ファイルを「{言語}/LC_MESSAGES/{ドメイン}.mo」という形式で言語ごとに管理するようです。

React などで行う i18n とは全く異なるアプローチであり、興味深いと感じました。 