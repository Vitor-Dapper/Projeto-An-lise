# Nome do Projeto

Este projeto é uma aplicação Java que utiliza **Swing**, **Apache POI**, **JFreeChart**, **Log4j**, **Apache Commons**, **Criptografia**, e **STDDraw**. O objetivo é criar uma interface gráfica (GUI) interativa com menus, gráficos dinâmicos, funcionalidades de criptografia e a capacidade de desenhar formas geométricas. O sistema foi projetado para ser fácil de usar e oferece recursos como:

- Interface gráfica com **JFrame** e **JInternalFrame**.
- **Gráficos** gerados com a biblioteca **JFreeChart**.
- Funcionalidades de **criptografia** para segurança de dados.
- Desenhos gráficos interativos utilizando a biblioteca **STDDraw**.
- Manipulação de **planilhas Excel** com **Apache POI**.

## Tecnologias Utilizadas

Este projeto faz uso das seguintes bibliotecas e ferramentas:

- **Swing**: Para criar interfaces gráficas, incluindo menus e janelas internas (`JFrame`, `JInternalFrame`).
- **Apache POI**: Para leitura e escrita de arquivos Excel.
- **JFreeChart**: Para criação de gráficos interativos.
- **Log4j**: Para registro de logs e monitoramento da execução da aplicação.
- **Apache Commons Collections**: Para manipulação eficiente de coleções.
- **Criptografia**: Para proteger dados sensíveis.
- **STDDraw**: Para desenhar formas e gráficos simples na tela.

## Dependências

Aqui estão as dependências necessárias para rodar o projeto. Você pode gerenciá-las usando o Maven.

```xml
<dependencies>
    <!-- Apache POI (para manipulação de arquivos Excel) -->
    <dependency>
        <groupId>org.apache.poi</groupId>
        <artifactId>poi</artifactId>
        <version>5.2.3</version> <!-- Verifique se há uma versão mais recente -->
    </dependency>
    <dependency>
        <groupId>org.apache.poi</groupId>
        <artifactId>poi-ooxml</artifactId>
        <version>5.2.3</version>
    </dependency>
    
    <!-- Apache Commons Collections (para manipulação de coleções) -->
    <dependency>
        <groupId>org.apache.commons</groupId>
        <artifactId>commons-collections4</artifactId>
        <version>4.4</version>
    </dependency>
    
    <!-- Log4j (para geração de logs) -->
    <dependency>
        <groupId>org.apache.logging.log4j</groupId>
        <artifactId>log4j-core</artifactId>
        <version>2.20.0</version> <!-- Verifique se há uma versão mais recente -->
    </dependency>
    <dependency>
        <groupId>org.apache.logging.log4j</groupId>
        <artifactId>log4j-api</artifactId>
        <version>2.20.0</version>
    </dependency>
    
    <!-- JFreeChart (para criação de gráficos) -->
    <dependency>
        <groupId>jfree</groupId>
        <artifactId>jfreechart</artifactId>
        <version>1.0.13</version>
    </dependency>

    <!-- STDDraw (para desenhos gráficos) -->
    <dependency>
        <groupId>edu.princeton.cs</groupId>
        <artifactId>stddraw</artifactId>
        <version>1.0.0</version>
    </dependency>
</dependencies>
