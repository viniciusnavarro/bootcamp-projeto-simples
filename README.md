# Lab de CI com GitHub Actions - Java com Maven

## Objetivo
Configurar uma pipeline de Integração Contínua (CI) com GitHub Actions para um projeto Java com Maven.

## Passo a Passo

1. **Fork este repositório** para a sua conta GitHub.
2. Vá até a aba **Actions** no seu repositório e ative os workflows, se necessário.
3. Faça uma alteração simples no arquivo `HelloWorld.java`, como mudar a mensagem para:
   ```java
   System.out.println("Olá, DevOps!");
   ```
4. Faça o `commit` e `push` dessa alteração.
5. Vá até a aba **Actions** no GitHub e observe o pipeline executando automaticamente.

## O que você vai aprender
- Como configurar um workflow de CI no GitHub Actions
- Como automatizar builds com Maven
- Como verificar logs de execução de pipelines

> Esse lab não contém testes automatizados, apenas a etapa de build.