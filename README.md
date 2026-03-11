links uteis
[guia passo a passo](https://code.visualstudio.com/docs/copilot/getting-started)
[overview](https://code.visualstudio.com/docs/copilot/overview)


sessão local, nuvem ou segundo plano

divisão de sessão por tarefa diferentes

```
Insira estas informações /initpara configurar seu projeto para IA. Isso cria instruções personalizadas que ajudam o agente a entender sua base de código e gerar um código melhor.
```



./github/copilot-instructions.md
(coding preferences and standards. These apply automatically to all chat interactions.;
your project's structure and coding patterns)

``` markdown
# Example

# Project general coding guidelines

## Code Style
- Use semantic HTML5 elements (header, main, section, article, etc.)
- Prefer modern JavaScript (ES6+) features like const/let, arrow functions, and template literals

## Naming Conventions
- Use PascalCase for component names, interfaces, and type aliases
- Use camelCase for variables, functions, and methods
- Prefix private class members with underscore (_)
- Use ALL_CAPS for constants

## Code Quality
- Use meaningful variable and function names that clearly describe their purpose
- Include helpful comments for complex logic
- Add error handling for user inputs and API calls

```

/init (inicializa o arquivo de instruções. usado uma vez no inicio do proj, e depois ir preenchendo e atualizando)

## Custom agent

para usar, selecione no select do chat (canto direito) e mande o prompt
'Review my full project'




