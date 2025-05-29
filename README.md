# Ferramenta de Simulação de Investimentos em Fundos Imobiliários
Este repositório contém uma planilha interativa desenvolvida em Excel que simula investimentos em FIIs. A ferramenta permite calcular o valor investido, a projeção do patrimônio acumulado e os dividendos mensais, utilizando conceitos avançados do Excel, como juros compostos, variáveis globais, nomeação de intervalos e dashboards. Ideal para investidores iniciantes, o projeto integra teoria e prática, proporcionando visões realistas para a tomada de decisões embasadas.

![Banner](./images/simulador_banner.png)

---

# Ferramenta de Simulação de Investimentos em Fundos Imobiliários

## 1. Descrição do Desafio

Este desafio tem como objetivo aplicar os conceitos de Excel para desenvolver uma ferramenta prática de simulação de investimentos em fundos imobiliários. O desafio consiste na criação de uma planilha que automatiza cálculos complexos, ajudando o usuário a:

- Calcular o valor total a ser investido;
- Projetar o patrimônio acumulado ao longo do tempo;
- Estimar dividendos mensais.

A ferramenta foi pensada para auxiliar investidores — principalmente iniciantes — a tomar decisões mais informadas, respondendo questões essenciais como: **Quanto investir? Por quanto tempo? Quanto será o patrimônio acumulado?**

## 2. Objetivos de Aprendizagem

Ao finalizar este desafio, serão atingidos os seguintes objetivos:

- **Criação de Ferramentas no Excel:** Desenvolver uma planilha que utilize cálculos financeiros e fórmulas avançadas.
- **Aplicação de Cálculos Financeiros:** Empregar funções do Excel para calcular dividendos e projeções de patrimônio.
- **Documentação Técnica:** Registrar detalhadamente o processo de desenvolvimento, facilitando o compartilhamento da experiência no GitHub.
- **Personalização e Escalabilidade:** Estruturar a planilha de forma modular, permitindo futuras expansões e customizações de acordo com diferentes perfis de investidores.

## 3. Conteúdo e Metodologia

O projeto foi desenvolvido com base em diversos tópicos abordados nas aulas, conforme descrito a seguir:

### 3.1 Introdução
- **Propósito:** Apresentar a ideia e os desafios de se criar uma ferramenta prática de simulação de investimentos.
- **Contexto:** Explicitação da importância de se entender os fundos imobiliários e como eles podem impactar as decisões de investimento.

### 3.2 Perguntas de Negócio
- **Principais Questionamentos:**  
  - Quanto investir por mês?
  - Por quantos anos?
  - Taxa de rendimento mensal?
  - Quanto de patrimônio acumulado?
  - Quanto de dividendos mensais?
- **Objetivo:** Essas questões ajudam a definir os parâmetros essenciais da simulação e orientam a construção da planilha para atender às necessidades reais dos investidores.

### 3.3 Pré-Requisitos
Antes de iniciar o desenvolvimento, é importante ter:
- Conhecimento básico e intermediário em Excel;
- Noções de funções financeiras e fórmulas (como juros compostos, funções financeiras, etc.);
- Entendimento de conceitos de organização de dados e dashboards.

### 3.4 Base da Tabela
- **Estrutura Inicial:** Montagem de uma tabela organizada para recolher os principais dados de entrada, como:
  - Salário;
  - Rendimento da carteira;
  - Valor investido por mês;
  - Taxa de rendimento mensal;
  - Tempo de investimento;
  - Perfil de investimento.
- **Objetivo:** Facilitar a atualização dos dados e servir de base para os cálculos subsequentes.

### 3.5 Simulador de Patrimônio
- **Funcionalidade Principal:** Projeção do patrimônio acumulado ao longo do tempo considerando a composição de juros.
- **Benefício:** Permite ao investidor visualizar a evolução de seu capital e o impacto dos juros compostos ao longo dos períodos.

### 3.6 Simulador de Cenários
- **Objetivo:** Mostrar projeção do patrimônio acumulado com variações no tempo de investimento.
- **Aplicação:** Permite comparar cenários de patrimônio acumulado e divivendos mensais, oferecendo uma visão abrangente dos potenciais ganhos.

### 3.7 Variáveis Globais
- **Definição:** Uso de variáveis para centralizar parâmetros essenciais (por exemplo, taxa de rendimento, valor investido, etc.).
- **Vantagem:** Facilita a manutenção e atualizações, pois ao alterar uma variável global, todas as fórmulas dependentes são automaticamente recalculadas.

### 3.8 Nomeando Intervalos
- **Por quê?** Nomear intervalos de células ajuda a:
  - Melhorar a legibilidade dos cálculos;
  - Tornar as fórmulas mais intuitivas e fáceis de manter.
- **Exemplo:** Em vez de usar referências como `A2:A10`, pode-se nomear o intervalo como `Investimentos`.

