# Sistema de Catalogação de Biblioteca

Este é um sistema de desktop desenvolvido em Python com a biblioteca Tkinter para catalogar materiais bibliográficos de uma biblioteca.

## Funcionalidades

- **Cadastro por Tipologia**: O sistema permite o cadastro de diferentes tipos de materiais (Livros, Folhetos, Multimeios, etc.) em seções separadas.
- **Armazenamento em Excel**: Cada tipologia de material é salva em sua própria planilha Excel (`biblioteca_livro.xlsx`, `biblioteca_folhetos.xlsx`, etc.), mantendo os dados organizados.
- **Pesquisa Consolidada**: Uma aba "Pesquisar Tudo" permite visualizar, filtrar e pesquisar todos os registros de todas as planilhas em um único local.
- **Visualização Individual**: É possível selecionar um registro na pesquisa e visualizá-lo em uma janela de detalhes.
- **Edição e Exclusão**: Os registros podem ser editados ou excluídos diretamente da interface de pesquisa. A alteração é salva no arquivo Excel de origem correto.
- **Exportação Geral**: A aba de pesquisa possui uma funcionalidade para exportar a visualização atual de todos os registros para uma única planilha Excel (`biblioteca_geral.xlsx`).

## Configuração

Para executar este projeto, você precisa ter o Python 3 instalado.

1.  **Crie um ambiente virtual (recomendado):**
    ```bash
    python -m venv venv
    source venv/bin/activate  # No Windows: venv\Scripts\activate
    ```

2.  **Instale as dependências:**
    ```bash
    pip install -r requirements.txt
    ```

## Como Usar

1.  **Execute o programa:**
    ```bash
    python biblioteca.py
    ```

2.  **Adicione a imagem do logo**: Para que o logo da instituição apareça, coloque uma imagem chamada `fcja2.jpg` na sua Área de Trabalho. O caminho exato no código é `C:\Users\Wenderson Barboza\OneDrive\Área de Trabalho\fcja2.jpg`. Se a imagem não for encontrada, o programa funcionará normalmente, mas sem o logo.

3.  **Navegue pelas abas** para cadastrar os materiais de acordo com sua tipologia.

4.  Use a aba **"Pesquisar Tudo"** para encontrar, visualizar, editar ou excluir registros.

---
Desenvolvido por Wenderson Barboza - 2024
