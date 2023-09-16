# Chrome is hanging on `aria-own`/`aria-hidden`/`display` property

`aria-owns` attribute causes Chrome to hang in some-case.

## Steps to reproduce

1. Visit https://azu.github.io/chrome-is-hanging-when-aria-owns-toggle-aria-hidden-display/
2. Click "Click me and Hang"
3. Chrome is hanging(CPU 100%)

## Tested environment

- Chrome 117.0.5938.62（Official Build） （arm64） - hang
- Chrome 118.0.5993.11（Official Build）dev （arm64） - hang
- Chrome Canary 119.0.6010.2（Official Build）canary （arm64）- crash

## License

MIT
