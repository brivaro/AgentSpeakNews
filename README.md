<div align="center">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" height="80" alt="Python Logo" />
  <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Microscope.png" height="80" alt="Agent Emoji" />

  <h1>🔍 AgentSpeakNews: Multiagent News Query System</h1>

  <p>
    <img src="https://img.shields.io/badge/Python-3.12.9-blue" alt="Python">
    <img src="https://img.shields.io/badge/SPADE-latest-green" alt="SPADE">
    <img src="https://img.shields.io/badge/Owlready2-latest-yellow" alt="Owlready2">
    <img src="https://img.shields.io/badge/Feedparser-latest-orange" alt="Feedparser">
  </p>
</div>

![image](https://github.com/user-attachments/assets/686fe2d9-e315-4682-a7fd-c389e770d895)

---

### 💡 Overview
AgentSpeakNews es un sistema multiagente implementado en Python utilizando SPADE. La idea central es que un agente coordinador (Agente 1) se encarga de enviar una consulta de búsqueda a otros agentes especializados, cada uno consultando diferentes fuentes RSS de noticias. Cada agente busca en su feed aquellos artículos que contengan el término buscado y envía un resumen al coordinador, el cual presenta un resumen consolidado al usuario. ¡Y esto se puede ampliar fácilmente para incluir más fuentes o funcionalidades adicionales!

### 🗳 Features
- **Arquitectura Multiagente:** Coordinación entre múltiples agentes para distribuir la búsqueda de noticias.
- **Búsqueda Dinámica:** Permite ingresar un término de búsqueda y cada agente responde con las noticias que coincidan.
- **Integración con RSS:** Uso de `feedparser` para la lectura y análisis de feeds de noticias.
- **Ontología para Noticias:** Utiliza `Owlready2` para gestionar una ontología (rNews) que puede enriquecer semánticamente la información (ampliable).

### 📌 Tecnologías Utilizadas
- **Python** - Lenguaje principal de desarrollo.
- **SPADE** - Framework para la creación de sistemas multiagente.
- **Owlready2** - Biblioteca para manejo de ontologías.
- **Feedparser** - Biblioteca para parsear feeds RSS.

## 📖 Getting Started

1. **Clonar el Repositorio:**
   ```bash
   git clone https://github.com/brivaro/AgentSpeakNews.git
   cd AgentSpeakNews
