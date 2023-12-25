# Sistema de de gerenciamento de tarefas
> Este aplicativo de gerenciamento de tarefas permite aos usuários criar e gerenciar tarefas e registrar logs de horas trabalhadas.
> 
 ![image](https://user-images.githubusercontent.com/17109060/32149040-04f3125c-bd25-11e7-8003-66fd29bc18d4.png)

## Conteúdo

- [Funcionalidades específicas](#funcionalidades-específicas)
- [Tecnologias empregadas](#funcionalidades-especificas)
- [Tecnologias empregadas](#tecnologias-empregadas)
- [Instalação](#instalação)
- [Exemplo de Uso](#exemplo-de-uso)
- [Development Setup](#development-setup)
- [Release History](#release-history)
- [Meta](#meta)
- [Contributing](#contributing)
  

## 🧰Funcionalidades específicas
[(Back to top)](#table-of-contents)
- Criação, listagem, atualização e exclusão de tarefas com os seguintes campos: título, descrição, data de vencimento.
- Conclusão de uma tarefa salvando a data/hora do encerramento.
- Registro das horas trabalhadas em uma tarefa, incluindo a data de realização, quantidade de horas e um comentário. 
- Visualização de horas trabalhadas em uma tarefa específica.
- Geração de gráfico exibindo a quantidade de tarefas concluídas por dia.

## 🚀Tecnologias empregadas
[(Back to top)](#table-of-contents)
-  [NestJS](https://nestjs.com/) - Na construção na API REST.
- [TypeORM](https://typeorm.io/) - Na integração com banco de dados PostgreSQL.
- [Angular14](https://angular.io/) e [Angular Material](https://material.angular.io/) - Na construção da interface de usuário.

## ♟️ Instalação
[(Back to top)](#table-of-contents)
OS X & Linux:

```sh
npm install my-crazy-module --save
```

Windows:

```sh
edit autoexec.bat
```

## 💡 Exemplo de uso
[(Back to top)](#table-of-contents)
A few motivating and useful examples of how your product can be used. Spice this up with code blocks and potentially more screenshots.

_For more examples and usage, please refer to the [Wiki][wiki]._

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://user-images.githubusercontent.com/25423296/163456776-7f95b81a-f1ed-45f7-b7ab-8fa810d529fa.png">
  <source media="(prefers-color-scheme: light)" srcset="https://user-images.githubusercontent.com/25423296/163456779-a8556205-d0a5-45e2-ac17-42d089e3c3f8.png">
  <img alt="Shows an illustrated sun in light mode and a moon with stars in dark mode." src="https://user-images.githubusercontent.com/25423296/163456779-a8556205-d0a5-45e2-ac17-42d089e3c3f8.png">
</picture>

## Development setup
[(Back to top)](#table-of-contents)
Describe how to install all development dependencies and how to run an automated test-suite of some kind. Potentially do this for multiple platforms.

```sh
make install
npm test
```

## Release History
[(Back to top)](#table-of-contents)
* 0.2.1
    * CHANGE: Update docs (module code remains unchanged)
* 0.2.0
    * CHANGE: Remove `setDefaultXYZ()`
    * ADD: Add `init()`
* 0.1.1
    * FIX: Crash when calling `baz()` (Thanks @GenerousContributorName!)
* 0.1.0
    * The first proper release
    * CHANGE: Rename `foo()` to `bar()`
* 0.0.1
    * Work in progress

## Meta
[(Back to top)](#table-of-contents)
Your Name – [@YourTwitter](https://twitter.com/dbader_org) – YourEmail@example.com

Distributed under the XYZ license. See ``LICENSE`` for more information.

[https://github.com/yourname/github-link](https://github.com/dbader/)

## Contributing
[(Back to top)](#table-of-contents)
1. Fork it (<https://github.com/yourname/yourproject/fork>)
2. Create your feature branch (`git checkout -b feature/fooBar`)
3. Commit your changes (`git commit -am 'Add some fooBar'`)
4. Push to the branch (`git push origin feature/fooBar`)
5. Create a new Pull Request

<!-- Markdown link & img dfn's -->
[npm-image]: https://img.shields.io/npm/v/datadog-metrics.svg?style=flat-square
[npm-url]: https://npmjs.org/package/datadog-metrics
[npm-downloads]: https://img.shields.io/npm/dm/datadog-metrics.svg?style=flat-square
[travis-image]: https://img.shields.io/travis/dbader/node-datadog-metrics/master.svg?style=flat-square
[travis-url]: https://travis-ci.org/dbader/node-datadog-metrics
[wiki]: https://github.com/yourname/yourproject/wiki
