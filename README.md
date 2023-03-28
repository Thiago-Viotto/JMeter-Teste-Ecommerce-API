# JMeter Teste Ecommerce
 
## Objetivo
Projeto pessoal utilizando o JMeter. Neste projeto você encontrará:
- Plano de teste com os cenários
- Arquivo separado por cenários
- Plugins de relatório em tempo real
- Cabeçalhos HTTP
- Asserção de resposta
- Arquivo CSV - massa de dados
- Relatório de execução como o de sumário e a árvore de resultado

## Setup
- Instalar [jmeter](https://jmeter.apache.org/download_jmeter.cgi)

## Execução
Pela linha de comando (recomendado):
- n: indica que o JMeter não precisa inicializar sua interface gráfica;
- t: indica qual o Plano de Teste vai ser utilizado (.jmx);
- l: indica qual arquivo irá salvar o resultado do teste (.jtl);
- e: gera um relatório após a execução do teste;
- o: indica onde o relatório será salvo (esta pasta precisa estar vazia ou não existir).

Ex: jmeter -n -t "..\TesteEcommerce.jmx" -l "..\resultados.jtl" -e -o "..\resultados"

Pela interface:
- Abrir arquivo "Teste Ecommerce.jmx" no Jmeter
- Clicar no play
- Resultado esperado: Relatório e Árvore de execução com rotas em verde

## Vídeo do projeto
![20230328_113531](https://user-images.githubusercontent.com/30843151/228274441-0d3b0fb1-01f8-435a-aae2-bebad073880a.gif)

## Contato
- Email: thiagohenriqueviotto1@gmail.com 
- Linkedin: https://www.linkedin.com/in/thiago-henrique-viotto-4485b5147/

