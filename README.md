# prova_ts_selenium
# Prova de Teste de Software com Selenium

Q1:
Selenium IDE é uma ferramenta mais simples, funcionando como uma extensão do navegador, focada em testes sem a necessidade de codificação, pois o seu propósito é de ser uma solução rápida e fácil. Enquanto o Selenium WebDriver é uma API avançada para automação de testes, tendo a necessidade de codificação para maior controle e flexibilidade, sendo ideal para automação de testes em larga escala e para realizar testes complexos e personalizados.

Q2:
No Selenium WebDriver, existem vários tipos de localizadores usados para encontrar elementos em uma página web. Os principais tipos de localizadores são: By.cssSelector, By.name, By.className, By.tagName, By.linkText, By.partialLinkText, By.id, localizador esse que encontra um elemento HTML com base no valor do atributo id do elemento, e By.xpath, que é um localizador baseado na linguagem de consulta XML, permitindo encontrar elementos em qualquer parte do DOM, usando caminhos relativos ou absolutos, e pode incluir atributos, texto ou outros critérios para identificar o elemento.

Q3:
WebElement no Selenium é uma interface que representa um elemento HTML na página web, permitindo que você interaja com o conteúdo e os atributos de um elemento, como clicar, digitar texto, verificar o valor, obter informações, entre outros. Um exemplo do uso de WebElement no python:

Encontrar um elemento (por exemplo, um campo de input) pelo ID 

elemento = driver.find_element(By.id("campoNome")) 

Interagir com o WebElement - digitar texto no campo

elemento.send_keys("Texto de Exemplo") 

Encontrar um botão e clicar nele 

botao = driver.find_element(By.id("botaoEnviar")) botao.click()

Q4:
No Selenium WebDriver, se você tentar interagir com um elemento que ainda não está visível ou carregado na página, ocorrerá uma exceção, geralmente uma ElementNotInteractableException ou NoSuchElementException. E para resolver esse tipo de erro você poderia usar a biblioteca time para poder utilizar o comando time.sleep(), que 
