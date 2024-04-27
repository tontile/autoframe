# autoframe

An iframe component that automatically syncs styles from the host.

An implementation of [react-frame-component](https://github.com/ryanseddon/react-frame-component).

## Quick start

```sh
npm i @tontile/autoframe
```

```jsx
import AutoFrame from "@tontile/autoframe";

export function Page() {
  return (
    <AutoFrame>
      {/* Hero class exists on parent */}
      <div className="Hero">Hello, world</div>
    </AutoFrame>
  );
}
```

## API

Shares an API with [react-frame-component](https://github.com/ryanseddon/react-frame-component), and exposes some additional props.

### debug

`debug: boolean`

Print debug messages when mounting styles to the console

### onStylesLoaded

`onStylesLoaded: function`

A callback that triggers when the initial styles [are loaded](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/link#stylesheet_load_events)

## License

MIT © [TonTile Corporation Ltd](https://tontile.io)
