# Typescript Cheatsheet for React
A cheatsheet of useful react types because it seems I can never remember them all 🙄

## Forms
### `<input>`

| Prop | Type |
| :----------- | :----------------- |
| onChange | `(e: React.ChangeEvent<HTMLInputElement>) => any` |
| value | `string` |

## Third-Party
### [react-select](https://github.com/JedWatson/react-select)

| Prop | Type |
| :----------- | :----------------- |
| defaultValue | `{ value: string, label: string }` |
| onChange | `(result: { value: string, label: string }) => any` |
| options | `{ value: string, label: string }[]` |
| value | `{ value: string, label: string }` |

### [react-daterange-picker](https://github.com/wojtekmaj/react-daterange-picker)

| Prop | Type |
| :----------- | :----------------- |
| onChange | `(result: Date[]) => any` |
| value | `Date[]` |

