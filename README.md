# Meow Find You a Job (MFYJ)

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)   [![Python Version](https://img.shields.io/badge/python-3.8+-brightgreen)](https://www.python.org/downloads/)

**Meow Find You a Job** é uma ferramenta open source que automatiza e personaliza o processo de preparação para aplicações em vagas de emprego. Combinando agentes inteligentes, análise de IA, e ferramentas de busca, o sistema auxilia candidatos a se destacarem em todas as etapas do processo seletivo.

## ✨ Funcionalidades

- **Análise de Vagas**: Extrai habilidades, qualificações e experiências necessárias a partir de URLs de vagas.
- **Perfis Profissionais**: Cria perfis detalhados baseados em informações públicas e arquivos do usuário.
- **Personalização de Currículos**: Ajusta currículos para destacar habilidades e experiências relevantes.
- **Preparação para Entrevistas**: Gera perguntas e pontos de discussão com base no currículo e nos requisitos do trabalho.

## 🚀 Como Funciona

O projeto utiliza o framework **CrewAI** para orquestrar múltiplos agentes, cada um responsável por uma etapa do processo, como análise de vagas, perfil profissional, personalização de currículos e preparação para entrevistas.

### Principais Agentes

1. **Tech Job Researcher**: Analisa descrições de vagas e extrai requisitos-chave.
2. **Personal Profiler for Engineers**: Compila perfis profissionais detalhados.
3. **Resume Strategist for Engineers**: Personaliza currículos para alinhar com os requisitos do trabalho.
4. **Engineering Interview Preparer**: Cria perguntas e pontos de discussão para entrevistas.

### Llama 3.2 Local
O MFYJ utiliza a LLM [Llama 3.2](https://github.com/ollama/ollama?tab=readme-ov-file#:~:text=Download-,Llama%203.2,-3B) que precisa ser configurado antes de rodar o script.
