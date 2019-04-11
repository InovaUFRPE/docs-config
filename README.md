# Documentos de Configuração

> Documentação da equipe de configuração

## Sumário

- [Links Úteis](#links-uteis)
- [Workflow](#workflow)
- [Pull Request Template](#pull-request-template)

## Links Úteis

- [Curso de react-native + firebase](https://www.youtube.com/watch?v=MxXyR0CN4v0)
- [Curso de angular](https://www.youtube.com/watch?v=MxXyR0CN4v0)
- [Curso Node](https://www.youtube.com/watch?v=LLqq6FemMNQ&list=PLJ_KhUnlXUPtbtLwaxxUxHqvcNQndmI4B)


## Workflow

![gitflow](https://cdn-images-1.medium.com/max/1150/1*8-zDz1s5Atux_yNW_mXmfg@2x.png)

0- Atualize a branch develop com o ``` git pull ```

1- Faça a branch da sua atividade **a partir da branch develop** de acordo o tipo seguindo o seguinte padrão:

```
{tipo}/{nome-curto-atividade}
```

- Os espaços deverão ser substituidos por "-";
- O nome deve ser todo minúsculo;
- O tipo da atividade deve ser: 
    - feature
    - bug-fix

2- Ralize sua atividade:

- Faça pequenos commits
- Escreva uma boa mensagem mensagem de commit

3- Suba seu código para o repositório remoto;

- Faça o push da sua branch local para o github

4- Crie seu Pull Request e aguarde a revisão do código;

- Siga o template

## Pull Request Template

O template está em Markdown. Remova as chaves e o conteúdo dentro delas e coloque o texto correspondente.

```

# {tipo}/{nome-curto-atividade}

- **Descrição da atividade**:
    
    { Texto da atividade do redmine }

- **O que foi realizado**:
    
    { Breve descrição do que foi realizado }

- **Pacotes instalados**:

    * { Nome do pacote } - { Motivo }

- **Observações**: 
    
    { Informaçẽos que você achar útil. É importante informar aqui procedimentos novos, como comandos para serem executados, instalação de software... Passos a serem seguidos para realizar alguma ação }

```
