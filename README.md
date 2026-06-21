# 🗺️ Nexus Explorer

Um File Explorer de altíssima performance para Windows, arquitetado com Tauri 2.0 e Svelte 5. O objetivo do Nexus é ser o navegador de arquivos visualmente mais deslumbrante e rápido disponível.

Onde o Windows Explorer convencional engasga, o Nexus brilha, delegando o trabalho sujo do sistema operacional para a eficiência implacável do Rust, enquanto o Svelte gerencia uma UI fluida de 60fps.

## 🧠 Core Features & Architecture

- **Svelte 5 Runes Engine:** Gestão de abas (`tabs.svelte.ts`), atalhos globais (`shortcuts.svelte.ts`) e layout modular totalmente refatorados para o novo paradigma de reatividade do Svelte.
- **Rust Backend:** Geração ultrarrápida de thumbnails usando a crate `image`, detecção real de formato de arquivo ignorando a extensão (via `infer`), e monitoramento de sistema (`sysinfo`).
- **Navegação Modular:** Um layout composto por *Inspector* dinâmico, área de visualização polida e atalhos customizados pensados para "Power Users".

## 🚀 Roadmap Atual (Phase 2 & 3)
Atualmente integrando acesso nativo ao FS através do `tauri-plugin-fs` e lapidando a experiência visual com transições avançadas, Blur (Acrylic/Mica feel) e context menus interativos e imersivos utilizando bibliotecas headless como `bits-ui`.
