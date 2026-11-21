> [!IMPORTANT]
> **Replaced by [`@arraypress/waveform-svelte`](https://www.npmjs.com/package/@arraypress/waveform-svelte) 2.0.** Import from `@arraypress/waveform-svelte/bar` instead — one package per framework, with a sub-path per component ([repo](https://github.com/WaveformPlayer/svelte), [migration guide](https://docs.waveformplayer.com/getting-started/migrating-from-1x/)).
> This repository is archived and the npm package is deprecated; its 1.x releases keep working.

<div align="center">

# Waveform Bar for Svelte

**Svelte 5 components for the persistent bottom-bar audio player.**
Render `<WaveformBar />` once, then drop `<WaveformBarTrigger />` anywhere you want a "play this track" element.

[![npm version](https://img.shields.io/npm/v/@arraypress/waveform-bar-svelte?style=flat-square&labelColor=09090b&color=3f3f46)](https://www.npmjs.com/package/@arraypress/waveform-bar-svelte)
[![license](https://img.shields.io/npm/l/@arraypress/waveform-bar-svelte?style=flat-square&labelColor=09090b&color=3f3f46)](https://github.com/arraypress)

**[Documentation](https://docs.waveformplayer.com/)** &middot; [npm](https://www.npmjs.com/package/@arraypress/waveform-bar-svelte)

</div>

---

## Install

```bash
npm install @arraypress/waveform-bar-svelte @arraypress/waveform-bar @arraypress/waveform-player svelte
```

```svelte
<script lang="ts">
  import { WaveformBar, WaveformBarTrigger } from '@arraypress/waveform-bar-svelte';
</script>

<!-- render ONCE in your root layout -->
<WaveformBar config={{ persist: true, continuous: true }} />

<!-- drop triggers anywhere -->
<WaveformBarTrigger url="/audio/track.mp3" title="My Track" artist="The Artist" />
```

## Documentation

Full guides, props, and the imperative API live on the docs site.

### -> [docs.waveformplayer.com](https://docs.waveformplayer.com/)

[Svelte guide](https://docs.waveformplayer.com/frameworks/svelte/) — install, props, the imperative API, and SSR notes. All four Svelte wrappers (player / bar / playlist) are on that page.

## License

MIT © [ArrayPress](https://github.com/arraypress)
