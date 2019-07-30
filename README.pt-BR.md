# [GitHub Desktop](https://desktop.github.com)

[![Travis](https://img.shields.io/travis/desktop/desktop.svg?style=flat-square&label=Travis+CI)](https://travis-ci.org/desktop/desktop)
[![CircleCI](https://img.shields.io/circleci/project/github/desktop/desktop.svg?style=flat-square&label=CircleCI)](https://circleci.com/gh/desktop/desktop)
[![AppVeyor Build Status](https://img.shields.io/appveyor/ci/github-windows/desktop/development.svg?style=flat-square&label=AppVeyor&logo=appveyor)](https://ci.appveyor.com/project/github-windows/desktop/branch/development)
[![Azure DevOps Pipelines Build Status](https://dev.azure.com/github/Desktop/_apis/build/status/Continuous%20Integration)](https://dev.azure.com/github/Desktop/_build/latest?definitionId=3)
[![license](https://img.shields.io/github/license/desktop/desktop.svg?style=flat-square)](https://github.com/desktop/desktop/blob/development/LICENSE)
![90+% TypeScript](https://img.shields.io/github/languages/top/desktop/desktop.svg?style=flat-square&colorB=green)

GitHub Desktop é uma aplicação de codigo aberto baseado em [Electron](https://electron.atom.io)
GitHub app. É escrito em [TypeScript](http://www.typescriptlang.org) e
usuários de [React](https://facebook.github.io/react/).

![GitHub Desktop screenshot - Windows](https://cloud.githubusercontent.com/assets/359239/26094502/a1f56d02-3a5d-11e7-8799-23c7ba5e5106.png)

## Onde posso baixar?
Baixe o instalador oficial para seu sistema operacional:

 - [macOS](https://central.github.com/deployments/desktop/desktop/latest/darwin)
 - [Windows](https://central.github.com/deployments/desktop/desktop/latest/win32)
 - [Windows machine-wide install](https://central.github.com/deployments/desktop/desktop/latest/win32?format=msi)

Você pode instalar ao lado do seu Atual GitHub Desktop

**NOTA**: não há caminho de migração atual para importar seus repositórios existentes para o novo aplicativo - você pode arrastar e soltar seus repositórios do disco para o aplicativo para começar.

### Canal Beta

Quer testar novas funcionalidades antes de todo mundo?, instale o canal beta para obter acesso antecipado as versões do GitHub Desktop

 - [macOS](https://central.github.com/deployments/desktop/desktop/latest/darwin?env=beta)
 - [Windows](https://central.github.com/deployments/desktop/desktop/latest/win32?env=beta)

### Laçamentos da Comunidade

Existe vários package managers que podem ser usados para instalar o GitHub Desktop:
 - Usuários de Windows pode instalar usando [Chocolatey](https://chocolatey.org/) package manager:
      `c:\> choco install github-desktop`
 - Usuários de macOS pode instalar usando [Homebrew](https://brew.sh/) package manager:
      `$ brew cask install github`

Instaladores para várias distros Linux podem ser encontrados no
[`shiftkey/desktop`](https://github.com/shiftkey/desktop) fork.

Usuários do Arch Linux pode instalar a última versão no
[AUR](https://aur.archlinux.org/packages/github-desktop-bin/).

## O GitHub Desktop é adequado para mim? Quais são as principais áreas de enfoque?

[Este documento](https://github.com/desktop/desktop/blob/development/docs/process/what-is-desktop.md) descreve o foco do GitHub Desktop e para quem o produto é mais útil.

E para ver no que a equipe está trabalhando atualmente e no futuro próximo, confira [GitHub Desktop roadmap](https://github.com/desktop/desktop/blob/development/docs/process/roadmap.md).

## Eu tenho um problema com GitHub Desktop

Nota: The [GitHub Desktop Code of Conduct](https://github.com/desktop/desktop/blob/development/CODE_OF_CONDUCT.md) applies in all interactions relating to the GitHub Desktop project.

Primeiro, por favor pesquise as [open issues](https://github.com/desktop/desktop/issues?q=is%3Aopen)
e [closed issues](https://github.com/desktop/desktop/issues?q=is%3Aclosed)
to see if your issue hasn't already been reported (it may also be fixed).

There is also a list of [known issues](https://github.com/desktop/desktop/blob/development/docs/known-issues.md)
that are being tracked against Desktop, and some of these issues have workarounds.

If you can't find an issue that matches what you're seeing, open a [new issue](https://github.com/desktop/desktop/issues/new/choose),
choose the right template and provide us with enough information to investigate
further.

## O problema que relatei ainda não está corrigido, O que eu posso fazer?

Se ninguém respondeu ao seu problema dentro de alguns dias, você pode responder a ele com um ping amigável no problema. Por favor, não responda mais de uma segunda vez se ninguém respondeu. Os mantenedores do GitHub Desktop são limitados em tempo e recursos, e o diagnóstico de configurações individuais pode ser difícil e demorado. Embora tentemos pelo menos apontar na direção certa, não podemos garantir que poderemos investigar profundamente o problema de qualquer pessoa.

## Como eu posso contribuir para o GitHub Desktop?

O Documento [CONTRIBUTING.md](./.github/CONTRIBUTING.md) will help you get setup and
familiar with the source. The [documentation](docs/) folder also contains more
resources relevant to the project.

If you're looking for something to work on, check out the [help wanted](https://github.com/desktop/desktop/issues?q=is%3Aissue+is%3Aopen+label%3A%22help%20wanted%22) label.

## Mais Informações

Veja [desktop.github.com](https://desktop.github.com) para mais orientações e informações sobre GitHub Desktop.

## Licença

**[MIT](LICENSE)**

A concessão de licença do MIT não é para marcas registradas do GitHub, que incluem os designs de logo. O GitHub reserva todos os direitos de marca e direitos autorais em todas as marcas registradas do GitHub. Os logotipos do GitHub incluem, por exemplo, os designs estilizados do Invertocat que incluem "logo" no título do arquivo na seguinte pasta: [logos](app/static/logos).

O GitHub® e suas versões estilizadas e a marca Invertocat são marcas comerciais ou marcas comerciais registradas do GitHub. Ao usar os logotipos do GitHub, siga o GitHub [logo guidelines](https://github.com/logos).
