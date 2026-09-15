# miniguia-estudos-notebooklm

Contexto e Objetivos: O assunto de interesse escolhido para este caderno temático é a **Análise Comparativa e Evolutiva das Arquiteturas de Processadores RISC (** **Reduced Instruction Set Computer** **) e CISC (** **Complex Instruction Set Computer** **)**, com foco no papel da **ISA (** **Instruction Set Architecture** **)** como o contrato lógico essencial entre o software e o silício físico. 
**Centralização de Conhecimento ("Segundo Cérebro"):** Estruturar uma base de consulta técnica unificada — reunindo artigos, vídeos, pesquisas acadêmicas e documentações de mercado — para fundamentar e dar suporte ao desenvolvimento de um **trabalho acadêmico**

Curadoria de Fontes: ### **Evaluating the Apple Silicon M-Series SoCs for HPC Performance and Efficiency** *(PDF / Artigo Científico - arXiv)*

* **Link de Acesso:** [arXiv:2502.05317v1 (Abstract)](https://www.google.com/url?sa=E&amp;q=https%3A%2F%2Farxiv.org%2Fabs%2F2502.05317v1) | [Download PDF](https://www.google.com/url?sa=E&amp;q=https%3A%2F%2Farxiv.org%2Fpdf%2F2502.05317v1)[1]
* **Resumo:** Este artigo de pesquisa investiga as características arquiteturais e o potencial de desempenho das gerações de chips Apple Silicon (M1, M2, M3 e M4) aplicados à Computação de Alto Desempenho (HPC)[2]. A publicação analisa a arquitetura de memória unificada, o consumo elétrico medido em Watts e a aceleração gráfica e matricial (AMX)[1][2].

### 2\. **3.1\. RVA23 Profiles :: RISC-V Ratified Specifications Library** *(PDF / Documentação Técnica Aberta)*

* **Link de Acesso:** [Especificação Oficial RVA23 (PDF)](https://www.google.com/url?sa=E&amp;q=https%3A%2F%2Fdocs.riscv.org%2Freference%2Frva23%2Fv1.0%2F%5Fattachments%2Frva23-profile.pdf)[3] | [Documentação do Perfil](https://www.google.com/url?sa=E&amp;q=https%3A%2F%2Fdocs.riscv.org%2Freference%2Frva23%2Fv1.0%2Frva23-profiles.html)[4]
* **Resumo:** Documento técnico oficial da RISC-V International que define os padrões do perfil RVA23 para processadores de aplicação em 64 bits[3][4]. Ele detalha as bases e extensões de instrução obrigatórias (como vetores `V` e hypervisor `H`), estabelecendo a linha de base necessária para garantir portabilidade de binários em distribuições Linux e Android[4][5].

### 3\. **Reduced Instruction Set Computers** *(PDF / Capítulo Técnico Acadêmico)*

* **Resumo:** Documento em PDF voltado à fundamentação teórica da revolução RISC[6]. Apresenta dados históricos sobre a contagem de transistores, número de estágios de pipeline, frequências de operação e taxas de execução (*issue rate*) de processadores históricos, contrastando a simplicidade de execução com a complexidade do microcódigo em sistemas tradicionais[6][7].

### 4\. **Marks EU RVA23 Keynote - RISC-V Summit Europe** *(PDF / Apresentação de Keynote)*

* **Resumo:** Apresentação em PDF exibida no *RISC-V Summit Europe* focada no impacto do perfil RVA23 em infraestruturas de servidores e data centers[8][9]. O material aborda a padronização de software entre fabricantes, suporte a virtualização de alta escala e extensões para criptografia vetorial[8].

E foi usado também um documento de docx com o nosso artigo que será apresentado e entregue junto a apresentação academica. 

---

Engenharia de Prompts e "Cicatrizes": Intuito do agente 

Crie um segundo cérebro de conhecimento, a partir de todas as fontes anexadas neste notebook e crie um agente que tenha um vasto conhecimento em Arquitetura RISC e CISC. De uma maneira mais descontraída e atual. Em um tom mais jovial e moderno para que fique claro e seja dinâmico para qualquer publico que deseje saber sobre este conhecimento. 

Este agente tem como papel, servir para o nosso trabalho acadêmico a respeito das Arquiteturas RISC e CISC ! 

Foi criado e usado este arquivo de texto para explicar o intuito deste agente para o nosso trabalho acadêmico e treinamento do bootcamp. E como dito anteriormente usei o nosso próprio artigo para servir de exemplo sobre qual tema estamos falando e o tipo de linguagem usar. E pode ver as respostas geradas por este agente nas linhas acima que pesguntei a ele para já entregar um material completo de como ele ficou e as respostas. 

Miniguia de Estudo: O Poder do NotebookLM
1. Resumos Estruturados do Assunto
O Conceito de um "Agente Focado": O NotebookLM funciona como um assistente de estudos altamente especializado. Ao alimentar a ferramenta com fontes específicas (artigos, sites e vídeos reais), o modelo filtra seu "pensamento" para atuar exclusivamente dentro daquele contexto. Isso garante respostas muito mais precisas e focadas no tema escolhido.

Embasamento e Confiabilidade: Diferente de IAs generativas abertas, que podem "alucinar" ou trazer informações genéricas, o NotebookLM cria respostas com base estrita no material fornecido. Ele aponta exatamente de onde tirou cada informação, o que traz muita segurança para quem está estudando.

Personalização do Aprendizado (Persona): Uma das maiores vantagens da ferramenta é a capacidade de moldar a forma como a IA se comunica. Ao definir instruções claras de formato — como pedir um tom descontraído, jovial, claro e sem termos técnicos excessivos —, o aprendizado se torna muito mais leve, dinâmico e fácil de absorver.

2. Glossário com os Principais Conceitos Aprendidos
Agente / Assistente Especialista: Uma Inteligência Artificial configurada para operar e responder apenas dentro de um escopo de informações predeterminado pelo usuário.

Embasamento (Grounding): A capacidade do modelo de ancorar suas respostas estritamente nas fontes (documentos, links) fornecidas, reduzindo o risco de informações falsas ou fora de contexto.

Persona / Instrução de Formato: A personalidade ou estilo de comunicação atribuído à IA (ex: agir como um professor jovem, usar linguagem descontraída, evitar jargões).

Fontes de Dados (Sources): O conjunto de materiais reais (PDFs, sites, vídeos) que o usuário faz o upload e que servem de "cérebro" para as respostas do NotebookLM.

3. Conjunto de Prompts Reutilizáveis para Revisões
(Estes prompts foram desenhados pensando no tom descontraído e jovial que você configurou no seu projeto)
