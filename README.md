Projeto Mottu - Previsão do Status das Motos
📌 Descrição
Este projeto tem como objetivo prever automaticamente o status operacional das motos da Mottu — Liberada, Manutenção ou Revisão — utilizando técnicas de Machine Learning. 
A iniciativa visa resolver a falta de organização e critérios objetivos nos pátios da empresa, o que atualmente causa atrasos, custos elevados e subutilização da frota.


⚙️ Tecnologias Utilizadas
O projeto foi desenvolvido no ambiente Google Colab, com os seguintes frameworks e bibliotecas:
pandas: manipulação e análise de dados.
scikit-learn: pré-processamento, criação e treinamento do modelo de ML.
matplotlib e seaborn: visualização de dados.


🧠 Técnica de Machine Learning
Foi utilizada a técnica de classificação supervisionada com uma Rede Neural Multicamadas (MLP).
Justificativas:
Capacidade de modelar relações não lineares;
Simplicidade de implementação;
Bom desempenho em dados tabulares.


🏗️ Arquitetura do Projeto
Coleta e preparação dos dados.
Normalização dos dados com StandardScaler.
Divisão dos dados: 80% treino / 20% teste.
Construção de modelo MLP com duas camadas ocultas (64 e 32 neurônios).
Treinamento com 500 iterações.
Avaliação com métricas de classificação (matriz de confusão, F1-score).
Previsão com novos dados (reais/sintéticos).
Salvamento do modelo para reutilização.


🚀 Etapas da Implementação
Dados normalizados e divididos.
Modelo MLP treinado com 2 camadas ocultas.
Avaliação do desempenho com métricas adequadas.
Testes com novos dados (reais/sintéticos).


📊 Resultados
Acurácia geral: 77%
Melhor desempenho: Classes Liberada e Revisão
Mesmo com abordagem simples, o modelo demonstrou confiabilidade operacional.


✅ Conclusão
A solução desenvolvida mostrou-se eficaz para apoiar decisões operacionais na Mottu, com potencial para integração aos sistemas internos da empresa.
Próximos passos recomendados:
Coleta de mais dados;
Testes com outros algoritmos de ML.
