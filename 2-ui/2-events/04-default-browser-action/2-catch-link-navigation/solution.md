これはイベント移譲パターンを大いに活用してものです。

実際には、尋ねる代わりに、訪問者がどこから離れたかに関する情報を保存する "ログ"要求をサーバーに送信できます。 または、コンテンツを読み込んでページに表示することもできます（許可されている場合）。

私たちに必要なことは、`contents.onclick` をキャッチし、ユーザの確認するために `confirm` を使うことです。良いアイデアは URL に対して `link.href` の代わりに、`link.getAttribute('href')` を使うことです。詳細は解決策を見てください。
