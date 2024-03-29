# Testes Automatizados para o Método "Create" - Reqres.in

Este projeto contém testes automatizados em Java para o método "create" do site regress.in. Utiliza Java 21 e Gradle com Kotlin para automação de testes.

## Configuração do Ambiente

### Pré-requisitos
- Java 21
- Gradle

### Passos de Configuração

1. **Clone o Repositório:**
   ```bash
   git clone https://github.com/jonataspeixoto/reqres-in-test
   cd seu-repositorio
   ```
2. **Configuração do Ambiente Gradle:**

- Certifique-se de ter o Gradle instalado. Caso não tenha, você pode instalá-lo manualmente ou usar o wrapper do Gradle fornecido no projeto.
- Se estiver usando o wrapper, execute os comandos:
   ```bash
   ./gradlew clean
   ```
3. **Configuração de Variáveis de Ambiente:**

Abra o arquivo `src/test/resources/dev.properties` e ajuste as variáveis de ambiente conforme necessário.

## Executando os Testes
Execute os testes usando o seguinte comando:

   ```bash
   ./gradlew test
   ```
Os resultados dos testes serão exibidos no console.

## Verificando Resultados
Execute o comando abaixo para visualizar o painel allure:

   ```bash
   ./gradlew allureServe
   ```
Será aberta uma página em seu navegador.

Este projeto está licenciado sob a MIT License - veja o arquivo LICENSE.md para detalhes.
