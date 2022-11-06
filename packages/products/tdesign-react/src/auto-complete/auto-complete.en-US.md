:: BASE_DOC ::

## API

### AutoComplete Props

name | type | default | description | required
-- | -- | -- | -- | --
className | String | - | 类名 | N
style | Object | - | 样式，Typescript：`React.CSSProperties` | N
autoFocus | Boolean | - | \- | N
clearable | Boolean | - | \- | N
disabled | Boolean | - | \- | N
filter | Function | - | Typescript：`(filterWords: string, option: T) => boolean \| Promise<boolean>` | N
filterable | Boolean | true | \- | N
highlightKeyword | Boolean | true | \- | N
inputProps | Object | - | Typescript：`InputProps`，[Input API Documents](./input?tab=api)。[see more ts definition](https://github.com/Tencent/tdesign-react/blob/develop/src/auto-complete/type.ts) | N
options | Array | - | Typescript：`Array<T>` | N
placeholder | String | - | \- | N
popupProps | Object | - | Typescript：`PopupProps`，[Popup API Documents](./popup?tab=api)。[see more ts definition](https://github.com/Tencent/tdesign-react/blob/develop/src/auto-complete/type.ts) | N
status | String | - | options：default/success/warning/error | N
textareaProps | Object | - | Typescript：`TextareaProps`，[Textarea API Documents](./textarea?tab=api)。[see more ts definition](https://github.com/Tencent/tdesign-react/blob/develop/src/auto-complete/type.ts) | N
tips | TNode | - | Typescript：`string \| TNode`。[see more ts definition](https://github.com/Tencent/tdesign-react/blob/develop/src/common.ts) | N
value | String | - | \- | N
onBlur | Function |  | Typescript：`(context: { e: FocusEvent; value: InputValue }) => void`<br/> | N
onChange | Function |  | Typescript：`(value: InputValue, context?: { e?: InputEvent \| MouseEvent }) => void`<br/> | N
onClear | Function |  | Typescript：`(context: { e: MouseEvent }) => void`<br/> | N
onCompositionend | Function |  | Typescript：`(context: { e: CompositionEvent; value: InputValue }) => void`<br/>trigger on compositionend | N
onCompositionstart | Function |  | Typescript：`(context: { e: CompositionEvent; value: InputValue }) => void`<br/>trigger on compositionstart | N
onEnter | Function |  | Typescript：`(context: { e: KeyboardEvent; value: InputValue }) => void`<br/> | N
onFocus | Function |  | Typescript：`(context: { e: FocusEvent; value: InputValue }) => void`<br/> | N