# Sistema de Controle de Estoque

Esse projeto é um mini-ERP desenvolvido em linguagem de programação Python para controle de estoque, permitindo cadastrar, excluir, movimentar, visualizar e exportar dados dos produtos.
Além disso, o sistema também permite gerar relatórios gerenciais para tomada de decisão ebasada em dados reais e visualização por meio de dashboards analíticos.

#Funcionalidades
Cadastro de Produtos:
- Código do produto;
- Descrição;
- Categoria (Matéria-prima / Produto acabado);
- Unidade de medida;
- Quantidade;
- Preço unitário.

Exclusão de produtos
- Remoção de um item anteriormente cadastrado pelo código.

Movimentação de estoque
- Entrada de produtos;
- Saída de produtos;
- Mensagens automáticas de validação.

Visualização
- Tabela completa de produtos cadastrados;
- Exibição em forma de pilha (útimo item aparece primeiro);
- Alerta automático para estoque baixo (quantidade < 5).

Exportação
- Exportação do banco de daods para Excel (.xlsx);
- Exportação do banco de daods para CSV (.csv).

Dashboards
- Inclui análises geradas com Matplotlib e Pandas;
- Gráfico de linhas (evolução do estoque);
- Gráfico de barras (para comparação de categorias);
- Gráfico de curva ABC ( para custos de estoques).

# Tecnologias Utilizadas
- Python 3.x
- Pandas
- Matplotlib

# Como Executar
1. Clonar o repositório (git clone https://github.com/nogueira-amanda/estoque.git)
2. Instalar dependências (pip install matplotlib)
3. Executar o programa.

# Contribuições
Este projeto foi desenvolvido por mim em parceria com @Silviane-Ribeiro, @dudacarr

