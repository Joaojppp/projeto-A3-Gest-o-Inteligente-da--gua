## Visão Geral do Fluxo de Dados
1. **Coleta (Sensores IoT):** Hidrômetros inteligentes medem continuamente vazão e pressão em tempo real nas redes de distribuição[cite: 7].
2. **Processamento em Nuvem:** Os dados são enviados para o back-end em nuvem, onde o algoritmo de Machine Learning analisa séries temporais em busca de desvios[cite: 7].
3. **Apresentação e Camada de Dados:**
   - **Front-end / MVP:** Desenvolvido em HTML, CSS e JavaScript para o painel operacional e app mobile do cliente[cite: 7, 11].
   - **Back-end & API:** Estrutura Serverless baseada em **Supabase**[cite: 7].
   - **Banco de Dados:** **PostgreSQL** hospedado no Supabase para armazenamento estruturado das informações[cite: 7].
