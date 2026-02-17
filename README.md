# Flutter Bloc Snippets for Zed

[![Zed](https://img.shields.io/badge/Zed-Editor-blue?style=flat&logo=zed)](https://zed.dev)
[![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat&logo=flutter)](https://flutter.dev)
[![Bloc](https://img.shields.io/badge/BLoC-orange?style=flat)](https://bloclibrary.dev)

A collection of useful Flutter BLoC pattern snippets for Zed editor to speed up your development workflow.


## Installation

1. Clone this repository or download the extension
2. Copy the extension to your Zed extensions directory:
   ```bash
   cp -r flutter-bloc ~/.config/zed/extensions/
   ```
3. Restart Zed editor
4. The snippets will be available in Dart files

## Available Snippets

| Prefix | Description |
|--------|-------------|
| `bloc` | Create a new BLoC class |
| `blocevent` | Create BLoC event file |
| `blocstate` | Create BLoC state file |
| `cubit` | Create a new Cubit |
| `blocbuilder` | BlocBuilder widget |
| `bloclistener` | BlocListener widget |
| `blocconsumer` | BlocConsumer widget |
| `blocprovider` | BlocProvider widget |
| `multiblocprovider` | MultiBlocProvider widget |
| `repositoryprovider` | RepositoryProvider widget |

## Usage

Simply type any of the prefixes above in a Dart file and press `Tab` to expand the snippet. Use `Tab` to navigate between placeholders and customize the generated code.

---

## Coverage

| Pattern/Method | Status |
|---------------|--------|
| BLoC Class | ✅ |
| Cubit | ✅ |
| Event/State Files | ✅ |
| BlocBuilder | ✅ |
| BlocListener | ✅ |
| BlocConsumer | ✅ |
| BlocProvider | ✅ |
| MultiBlocProvider | ✅ |
| RepositoryProvider | ✅ |
| context.read<T>() | ❌ |
| context.watch<T>() | ❌ |
| context.select<T, R>() | ❌ |
| BlocSelector | ❌ |
| MultiBlocListener | ❌ |
| MultiRepositoryProvider | ❌ |
| on<EventType>() | ❌ |
| BlocObserver | ❌ |
| emit() patterns | ❌ |
