### disabled

|                 |                                                                                                                                 |
| --------------- | ------------------------------------------------------------------------------------------------------------------------------- |
| **Description** | If `true`, the accordion cannot be interacted with.<br /><br />自動翻訳: `true`の場合、アコーディオンは対話することができない。 |
| **Attribute**   | `disabled`                                                                                                                      |
| **Type**        | `boolean`                                                                                                                       |
| **Default**     | `false`                                                                                                                         |

### mode

|                 |                                                                                                                                           |
| --------------- | ----------------------------------------------------------------------------------------------------------------------------------------- |
| **Description** | The mode determines which platform styles to use.<br /><br />自動翻訳: モードは、どのプラットフォームのスタイルを使用するかを決定します。 |
| **Attribute**   | `mode`                                                                                                                                    |
| **Type**        | `"ios" ｜ "md"`                                                                                                                           |
| **Default**     | `undefined`                                                                                                                               |

### readonly

|                 |                                                                                                                                                                                                               |
| --------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Description** | If `true`, the accordion cannot be interacted with, but does not alter the opacity.<br /><br />自動翻訳: `true`の場合、アコーディオンはインタラクティブに操作することはできませんが、不透明度は変化しません。 |
| **Attribute**   | `readonly`                                                                                                                                                                                                    |
| **Type**        | `boolean`                                                                                                                                                                                                     |
| **Default**     | `false`                                                                                                                                                                                                       |

### toggleIcon

|                 |                                                                                                                                                                                                                    |
| --------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **Description** | The toggle icon to use. This icon will be rotated when the accordion is expanded or collapsed.<br /><br />自動翻訳: 使用するトグルアイコンです。このアイコンは、アコーディオンの展開・折りたたみ時に回転されます。 |
| **Attribute**   | `toggle-icon`                                                                                                                                                                                                      |
| **Type**        | `string`                                                                                                                                                                                                           |
| **Default**     | `chevronDown`                                                                                                                                                                                                      |

### toggleIconSlot

|                 |                                                                                                                                                                                     |
| --------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Description** | The slot inside of `ion-item` to place the toggle icon. Defaults to `'end'`.<br /><br />自動翻訳: トグルアイコンを配置する `ion-item` の内側のスロット。デフォルトは `'end'` です。 |
| **Attribute**   | `toggle-icon-slot`                                                                                                                                                                  |
| **Type**        | `"end" ｜ "start"`                                                                                                                                                                  |
| **Default**     | `'end'`                                                                                                                                                                             |

### value

|                 |                                                                                                                                                 |
| --------------- | ----------------------------------------------------------------------------------------------------------------------------------------------- |
| **Description** | The value of the accordion. Defaults to an autogenerated value.<br /><br />自動翻訳: アコーディオンの値です。デフォルトは自動生成された値です。 |
| **Attribute**   | `value`                                                                                                                                         |
| **Type**        | `string`                                                                                                                                        |
| **Default**     | `ion-accordion-${accordionIds++}`                                                                                                               |
