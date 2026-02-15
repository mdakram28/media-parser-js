# Media Parser JS

TypeScript/JavaScript library to parse multimedia bitstreams (MP4, AV1, HEVC, IVF). Extract frames from files and access syntax elements.

## Installation

```bash
npm install media-parser-js
```

## Usage

```javascript
import { parseMP4, parseAV1 } from 'media-parser-js';

// Parse MP4 container
const mp4 = parseMP4(buffer);

// Parse AV1 bitstream
const av1 = parseAV1(buffer);
```

## Supported formats

- **MP4** (ISOBMFF)
- **AV1** (OBU)
- **HEVC** (NAL units)
- **IVF** (VP8/VP9 container)

## Links

- [media-parser-gui](https://github.com/mdakram28/media-parser-gui) — Browser-based parser GUI using this library
- [npm](https://www.npmjs.com/package/media-parser-js)

## License

MIT
