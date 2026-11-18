Template da proposta (copiar para docs/proposta.md):
# Proposta de Projeto — Programação Web 2026.2
 
- **Aluno:** Webert Henrique Esperandio Ramos· **SI/PW:**
- **Repositório:** https://github.com/riqueweb/ra-202451077708
 
## 1. Tema e problema
O projeto consiste no desenvolvimento de uma loja virtual de camisas esportivas, com foco em camisas de times de futebol, seleções e outros esportes. O site tem com mo objetivo facilitar a visualização e a busca por camisas disponiveis, permitindo que o usuario consulte informações de cada produto e demonstre interesse por meio de um formulario.
 
## 2. Público-alvo
Pessoas interessadas em camisas esportivas, principalmente torcedores e fã de clubes, seleções e diferentes modalidades esportivas, como por exemplo, Basquete. O site poderá ser utilizado por usuarios que desejam pesquisar modelos, tamanhos disponiveis, comparar informações basicas e consultar detalhes de uma camisa.
 
## 3. Coleção de itens
A coleção principal sera composta por camisas esportivas disponiveis na loja, contendo no minimo 8 itens
Cada camisa tera os seguintes atributos:
id: identificador da camisa
nome: nome ou modelo da camisa
time: clube, seleção ou equipe representada
categoria: modalidade ou tipo da camisa
preco: preço da camisa;
tamanho: tamanho disponivel;
imagem: imagem representativa da camisa.
 
## 4. Telas previstas
Tela inicial/Catalogo - que presentará as camisas disponiveis em formato de cards, com informações badsicas como imagem, nome, time, categoria e preço. Tambem contara com uma opção de busca ou filtro para facilitar a localização das camisas.
 
Tela de detalhes da camisa - Que presentará as informações completas de uma camisa selecionada pelo usuario, como imagem, nome, time, categoria, preço e tamanho. Na Fase 2, a tela sera acessada por meio de uma rota com parâmetro identificando a camisa.

tela de formulario - que contará com um formulário para que o usuario possa demonstrar interesse em uma camisa. O formulário terá campos como nome, e-mail, telefone, camisa desejada, tamanho, quantidade e observação, além de validações dos campos.

## 5. Formulário
O formulario será utilizado para registrar o interesse do usuário em uma camisa: 
Nome
E-mail
Telefone
Camisa desejada
Tamanho
Quantidade
Observação.
As validações com campos obrigatórios, formato válido de e-mail, preenchimento do telefone, seleção da camisa e do tamanho e quantidade mínima de uma unidade.
 
## 6. Filtro/busca
filtro e busco pelo nome/time da camisa ou por categoria,
Ex: "Camisa Atletico-MG", "Todas", "Futebol", "Basquete", "Seleções", "Outros Esportes", etc...

## 7. Origem dos dados na Fase 2
oos dados das camisas serão armazenados em um arquivo JSON local. Na fase 2, os dados poderão ser disponibilizados por meio de um mock local utilizando json-server, permitindo o consumo dos dados através de fetch e useEffect.

## 8. Diferencial pretendido
O diferencial pretendido é apresentar as camisas de forma visual e organizada, facilitando a navegação por meio de cards, busca e filtros. A página de detalhes permiteconsultar individualmente cada camisa, mantendo o projeto simples e focado na experiência de navegação de uma loja esportiva.
