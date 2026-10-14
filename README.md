# Feira Plus+

**Aplicativo de listas de compras organizado por corredores de supermercado.**

Projeto desenvolvido com React e JavaScript, com foco em praticidade, organização de compras e acessibilidade.

O Feira Plus+ permite cadastrar produtos, interpretar quantidades, organizar itens conforme corredores de atacarejos e acompanhar o andamento das compras em uma interface adaptada ao uso cotidiano.

## Sobre o projeto

Listas de compras tradicionais apresentam produtos apenas na ordem em que foram adicionados.

O Feira Plus+ propõe uma organização baseada na disposição dos produtos no supermercado, permitindo agrupar itens por corredor e reduzir a necessidade de percorrer repetidamente diferentes setores.

A aplicação conta com configurações específicas para três redes:

- Novo Atacarejo
- Assaí Atacadista
- Atacadão

As classificações são configuráveis e utilizam palavras-chave, sem depender de integração com os sistemas internos dos estabelecimentos.

## Tecnologias

| Tecnologia | Aplicação |
|---|---|
| React | Construção da interface |
| JavaScript | Lógica e gerenciamento dos itens |
| JSX | Estrutura dos componentes |
| CSS | Apresentação visual |
| Armazenamento local | Persistência das preferências e listas |
| Capacitor | Tecnologia utilizada na versão Android informada pelo projeto |

## Funcionalidades

### Gerenciamento de listas

- Adição e organização de produtos.
- Interpretação de quantidades e unidades.
- Marcação de itens durante as compras.
- Acompanhamento visual dos produtos pendentes.

### Organização por corredores

- Classificação de produtos por palavras-chave.
- Configuração de corredores para cada supermercado.
- Personalização das regras de categorização.
- Agrupamento dos produtos conforme a loja selecionada.

### Exportação

- Exportação da lista em formato TXT.
- Exportação visual em JPG.

### Interface e acessibilidade

- Interface com tema escuro.
- Elementos visuais de leitura facilitada.
- Tipografia ampliada.
- Interações voltadas ao uso durante as compras.

## Como funciona

O usuário seleciona um supermercado e adiciona os itens desejados.

A aplicação interpreta o conteúdo informado, identifica palavras-chave associadas aos produtos e utiliza as configurações da loja para organizar os itens.

Durante as compras, é possível acompanhar o progresso e marcar os produtos já encontrados.

As regras de classificação podem ser personalizadas para representar melhor a organização real de cada estabelecimento.

## Estrutura publicada

```text
Feira-PLUS/
├── Feira PLUS+.jsx
├── Feira-PLUS.apk
├── README.md
└── LICENSE
```

O arquivo `Feira PLUS+.jsx` contém o componente React disponibilizado publicamente.

O arquivo `Feira-PLUS.apk` corresponde ao pacote Android distribuído no repositório.

**Observação:** o repositório atual não contém a estrutura completa de um projeto React/Vite/Capacitor. Para executar ou compilar a aplicação a partir do código, é necessário integrá-lo a um projeto com as dependências e configurações apropriadas.

## Distribuição Android

O pacote APK está disponível no repositório:

[Consultar versão Android](https://github.com/Biieru/Feira-PLUS/blob/main/Feira-PLUS.apk)

O APK deve ser tratado como uma distribuição para testes e avaliação, não como uma versão auditada ou publicada em uma loja oficial.

## Conceitos aplicados

- Desenvolvimento de interfaces com React.
- Gerenciamento de estado.
- Manipulação de listas e formulários.
- Categorização baseada em regras.
- Persistência local de informações.
- Exportação de dados.
- Design de interface orientado a tarefas reais.
- Prototipação de aplicações mobile.

## Melhorias futuras

- Publicação da estrutura completa do projeto.
- Testes automatizados das regras de categorização.
- Aprimoramento da responsividade.
- Melhorias de acessibilidade.
- Importação de listas salvas.
- Configurações compartilháveis entre dispositivos.
- Empacotamento e distribuição Android reproduzíveis.

## Licença

Distribuído sob a licença [PolyForm Noncommercial 1.0.0](LICENSE).

O uso comercial está sujeito às condições de licenciamento e autorização aplicáveis.

## Autor

**Gabriel Coelho de Araújo**

[GitHub](https://github.com/Biieru)

**React · JavaScript · Mobile · UI/UX · Accessibility**
