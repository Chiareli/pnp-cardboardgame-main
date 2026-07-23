# PnP & Past Up — PDF Card Extractor

**Grid de Impressão CMYK Multi-Página com Extração Automática de PDFs**

---

## 🎯 Sobre o Projeto

**PnP & Past Up** é uma ferramenta web para criar grids de impressão de cartas de jogos em alta definição (até 900 DPI) com suporte a exportação profissional em CMYK.

### ✨ Principais Funcionalidades

- 📄 **Upload de imagens e PDFs**
- 🔍 **Detecção automática de cartas em PDFs** (3 estratégias inteligentes)
- 📊 **Renderização em alta definição** (150-900 DPI configurável)
- 🎨 **Grid de impressão customizável** (formatos A3, A4, Letter, Tabloid, fotográfico)
- 💾 **Exportação CMYK profissional** com marcas de corte e sangria
- 🎭 **Suporte a frente e verso** (duplex printing)
- 📏 **Predefinições de tamanho** (Poker, Bridge, Tarot, e mais)

---

## 📜 Créditos

**Projeto Original**: [Rafael D. Scarpille](https://github.com/rafaeldscarpille)
- Repositório original: https://github.com/rafaeldscarpille/pnp-cardboardgame
- Conceito, design UI/UX e funcionalidades base de grid/exportação CMYK

**Melhorias Implementadas**:
- ✨ **Suporte a PDFs** com detecção automática de cartas
- 🔍 **Sistema de detecção em cascata** (Transição de Cor → Grid Automático)
- 📊 **Extração em alta definição** (até 900 DPI)
- 🎯 **Detecção inteligente** com 3 estratégias diferentes
- ⚙️ **Configurações avançadas** (sensibilidade, resolução, qualidade)
- 🧪 **Validado** com múltiplos tipos de PDFs

---

## 🚀 Como Usar

### Via Web (Recomendado)

Abra em seu navegador:
```
http://localhost:8000/index.html
```

Ou acesse a versão online (GitHub Pages):
```
https://seu-usuario.github.io/pnp-cardboardgame/
```

### Localmente

1. **Clone ou baixe o repositório**
2. **Inicie um servidor HTTP** (Python):
   ```powershell
   python -m http.server 8000
   ```
3. **Abra no navegador**: `http://localhost:8000`

### Passos de Uso

1. **Configure a folha** (formato, tamanho de peça, sangria)
2. **Importe imagens ou PDFs**
   - Imagens: Arraste diretamente
   - PDFs: Ajuste resolução (600 DPI recomendado) e deixe a detecção automática fazer o trabalho
3. **Visualize no grid**
4. **Configure frente/verso** (opcional)
5. **Exporte em CMYK** com marcas de corte

---

## 🛠️ Tecnologia

- **HTML5 + CSS3 + JavaScript** (sem dependências externas)
- **PDF.js** (via CDN) para leitura de PDFs
- **Canvas API** para processamento de imagens
- **Detecção de cartas**: Algoritmos de Transição de Cor + Grid automático

---

## 📋 Requisitos

- Navegador moderno (Chrome, Firefox, Safari, Edge)
- Sem instalação necessária
- Funciona 100% offline após carregamento

---

## 📝 Licença

Mantém a licença do projeto original. Consulte o repositório original para detalhes.

---

## 🔗 Links

- **Projeto Original**: https://github.com/rafaeldscarpille/pnp-cardboardgame
- **Autor Original**: [@rafaeldscarpille](https://github.com/rafaeldscarpille)
- **Versão Online**: https://rafaeldscarpille.github.io/pnp-cardboardgame/

---

## 💡 Dicas de Uso

- **PDFs com espaçamento**: Use estratégia de Transição de Cor (detecção automática)
- **PDFs compactados (3×3)**: Use fallback Grid Automático
- **Máxima qualidade**: Configure resolução em 900 DPI + qualidade 100%
- **Impressão profissional**: Sempre use exportação CMYK

---

**Desenvolvido com ❤️ para a comunidade de jogos de tabuleiro**
