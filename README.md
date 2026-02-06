# Moxie | <sup><sub>[![](https://jitpack.io/v/a8kj7sea/Moxie.svg)](https://jitpack.io/#a8kj7sea/Moxie)</sup></sub>

**Moxie** is a high-performance configuration engine that treats files as dynamic templates. It decouples data storage from file logic, ensuring thread-safe, memory-efficient, and transformable configuration management.

### Key Features
* **Dynamic Templates:** On-the-fly placeholder injection using `ReplacementProcessor`.
* **Layered Memory:** Modular `DataMemory` for Enum, Map, or Paired data structures.
* **Service Registry:** Centralized, thread-safe management of all config instances.
* **UTF-8 Core:** Built-in encoding integrity for cross-platform stability.

### Roadmap
- [ ] **Annotation System:** Auto-mapping classes to files via reflection.
- [ ] **Backup System:** Fail-safe snapshots for corrupted data prevention.

---

### Inspired By
* **[UltimisMC/SkyWars](https://github.com/UltimisMC/SkyWars)** - Inspired by their robust core configuration system.
* **[Mqzn/Cardinal](https://github.com/Mqzn/Cardinal)** - Inspired by the API and Provider patterns for modularity.
* **[a8kj7sea/a8kjCfg](https://github.com/a8kj7sea/a8kjCfg)** - My previous iteration that motivated the architectural improvements in Moxie.
* **[a8kj7sea/Lootboxes](https://github.com/a8kj7sea/Lootboxes)** - A previous attempt at a general configuration system that evolved into this project.
