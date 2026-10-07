# Bundled font licenses

The SVGs embed two WOFF2 fonts as base64 data URLs so they do not make external font requests.

- **Inter Display Bold** — Copyright 2016 The Inter Project Authors. SIL Open Font License 1.1.
- **Noto Sans Mono Regular** — Copyright 2015 Google LLC. SIL Open Font License 1.1.

## SIL Open Font License 1.1

Copyright (c) 2016 The Inter Project Authors
Copyright (c) 2015 Google LLC

Permission is hereby granted, free of charge, to any person obtaining a copy of the Font Software, to use, study, copy, merge, embed, modify, redistribute, and sell modified and unmodified copies of the Font Software, subject to the following conditions:

1. Neither the Font Software nor any of its individual components, in Original or Modified Versions, may be sold by itself.
2. Original or Modified Versions of the Font Software may be bundled, redistributed and/or sold with any software, provided that the above copyright notice and this license are retained.
3. The Font Software, modified or unmodified, in whole or in part, must not be distributed under a license that does not comply with the terms of this license.

THE FONT SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO ANY WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.

The bundled fonts were converted to WOFF2 for self-contained SVG embedding; the font contents were not modified beyond format conversion.

## Social icon note

The connect SVG uses compact platform monograms (`GH`, `in`, `ig`, `@`) rather than externally fetched brand SVGs. This keeps the README completely self-contained and avoids making unverified third-party asset requests. The Simple Icons project is a CC0-1.0 icon library; if you later want exact Simple Icons paths, they can be substituted without changing the layout. Source: Simple Icons project.

## Stack marks

The Stack SVG embeds Simple Icons paths for the available technology brands. Simple Icons is distributed under CC0-1.0: [Simple Icons project](https://github.com/simple-icons/simple-icons). The Visual Studio Code mark is from [Microsoft's Visual Studio documentation assets](https://github.com/MicrosoftDocs/visualstudio-docs/blob/main/docs/media/vs-code-logo.svg). Generic concepts such as forecasting, APIs, and architecture use small custom vector symbols. All marks are embedded in `assets/stack.svg`; rendering makes no network requests.
