
# AI_local_acessivel Ollama + WebUI Simples e Seguro

Stack 100% local, simples e acessível, para rodar IA generativa sem custo de API e sem necessidade de conexão.

Ideal para situações em que não há disponibilidade de rede, que exigem privacidade, segurança ou poucos recursos financeiros — incluindo rodar LLaMA 3.2 (3B) em CPU comum.

## Por que este projeto?

- **Acessibilidade**: Tenha uma IA local que funciona mesmo sem internet, acessível para diversos usos (estudos, marketing, negócios, prototipagem).
- **Privacidade**: Tudo roda local, nenhum dado enviado para nuvem.
- **Zero custo de API**: Só é preciso baixar o modelo uma vez; depois, o uso é ilimitado.
- **Simplicidade**: Um comando (`docker compose up -d`) e você já tem um “ChatGPT local” pronto.
- **Flexibilidade**: Escolha o modelo de IA mais adequado (leve, rápido ou profundo).

## Como rodar

1. **Pré-requisitos**:
   - Instale [Docker](https://docs.docker.com/get-docker/) e [Docker Compose](https://docs.docker.com/compose/install/).
   - Pelo menos 4GB de RAM para rodar modelos leves como LLaMA 3.2 (3B).

2. **Clone o repositório**:
   ```bash
   git clone https://github.com/RGROU1/PrivateAI_acessible.git
   cd PrivateAI_acessible
