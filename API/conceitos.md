# Conceitos

## API (Application Programming Interface / Interface de Programação de Aplicativos)
```
- Um conjunto de especificações que definem de que forma as aplicações irão se comunicar
- Regras e protocolos para que diferentes softwares interajam enrte si
- Interface para que um sistema se comunique com outro sistema
- Uma API funciona como um garçom em um restaurante, intermediando as solicitações de um software e fornecendo os resultados esperados.
```

## REST (Representational State Transfer)
```
- Restrição de Arquitetura
- Conjunto de regras e convençoes que permite que 2 sistemas se comuniquem pela internet
- REST (Representational State Transfer) é um estilo de arquitetura para serviços web que utiliza o protocolo HTTP para comunicação entre cliente e servidor.
- No REST, os recursos são identificados por URLs e podem ser manipulados através de métodos HTTP, como GET, POST, PUT e DELETE.
- O REST enfatiza a simplicidade, escalabilidade e independência de estado nas operações realizadas nos recursos.
- Ele permite que sistemas distribuídos se comuniquem de forma padronizada e interoperável, facilitando a integração entre diferentes plataformas e tecnologias.
```

## RESTFUL
```
- Utiliza métodos HTTP
- Utiliza em nuvem
- Capacidade de aplicar os principios REST
- O RESTful é um estilo de arquitetura para sistemas distribuídos na web. 
- Ele usa URLs para identificar recursos e métodos HTTP para manipulá-los.
- É stateless, ou seja, não mantém informações de estado entre solicitações.
- Fornece uma interface uniforme e consistente para acessar e manipular recursos.
- Suporta operações básicas de CRUD (criar, ler, atualizar, excluir) em recursos.
- Pode ser implementado em várias linguagens de programação e tecnologias.
- É escalável e permite o uso de camadas intermediárias, como caches e proxies.
- As respostas podem ser armazenadas em cache para melhorar o desempenho.
- Permite a interoperabilidade entre diferentes clientes e plataformas.
- É amplamente utilizado em serviços web e APIs.
```

## Maturidade de modelo RESTful
```
lvl 0
- A API precisa utilizar o protocolo HTTP para a comunicação

lvl 1
- A API devce possuir mapeamento de recursos bem definitos.
Representando substantivos que fazem a utilização correta das URLs para os recursos respectivos

lvl 2
- A API deve utilizar o protocolo HTTP de forma semantica com seus verbos com o uso de GET, POST, PUT, DELETE de acordo com a requisição

lvl 3
- A API deve mostrar o seu estado atual de relacionamento com os demais recursos da API
```

## JSON (Javascript Object Notation / Notação de objeto javascript)
```
- Padrão de dados
- Estrutura de dados em formato de txt.
- Transfere info client x server / transfere informação do back pro front
{
   "cliente": {
       "id": 2020,
       "nome": "Maria Aparecida"
   },
   "pagamentos": [
       {
           "id": 123,
           "descricacao": "Compra do livro Cangaceiro JavaScript",
           "valor": 50.5
       },
       {
           "id": 124,
           "descricacao": "Mensalidade escolar",
           "valor": 1500
       }
   ]
}
```

## Requisições HTTP
```
- O protocolo HTTP define um conjunto de métodos de requisições responsáveis por indicar a ação a ser executada para um dado recurso.
- GET, PUSH, DELETE, PUT, PATCH
```

## Headers HTTP
```
- Campo para envio de infos adicionais (normalmente formatação ou autorização) que não temrelaçãocom os dados em si: Authorization, Content Type, Accept
```

## HTTP Codes
```
- 100 - 199: Informativos
- 200 - 299: Sucesso
- 300 - 399: Redirecionamento
- 400 - 499: Erros do cliente
- 500 - 599: Erros do servidor
```

## Framework
```
- Biblioteca
- Reune varios projetos provendo uma funcionalidade generica
```

## ExpressJS
```
- Framework para nodeJS
- Fornece requisitos minimos paraz servidor WEB
```