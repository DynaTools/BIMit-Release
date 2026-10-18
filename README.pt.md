[Italiano](README.md) · **Português** · [English](README.en.md)

# BIMit — plugin para Autodesk Revit

[![Última versão](https://img.shields.io/github/v/release/DynaTools/BIMit-Release?label=vers%C3%A3o)](https://github.com/DynaTools/BIMit-Release/releases/latest)
![Revit 2022–2026](https://img.shields.io/badge/Revit-2022%E2%80%932026-0696D7)
![Windows 10 | 11](https://img.shields.io/badge/Windows-10%20%7C%2011-555)

O BIMit atribui a **EAP (WBS)** aos elementos do modelo, exporta **folhas e vistas** em todos os
formatos de uma só vez e acrescenta ao Revit as ferramentas que faltam para **parâmetros**,
**modelo** e instalações **MEP**. Com o **Claude (MCP)** você também pode pedir ao Claude que faça
isso por você, em português.

Durante a **beta** o BIMit é gratuito.

**[Baixar a última versão (MSI)](https://github.com/DynaTools/BIMit-Release/releases/latest)** ·
[Guia](https://unibim.io/pt/bimit/guia/) · [unibim.io/pt/bimit](https://unibim.io/pt/bimit/)

## O que faz

| Ferramenta | O que faz |
|---|---|
| **WBS** | Parta da WBS normativa ou de uma estrutura sua, defina os parâmetros uma vez para todo o projeto, mude só o necessário em cada categoria, confira a pré-visualização e grave no modelo. |
| **Exportar folhas e vistas** | PDF, DWG, DGN, DWF, NWC, IFC e imagens de uma só vez: formato do papel a partir do carimbo, nomes dos arquivos a partir dos parâmetros, só as folhas novas ou com revisão alterada, fila, relatório, exportações agendadas, lista de documentos em Excel, perfis para compartilhar com a equipe. |
| **Parâmetros** | Adicione parâmetros compartilhados a todas as categorias que escolher, encontre e exclua parâmetros de projeto vazios ou inúteis, remova das famílias carregadas os parâmetros que não servem. |
| **Modelo** | Desafixe os elementos fixados categoria por categoria, mova um nível com tudo o que depende dele, exporte o modelo em tabelas CSV para um assistente de IA. |
| **MEP** | Luvas e furos onde as instalações atravessam paredes, lajes, vigas e outros elementos; linhas de separação de espaços a partir do contorno dos ambientes de um modelo vinculado. |
| **Claude (MCP)** | Conecte o Claude com a sua conta: ele usa todas as ferramentas do BIMit no modelo aberto, também em vários Revit abertos ao mesmo tempo. Cada alteração se desfaz com Ctrl+Z. |

## Requisitos

- Windows 10 ou 11
- Autodesk Revit 2022, 2023, 2024, 2025 ou 2026
- Uma conta BIMit, que você cria no plugin na primeira execução

## Instalação

1. Feche o Revit.
2. Baixe `BIMit_Setup_<versão>.msi` da [última release](https://github.com/DynaTools/BIMit-Release/releases/latest).
3. Abra-o com um duplo clique. **Não são necessárias permissões de administrador**: o BIMit é
   instalado para o seu usuário, em todas as versões do Revit presentes.
4. Abra o Revit: você encontra a guia **BIMit**.

### Instalador assinado digitalmente

O instalador é assinado com um certificado de assinatura de código **Certum** em nome de
**GIAVONI PAULO AUGUSTO**. Para verificar: clique com o botão direito no arquivo `.msi` →
*Propriedades* → *Assinaturas Digitais*. Se o Windows SmartScreen mostrar um aviso, confira se o
editor é GIAVONI PAULO AUGUSTO e escolha *Mais informações* → *Executar assim mesmo*.

## Atualizações

Automáticas: o BIMit baixa a nova versão, verifica a integridade e a instala quando você fecha o Revit.

## Desinstalação

*Configurações do Windows* → *Aplicativos* → *Aplicativos instalados* → **BIMit** → *Desinstalar*.
Para excluir também a conta e os dados: no Revit, *BIMit* → *Conta* → *Excluir conta*.

## Guia e documentos

| | Italiano | Português | English |
|---|---|---|---|
| Guia | [Guida](https://unibim.io/it/bimit/guida/) | [Guia](https://unibim.io/pt/bimit/guia/) | [Guide](https://unibim.io/en/bimit/guide/) |
| Privacidade | [Informativa privacy](https://unibim.io/it/bimit/privacy/) | [Privacidade](https://unibim.io/pt/bimit/privacidade/) | [Privacy](https://unibim.io/en/bimit/privacy/) |
| Termos | [Termini d'uso](https://unibim.io/it/bimit/termini/) | [Termos de uso](https://unibim.io/pt/bimit/termos/) | [Terms of use](https://unibim.io/en/bimit/terms/) |

O guia também se abre pelo botão **Guia** em cada janela do plugin, na seção certa.

## Suporte

- No plugin: botão **Feedback** no alto de cada janela.
- E-mail: paulo.giavoni@gmail.com

---

© DynaTools · Autodesk e Revit são marcas registradas da Autodesk, Inc. O BIMit não é afiliado
nem endossado pela Autodesk.
