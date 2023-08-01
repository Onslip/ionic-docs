### button

|                 |                                                                                                                                                                       |
| --------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Description** | If `true`, a button tag will be rendered and the item will be tappable.<br /><br />自動翻訳: `true`の場合、ボタンタグがレンダリングされ、アイテムはタップ可能になる。 |
| **Attribute**   | `button`                                                                                                                                                              |
| **Type**        | `boolean`                                                                                                                                                             |
| **Default**     | `false`                                                                                                                                                               |

### color

|                 |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| --------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Description** | The color to use from your application's color palette. Default options are: `"primary"`, `"secondary"`, `"tertiary"`, `"success"`, `"warning"`, `"danger"`, `"light"`, `"medium"`, and `"dark"`. For more information on colors, see [theming](/docs/theming/basics).<br /><br />自動翻訳: アプリケーションのカラーパレットから使用する色を指定します。デフォルトのオプションは以下の通りです。一次色"`、二次色"`、三次色"`、成功色"`、警告色"`、危険色"`、明色"`、中色"`、暗色"`です．色に関する詳しい情報は [theming](/docs/theming/basics) を参照してください。 |
| **Attribute**   | `color`                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
| **Type**        | `"danger" ｜ "dark" ｜ "light" ｜ "medium" ｜ "primary" ｜ "secondary" ｜ "success" ｜ "tertiary" ｜ "warning" ｜ string & Record<never, never> ｜ undefined`                                                                                                                                                                                                                                                                                                                                                                                                       |
| **Default**     | `undefined`                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |

### counter

|                 |                                                                                                                                                                                                                                                                                                                                                                                                                   |
| --------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Description** | If `true`, a character counter will display the ratio of characters used and the total character limit. Only applies when the `maxlength` property is set on the inner `ion-input` or `ion-textarea`.<br /><br />自動翻訳: `true`の場合、文字カウンタが使用された文字の比率と総文字数制限を表示します。内側の `ion-input` または `ion-textarea` に `maxlength` プロパティが設定されている場合にのみ適用されます。 |
| **Attribute**   | `counter`                                                                                                                                                                                                                                                                                                                                                                                                         |
| **Type**        | `boolean`                                                                                                                                                                                                                                                                                                                                                                                                         |
| **Default**     | `false`                                                                                                                                                                                                                                                                                                                                                                                                           |

### counterFormatter

|                 |                                                                                                                                                                                                                                                                                               |
| --------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Description** | A callback used to format the counter text. By default the counter text is set to "itemLength / maxLength".<br /><br />自動翻訳: カウンターのテキストをフォーマットするために使用されるコールバックです。デフォルトでは、カウンターのテキストは「itemLength / maxLength」に設定されています。 |
| **Attribute**   | `undefined`                                                                                                                                                                                                                                                                                   |
| **Type**        | `((inputLength: number, maxLength: number) => string) ｜ undefined`                                                                                                                                                                                                                           |
| **Default**     | `undefined`                                                                                                                                                                                                                                                                                   |

### detail

|                 |                                                                                                                                                                                                                                                                                                                             |
| --------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Description** | If `true`, a detail arrow will appear on the item. Defaults to `false` unless the `mode` is `ios` and an `href` or `button` property is present.<br /><br />自動翻訳: `true`の場合、アイテムに詳細矢印が表示されます。デフォルトは `false` で、`mode` が `ios` で `href` または `button` プロパティが存在する場合のみです。 |
| **Attribute**   | `detail`                                                                                                                                                                                                                                                                                                                    |
| **Type**        | `boolean ｜ undefined`                                                                                                                                                                                                                                                                                                      |
| **Default**     | `undefined`                                                                                                                                                                                                                                                                                                                 |

### detailIcon

|                 |                                                                                                                                   |
| --------------- | --------------------------------------------------------------------------------------------------------------------------------- |
| **Description** | The icon to use when `detail` is set to `true`.<br /><br />自動翻訳: detail`が`true` に設定されているときに使用するアイコンです。 |
| **Attribute**   | `detail-icon`                                                                                                                     |
| **Type**        | `string`                                                                                                                          |
| **Default**     | `chevronForward`                                                                                                                  |

### disabled

|                 |                                                                                                                                      |
| --------------- | ------------------------------------------------------------------------------------------------------------------------------------ |
| **Description** | If `true`, the user cannot interact with the item.<br /><br />自動翻訳: `true`の場合、ユーザはそのアイテムと対話することができない。 |
| **Attribute**   | `disabled`                                                                                                                           |
| **Type**        | `boolean`                                                                                                                            |
| **Default**     | `false`                                                                                                                              |

### download

|                 |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| --------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Description** | This attribute instructs browsers to download a URL instead of navigating to it, so the user will be prompted to save it as a local file. If the attribute has a value, it is used as the pre-filled file name in the Save prompt (the user can still change the file name if they want).<br /><br />自動翻訳: この属性は、ブラウザが URL に移動する代わりに URL をダウンロードするように指示し、ユーザはローカルファイルとして保存するように促されます。この属性に値がある場合、保存のプロンプトであらかじめ入力されたファイル名として使用されます（ユーザーはファイル名を変更することができます）。 |
| **Attribute**   | `download`                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
| **Type**        | `string ｜ undefined`                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| **Default**     | `undefined`                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |

### fill

|                 |                                                                                                                                                                                                                                                                                                                                                                     |
| --------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Description** | The fill for the item. If `'solid'` the item will have a background. If `'outline'` the item will be transparent with a border. Only available in `md` mode.<br /><br />自動翻訳: アイテムの塗りつぶし。もし `'solid'` ならば、アイテムは背景を持つようになる。もし `'outline'` ならば、アイテムは透明でボーダーを持つようになります。md`モードでのみ使用可能です。 |
| **Attribute**   | `fill`                                                                                                                                                                                                                                                                                                                                                              |
| **Type**        | `"outline" ｜ "solid" ｜ undefined`                                                                                                                                                                                                                                                                                                                                 |
| **Default**     | `undefined`                                                                                                                                                                                                                                                                                                                                                         |

