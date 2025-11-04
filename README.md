# 🧪 Priorização de Hipóteses, Teste A/B e Análise de Resultados - Loja Online

## 📊 Descrição do Conjunto de Dados
O projeto utiliza três conjuntos principais de dados fornecidos por uma loja online, contendo:

1. **Hipóteses de marketing** com informações sobre:
   - Reach (alcance): número de usuários impactados;
   - Impact (impacto): força esperada da melhoria na experiência do usuário;
   - Confidenc` (confiança): grau de certeza sobre o impacto estimado;
   - Effort (esforço): custo ou complexidade para implementar a hipótese.

2. **Resultados do Teste A/B**:
   - Registros de visitantes, transações e receita por grupo (A e B);
   - Datas e valores de pedidos;
   - Identificação de duplicidades entre grupos para evitar contaminação dos resultados.

O período do teste abrange várias semanas, permitindo comparar o desempenho cumulativo dos dois grupos em termos de receita, ticket médio e taxa de conversão.

## 🧠 Objetivos da Análise
O objetivo principal deste projeto é identificar e validar oportunidades de crescimento para a loja online por meio de:

1. **Priorização de hipóteses** com base em frameworks quantitativos (ICE e RICE);
2. **Execução e avaliação de um teste A/B** para validar a hipótese de maior potencial;
3. **Análise estatística dos resultados**, garantindo a robustez das conclusões obtidas.

O estudo visa oferecer recomendações estratégicas baseadas em dados para otimização de conversão e aumento de receita.

## 🛠️ Tecnologias Utilizadas
O projeto foi desenvolvido em **Python**, utilizando as seguintes bibliotecas:

- **Pandas** → manipulação e limpeza de dados  
- **NumPy** → cálculos e análise numérica  
- **Matplotlib** e **Seaborn** → visualização de dados e análise exploratória  
- **SciPy** → testes estatísticos e cálculo de significância  
- **Jupyter Notebook** → ambiente de análise e documentação  


## 📈 Principais Insights e Conclusões

### 🔹 Priorização de Hipóteses
- A aplicação dos frameworks ICE e RICE resultou em ordens diferentes de prioridade.
- O fator Reach (alcance) teve forte impacto na priorização via RICE, destacando a Hipótese 7 como a mais promissora: Adicionar um formulário de inscrição em todas as páginas principais para criar uma lista de e-mails.

### 🔹 Teste A/B
- **Duplicidades removidas:** 58 usuários estavam presentes em ambos os grupos e foram excluídos para evitar viés.  
- **Receita acumulada:** o grupo B apresentou receita consistentemente superior ao grupo A durante o período do teste.  
- **Ticket médio:** após o dia 18/08/2019, o grupo B manteve ticket médio maior, possivelmente influenciado por um pedido atípico (outlier).  
- **Conversão:** o grupo B apresentou taxa de conversão ligeiramente superior, confirmando a eficácia da mudança testada.  

### 🔹 Conclusão
O teste A/B validou a hipótese de que a adição de um formulário de inscrição aumenta o engajamento e a receita.  
Os resultados foram estatisticamente significativos, sugerindo manter e expandir a implementação dessa funcionalidade em todo o site.
