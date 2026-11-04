### **Projeto: Avaliando a Qualidade de Laudos Médicos com o uso de LLMs**

Um laudo médico em texto é um documento técnico e legal formal emitido exclusivamente por um profissional de saúde habilitado. O seu objetivo principal é transcrever, 
de forma detalhada e objetiva, os resultados de exames, diagnósticos, evolução clínica e limitações funcionais de um paciente. Seu objetivo é empregar modelos de LLM
abertos para construir um pipeline de qualidade dos laudos.

Acesse a descrição dos dados [aqui](https://physionet.org/content/mimic-iv-note/2.2/note/)
Acesse os arquivos [aqui](https://drive.google.com/drive/folders/1Nz6NrF_r3qlR5yeEEiF2qggZxPmIVXRj?usp=drive_link).

1. **Ferramentas**. Empregue somente modelos e recursos abertos, sendo 100% executável e aberto. Preferencialmente executar 100% em um notebook Colab. 
2. **GitHub**. Implementar um GitHub com o projeto.
3. **Referências**. Incluir referências.
4. **Entrega**. No formato de um artigo [SBC](https://www.sbc.org.br/wp-content/uploads/2024/07/modelosparapublicaodeartigos.zip), preferencialmente em Latex. Apresentação presencial (opcional no YouTube).

#### Sugestão de Cronograma

| Bom até | Atividade |
|--|--|
| 04-11 | Definição dos grupos, busca por referências e abordagens |
| 11-11 | Seleção dos dados (resumos de alta ou laudos radiológicos) e definição da abordagem |
| 18-11 | Seleção de modelos de linguagem e primeiros testes (base reduzida) e definição dos modelos a serem empregados (no caso de comparação) |
| 25-11 | Execução das abordagens |
| 02-12 | Ajustes e Análise dos resultados |
| 09-12 | Escrita do trabalho, apresentação e repositório |

#### Seções do Artigo

|  | Conteúdo |
|-|-|
|   | **Resumo**: *Por quê o trabalho é importante; O que faz; Breve descrição do resultado.*  |
| 1 | **Introdução**: *Justificativa/Relevância; O que faz; Breve descrição do resultado; com referências e números que suportem a argumentação.*|
| 2 | **Referencial Teórico**: *Conceitos empregados (aqui pode estar reduzido a um mínimo, como em um artigo de pesquisa especializado) e trabalhos correlatos: o que já fizeram e quem.* |
| 3 | **Metodologia**: *Apresente os dados, seu pipeline de experimentos, as métricas empregadas - com justificativas das escolhas.* |
| 4 | **Resultados**: *Tabelas, gráficos, e pode conter uma subseção de Discussão.* |
| 5 | **Conclusão**: *O que o trabalho conclui, quais limitações foram encontradas e sugestões de como superá-las, incluindo ideias para trabalhos futuros.* |
| 6 | **Referências**: *Referenciadas no texto* |
| 7 | Declaração do uso de IA |

Use IA para ajudar a gerar o texto, mas humanize e não deixe de dar a direção do texto para o gerador de IA.

#### Dicas de Abordagens

- **Domínio do Problema**. A análise de qualidade pode envolver diversas abordagens complementares. Alguns itens de qualidade de um laudo médico : 1. Completo e correto (identificação precisa da doença, CID, prescrição correta dos remédios etc., identificação do paciente _ embora anonimizado -, datas etc.); 2. Nexo causal (diagnóstico/resultado compatível com os dados); 3. Padrões de exames; 4. Linguagem correta; 5. Conclusão (por exemplo, detalhar o que o paciente não consegue fazer) etc. 

- **Domínio da Solução**. O problema pode também considerar várias abordagens técnicas diferentes: 1. Comparativo de modelos; 2. Comparativo de bons e maus laudos (requer a classificação prévia de exemplos); 3. Uso de Modelos gerais ou especializados se houverem; 4. Extração de métricas, como médias e quartis etc.



 
