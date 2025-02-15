# Changelog

## [1.1.0] - 2025-02-16

### Added
- **Vector Utilities**
  - `CouldSee` extension methods for Vector3 and Vector2
  - Relevant docs

### Changed
- added `in` keywords for number extensions

## [1.0.1] - 2025-02-15
### Added
- extensions for generating random numbers from Unity.Mathematics number structs

### Changed
- changed **RandomsTo** -> **RandomsBetween** for more clarity, since it uses the first parameter as the **amount**
- changed IntExtensions to NumberExtensions

## [1.0.0] - 2025-02-15

### Added
- **Core Utilities:**
  - `DisposableWrapper` for custom resource cleanup
  - `RingBuffer` and thread-safe `RingBufferSafe`
  - `Trigger` class for one-shot boolean logic
- **2D Tools:**
  - ShadowCaster2D shape conversion (collider/sprite paths)
  - Sprite outline generation with configurable settings
- **Addressables Management:**
  - Synchronous/asynchronous asset loading
  - Preloading and cache management
- **Editor Utilities:**
  - Package Installer Window for third-party dependencies
  - GUI interface for VContainer/UniTask/MessagePipe installation
- **Extensions:**
  - Mathematics conversions (Color <-> float4)
  - Pooled collection helpers (List/HashSet)
  - More comfortable randomization methods
- **Pooling System:**
  - `[Pooled]` attribute for automatic object pooling
  - Custom pool configuration with creation/destruction actions
- **Package Infrastructure:**
  - UPM installation support
  - Unity 6000.0.1 compatibility