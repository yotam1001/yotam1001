# Yotam Moshe

Student developer in Israel. I build practical tools in Python, C# and JavaScript, and contribute fixes to open-source projects.

My interests are systems programming, cybersecurity and understanding how software behaves when things go wrong. My projects include file integrity checks, isolated Git command previews, offline desktop applications and browser graphics.

## Selected projects

| Project | What it does | Technical evidence |
| --- | --- | --- |
| **[File Integrity Timeline](https://github.com/yotam1001/file-integrity-timeline)** | Tracks added, missing and changed files against trusted SHA-256 baselines. | Python, SQLite scan history, streaming hashing, incomplete-scan handling, GUI and CLI. [Core](https://github.com/yotam1001/file-integrity-timeline/blob/main/file_integrity_timeline/core.py) · [Tests](https://github.com/yotam1001/file-integrity-timeline/blob/main/tests/test_core.py) |
| **[Git Impact](https://github.com/yotam1001/git-impact)** | Previews what `git reset` would change in staging, working files and history. | Temporary Git sandbox, configuration isolation, source-state checks and tests against actual Git operations. [Core](https://github.com/yotam1001/git-impact/blob/main/gitimpact/core.py) · [Live example](https://yotam1001.github.io/git-impact/) |
| **[Offline Drive Gallery](https://github.com/yotam1001/offline-drive-gallery)** | Searches files and stored thumbnails after a drive is disconnected. | C#/.NET, SQLite, Windows Shell integration, cancellable scans and transaction rollback. [Catalog](https://github.com/yotam1001/offline-drive-gallery/blob/main/src/OfflineDriveGallery.Core/Catalog.cs) · [Tests](https://github.com/yotam1001/offline-drive-gallery/tree/main/tests/OfflineDriveGallery.Tests) |
| **[Schwarzschild Ray Tracer](https://github.com/yotam1001/schwarzschild-ray-tracer)** | Renders a non-rotating black hole in real time in the browser. | React, Three.js, WebGL2, GLSL and geodesic lookup tables adapted from published work, with attribution. [Shaders](https://github.com/yotam1001/schwarzschild-ray-tracer/blob/main/src/simulation/physics/schwarzschildShaders.js) · [Model and limits](https://github.com/yotam1001/schwarzschild-ray-tracer#physical-model) |

Also: **[OverlapAtlas](https://github.com/yotam1001/overlapatlas)** compares folder trees by file content using SHA-256 and Jaccard similarity. **[Campus Live Subtitles](https://github.com/yotam1001/campus-live-subtitles)** connects a Chrome audio-capture extension to local Whisper transcription for Hebrew subtitles.

## Upstream contributions

- **[pycubrid #515 — merged](https://github.com/cubrid-lab/pycubrid/pull/515):** reject malformed qualified stored-procedure names before SQL execution, with regression tests for synchronous and asynchronous cursors.
- **[text-enhancer #8 — merged](https://github.com/eladmoshe/text-enhancer/pull/8):** use configured token limits and timeouts in Swift API clients, with provider request tests.
- **[dnp3py #214 — open](https://github.com/craigpnnl/dnp3py/pull/214):** preserve the no-acknowledgement response policy for unsupported DNP3 requests, with protocol regression tests.
- **[Karakeep #3132 — open](https://github.com/karakeep-app/karakeep/pull/3132):** add opt-in recent-article retention for mobile offline reading, with cancellation, account isolation, download restrictions and cleanup tests.

The linked PRs document validation, limitations and AI assistance. Open contributions are still under review.

## What I am studying

C and memory, C# and object-oriented programming, Linux and operating systems, networking, web fundamentals and security. I use small projects, code tracing and debugging to connect the concepts to working software.

For a quick technical review, start with **File Integrity Timeline**, **Git Impact**, and the merged **pycubrid** contribution above.
