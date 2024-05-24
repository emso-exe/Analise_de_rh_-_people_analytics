# 🔎 Análise de Recursos Humanos - People Analytics 👥

Este projeto utiliza dados disponibilizados no [Kaggle](https://www.kaggle.com/datasets/2e87aca9cfb969c5d6e89dbba2aba6d7b5a3cb769e43608a247859512197917d) sobre "People Analytics aplicados a RH e CRM". O objetivo é analisar informações de funcionários, avaliações sobre o ambiente de trabalho e outros dados relevantes para identificar perfis de colaboradores propensos a deixar a empresa.

Será empregada a metodologia CRISP-DM, e um modelo preditivo será desenvolvido para identificar os grupos mais propensos ao desligamento, oferecendo insights e sugerindo soluções para os problemas identificados. O foco é reduzir a saída de colaboradores e aprimorar a retenção de talentos.

## Contexto do problema

A _RetaiX_, com uma equipe de aproximadamente **4000 funcionários**, enfrenta uma alta **rotatividade anual de cerca de 15%**. Essa taxa de saída, seja por vontade própria ou demissão, é considerada prejudicial pela gestão, devido a:

- Impacto negativo nos prazos, afetando a reputação da empresa perante consumidores e parceiros;
- Necessidade de manter um departamento significativo para recrutamento;
- Requerimento de treinamento e período de adaptação para os novos funcionários.

## 💼 Demanda do negócio

- Analisar os dados para identificar padrões de comportamento dos funcionários (obter personas);
- Identificar as variáveis que mais influenciam na alta rotatividade dos funcionários;
- Calcular a probabilidade de um funcionário deixar a empresa e identificar as variáveis que mais contribuem para esse aumento;
- Elaborar um relatório com as conclusões para que o gestor de RH possa tomar medidas para reduzir a rotatividade.

## 📋 Tópicos da análise

-
-
-
-

## 📃 Compreensão dos dados

Os dados que serão utilizados no Projeto de Análise de Recursos Humanos - People Analytics.

## 📓 Dicionário de dados

| Variáveis | Descrição | Domínios |
|------------------------------|------------------------------|------------------------------|
| Idade                        | Idade do funcionário | |
| Rotatividade                 | Se o funcionário deixou a empresa no ano anterior ou não | |
| ViagensDeNegocio             | Com que frequência os funcionários viajaram a negócios no último ano | |
| Departamento                 | Departamento na empresa | |
| DistanciaDeCasa              | Distância de casa em quilômetros | |
| Educacao                     | Nível de Educação | 1 'Abaixo do Ensino Superior'<br>2 'Ensino Superior Incompleto'<br>3 'Bacharel'<br>4 'Mestre'<br>5 'Doutor' |
| CampoDeEducacao              | Campo de educação | |
| ContagemDeEmpregados         | Contagem de funcionários | |
| IDDoEmpregado                | Número/ID do funcionário | |
| SatisfacaoComAmbiente        | Nível de Satisfação com o Ambiente de Trabalho | 1 'Baixo'<br>2 'Médio'<br>3 'Alto'<br>4 'Muito Alto' |
| Genero                       | Gênero do funcionário | |
| EnvolvimentoNoTrabalho       | Nível de Envolvimento no Trabalho | 1 'Baixo'<br>2 'Médio'<br>3 'Alto'<br>4 'Muito Alto' |
| NivelDeCargo                 | Nível do cargo na empresa em uma escala de 1 a 5 | |
| NomeFuncao                   | Nome da função na empresa | |
| SatisfacaoNoTrabalho         | Nível de Satisfação no Trabalho | 1 'Baixo'<br>2 'Médio'<br>3 'Alto'<br>4 'Muito Alto' |
| EstadoCivil                  | Estado civil do funcionário | |
| RendaMensal                  | Renda mensal em rúpias por mês | |
| NumeroDeEmpresas             | Número total de empresas pelas quais o funcionário passou | |
| MaiorDe18                    | Se o funcionário é maior de 18 anos ou não | |
| AumentoPercentualSalario     | Percentual de aumento salarial no último ano | |
| AvaliacaoDeDesempenho        | Avaliação de desempenho do último ano | 1 'Baixo'<br>2 'Bom'<br>3 'Excelente'<br>4 'Excepcional' |
| HorasPadrao                  | Horas padrão de trabalho para o funcionário | |
| NivelDeOpcaoDeCompraDeAcoes  | Nível de opção de ações do funcionário | |
| TotalDeAnosTrabalhados       | Número total de anos que o funcionário trabalhou até agora | |
| TreinamentosNoUltimoAno      | Número de vezes que treinamentos foram realizados para este funcionário no último ano | |
| EquilibrioTrabalhoVida       | Nível de equilíbrio entre trabalho e vida pessoal   | 1 'Ruim'<br>2 'Bom'<br>3 'Melhor'<br>4 'Ótimo' |
| AnosNaEmpresa                | Número total de anos que o funcionário passou na empresa | |
| AnosDesdeUltimaPromocao      | Número de anos desde a última promoção | |
| AnosComAtualGestor           | Número de anos sob o gerente atual | |

> fonte: [Kaggle - People Analytics aplicado em RH e CRM](https://www.kaggle.com/datasets/2e87aca9cfb969c5d6e89dbba2aba6d7b5a3cb769e43608a247859512197917d "People Analytics aplicado em RH e CRM")

## 💻 Tecnologias

- Python
    - Biblioteca GC
    - Biblioteca Pandas
    - Biblioteca Matplotlib
    - Biblioteca Seaborn
    - Biblioteca Numpy
    - Biblioteca Warnings
    - Biblioteca PySpark
    - Biblioteca Glob

## 💳 Créditos

- [Estênio Mariano](https://github.com/emso-exe)

## 🔖 Licença

Licença MIT (MIT). Por favor leia o [arquivo da licença](LICENSE.md) para mais informações.
