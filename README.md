# Conversor de Moedas

## Descrição
Este projeto é um **Conversor de Moedas Simples**, baseando-se na taxa de câmbio de 24/10/2024, desenvolvido em trio na disciplina de **Desenvolvimento Web**,  sob a orientação do professor **Leonardo da Rocha** e colaboração de **Chrystian de Almeida Silva** e **Ana Laura Cenali**. O objetivo é permitir a conversão de valores monetários entre diferentes moedas (Libra, Euro, Dolar e Real) de forma interativa e visual. 

## O Que é um Conversor de Moedas?
Um conversor de moedas é uma ferramenta que permite calcular o valor de uma moeda com base na taxa de câmbio em relação a outra moeda. Essa ferramenta é amplamente usada em viagens internacionais, comércio exterior, investimentos, e mais, pois facilita a compreensão de quanto um valor em uma moeda vale em outra moeda. Neste projeto, o usuário pode converter valores entre **Real (BRL)**, **Dólar Americano (USD)**, **Euro (EUR)** e **Libra Esterlina (GBP)**.

## Funcionalidades do Projeto
- **Entrada de Valor**: O usuário insere o valor que deseja converter.
- **Seleção de Moedas**: O usuário escolhe a moeda de origem e a moeda de destino.
- **Conversão**: Ao clicar no botão de conversão, o valor é convertido conforme as moedas selecionadas.
- **Limpar Dados**: Um botão de reset para limpar todos os campos e realizar novas conversões.

## Tecnologias Utilizadas
- **HTML5**: Estrutura e marcação da interface.
- **CSS3**: Estilização do layout, cores, fontes e design geral.
- **JavaScript**: Responsável pela lógica de conversão e interatividade.
- **Live Server**: Atualiza página de forma sincrona.
- **Git**: Versionamento de código.
- **GitHub**: Hospedagem e documentação.

## Estrutura do Código
 
 Arquivos Principais
- `index.html`: Contém a estrutura da página, os campos de entrada de dados, botões e títulos.
- `converter.css`: Define o design, como cores, espaçamento, fontes e outros estilos.
- `conversor.js`: Contém a lógica principal para conversão das moedas e manipulação dos elementos da interface.

### Explicação do Código

#### HTML (`index.html`)
1. **Título**: `Conversor de Moedas` — o título é exibido na página principal e deixa claro o objetivo da aplicação.
2. **Formulário de Conversão**: 
   - Campo para inserir o valor desejado.
   - Menus de seleção para escolher a moeda de origem e a moeda de destino.
   - Botões **Converter** e **Limpar**.
3. **Área de Resultado**: Exibe a conversão calculada quando o botão `Converter` é pressionado.

#### CSS (`converter.css`)
1. **Cores e Fontes**: Variáveis CSS (`:root`) são usadas para definir uma paleta de cores e as fontes do projeto, facilitando a manutenção e a personalização.
2. **Layout Responsivo**: A estrutura CSS permite uma interface adaptada a diferentes tamanhos de tela.
3. **Estilos de Botões**: Definidos com animações para melhor experiência do usuário ao interagir com os botões de `Converter` e `Limpar`.

#### JavaScript (`conversor.js`)
1. **Seleção de Moedas e Valor**: O JavaScript captura as escolhas de moeda de origem e de destino e o valor inserido.
2. **Cálculo de Conversão**: O script utiliza uma função que converte o valor com base em taxas de câmbio definidas (ou via uma API, se disponível).
3. **Atualização da Interface**: Após a conversão, o valor resultante é exibido na área de resultados da página. A função de `Limpar` redefine os campos para permitir uma nova conversão.

### Estrutura de Pastas
- `index.html`: Página principal com a interface do conversor.
- `css/converter.css`: Arquivo de estilo para o layout.
- `fonts/`: Pasta com fontes personalizadas.
- `conversor.js`: Contém a lógica para a conversão de moedas.

### Como Executar
1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/conversor-moedas.git
   ```


### Colaboradores:
[Chrystian de Almeida Silva](https://github.com/ESChrystian)

[Geovana Aparecida de Lima](https://github.com/Geovanaaplima?tab=repositories)

[Ana Laura Cenali](https://github.com/anacenali)