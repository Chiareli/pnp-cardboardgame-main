# PnP & Past Up — PDF Card Extractor

**Grid de Impressão CMYK Multi-Página com Extração Automática de PDFs**

---

## 🎯 Sobre o Projeto

**PnP & Past Up** é uma ferramenta web para criar grids de impressão de cartas de jogos em alta definição (até 900 DPI) com suporte a exportação profissional em CMYK.

### ✨ Principais Funcionalidades

- 📄 **Upload de imagens e PDFs**
- 🔍 **Detecção automática de cartas em PDFs
- 📊 **Renderização em alta definição** (150-900 DPI configurável)
- 🎨 **Grid de impressão customizável** (formatos A3, A4, Letter, Tabloid, fotográfico)
- 💾 **Exportação CMYK profissional** com marcas de corte e sangria
- 🎭 **Suporte a frente e verso** (duplex printing), incluindo extração de versos direto de PDF
- 📏 **Predefinições de tamanho** (Poker, Bridge, Tarot, e mais)
- 🔀 **Organização de grid**: embaralhar, duplicar (ao lado da original) e reorganizar automaticamente removendo espaços vazios entre páginas
- 🖱️ **Movimentação de cartas** entre células via botão "Mover" (seleciona origem e destino)

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

 acesse a versão online (GitHub Pages):
```
https://chiareli.github.io/pnp-cardboardgame-main/
```


### Passos de Uso

1. **Configure a folha** (formato, tamanho de peça, sangria)
2. **Importe imagens ou PDFs**
   - Imagens: Arraste diretamente
   - PDFs: Ajuste resolução (600 DPI recomendado) e deixe a detecção automática fazer o trabalho
3. **Visualize no grid**
   - Use **Embaralhar** para randomizar a ordem das cartas
   - Use **Organizar** para remover espaços vazios (ex: após excluir uma carta) e compactar as páginas automaticamente
   - Use **Mover** em uma carta e depois em outra célula para trocar as duas de lugar
   - Use **Dup** para duplicar uma carta, inserindo a cópia logo ao lado da original
4. **Configure frente/verso** (opcional) — aceita tanto imagens quanto PDFs para os versos.
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

- **Máxima qualidade**: Configure resolução em 900 DPI + qualidade 100%
- **Impressão profissional**: Sempre use exportação CMYK

---

**Desenvolvido com ❤️ para a comunidade de jogos de tabuleiro**