### href

|                 |                                                                                                                                                                                                                                                                                       |
| --------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Description** | Contains a URL or a URL fragment that the hyperlink points to. If this property is set, an anchor tag will be rendered.<br /><br />自動翻訳: ハイパーリンクが指し示す URL または URL フラグメントを格納する。このプロパティが設定されている場合、アンカータグがレンダリングされます。 |
| **Attribute**   | `href`                                                                                                                                                                                                                                                                                |
| **Type**        | `string ｜ undefined`                                                                                                                                                                                                                                                                 |
| **Default**     | `undefined`                                                                                                                                                                                                                                                                           |

### lines

|                 |                                                                                                                  |
| --------------- | ---------------------------------------------------------------------------------------------------------------- |
| **Description** | How the bottom border should be displayed on the item.<br /><br />自動翻訳: アイテムに表示される下枠の表示方法。 |
| **Attribute**   | `lines`                                                                                                          |
| **Type**        | `"full" ｜ "inset" ｜ "none" ｜ undefined`                                                                       |
| **Default**     | `undefined`                                                                                                      |

### mode

|                 |                                                                                                                                           |
| --------------- | ----------------------------------------------------------------------------------------------------------------------------------------- |
| **Description** | The mode determines which platform styles to use.<br /><br />自動翻訳: モードは、どのプラットフォームのスタイルを使用するかを決定します。 |
| **Attribute**   | `mode`                                                                                                                                    |
| **Type**        | `"ios" ｜ "md"`                                                                                                                           |
| **Default**     | `undefined`                                                                                                                               |

### rel

|                 |                                                                                                                                                                                                                                                                                                                                                                                                |
| --------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Description** | Specifies the relationship of the target object to the link object. The value is a space-separated list of [link types](https://developer.mozilla.org/en-US/docs/Web/HTML/Link_types).<br /><br />自動翻訳: ターゲットオブジェクトとリンクオブジェクトの関係を指定する。値は、スペースで区切られた[リンクタイプ](https://developer.mozilla.org/en-US/docs/Web/HTML/Link_types)のリストである。 |
| **Attribute**   | `rel`                                                                                                                                                                                                                                                                                                                                                                                          |
| **Type**        | `string ｜ undefined`                                                                                                                                                                                                                                                                                                                                                                          |
| **Default**     | `undefined`                                                                                                                                                                                                                                                                                                                                                                                    |

### routerAnimation

|                 |                                                                                                                                                                                                                            |
| --------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Description** | When using a router, it specifies the transition animation when navigating to another page using `href`.<br /><br />自動翻訳: ルータを使用する場合、`href`を使用して別のページに移動する際の遷移アニメーションを指定する。 |
| **Attribute**   | `undefined`                                                                                                                                                                                                                |
| **Type**        | `((baseEl: any, opts?: any) => Animation) ｜ undefined`                                                                                                                                                                    |
| **Default**     | `undefined`                                                                                                                                                                                                                |

### routerDirection

|                 |                                                                                                                                                                                                                  |
| --------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Description** | When using a router, it specifies the transition direction when navigating to another page using `href`.<br /><br />自動翻訳: ルータを使用する場合、`href`を使用して他のページに移動する際の遷移方向を指定する。 |
| **Attribute**   | `router-direction`                                                                                                                                                                                               |
| **Type**        | `"back" ｜ "forward" ｜ "root"`                                                                                                                                                                                  |
| **Default**     | `'forward'`                                                                                                                                                                                                      |

### shape

|                 |                                                                                                                                                                       |
| --------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Description** | The shape of the item. If "round" it will have increased border radius.<br /><br />自動翻訳: アイテムの形状を指定します。円形」の場合、境界線の半径が大きくなります。 |
| **Attribute**   | `shape`                                                                                                                                                               |
| **Type**        | `"round" ｜ undefined`                                                                                                                                                |
| **Default**     | `undefined`                                                                                                                                                           |

### target

|                 |                                                                                                                                                                                                                                                                                                                              |
| --------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Description** | Specifies where to display the linked URL. Only applies when an `href` is provided. Special keywords: `"_blank"`, `"_self"`, `"_parent"`, `"_top"`.<br /><br />自動翻訳: リンク先の URL を表示する場所を指定する。href`を指定した場合のみ適用される。特別なキーワードがあります。_blank"`, `"_self"`, `"_parent"`, `"_top"`. |
| **Attribute**   | `target`                                                                                                                                                                                                                                                                                                                     |
| **Type**        | `string ｜ undefined`                                                                                                                                                                                                                                                                                                        |
| **Default**     | `undefined`                                                                                                                                                                                                                                                                                                                  |

### type

|                 |                                                                                                                                                                                          |
| --------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Description** | The type of the button. Only used when an `onclick` or `button` property is present.<br /><br />自動翻訳: ボタンの種類。onclick`または`button`プロパティが存在する場合にのみ使用される。 |
| **Attribute**   | `type`                                                                                                                                                                                   |
| **Type**        | `"button" ｜ "reset" ｜ "submit"`                                                                                                                                                        |
| **Default**     | `'button'`                                                                                                                                                                               |
