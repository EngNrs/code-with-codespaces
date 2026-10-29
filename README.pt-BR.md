# Configurar o VS Code para Português (pt-BR)

Siga estes passos para alterar a interface do VS Code para Português do Brasil.

1. Instalar a extensão (recomendado):

- Abra a visão de Extensões (`Ctrl+Shift+X`) e procure por "Portuguese (Brazil) Language Pack".
- Instale a extensão com ID `MS-CEINTL.vscode-language-pack-pt-BR`.

2. Alternativa (linha de comando):

```powershell
code --install-extension MS-CEINTL.vscode-language-pack-pt-BR
```

3. Definir o idioma da interface:

- Abra a Paleta de Comandos (`Ctrl+Shift+P`) e execute `Configure Display Language`.
- Selecione `pt-BR` na lista e reinicie o VS Code quando solicitado.

4. Observações:

- A recomendação de extensão foi adicionada ao workspace em `.vscode/extensions.json` e aparece na visão de Extensões.
- A alteração do idioma é feita no nível do usuário; o workspace só pode recomendar a extensão.
