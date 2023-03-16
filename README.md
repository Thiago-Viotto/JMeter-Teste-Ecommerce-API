# JMeter Teste Ecommerce
 
## Objetivo

Projeto pessoal utilizando o JMeter. Neste projeto você encontrará:
- Plano de teste com os cenários
- Arquivo separado por cenários
- Relatório de execução como o de sumário e a árvore de resultado

## Setup
- Instalar [jmeter](https://jmeter.apache.org/download_jmeter.cgi)

## Execução
Pela linha de comando (recomendado):
-n: indica que o JMeter não precisa inicializar sua interface gráfica;
-t: indica qual o Plano de Teste vai ser utilizado (.jmx);
-l: indica qual arquivo irá salvar o resultado do teste (.jtl);
-e: gera um relatório após a execução do teste;
-o: indica onde o relatório será salvo (esta pasta precisa estar vazia ou não existir).

Ex: jmeter -n -t "C:\Users\thiag\Documents\Github\JMeter-Teste-Ecommerce\TesteEcommerce.jmx" -l "C:\Users\thiag\Documents\Github\JMeter-Teste-Ecommerce\resultados.jtl" -e -o "C:\Users\thiag\Documents\Github\JMeter-Teste-Ecommerce\resultados"

Pela interface:
- Abrir arquivo 'Teste Ecommerce.jmx' no Jmeter
- Clicar no play
- Resultado esperado: Relatório e Árvore de execução com rotas em verde

## Vídeo do projeto
Em breve

## Contato
- Email: thiagohenriqueviotto1@gmail.com 
- Linkedin: https://www.linkedin.com/in/thiago-henrique-viotto-4485b5147/

