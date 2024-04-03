+++
author = "Roshan Patel"
title = "Cloudflare Workers-rs"
date = "2024-03-01"
description = "[open repo](https://github.com/cloudflare/workers-rs)"
+++

Rust bindings for a serverless edge computing platform. <!--more-->Contributor to a project by Cloudflare called workers-rs. The project seeks to provide Rust bindings to the existing [Workers platform](https://developers.cloudflare.com/workers/). My work primarily consisted of using [WebAssembly](https://webassembly.org/) to create analogues to the original platform's functionality. This involved integrating support for concurrency by allowing for asynchronous and parallel code using [Tokio](https://tokio.rs/). I also refactored portions of the project using custom HTML types and handlers to use a modern open-source library instead.

{{< css.inline >}}
<style>
.canon { background: white; width: 100%; height: auto; }
</style>
{{< /css.inline >}}