# Azuos PDV — Releases

Instaladores e `latest.json` do Azuos PDV. O código-fonte fica em repositório privado.

**Não edite este repositório à mão.** Cada release é publicado pelo workflow
`release.yml` do `AzuosDev/uSolutionsPDV` ao receber uma tag `v*`.

## Instalação

Baixe o `Azuos.PDV_x.y.z_x64-setup.exe` do [release mais recente](../../releases/latest)
e execute. Para atualizar uma instalação existente não é preciso desinstalar: rode o
instalador novo por cima.

## Atualização automática

O PDV consulta `releases/latest/download/latest.json` ao abrir e, havendo versão nova
assinada, instala e reabre sozinho.
