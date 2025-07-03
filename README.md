# Banco de Imagens para Estudos em Processamento de Imagens Digitais

Este repositório serve como um banco de imagens centralizado, destinado a estudantes, pesquisadores e entusiastas da área de Processamento de Imagens Digitais (PDI). O objetivo é fornecer conjuntos de dados (datasets) variados e comumente utilizados na literatura acadêmica e em projetos de desenvolvimento.

## Estrutura do Repositório

O repositório está organizado da seguinte forma, visando facilitar o acesso e a referência dos dados:

```
.
├── test_set_data_1/       # Imagens clássicas de teste (512x512)
├── test_set_data_2/       # Corel-1000 Dataset (384x256 ou 256x384)
├── test_set_data_3/       # Imagens diversas de uso livre (512x512)
├── test_set_data_4/       # Imagens diversas de uso livre (Alta Resolução)
├── REF_test_set_data_1.txt # Referências para o test_set_data_1
├── REF_test_set_data_2.txt # Referências para o test_set_data_2
├── REF_test_set_data_3.txt # Referências para o test_set_data_3
└── REF_test_set_data_4.txt # Referências para o test_set_data_4
```

## Descrição dos Conjuntos de Imagens (Datasets)

Cada pasta `test_set_data_(i)` contém um conjunto específico de imagens, e cada arquivo `REF_test_set_data_(i).txt` correspondente contém as referências e os créditos de cada imagem.

### 📷 `test_set_data_1`
- **Conteúdo**: Imagens clássicas de 512x512 pixels, amplamente conhecidas e utilizadas como padrão em testes de algoritmos de PDI.
- **Exemplos**: Lenna, Peppers, Mandril, Baboon, etc.
- **Referências**: Consulte o arquivo `REF_test_set_data_1.txt`.

### 🖼️ `test_set_data_2`
- **Conteúdo**: O dataset Corel-1000, que consiste em 1.000 imagens de categorias diversas.
- **Dimensões**: 384x256 ou 256x384 pixels.
- **Uso Comum**: Estudos em PDI.
- **Referências**: Consulte o arquivo `REF_test_set_data_2.txt`.

### 🏞️ `test_set_data_3`
- **Conteúdo**: Uma coleção variada de imagens de uso livre, obtidas das plataformas Pexels e Unsplash.
- **Dimensões**: 512x512 pixels.
- **Licença**: As imagens deste conjunto seguem as diretrizes das licenças **Pexels** e **Unsplash**. Veja a seção [Licenças](#licenças) no final deste documento para mais detalhes.
- **Referências**: Consulte o arquivo `REF_test_set_data_3.txt`.

### 🌄 `test_set_data_4`
- **Conteúdo**: Uma coleção variada de imagens de alta resolução, também de uso livre, provenientes do Pexels e Unsplash.
- **Dimensões**: Variadas (alta resolução).
- **Licença**: As imagens deste conjunto seguem as diretrizes das licenças **Pexels** e **Unsplash**. Veja a seção [Licenças](#licenças) no final deste documento para mais detalhes.
- **Referências**: Consulte o arquivo `REF_test_set_data_4.txt`.

## Como Utilizar

1.  **Clonar o repositório:**
    ```bash
    git clone [https://github.com/ribas858/images-for-research-purposes.git](https://github.com/ribas858/images-for-research-purposes.git)
    ```
2.  Navegue até a pasta do dataset desejado.
3.  Utilize as imagens em seus projetos de PDI, como segmentação, filtros, compressão, etc.
4.  Para atribuição e verificação da origem, consulte sempre os arquivos `REF_` correspondentes.

## Licenças

As imagens contidas nos conjuntos `test_set_data_3` e `test_set_data_4` foram obtidas de fontes que permitem o uso gratuito, mas com algumas restrições. É fundamental respeitar os termos de cada licença.

---

### Licença Pexels

**O que é permitido? 👌**
- Todas as fotos e vídeos do Pexels podem ser usados de forma gratuita.
- Não é obrigatório mencionar a fonte. Dar crédito aos fotógrafos ou ao Pexels não é necessário, mas é bem-vindo.
- Você pode modificar as fotos e vídeos do Pexels. Use sua criatividade e faça as edições que quiser.

**O que não é permitido? 👎**
- As pessoas que sejam identificáveis na foto não devem aparecer em uma situação desfavorável nem de uma maneira que possa ser ofensiva.
- Não venda cópias inalteradas de uma foto ou vídeo, por exemplo, em um formato impresso, de cartaz ou em um produto físico, sem modificá-las antes.
- Não dê a entender que as pessoas ou marcas nas imagens endossam seu produto.
- Não redistribua ou venda as fotos e vídeos em outras plataformas de fotos profissionais ou de papéis de parede.
- Não utilize as fotos ou os vídeos como parte da sua marca registrada, marca de design, nome comercial, razão social ou marca de serviço.

*Fonte: [https://www.pexels.com/pt-br/license/](https://www.pexels.com/pt-br/license/)*

---

### Licença Unsplash

Os recursos visuais da Unsplash foram feitos para serem usados gratuitamente. Nossa licença reflete isso.

- Todas as imagens podem ser baixadas e usadas gratuitamente.
- Para fins comerciais e não comerciais.
- Não é necessária permissão (embora a atribuição seja bem-vinda!).

**O que não é permitido? 👎**
- As imagens não podem ser vendidas sem modificações significativas.
- A compilação de imagens da Unsplash para replicar um serviço semelhante ou concorrente.

*Fonte: [https://unsplash.com/license](https://unsplash.com/license)*
