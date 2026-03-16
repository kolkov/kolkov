# Hi there, I'm Andrey Kolkov 👋

Go Systems Engineer | Open Source Architect | 35+ Projects, 1500+ Stars | 10 Projects in awesome-go

---

## About Me

I build production-grade open-source infrastructure in pure Go — from GPU graphics and ML frameworks to regex engines and scientific computing libraries. My focus is on solving problems where Go was traditionally considered weak: GPU computing, machine learning, high-performance text processing, and scientific file formats.

Every project follows a strict quality bar: zero CGO dependencies, 70-95% test coverage, zero linter issues, and production-ready from day one.

### Core Technologies

**Backend & Systems**
- **Go 1.25+** - Primary language, pure Go implementations (zero CGO)
- **GPU Computing** - WebGPU, Vulkan, shader compilers
- **High-Performance** - SIMD assembly, zero-allocation hot paths
- **PostgreSQL, MySQL 8.0+, SQLite** - Database design and optimization

**Frontend**
- **Angular** (6-19+) - Component architecture, WYSIWYG editors
- **TypeScript** - Type-safe development
- **NX** - Monorepo tooling

**Quality Standards**
- 70-95% code coverage across all projects
- Zero linter issues policy (golangci-lint)
- Pure Go — no CGO, easy cross-compilation
- Type-safe APIs with Go 1.25+ generics

### From Enterprise to Open Source

Most projects here started as battle-tested internal code. Over 2025-2026, I've been systematically extracting reusable components, refining them into standalone libraries, and publishing them. The result: 35+ projects across 12 organizations, covering GPU graphics, machine learning, scientific computing, web infrastructure, and system tools.

