`permissions`キーを使って、フォークされたリポジトリの読み取り権限の付与や削除ができますが、通常は書き込みアクセス権を付与することはできません。 この動作の例外としては、管理ユーザが{% data variables.product.prodname_actions %}の設定で**Send write tokens to workflows from pull requests（Pull Requestからワークフローに書き込みトークンを送る）**を選択している場合があります。 詳しい情報については、「[リポジトリの {% data variables.product.prodname_actions %} 設定の管理](/repositories/managing-your-repositorys-settings-and-features/enabling-features-for-your-repository/managing-github-actions-settings-for-a-repository#enabling-workflows-for-private-repository-forks)」を参照してください。