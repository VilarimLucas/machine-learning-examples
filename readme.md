# Guia de Configuração do Ambiente Virtual em Python

Este guia fornece instruções passo a passo sobre como configurar e usar um ambiente virtual em Python para o seu projeto. Utilizar um ambiente virtual é uma prática recomendada para isolar as dependências do projeto e manter a consistência entre diferentes ambientes de desenvolvimento.

## Pré-requisitos

Antes de começar, certifique-se de ter o Python instalado em seu sistema. Você pode verificar isso executando o comando `python --version` no prompt de comando para ver a versão instalada.

## Criação do Ambiente Virtual

Para criar um ambiente virtual para o seu projeto, siga estes passos:

1. **Navegue até o diretório do seu projeto:**
   Abra o prompt de comando e navegue até a pasta onde você deseja criar o ambiente virtual. Por exemplo:

```bash

cd exemplo2

```

2. **Crie o ambiente virtual:**
Execute o seguinte comando para criar um ambiente virtual na pasta `.venv` dentro do seu diretório atual:

```bash

python -m venv .venv

```


## Ativação do Ambiente Virtual

Uma vez criado, você precisa ativar o ambiente virtual para usar as bibliotecas Python isoladas. Para ativar o ambiente virtual, use o seguinte comando:

```bash

.\.venv\Scripts\activate

```


Após a ativação, o nome do ambiente virtual (`.venv`) aparecerá no seu prompt, indicando que todas as operações de Python e `pip` estão isoladas dentro deste ambiente.

## Instalando Dependências

Com o ambiente virtual ativado, você pode instalar as dependências necessárias usando `pip`. Por exemplo:


```bash

pip install nome_da_biblioteca

```

## Instalando Dependências utilizando o requirements.txt

Com o ambiente virtual ativado, você pode instalar as dependências necessárias usando `pip`. Por exemplo:

```bash

pip install -r requirements.txt

```
## Desativação do Ambiente Virtual

Para sair do ambiente virtual e voltar ao ambiente Python global, use o comando:

```bash

deactivate

```


Após executar `deactivate`, o prompt voltará ao normal, indicando que o ambiente global está ativo.

## Conclusão

Seguindo estas instruções, você pode facilmente configurar e gerenciar ambientes virtuais para seus projetos Python, garantindo que as dependências estejam isoladas e que seu ambiente de desenvolvimento seja tão limpo e controlado quanto possível.