I write about AI-assisted development methodology on [dev.to](https://dev.to/kolkov) — including the concept of **Smart Coding**, a framework for disciplined AI collaboration that I introduced before Karpathy coined "Agentic Engineering".

---

## Featured Projects

### 🌟 Most Popular

#### [angular-editor](https://github.com/kolkov/angular-editor) - Angular Editor
> Native WYSIWYG/Rich Text editor for Angular 6-19+

[![Angular](https://img.shields.io/badge/Angular-6--19%2B-DD0031?style=flat-square&logo=angular&logoColor=white)](https://github.com/kolkov/angular-editor)
[![npm version](https://img.shields.io/npm/v/@kolkov/angular-editor?style=flat-square&logo=npm)](https://www.npmjs.com/package/@kolkov/angular-editor)
[![Activity](https://img.shields.io/github/last-commit/kolkov/angular-editor?style=flat-square&logo=github&label=activity)](https://github.com/kolkov/angular-editor/commits)
[![GitHub stars](https://img.shields.io/github/stars/kolkov/angular-editor?style=flat-square&logo=github)](https://github.com/kolkov/angular-editor/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/kolkov/angular-editor?style=flat-square&logo=github)](https://github.com/kolkov/angular-editor/network/members)
[![GitHub issues](https://img.shields.io/github/issues/kolkov/angular-editor?style=flat-square&logo=github)](https://github.com/kolkov/angular-editor/issues)
[![GitHub PRs](https://img.shields.io/github/issues-pr/kolkov/angular-editor?style=flat-square&logo=github&label=PRs)](https://github.com/kolkov/angular-editor/pulls)

A lightweight, highly customizable text editor component without external dependencies. Features include visual/HTML modes, image uploads, theming with CSS variables, and full Angular Forms integration. **Launched:** May 2018

**Tech**: Angular, TypeScript, SCSS | **Status**: Active development

---

### 🚀 Flagship Projects

#### [phoenix](https://github.com/phoenix-tui/phoenix) - Phoenix TUI Framework
> High-performance Terminal UI framework for Go

[![Go Version](https://img.shields.io/github/go-mod/go-version/phoenix-tui/phoenix?style=flat-square&logo=go)](https://github.com/phoenix-tui/phoenix)
[![GitHub release](https://img.shields.io/github/v/release/phoenix-tui/phoenix?style=flat-square)](https://github.com/phoenix-tui/phoenix/releases)
[![Activity](https://img.shields.io/github/last-commit/phoenix-tui/phoenix?style=flat-square&logo=github&label=activity)](https://github.com/phoenix-tui/phoenix/commits)
[![GitHub stars](https://img.shields.io/github/stars/phoenix-tui/phoenix?style=flat-square&logo=github)](https://github.com/phoenix-tui/phoenix/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/phoenix-tui/phoenix?style=flat-square&logo=github)](https://github.com/phoenix-tui/phoenix/network/members)
[![GitHub issues](https://img.shields.io/github/issues/phoenix-tui/phoenix?style=flat-square&logo=github)](https://github.com/phoenix-tui/phoenix/issues)
[![GitHub PRs](https://img.shields.io/github/issues-pr/phoenix-tui/phoenix?style=flat-square&logo=github&label=PRs)](https://github.com/phoenix-tui/phoenix/pulls)

A next-generation TUI framework featuring Domain-Driven Design architecture, perfect Unicode/emoji support, and Elm-inspired patterns. Achieves 10x performance improvement (29,000 FPS) with differential rendering. **Launched:** October 2025

**Highlights**:
- 91.8% test coverage
- 10x faster than alternatives
- Zero external dependencies
- Cross-platform mouse & clipboard support

**Tech**: Go 1.25+, DDD architecture | **Status**: Production-ready

---

#### [hdf5](https://github.com/scigolib/hdf5) - HDF5 for Go
> Pure Go implementation of HDF5 file format

[![Go Version](https://img.shields.io/github/go-mod/go-version/scigolib/hdf5?style=flat-square&logo=go)](https://github.com/scigolib/hdf5)
[![GitHub release](https://img.shields.io/github/v/release/scigolib/hdf5?style=flat-square)](https://github.com/scigolib/hdf5/releases)
[![Activity](https://img.shields.io/github/last-commit/scigolib/hdf5?style=flat-square&logo=github&label=activity)](https://github.com/scigolib/hdf5/commits)
[![GitHub stars](https://img.shields.io/github/stars/scigolib/hdf5?style=flat-square&logo=github)](https://github.com/scigolib/hdf5/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/scigolib/hdf5?style=flat-square&logo=github)](https://github.com/scigolib/hdf5/network/members)
[![GitHub issues](https://img.shields.io/github/issues/scigolib/hdf5?style=flat-square&logo=github)](https://github.com/scigolib/hdf5/issues)
[![GitHub PRs](https://img.shields.io/github/issues-pr/scigolib/hdf5?style=flat-square&logo=github&label=PRs)](https://github.com/scigolib/hdf5/pulls)

Modern HDF5 library with no CGO dependencies. Passes 98.2% of official HDF5 test suite (380/387 files). Supports AI/ML datatypes (FP8, bfloat16) and achieves 10-250x faster hyperslab selections. **Launched:** November 2025

**Highlights**:
- Zero C dependencies
- Full HDF5 2.0.0 compatibility
- Security hardening (4 CVEs fixed)
- 86.1% code coverage

**Tech**: Pure Go 1.25+ | **Status**: Production-ready

---

#### [racedetector](https://github.com/kolkov/racedetector) - Pure Go Race Detector
> Production-ready race detector in pure Go without CGO

[![Go Version](https://img.shields.io/github/go-mod/go-version/kolkov/racedetector?style=flat-square&logo=go)](https://github.com/kolkov/racedetector)
[![GitHub release](https://img.shields.io/github/v/release/kolkov/racedetector?style=flat-square)](https://github.com/kolkov/racedetector/releases)
[![Activity](https://img.shields.io/github/last-commit/kolkov/racedetector?style=flat-square&logo=github&label=activity)](https://github.com/kolkov/racedetector/commits)
[![GitHub stars](https://img.shields.io/github/stars/kolkov/racedetector?style=flat-square&logo=github)](https://github.com/kolkov/racedetector/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/kolkov/racedetector?style=flat-square&logo=github)](https://github.com/kolkov/racedetector/network/members)
[![GitHub issues](https://img.shields.io/github/issues/kolkov/racedetector?style=flat-square&logo=github)](https://github.com/kolkov/racedetector/issues)
[![GitHub PRs](https://img.shields.io/github/issues-pr/kolkov/racedetector?style=flat-square&logo=github&label=PRs)](https://github.com/kolkov/racedetector/pulls)

Solves the 10-year limitation where Go's race detector required C++ ThreadSanitizer. Multi-algorithm approach (FastTrack, escape analysis, shadow memory, vector clocks) with 260x memory optimization. **Launched:** November 2025

**Highlights**:
- Works with `CGO_ENABLED=0` on all platforms
- Drop-in replacement for `go build -race`
- 70+ tests, 45-92% coverage
- Multiple research papers implemented

**Tech**: Pure Go, AST instrumentation | **Status**: v0.8.4 Active development

---

#### [uawk](https://github.com/kolkov/uawk) - Ultra AWK Interpreter
> High-performance AWK interpreter — up to 19x faster than GoAWK

[![Go Version](https://img.shields.io/github/go-mod/go-version/kolkov/uawk?style=flat-square&logo=go)](https://github.com/kolkov/uawk)
[![GitHub release](https://img.shields.io/github/v/release/kolkov/uawk?style=flat-square)](https://github.com/kolkov/uawk/releases)
[![Activity](https://img.shields.io/github/last-commit/kolkov/uawk?style=flat-square&logo=github&label=activity)](https://github.com/kolkov/uawk/commits)
[![GitHub stars](https://img.shields.io/github/stars/kolkov/uawk?style=flat-square&logo=github)](https://github.com/kolkov/uawk/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/kolkov/uawk?style=flat-square&logo=github)](https://github.com/kolkov/uawk/network/members)
[![GitHub issues](https://img.shields.io/github/issues/kolkov/uawk?style=flat-square&logo=github)](https://github.com/kolkov/uawk/issues)
[![GitHub PRs](https://img.shields.io/github/issues-pr/kolkov/uawk?style=flat-square&logo=github&label=PRs)](https://github.com/kolkov/uawk/pulls)

Ultra-fast AWK interpreter leveraging coregex engine for dramatic performance gains. NFA/DFA hybrid regex achieves 19x faster pattern matching compared to GoAWK. Designed for text processing, log analysis, and data transformation. **Launched:** January 2026

**Performance**:
- 19x faster than GoAWK on /BEGIN patterns
- 2.8x faster simple field operations
- 4.7x faster regex field matching
- NFA/DFA hybrid regex engine (coregex-powered)

**Tech**: Pure Go 1.25+ | **Status**: v0.2.2 Active development

---

#### [relica](https://github.com/coregx/relica) - Relica Query Builder
> Type-safe database query builder for Go with zero production dependencies

[![Go Version](https://img.shields.io/github/go-mod/go-version/coregx/relica?style=flat-square&logo=go)](https://github.com/coregx/relica)
[![GitHub release](https://img.shields.io/github/v/release/coregx/relica?style=flat-square)](https://github.com/coregx/relica/releases)
[![Activity](https://img.shields.io/github/last-commit/coregx/relica?style=flat-square&logo=github&label=activity)](https://github.com/coregx/relica/commits)
[![GitHub stars](https://img.shields.io/github/stars/coregx/relica?style=flat-square&logo=github)](https://github.com/coregx/relica/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/coregx/relica?style=flat-square&logo=github)](https://github.com/coregx/relica/network/members)
[![GitHub issues](https://img.shields.io/github/issues/coregx/relica?style=flat-square&logo=github)](https://github.com/coregx/relica/issues)
[![GitHub PRs](https://img.shields.io/github/issues-pr/coregx/relica?style=flat-square&logo=github&label=PRs)](https://github.com/coregx/relica/pulls)

Zero production dependencies, type-safe reflection-based struct scanning. High performance with LRU statement cache and batch operations (3.3x faster). Full ACID transaction support with all isolation levels. **Launched:** November 2025

**Features**:
- PostgreSQL, MySQL 8.0+, SQLite 3.25+ support
- Expression API for type-safe WHERE clauses
- Multiple JOIN types, CTEs, subqueries
- 326+ tests, 93.3% coverage

**Tech**: Pure Go 1.25+ | **Status**: Active development

---

#### [fursy](https://github.com/coregx/fursy) - FURSY HTTP Router
> Next-generation HTTP router for Go with type-safe handlers and OpenAPI generation

[![Go Version](https://img.shields.io/github/go-mod/go-version/coregx/fursy?style=flat-square&logo=go)](https://github.com/coregx/fursy)
[![GitHub release](https://img.shields.io/github/v/release/coregx/fursy?style=flat-square)](https://github.com/coregx/fursy/releases)
[![Activity](https://img.shields.io/github/last-commit/coregx/fursy?style=flat-square&logo=github&label=activity)](https://github.com/coregx/fursy/commits)
[![GitHub stars](https://img.shields.io/github/stars/coregx/fursy?style=flat-square&logo=github)](https://github.com/coregx/fursy/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/coregx/fursy?style=flat-square&logo=github)](https://github.com/coregx/fursy/network/members)
[![GitHub issues](https://img.shields.io/github/issues/coregx/fursy?style=flat-square&logo=github)](https://github.com/coregx/fursy/issues)
[![GitHub PRs](https://img.shields.io/github/issues-pr/coregx/fursy?style=flat-square&logo=github&label=PRs)](https://github.com/coregx/fursy/pulls)

Type-safe generic handlers using Box[Req, Res] pattern. High-performance routing (~10M req/s throughput, 256-326 ns/op). Automatic validation with 100+ supported tags. **Launched:** November 2025

**Features**:
- Built-in OpenAPI 3.1 spec generation
- RFC 9457 Problem Details for errors
- 8 middleware: Logger, Recovery, CORS, JWT, Rate limiting, Circuit breaker
- Zero external dependencies for core routing

**Tech**: Go 1.25+ | **Status**: Production-ready | **Coverage**: 93.1%

---

#### [signals](https://github.com/coregx/signals) - Signals for Go
> Type-safe reactive state management inspired by Angular Signals

[![Go Version](https://img.shields.io/github/go-mod/go-version/coregx/signals?style=flat-square&logo=go)](https://github.com/coregx/signals)
[![GitHub release](https://img.shields.io/github/v/release/coregx/signals?style=flat-square)](https://github.com/coregx/signals/releases)
[![Activity](https://img.shields.io/github/last-commit/coregx/signals?style=flat-square&logo=github&label=activity)](https://github.com/coregx/signals/commits)
[![GitHub stars](https://img.shields.io/github/stars/coregx/signals?style=flat-square&logo=github)](https://github.com/coregx/signals/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/coregx/signals?style=flat-square&logo=github)](https://github.com/coregx/signals/network/members)
[![GitHub issues](https://img.shields.io/github/issues/coregx/signals?style=flat-square&logo=github)](https://github.com/coregx/signals/issues)
[![GitHub PRs](https://img.shields.io/github/issues-pr/coregx/signals?style=flat-square&logo=github&label=PRs)](https://github.com/coregx/signals/pulls)

Angular Signals pattern for Go with zero-allocation hot paths (0.51 ns/op Signal.Get). Thread-safe operations with fine-grained reactivity and glitch-free execution. **Launched:** November 2024

**Features**:
- Pure Go with zero external dependencies
- Lazy evaluation for computed values
- Effect batching for multiple updates
- Angular API compatibility

**Tech**: Go 1.25+ | **Status**: Stable | **Coverage**: 67.9%

---

#### [pubsub](https://github.com/coregx/pubsub) - PubSub Messaging
> Production-ready publish-subscribe library with guaranteed delivery and Dead Letter Queue

[![Go Version](https://img.shields.io/github/go-mod/go-version/coregx/pubsub?style=flat-square&logo=go)](https://github.com/coregx/pubsub)
[![GitHub release](https://img.shields.io/github/v/release/coregx/pubsub?include_prereleases&style=flat-square)](https://github.com/coregx/pubsub/releases)
[![Activity](https://img.shields.io/github/last-commit/coregx/pubsub?style=flat-square&logo=github&label=activity)](https://github.com/coregx/pubsub/commits)
[![GitHub stars](https://img.shields.io/github/stars/coregx/pubsub?style=flat-square&logo=github)](https://github.com/coregx/pubsub/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/coregx/pubsub?style=flat-square&logo=github)](https://github.com/coregx/pubsub/network/members)
[![GitHub issues](https://img.shields.io/github/issues/coregx/pubsub?style=flat-square&logo=github)](https://github.com/coregx/pubsub/issues)
[![GitHub PRs](https://img.shields.io/github/issues-pr/coregx/pubsub?style=flat-square&logo=github&label=PRs)](https://github.com/coregx/pubsub/pulls)

Reliable message delivery with exponential backoff retry logic and automatic Dead Letter Queue handling. Battle-tested in FreiCON Railway Management System. Supports deployment as library or standalone microservice. **Launched:** November 2025

**Features**:
- Guaranteed delivery with progressive retry delays (30s → 30m max)
- Dead Letter Queue with failure tracking and statistics
- Domain-Driven Design with Repository Pattern
- Multi-database support (MySQL, PostgreSQL, SQLite via Relica)
- Standalone REST API microservice or embeddable library
- Cloud-native with Docker support and health checks

**Tech**: Go 1.25+ | **Status**: v0.1.0 | **Coverage**: 95.9%

---

#### [stream](https://github.com/coregx/stream) - Real-time Communications
> RFC-compliant Server-Sent Events and WebSocket for Go

[![Go Version](https://img.shields.io/github/go-mod/go-version/coregx/stream?style=flat-square&logo=go)](https://github.com/coregx/stream)
[![GitHub release](https://img.shields.io/github/v/release/coregx/stream?style=flat-square)](https://github.com/coregx/stream/releases)
[![Activity](https://img.shields.io/github/last-commit/coregx/stream?style=flat-square&logo=github&label=activity)](https://github.com/coregx/stream/commits)
[![GitHub stars](https://img.shields.io/github/stars/coregx/stream?style=flat-square&logo=github)](https://github.com/coregx/stream/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/coregx/stream?style=flat-square&logo=github)](https://github.com/coregx/stream/network/members)
[![GitHub issues](https://img.shields.io/github/issues/coregx/stream?style=flat-square&logo=github)](https://github.com/coregx/stream/issues)
[![GitHub PRs](https://img.shields.io/github/issues-pr/coregx/stream?style=flat-square&logo=github&label=PRs)](https://github.com/coregx/stream/pulls)

Production-ready SSE (RFC text/event-stream) and WebSocket (RFC 6455) implementations. High performance with <100μs latency and zero external dependencies. **Launched:** November 2025

**Features**:
- Named event types, event IDs for reconnection
- Text/binary messages, control frames
- Broadcasting hub for multi-client
- 314 tests, 84.3% coverage

**Tech**: Go 1.25+ | **Status**: Production-ready

---

#### [coregex](https://github.com/coregx/coregex) - High-Performance Regex
> Multi-engine regex up to 263x faster than stdlib with SIMD optimizations

[![Go Version](https://img.shields.io/github/go-mod/go-version/coregx/coregex?style=flat-square&logo=go)](https://github.com/coregx/coregex)
[![GitHub release](https://img.shields.io/github/v/release/coregx/coregex?style=flat-square)](https://github.com/coregx/coregex/releases)
[![Activity](https://img.shields.io/github/last-commit/coregx/coregex?style=flat-square&logo=github&label=activity)](https://github.com/coregx/coregex/commits)
[![GitHub stars](https://img.shields.io/github/stars/coregx/coregex?style=flat-square&logo=github)](https://github.com/coregx/coregex/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/coregx/coregex?style=flat-square&logo=github)](https://github.com/coregx/coregex/network/members)
[![GitHub issues](https://img.shields.io/github/issues/coregx/coregex?style=flat-square&logo=github)](https://github.com/coregx/coregex/issues)
[![GitHub PRs](https://img.shields.io/github/issues-pr/coregx/coregex?style=flat-square&logo=github&label=PRs)](https://github.com/coregx/coregex/pulls)

Multi-engine regex inspired by Rust's regex crate: Thompson NFA, Pike VM, one-pass DFA, bounded backtracker with meta-engine. AVX2/SSSE3 SIMD assembly. Prefilter coordination (memchr, memmem, teddy, Aho-Corasick). **Launched:** November 2025

**Performance**:
- Up to 263x faster than stdlib (case-insensitive patterns)
- 3-3000x faster depending on pattern complexity
- 30-50x faster log parsing with prefilters
- SIMD memchr: 12.3x faster on 64KB input

**Tech**: Go 1.25+, AMD64 SIMD | **Status**: v0.12.3 Production-ready

---

#### [ahocorasick](https://github.com/coregx/ahocorasick) - High-Performance Multi-Pattern Matching
> Aho-Corasick algorithm for Go — 1.6 GB/s throughput, zero allocations

[![Go Version](https://img.shields.io/github/go-mod/go-version/coregx/ahocorasick?style=flat-square&logo=go)](https://github.com/coregx/ahocorasick)
[![GitHub release](https://img.shields.io/github/v/release/coregx/ahocorasick?style=flat-square)](https://github.com/coregx/ahocorasick/releases)
[![Activity](https://img.shields.io/github/last-commit/coregx/ahocorasick?style=flat-square&logo=github&label=activity)](https://github.com/coregx/ahocorasick/commits)
[![GitHub stars](https://img.shields.io/github/stars/coregx/ahocorasick?style=flat-square&logo=github)](https://github.com/coregx/ahocorasick/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/coregx/ahocorasick?style=flat-square&logo=github)](https://github.com/coregx/ahocorasick/network/members)
[![GitHub issues](https://img.shields.io/github/issues/coregx/ahocorasick?style=flat-square&logo=github)](https://github.com/coregx/ahocorasick/issues)
[![GitHub PRs](https://img.shields.io/github/issues-pr/coregx/ahocorasick?style=flat-square&logo=github&label=PRs)](https://github.com/coregx/ahocorasick/pulls)

High-performance Aho-Corasick multi-pattern string matching with 1.6 GB/s IsMatch and 1.1 GB/s Find throughput. Optimized for large pattern sets with efficient memory layout and failure link traversal. **Launched:** January 2026

**Performance**:
- IsMatch: 1.6 GB/s throughput
- Find: 1.1 GB/s throughput
- Zero allocations per search
- Efficient for large pattern dictionaries

**Tech**: Pure Go 1.25+ | **Status**: v0.1.0 Stable

---

#### [gxpdf](https://github.com/coregx/gxpdf) - Enterprise PDF Library
> Create and read PDF documents — 100% table extraction accuracy, DDD architecture

[![Go Version](https://img.shields.io/github/go-mod/go-version/coregx/gxpdf?style=flat-square&logo=go)](https://github.com/coregx/gxpdf)
[![GitHub release](https://img.shields.io/github/v/release/coregx/gxpdf?style=flat-square)](https://github.com/coregx/gxpdf/releases)
[![Activity](https://img.shields.io/github/last-commit/coregx/gxpdf?style=flat-square&logo=github&label=activity)](https://github.com/coregx/gxpdf/commits)
[![GitHub stars](https://img.shields.io/github/stars/coregx/gxpdf?style=flat-square&logo=github)](https://github.com/coregx/gxpdf/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/coregx/gxpdf?style=flat-square&logo=github)](https://github.com/coregx/gxpdf/network/members)
[![GitHub issues](https://img.shields.io/github/issues/coregx/gxpdf?style=flat-square&logo=github)](https://github.com/coregx/gxpdf/issues)
[![GitHub PRs](https://img.shields.io/github/issues-pr/coregx/gxpdf?style=flat-square&logo=github&label=PRs)](https://github.com/coregx/gxpdf/pulls)

Modern PDF library with comprehensive creation and extraction capabilities. Industry-leading table extraction accuracy (100% on bank statements). Built with Domain-Driven Design principles. **Launched:** January 2026

**Creation Features**:
- Text, graphics, gradients, complex tables with merged cells
- TTF/OTF font embedding + 14 standard PDF fonts
- RC4/AES encryption (40/128/256-bit)
- Auto-generated table of contents, watermarks

**Extraction Features**:
- Table extraction with 100% accuracy
- Text/image extraction, CSV/JSON/Excel export

**Tech**: Pure Go 1.25+, DDD | **Status**: v0.6.0 Active development

---

#### [born](https://github.com/born-ml/born) - Born ML Framework
> Production-ready deep learning framework for Go with zero Python dependencies

[![Go Version](https://img.shields.io/github/go-mod/go-version/born-ml/born?style=flat-square&logo=go)](https://github.com/born-ml/born)
[![GitHub release](https://img.shields.io/github/v/release/born-ml/born?style=flat-square)](https://github.com/born-ml/born/releases)
[![Activity](https://img.shields.io/github/last-commit/born-ml/born?style=flat-square&logo=github&label=activity)](https://github.com/born-ml/born/commits)
[![GitHub stars](https://img.shields.io/github/stars/born-ml/born?style=flat-square&logo=github)](https://github.com/born-ml/born/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/born-ml/born?style=flat-square&logo=github)](https://github.com/born-ml/born/network/members)
[![GitHub issues](https://img.shields.io/github/issues/born-ml/born?style=flat-square&logo=github)](https://github.com/born-ml/born/issues)
[![GitHub PRs](https://img.shields.io/github/issues-pr/born-ml/born?style=flat-square&logo=github&label=PRs)](https://github.com/born-ml/born/pulls)

Single-binary deployment ML framework. MNIST accuracy: 97.44% (MLP), 98.18% (CNN). Auto-differentiation via decorator pattern. Multiple backends (CPU with SIMD, GPU planned). **Launched:** November 2025

**Features**:
- Type safety with generics-powered API
- Neural Network modules: Linear, ReLU, Sigmoid, Tanh
- Optimizers: SGD with momentum, Adam
- WebAssembly support for browser inference

**Tech**: Go 1.25+ | **Status**: v0.7.11 Active development | **Coverage**: 83.8%

---

#### [gosh](https://github.com/grpmsoft/gosh) - GoSh Modern Shell
> Modern cross-platform shell written in Go with beautiful TUI

[![Go Version](https://img.shields.io/github/go-mod/go-version/grpmsoft/gosh?style=flat-square&logo=go)](https://github.com/grpmsoft/gosh)
[![GitHub release](https://img.shields.io/github/v/release/grpmsoft/gosh?include_prereleases&style=flat-square)](https://github.com/grpmsoft/gosh/releases)
[![Activity](https://img.shields.io/github/last-commit/grpmsoft/gosh?style=flat-square&logo=github&label=activity)](https://github.com/grpmsoft/gosh/commits)
[![GitHub stars](https://img.shields.io/github/stars/grpmsoft/gosh?style=flat-square&logo=github)](https://github.com/grpmsoft/gosh/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/grpmsoft/gosh?style=flat-square&logo=github)](https://github.com/grpmsoft/gosh/network/members)
[![GitHub issues](https://img.shields.io/github/issues/grpmsoft/gosh?style=flat-square&logo=github)](https://github.com/grpmsoft/gosh/issues)
[![GitHub PRs](https://img.shields.io/github/issues-pr/grpmsoft/gosh?style=flat-square&logo=github&label=PRs)](https://github.com/grpmsoft/gosh/pulls)

4 UI modes (Classic, Warp, Compact, Chat) with native POSIX script execution via mvdan.cc/sh. Git integration with branch display and dirty status indicators. **Launched:** October 2025

**Features**:
- Persistent command history with smart deduplication
- Real-time syntax highlighting
- Tab completion and multi-line input
- Viewport scrolling and visual help

**Tech**: Go 1.25+ | **Status**: Beta | **Target**: Q1 2026 stable

---

#### [grpm](https://github.com/grpmsoft/grpm) - Next-Gen Package Manager
> Gentoo package manager replacement — SAT solver, daemon architecture, transactional updates

[![Go Version](https://img.shields.io/github/go-mod/go-version/grpmsoft/grpm?style=flat-square&logo=go)](https://github.com/grpmsoft/grpm)
[![GitHub release](https://img.shields.io/github/v/release/grpmsoft/grpm?style=flat-square)](https://github.com/grpmsoft/grpm/releases)
[![Activity](https://img.shields.io/github/last-commit/grpmsoft/grpm?style=flat-square&logo=github&label=activity)](https://github.com/grpmsoft/grpm/commits)
[![GitHub stars](https://img.shields.io/github/stars/grpmsoft/grpm?style=flat-square&logo=github)](https://github.com/grpmsoft/grpm/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/grpmsoft/grpm?style=flat-square&logo=github)](https://github.com/grpmsoft/grpm/network/members)
[![GitHub issues](https://img.shields.io/github/issues/grpmsoft/grpm?style=flat-square&logo=github)](https://github.com/grpmsoft/grpm/issues)
[![GitHub PRs](https://img.shields.io/github/issues-pr/grpmsoft/grpm?style=flat-square&logo=github&label=PRs)](https://github.com/grpmsoft/grpm/pulls)

Modern Portage replacement for Gentoo Linux. SAT-based conflict-free dependency resolution, binary packages (GPKG/TBZ2), transactional updates via Btrfs/ZFS snapshots, daemon mode with gRPC/REST APIs. **Launched:** January 2026

**Features**:
- SAT solver for dependency resolution
- Binary & source package support
- Transactional updates (Btrfs/ZFS snapshots)
- Daemon architecture (gRPC + REST API)
- Namespace-based build sandboxing

**Tech**: Go 1.25+, SAT solver, gRPC | **Status**: v0.9.4 Active development

---

#### [gogpu](https://github.com/gogpu/gogpu) - GoGPU Graphics Framework
> Pure Go graphics framework - GPU power meets Go simplicity with zero CGO

[![Go Version](https://img.shields.io/github/go-mod/go-version/gogpu/gogpu?style=flat-square&logo=go)](https://github.com/gogpu/gogpu)
[![GitHub release](https://img.shields.io/github/v/release/gogpu/gogpu?include_prereleases&style=flat-square)](https://github.com/gogpu/gogpu/releases)
[![Activity](https://img.shields.io/github/last-commit/gogpu/gogpu?style=flat-square&logo=github&label=activity)](https://github.com/gogpu/gogpu/commits)
[![GitHub stars](https://img.shields.io/github/stars/gogpu/gogpu?style=flat-square&logo=github)](https://github.com/gogpu/gogpu/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/gogpu/gogpu?style=flat-square&logo=github)](https://github.com/gogpu/gogpu/network/members)
[![GitHub issues](https://img.shields.io/github/issues/gogpu/gogpu?style=flat-square&logo=github)](https://github.com/gogpu/gogpu/issues)
[![GitHub PRs](https://img.shields.io/github/issues-pr/gogpu/gogpu?style=flat-square&logo=github&label=PRs)](https://github.com/gogpu/gogpu/pulls)

High-level graphics framework that simplifies GPU programming. Dual backend architecture: Rust (wgpu-native via FFI) for performance or Pure Go for zero dependencies. Reduces WebGPU complexity from 480+ lines to ~20 lines. **Launched:** December 2025

**Features**:
- Dual backends: wgpu-native (Rust FFI) or Pure Go implementation
- Zero CGO requirement (with Go backend)
- Simple API inspired by raylib, Processing, Ebitengine
- Cross-platform: Windows, Linux, macOS
- Full ecosystem: graphics (gogpu), 2D API (gg), shaders (naga), GUI (ui)

**Tech**: Go 1.25+, WebGPU | **Status**: v0.24.4 Production-ready | **Ecosystem**: 580K+ LOC pure Go

---

#### [wgpu](https://github.com/gogpu/wgpu) - Pure Go WebGPU Implementation
> Complete WebGPU in pure Go — no Rust, no CGO, direct GPU access

[![Go Version](https://img.shields.io/github/go-mod/go-version/gogpu/wgpu?style=flat-square&logo=go)](https://github.com/gogpu/wgpu)
[![GitHub release](https://img.shields.io/github/v/release/gogpu/wgpu?include_prereleases&style=flat-square)](https://github.com/gogpu/wgpu/releases)
[![Activity](https://img.shields.io/github/last-commit/gogpu/wgpu?style=flat-square&logo=github&label=activity)](https://github.com/gogpu/wgpu/commits)
[![GitHub stars](https://img.shields.io/github/stars/gogpu/wgpu?style=flat-square&logo=github)](https://github.com/gogpu/wgpu/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/gogpu/wgpu?style=flat-square&logo=github)](https://github.com/gogpu/wgpu/network/members)
[![GitHub issues](https://img.shields.io/github/issues/gogpu/wgpu?style=flat-square&logo=github)](https://github.com/gogpu/wgpu/issues)
[![GitHub PRs](https://img.shields.io/github/issues-pr/gogpu/wgpu?style=flat-square&logo=github&label=PRs)](https://github.com/gogpu/wgpu/pulls)

Full WebGPU implementation without Rust/wgpu-native dependencies. Multi-backend: Vulkan 1.3, OpenGL ES, Software (CPU). W3C WebGPU spec compliant with type-safe GPU access. **Launched:** December 2025

**Features**:
- 100+ texture formats, comprehensive GPU type definitions
- Core validation layer: 17 resource registries, comprehensive tests
- Production-ready Vulkan backend (~27K lines of code)
- Headless rendering via software backend (CI/CD ready)
- Generic ID system with epoch-based memory safety

**Tech**: Go 1.25+, Vulkan/OpenGL/Software | **Status**: v0.21.3 Production-ready (~124K LOC)

---

#### [naga](https://github.com/gogpu/naga) - Pure Go Shader Compiler
> WGSL to SPIR-V compiler — 10,000+ lines of pure Go, zero CGO

[![Go Version](https://img.shields.io/github/go-mod/go-version/gogpu/naga?style=flat-square&logo=go)](https://github.com/gogpu/naga)
[![GitHub release](https://img.shields.io/github/v/release/gogpu/naga?include_prereleases&style=flat-square)](https://github.com/gogpu/naga/releases)
[![Activity](https://img.shields.io/github/last-commit/gogpu/naga?style=flat-square&logo=github&label=activity)](https://github.com/gogpu/naga/commits)
[![GitHub stars](https://img.shields.io/github/stars/gogpu/naga?style=flat-square&logo=github)](https://github.com/gogpu/naga/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/gogpu/naga?style=flat-square&logo=github)](https://github.com/gogpu/naga/network/members)
[![GitHub issues](https://img.shields.io/github/issues/gogpu/naga?style=flat-square&logo=github)](https://github.com/gogpu/naga/issues)
[![GitHub PRs](https://img.shields.io/github/issues-pr/gogpu/naga?style=flat-square&logo=github&label=PRs)](https://github.com/gogpu/naga/pulls)

Complete WGSL shader compiler generating Vulkan-compatible SPIR-V bytecode. Full lexer, parser, semantic analysis, type checking. CLI tool `nagac` for command-line compilation. **Launched:** December 2025

**Features**:
- Full WGSL support: 140+ tokens, complete IR
- Three-stage pipeline: parsing → IR lowering → codegen
- 40+ built-in functions (math, geometric, interpolation)
- Vertex, fragment, and compute shaders
- Comprehensive error reporting and validation

**Tech**: Go 1.25+, WGSL → SPIR-V/MSL/GLSL/HLSL | **Status**: v0.14.8 Production-ready (~65K LOC)

---

#### [gg](https://github.com/gogpu/gg) - Pure Go 2D Graphics
> Canvas-like drawing API — simple, zero dependencies, pure Go

[![Go Version](https://img.shields.io/github/go-mod/go-version/gogpu/gg?style=flat-square&logo=go)](https://github.com/gogpu/gg)
[![GitHub release](https://img.shields.io/github/v/release/gogpu/gg?include_prereleases&style=flat-square)](https://github.com/gogpu/gg/releases)
[![Activity](https://img.shields.io/github/last-commit/gogpu/gg?style=flat-square&logo=github&label=activity)](https://github.com/gogpu/gg/commits)
[![GitHub stars](https://img.shields.io/github/stars/gogpu/gg?style=flat-square&logo=github)](https://github.com/gogpu/gg/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/gogpu/gg?style=flat-square&logo=github)](https://github.com/gogpu/gg/network/members)
[![GitHub issues](https://img.shields.io/github/issues/gogpu/gg?style=flat-square&logo=github)](https://github.com/gogpu/gg/issues)
[![GitHub PRs](https://img.shields.io/github/issues-pr/gogpu/gg?style=flat-square&logo=github&label=PRs)](https://github.com/gogpu/gg/pulls)

Lightweight 2D graphics with HTML Canvas-like API. Immediate-mode drawing with GPU acceleration. Part of GoGPU ecosystem. **Launched:** December 2025

**Features**:
- Rich shapes: circles, rectangles, ellipses, arcs, Bezier curves
- Path operations: MoveTo, LineTo, QuadraticTo, CubicTo
- Matrix transformations: translate, rotate, scale
- Color support: RGBA, hex parsing, named colors
- GPU-accelerated rendering via WebGPU

**Tech**: Pure Go 1.25+ | **Status**: v0.37.3 Production-ready (~194K LOC)

---

#### [ui](https://github.com/gogpu/ui) - Enterprise GUI Toolkit
> Pure Go GUI toolkit — 22 widgets, 3 design systems, GPU rendering, 97%+ coverage

[![Go Version](https://img.shields.io/github/go-mod/go-version/gogpu/ui?style=flat-square&logo=go)](https://github.com/gogpu/ui)
[![GitHub release](https://img.shields.io/github/v/release/gogpu/ui?style=flat-square)](https://github.com/gogpu/ui/releases)
[![Activity](https://img.shields.io/github/last-commit/gogpu/ui?style=flat-square&logo=github&label=activity)](https://github.com/gogpu/ui/commits)
[![GitHub stars](https://img.shields.io/github/stars/gogpu/ui?style=flat-square&logo=github)](https://github.com/gogpu/ui/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/gogpu/ui?style=flat-square&logo=github)](https://github.com/gogpu/ui/network/members)
[![GitHub issues](https://img.shields.io/github/issues/gogpu/ui?style=flat-square&logo=github)](https://github.com/gogpu/ui/issues)
[![GitHub PRs](https://img.shields.io/github/issues-pr/gogpu/ui?style=flat-square&logo=github&label=PRs)](https://github.com/gogpu/ui/pulls)

Enterprise-grade GUI toolkit with 22 interactive widgets and 3 design systems (Material 3, Fluent, Cupertino). Pure Go with GPU-accelerated SDF rendering, reactive signals-based state management, and W3C Pointer Events. **Launched:** January 2026

**Features**:
- 22 widgets: buttons, text fields, tables, trees, charts, docking, menus
- 3 design systems: Material 3, Fluent, Cupertino (pluggable Painter pattern)
- CGO-free pure Go implementation (~146K LOC)
- GPU-accelerated SDF rendering, retained-mode with dirty tracking
- 3,900+ tests, 97%+ coverage
- Reactive state via Angular Signals pattern
- Event-driven: 0% CPU when idle

**Tech**: Pure Go 1.25+, WebGPU | **Status**: v0.1.2 Released | **Coverage**: 97%+

---

#### [webgpu](https://github.com/go-webgpu/webgpu) - WebGPU for Go
> Zero-CGO WebGPU bindings — GPU-accelerated graphics and compute in pure Go

[![Go Version](https://img.shields.io/github/go-mod/go-version/go-webgpu/webgpu?style=flat-square&logo=go)](https://github.com/go-webgpu/webgpu)
[![GitHub release](https://img.shields.io/github/v/release/go-webgpu/webgpu?style=flat-square)](https://github.com/go-webgpu/webgpu/releases)
[![Activity](https://img.shields.io/github/last-commit/go-webgpu/webgpu?style=flat-square&logo=github&label=activity)](https://github.com/go-webgpu/webgpu/commits)
[![GitHub stars](https://img.shields.io/github/stars/go-webgpu/webgpu?style=flat-square&logo=github)](https://github.com/go-webgpu/webgpu/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/go-webgpu/webgpu?style=flat-square&logo=github)](https://github.com/go-webgpu/webgpu/network/members)
[![GitHub issues](https://img.shields.io/github/issues/go-webgpu/webgpu?style=flat-square&logo=github)](https://github.com/go-webgpu/webgpu/issues)
[![GitHub PRs](https://img.shields.io/github/issues-pr/go-webgpu/webgpu?style=flat-square&logo=github&label=PRs)](https://github.com/go-webgpu/webgpu/pulls)

Pure Go FFI-based WebGPU bindings via wgpu-native. Cross-platform GPU access without CGO. Comprehensive API covering graphics and compute pipelines. **Launched:** November 2025

**Features**:
- Complete WebGPU API: Instance, Adapter, Device, Buffers, Textures, Samplers
- Render & Compute Pipelines with shader support
- Advanced rendering: Depth buffers, MRT, instanced/indirect rendering
- RenderBundle for pre-recorded commands
- GPU timestamp queries and error scopes
- 12 working examples (triangles, textures, 3D, compute shaders)

**Tech**: Go 1.25+, wgpu-native v24.0.3.1 | **Status**: v0.3.2 Stable | **Platform**: Windows/Linux/macOS

---

#### [matlab](https://github.com/scigolib/matlab) - MATLAB for Go
> Pure Go library for reading and writing MATLAB .mat files (v5-v7.3+)

[![Go Version](https://img.shields.io/github/go-mod/go-version/scigolib/matlab?style=flat-square&logo=go)](https://github.com/scigolib/matlab)
[![GitHub release](https://img.shields.io/github/v/release/scigolib/matlab?include_prereleases&style=flat-square)](https://github.com/scigolib/matlab/releases)
[![Activity](https://img.shields.io/github/last-commit/scigolib/matlab?style=flat-square&logo=github&label=activity)](https://github.com/scigolib/matlab/commits)
[![GitHub stars](https://img.shields.io/github/stars/scigolib/matlab?style=flat-square&logo=github)](https://github.com/scigolib/matlab/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/scigolib/matlab?style=flat-square&logo=github)](https://github.com/scigolib/matlab/network/members)
[![GitHub issues](https://img.shields.io/github/issues/scigolib/matlab?style=flat-square&logo=github)](https://github.com/scigolib/matlab/issues)
[![GitHub PRs](https://img.shields.io/github/issues-pr/scigolib/matlab?style=flat-square&logo=github&label=PRs)](https://github.com/scigolib/matlab/pulls)

Read/write MATLAB files without CGO dependencies. Supports all numeric types, complex numbers, multi-dimensional arrays, and character arrays. Round-trip verified. **Launched:** June 2025

**Features**:
- MATLAB v5-v7.2 (binary format)
- MATLAB v7.3+ (HDF5-based format)
- Pure Go HDF5 implementation
- Cross-platform compatibility

**Tech**: Pure Go 1.25+ | **Status**: v0.3.4 Production-ready

---

#### [uniwidth](https://github.com/unilibs/uniwidth) - Unicode Width Calculator
> High-performance Unicode width calculation library - 3.9-46x faster than go-runewidth

[![Go Version](https://img.shields.io/github/go-mod/go-version/unilibs/uniwidth?style=flat-square&logo=go)](https://github.com/unilibs/uniwidth)
[![GitHub release](https://img.shields.io/github/v/release/unilibs/uniwidth?include_prereleases&style=flat-square)](https://github.com/unilibs/uniwidth/releases)
[![Activity](https://img.shields.io/github/last-commit/unilibs/uniwidth?style=flat-square&logo=github&label=activity)](https://github.com/unilibs/uniwidth/commits)
[![GitHub stars](https://img.shields.io/github/stars/unilibs/uniwidth?style=flat-square&logo=github)](https://github.com/unilibs/uniwidth/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/unilibs/uniwidth?style=flat-square&logo=github)](https://github.com/unilibs/uniwidth/network/members)
[![GitHub issues](https://img.shields.io/github/issues/unilibs/uniwidth?style=flat-square&logo=github)](https://github.com/unilibs/uniwidth/issues)
[![GitHub PRs](https://img.shields.io/github/issues-pr/unilibs/uniwidth?style=flat-square&logo=github&label=PRs)](https://github.com/unilibs/uniwidth/pulls)

Zero memory allocations (0 B/op, 0 allocs/op) with Unicode 16.0 support. Tiered lookup strategy achieving O(1) performance for 90-95% of typical use cases. **Launched:** October 2025

**Performance**:
- 15-46x faster for ASCII
- 4-14x faster for CJK
- 6-8x faster for mixed/emoji

**Tech**: Go 1.25+ | **Status**: v0.2.0 Stable Production-ready | **Coverage**: 87.1%

---

### 🧬 Organizations & Ecosystems

#### **born-ml** - Deep Learning for Go
Building a production-ready ML framework for Go with zero Python dependencies.

- **[born](https://github.com/born-ml/born)** - ML framework achieving 97-98% MNIST accuracy
  - Single-binary deployment, WebAssembly support
  - Auto-differentiation, multiple backends (CPU/GPU)
  - `v0.7.11` | Active development, 83.8% coverage

---

#### **CausalGo** - Statistical & Causal Learning
High-performance implementations of causal discovery and statistical learning algorithms.

- **[causalgo](https://github.com/causalgo/causalgo)** - SURD algorithm for causal discovery

[![Go Version](https://img.shields.io/github/go-mod/go-version/causalgo/causalgo?style=flat-square&logo=go)](https://github.com/causalgo/causalgo)
[![GitHub release](https://img.shields.io/github/v/release/causalgo/causalgo?style=flat-square)](https://github.com/causalgo/causalgo/releases)
[![Activity](https://img.shields.io/github/last-commit/causalgo/causalgo?style=flat-square&logo=github&label=activity)](https://github.com/causalgo/causalgo/commits)
[![GitHub stars](https://img.shields.io/github/stars/causalgo/causalgo?style=flat-square&logo=github)](https://github.com/causalgo/causalgo/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/causalgo/causalgo?style=flat-square&logo=github)](https://github.com/causalgo/causalgo/network/members)
[![GitHub issues](https://img.shields.io/github/issues/causalgo/causalgo?style=flat-square&logo=github)](https://github.com/causalgo/causalgo/issues)
[![GitHub PRs](https://img.shields.io/github/issues-pr/causalgo/causalgo?style=flat-square&logo=github&label=PRs)](https://github.com/causalgo/causalgo/pulls)

  High-performance SURD (Synergy-Unique-Redundancy Decomposition) algorithm validated against Nature Communications 2024 research. Implements information-theoretic causal discovery with LASSO-based VarSelect for identifying causal ordering in nonlinear systems.

  **Highlights**:
  - 97.2% test coverage for SURD core
  - 100% match with Python reference on turbulence data
  - MATLAB file format support (v5 and v7.3 HDF5)
  - Visualization exports (PNG/SVG/PDF)
  - CLI tool for graph generation

  **Tech**: Pure Go 1.25+, Gonum | **Status**: v0.6.0 | **Coverage**: 97.2%

- **[lasso](https://github.com/CausalGo/lasso)** - Parallel LASSO regression
  - Coordinate descent with goroutines
  - ~25ms on 10K samples with 100 features
  - `v0.2.1` | Production-ready

---

#### **coregx** - Core Go Extensions
Type-safe, high-performance libraries for modern Go applications.

- **[relica](https://github.com/coregx/relica)** - Type-safe database query builder
  - Zero production dependencies, 3.3x faster batch operations
  - PostgreSQL, MySQL, SQLite support
  - `v0.9.1` | Production-ready, 93.3% coverage

- **[fursy](https://github.com/coregx/fursy)** - Next-gen HTTP router
  - Type-safe handlers, ~10M req/s throughput
  - Built-in OpenAPI 3.1 generation, RFC 9457 errors
  - `v0.3.3` | Production-ready, 93.1% coverage

- **[stream](https://github.com/coregx/stream)** - Real-time communications
  - RFC-compliant SSE & WebSocket, <100μs latency
  - Zero external dependencies
  - `v0.1.0` | 314 tests, 84.3% coverage

- **[signals](https://github.com/coregx/signals)** - Reactive state management
  - Angular Signals pattern, zero-allocation hot paths
  - 0.51 ns/op Signal.Get
  - `v0.1.0` | 51 tests, 67.9% coverage

- **[pubsub](https://github.com/coregx/pubsub)** - Publish-Subscribe messaging
  - Guaranteed delivery with exponential backoff retry
  - Dead Letter Queue for failed messages
  - Battle-tested in FreiCON Railway Management System
  - `v0.1.0` | 95.9% coverage, Stable

- **[coregex](https://github.com/coregx/coregex)** - See Featured Projects above

- **[ahocorasick](https://github.com/coregx/ahocorasick)** - Multi-pattern string matching
  - Aho-Corasick algorithm, 1.6 GB/s throughput
  - Zero allocations per search
  - `v0.1.0` | Stable

- **[gxpdf](https://github.com/coregx/gxpdf)** - Enterprise PDF library
  - Create & read PDFs, 100% table extraction accuracy
  - TTF/OTF fonts, encryption, watermarks
  - `v0.6.0` | Active development

---

#### **go-webgpu** - GPU Computing for Go
Pure Go WebGPU ecosystem for graphics and compute workloads.

- **[webgpu](https://github.com/go-webgpu/webgpu)** - See Featured Projects above

- **[goffi](https://github.com/go-webgpu/goffi)** - Pure Go FFI library
  - Call C libraries without CGO
  - 88-114ns FFI call overhead
  - Platform-specific assembly optimizations
  - `v0.3.8` | 87.1% coverage, Production-ready

---

#### **gogpu** - Pure Go Graphics Framework (580K+ LOC, 415+ Stars)
GPU power, Go simplicity — zero CGO graphics ecosystem. 5 GPU backends, 4 shader targets.

- **[gogpu](https://github.com/gogpu/gogpu)** - Core graphics framework (~42K LOC)
  - Zero CGO, no C compiler required
  - WebGPU backend, cross-platform (Windows/Linux/macOS)
  - Simple API inspired by raylib, Processing, Ebitengine
  - `v0.24.4` | Production-ready

- **[wgpu](https://github.com/gogpu/wgpu)** - Pure Go WebGPU implementation (~124K LOC)
  - No wgpu-native, no Rust dependencies
  - Direct GPU access: Vulkan, Metal, DirectX 12, OpenGL ES, Software
  - WASM-compatible for browser deployment
  - `v0.21.3` | Production-ready

- **[gg](https://github.com/gogpu/gg)** - GPU-accelerated 2D graphics (~194K LOC)
  - Enterprise-grade 2D graphics with GPU acceleration
  - Processing-style creative coding interface
  - Shapes, curves, text, images, gradients
  - `v0.37.3` | Production-ready

- **[naga](https://github.com/gogpu/naga)** - Pure Go shader compiler (~65K LOC)
  - Port of Rust naga to pure Go
  - WGSL → SPIR-V, GLSL, HLSL, MSL (4 targets)
  - Runtime shader generation, WASM support
  - `v0.14.8` | Production-ready

- **[ui](https://github.com/gogpu/ui)** - Enterprise GUI toolkit (~146K LOC)
  - 22 widgets, 3 design systems (Material 3, Fluent, Cupertino)
  - GPU-accelerated SDF rendering, reactive signals
  - W3C Pointer Events, event-driven (0% CPU idle)
  - `v0.1.2` | Released, 97%+ coverage, 3900+ tests

---

#### **scigolib** - Scientific Computing Libraries
Building Go's scientific computing ecosystem with pure Go implementations.

- **[hdf5](https://github.com/scigolib/hdf5)** - See Featured Projects above

- **[matlab](https://github.com/scigolib/matlab)** - MATLAB file format library
  - Read/write .mat files (v5-v7.3+)
  - Pure Go, no CGO
  - `v0.3.4` | Production-ready

---

#### **phoenix-tui** - Terminal User Interfaces

- **[phoenix](https://github.com/phoenix-tui/phoenix)** - See Featured Projects above

---

#### **grpmsoft** - System Software

- **[gosh](https://github.com/grpmsoft/gosh)** - Modern cross-platform shell
  - 4 UI modes: Classic, Warp, Compact, Chat
  - Native POSIX script execution, Git integration
  - `v0.1.0-beta.7` | Targeting stable Q1 2026

- **[grpm](https://github.com/grpmsoft/grpm)** - Next-gen package manager
  - SAT solver, daemon architecture (gRPC/REST)
  - Transactional updates via Btrfs/ZFS snapshots
  - `v0.9.4` | Active development

---

#### **irismail** - Email Infrastructure

- **[iris](https://github.com/irismail/iris)** - 🔒 Private (launching Q2 2026)
  - IrisMX modern mail exchange server
  - Modern SMTP/IMAP/POP3 implementation

---

#### **unilibs** - Universal Libraries

- **[uniwidth](https://github.com/unilibs/uniwidth)** - Unicode width calculation
  - 3.9-46x faster than go-runewidth
  - Zero allocations
  - `v0.2.0` | 87.1% coverage, Stable

---

### 🛠️ Utility Libraries

#### Angular Components
- **[ngx-dadata](https://github.com/kolkov/ngx-dadata)** - DaData address autocomplete for Angular

#### Go Validation Libraries
- **[iso6346](https://github.com/kolkov/iso6346)** - Container number validation (ISO 6346)
- **[luhn](https://github.com/kolkov/luhn)** - Luhn algorithm (credit card validation)
- **[esr](https://github.com/kolkov/esr)** - Check-digit mod11 algorithm

#### Text Processing
- **[uawk](https://github.com/kolkov/uawk)** - Ultra AWK interpreter (19x faster than GoAWK)

#### Utilities
- **[url-translit](https://github.com/kolkov/url-translit)** - Cyrillic to Latin URL transliteration
- **[prerender](https://github.com/goprerender/prerender)** - Headless Chrome prerendering server

---

## 📊 Statistics

| Metric | Value |
|--------|-------|
| **Total Projects** | 36 (35 public + 1 private) |
| **Organizations** | 12 |
| **Total Stars** | 1500+ |
| **Total Forks** | 410+ |
| **In awesome-go** | 10 projects |
| **Code Coverage** | 70-97% across projects |
| **Linter Issues** | 0 (strict policy) |

---

## 🎯 Roadmap

### Q1 2026 (In Progress)
- ✅ **gogpu v0.24.4** - Major progress, 580K+ LOC ecosystem
- ✅ **wgpu v0.16.17** - Major progress (was v0.7.1)
- ✅ **gg v0.30.2** - Major progress (was v0.15.0)
- ✅ **naga v0.14.3** - Major progress (was v0.6.0)
- ✅ **coregex v0.12.3** - 124 stars, growing fast
- ✅ **grpm v0.9.4** - Near-stable (was v0.2.0)
- ✅ **racedetector v0.8.4** - Major progress (was v0.1.0)
- 🔄 **relica v1.0.0** - Stable API target
- 🔄 **fursy v1.0.0** - Stable API target

### Q2 2026
- **gogpu v1.0.0** - Stable graphics framework (580K+ LOC, 22 widgets, 3 design systems)
- **born v1.0.0** - Production ML framework
- **grpm v1.0.0** - Production ready
- **phoenix v0.3.0** - Signals integration
- **ui v0.1.0** - Pure Go GUI toolkit

### Q3 2026
- **wgpu v1.0.0** - Stable Pure Go WebGPU
- **coregex v1.0.0** - Stable regex engine
- **hdf5 v1.0.0** - Full HDF5 compliance
- **racedetector v1.0.0** - Stable release

---

## 💼 Professional Services

Available for consulting and contract work:

- **Go Systems Development** - GPU computing, high-performance libraries, pure Go implementations
- **AI-Assisted Engineering** - Smart Coding methodology, agent workflows, knowledge architecture
- **Performance Optimization** - SIMD, zero-allocation strategies, profiling
- **Code Review & Architecture** - Best practices, scalability, Go ecosystem design
- **Angular/TypeScript Frontend** - Component libraries, reactive architectures

**Work Format**: Part-time, freelance, consulting, open source collaboration

---

## 🤝 Open Source Philosophy

- **Quality over quantity** - Every project is production-ready with high test coverage
- **Pure Go** - Zero CGO dependencies, easy cross-compilation
- **Type safety** - Go 1.25+ generics for compile-time guarantees
- **Battle-tested** - Most libraries extracted from real production systems
- **AI-augmented development** - Using [Smart Coding](https://dev.to/kolkov/smart-coding-vs-vibe-coding-engineering-discipline-in-the-age-of-ai-5b20) methodology for disciplined collaboration with AI agents

---

## 📫 Get in Touch

- **GitHub**: [@kolkov](https://github.com/kolkov)
- **Dev.to**: [kolkov](https://dev.to/kolkov) — articles on Smart Coding and AI-assisted development
- **Organizations**: [gogpu](https://github.com/gogpu) | [coregx](https://github.com/coregx) | [born-ml](https://github.com/born-ml) | [scigolib](https://github.com/scigolib) | [phoenix-tui](https://github.com/phoenix-tui) | [go-webgpu](https://github.com/go-webgpu) | [CausalGo](https://github.com/CausalGo) | [grpmsoft](https://github.com/grpmsoft) | [unilibs](https://github.com/unilibs)

**Open to**: Consulting, open source collaboration, technical partnerships

---

## 🌱 Current Focus

- **GPU Graphics Ecosystem** - Building Go's first comprehensive GPU stack: graphics framework, WebGPU, shader compiler, GUI toolkit (**gogpu** — 415+ stars, 580K+ LOC)
- **High-Performance Regex** - Multi-engine regex with SIMD, approaching stdlib replacement quality (**coregex** — 124 stars, growing fast)
- **ML for Go** - Production deep learning without Python dependencies (**born** — 44 stars)
- **AI-Assisted Development** - Writing about Smart Coding methodology and building tools for disciplined AI collaboration
- **Scientific Computing** - Pure Go implementations of HDF5, MATLAB, and causal discovery algorithms

---

<div align="center">

**Let's build something amazing together!**

**Gophers of all lands, unite!**

[![GitHub followers](https://img.shields.io/github/followers/kolkov?style=social)](https://github.com/kolkov)
[![GitHub stars](https://img.shields.io/github/stars/kolkov?style=social)](https://github.com/kolkov)

</div>
