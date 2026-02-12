# -RAGleis-
**LegalLens** é um sistema de análise jurídica inteligente que detecta cláusulas críticas em contratos e documentos legais usando técnicas avançadas de processamento de linguagem natural (NLP). 100% open-source, otimizado para CPU e funcionando 24/7 no Hugging Face Spaces.

# ⚖️ LegalLens - Analisador Jurídico com IA

[![HF Spaces](https://img.shields.io/badge/Hugging%20Face-Spaces-FFD21E?logo=huggingface&logoColor=white)](https://huggingface.co/spaces/Danielfonseca1212/RAGleis)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://python.org)

> **LegalLens** é um sistema de análise jurídica inteligente que detecta cláusulas críticas em contratos e documentos legais usando técnicas avançadas de processamento de linguagem natural (NLP). 100% open-source, otimizado para CPU e funcionando 24/7 no Hugging Face Spaces.

https://huggingface.co/spaces/Danielfonseca1212/RAGleis

## 🚀 Funcionalidades

✅ **Processamento de Linguagem Natural (NLP)** - Análise avançada de texto jurídico  
✅ **Análise Multilíngue** - Suporta documentos em Português e Inglês  
✅ **Leitor de PDF Integrado** - Upload e extração automática de texto  
✅ **Detecção de Cláusulas Críticas** - 6 tipos de riscos jurídicos  
✅ **Classificação por Nível de Risco** - Alto, Médio e Baixo risco  
✅ **Interface Profissional** - Design clean e focado em experiência do usuário  
✅ **100% CPU** - Funciona perfeitamente no HF Spaces FREE  
✅ **Open Source** - Código transparente e auditável  

## 🔍 Processamento de Linguagem Natural (NLP) Avançado

O LegalLens utiliza **técnicas modernas de NLP** para analisar documentos jurídicos:

### 🧠 **Tecnologias de NLP Utilizadas**
- **Sentence Transformers** - Embeddings semânticos para compreensão contextual
- **Busca Semântica** - Compreensão de significado além de palavras-chave
- **Processamento de Linguagem Natural** - Análise estruturada de texto jurídico
- **Extração de Entidades** - Identificação de termos jurídicos relevantes

### 📋 **Cláusulas Detectadas por NLP**

| Tipo | Palavras-Chave | Nível de Risco |
|------|----------------|----------------|
| **Indenização** | indenização, damages, liability | ⚠️ **ALTO** |
| **Rescisão Unilateral** | rescisão unilateral, termination rights | ⚠️ **ALTO** |
| **Multa Contratual** | multa contratual, penalty clause | ⚠️ **MÉDIO** |
| **Confidencialidade** | confidencialidade, non-disclosure | ⚠️ **MÉDIO** |
| **Exclusividade** | exclusividade, exclusivity | ⚠️ **MÉDIO** |
| **Foro de Eleição** | foro de eleição, jurisdiction | ⚠️ **BAIXO** |

### 🎯 **Como o NLP Funciona no LegalLens**

1. **Pré-processamento**: Limpeza e normalização do texto jurídico
2. **Embedding Semântico**: Conversão de texto em representações vetoriais
3. **Busca por Similaridade**: Comparação com padrões de cláusulas críticas
4. **Classificação de Risco**: Avaliação baseada em contexto e gravidade
5. **Geração de Insights**: Explicação clara dos riscos identificados

## 🛠️ Tecnologias Utilizadas

- **Gradio** - Interface web interativa
- **PyPDF2** - Extração de texto de PDFs
- **Sentence Transformers** - Busca semântica (opcional)
- **FAISS** - Indexação e busca eficiente
- **Hugging Face Spaces** - Deploy 24/7 gratuito

## 🚀 Como Usar

### Demo Online (Recomendado)
Acesse o https://huggingface.co/spaces/Danielfonseca1212/RAGleis e comece a analisar documentos imediatamente!

### Executar Localmente

1. **Clone o repositório:**
```bash
git clone https://github.com/Danielfonseca1212/LegalLens.git
cd LegalLens