### 3.9 Criando Uniformidade Visual
- **Práticas Utilizadas:**
  - Uso de esquemas de cores e layouts padronizados para criar um ambiente de fácil interpretação;
  - Criação de dashboards e gráficos que sintetizam as informações e resultados.
- **Resultado:** Melhor experiência visual e usabilidade da planilha.

### 3.10 Tipos de Fundo de Investimento (FII)
- **Conteúdo Abordado:**
  - Diferenciação entre tipos de fundos (ex.: Fundos de Renda, de Desenvolvimento, de Papel, etc.);
  - Definição da recomendação de diferentes tipos de fundos FII a partir do perfil de investidor.
- **Aplicação:** A ferramenta permite realizar sugestões de investimentos por tipo de fundo de acordo com o perfil de investimento selecionado.

## 4. Estrutura do Projeto

A organização do repositório segue a estrutura abaixo:

```
├── README.md
├── perguntas_negocio.txt
├── Simulador_Investimentos_FII.xlsx
└── images/
    ├── simulador_banner.png
    ├── simulador_cenarios_recomendacoes.png
    └── simulador_entradas.png
```

- **README.md:** Este arquivo de documentação.
- **perguntas_negocio.txt:** Arquivo com perguntas de negócio consideradas para criação da ferramenta.
- **Simulador_Investimentos_FII.xlsx:** A planilha com a ferramenta de simulação.
- **/images:** Pasta destinada a armazenar capturas de tela, diagramas e demais recursos visuais que comprovem o funcionamento e a organização do projeto.

## 5. Instruções de Uso

Para aproveitar ao máximo a ferramenta, siga os passos abaixo:

1. **Abrir a Planilha:**  
   Inicie o Microsoft Excel e abra o arquivo `Simulador_Investimentos_FII.xlsx`.

2. **Configuração Inicial:**  
   Insira as informações necessárias na ferramenta:
   - Salário.
   - Rendimento Carteira.
   - Quanto investir por mês?
   - Por quantos anos?
   - Taxa de rendimento mensal?
   - Perfil.

3. **Realização das Simulações:**  
   - **Simulador de Patrimônio:** Visualize a projeção do patrimônio acumulado ao longo do período definido.
   - **Simulador de Cenários:** Visualize a projeção do patrimônio acumulado ao longo de diferentes períodos pré-definidos.
   - **Sugestor de Investimentos:** Teste diferentes sugestões de investimentos por tipo de FII de acordo com o seu perfil de investidor.

4. **Análise Visual:**  
   Utilize os gráficos e dashboards incorporados para interpretar as simulações de forma prática e intuitiva.

5. **Personalização:**  
   Caso deseje expandir ou adaptar a planilha, ajuste as variáveis globais e intervalos nomeados conforme necessário.

## 6. Documentação Técnica

Durante o desenvolvimento deste projeto, foram aplicados diversos conceitos e boas práticas:

- **Cálculos Financeiros e Funções do Excel:**  
  Utilização de fórmulas para o cálculo de dividendos e projeção de patrimônio e recomendação dinâmica de investimento de acordo com o perfil de investidor selecionado, além da Utilização de validação de dados para seletor de perfil de investidor.

- **Organização dos Dados:**  
  Estruturação da planilha com uma base organizada e módulos específicos (dados de entrada, simuladores, gráficos).

- **Visualização dos Dados:**  
  Criação de dashboards e aplicação de formatações que melhoram a credibilidade e interpretabilidade dos resultados.

- **Boas Práticas de Manutenção:**  
  Uso de variáveis globais e nomenclatura para intervalos, facilitando ajustes e atualizações futuras.

## 7. Lições Aprendidas

O desenvolvimento deste projeto evidenciou diversos aprendizados importantes:

- **Planejamento e Organização:**  
  Estruturar a planilha de forma modular ajuda tanto na construção quanto na manutenção do projeto.

- **Integração da Teoria com a Prática:**  
  A aplicação de conceitos de Excel resulta em uma ferramenta robusta e útil para a tomada de decisões.

- **Importância da Documentação:**  
  Registrar cada etapa do desenvolvimento, inclusive os desafios e soluções encontradas, facilita a compreensão do projeto e a colaboração com outros profissionais por meio do GitHub.

## 8. Conclusão

Este projeto demonstra como os conhecimentos adquiridos em Excel podem ser aplicados na criação de uma ferramenta prática e eficaz para simulação de investimentos em fundos imobiliários. Ao automatizar cálculos complexos e oferecer uma visualização clara dos potenciais retornos, a planilha se torna uma ferramenta valiosa para investidores que buscam decisões mais embasadas e informadas.

## 9. Contato

Para mais informações, dúvidas ou sugestões, você pode entrar em contato por meio dos seguintes canais:

- **GitHub:** [anapcrodrigues](https://github.com/anapcrodrigues)
- **E-mail:** anapaulacrodrigues@gmail.com

---

*Desenvolvido por Ana Paula Costa Rodrigues @ 2025-05-28*

---
