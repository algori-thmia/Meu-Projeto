<h1 align="center"> ArtCarton Artesanato em Cartonagem</h1>

<h4 align="center"> 
    :construction:  Projeto em construção  :construction:
</h4>
Documentação.  ArteCarton 
E-commerce de Cartonagem Sustentável.

Visão Geral.
O projeto ArteCarton é um site de e-commerce  desenvolvido para simular uma loja virtual especializada em cartonagem sustentável. A ideia surgiu como uma forma de integrar conhecimentos de desenvolvimento web com um tema socialmente relevante, o artesanato com reaproveitamento de materiais. Este documento registra toda a trajetória de criação, solução de problemas e aprimoramentos realizados no projeto.

Motivação e Objetivo.
O objetivo principal é desenvolver, de forma educativa, um site que simula um pequeno e-commerce de produtos artesanais, com foco na sustentabilidade e na valorização do trabalho manual. A experiência também teve como finalidade exercitar habilidades em HTML, CSS, JavaScript e PHP, além de trabalhar com banco de dados MySQL em ambiente local.
Tecnologias Utilizadas.
HTML5: estrutura das páginas
CSS3: estilização e responsividade
JavaScript: interatividade com o usuário
PHP: processamento de formulários e conexão com banco de dados
MySQL: armazenamento de mensagens enviadas pelo formulário
WAMP Server: servidor local para executar PHP e MySQL


Estrutura Atual do Projeto.
Páginas Criadas:
Home (index.html)
Saudação de boas-vindas com mensagem dinâmica via JavaScript.
Produtos (produtos.html)
Apresenta produtos como caixas decorativas e porta-jóias com imagens e descrições.
Contato (contato.html)
Formulário funcional para envio de mensagem, armazenada no banco de dados via PHP.
Sobre (sobre.html)
Narra a história da ArteCarton, sua missão e motivações.
Mensagens (mensagens.php)
Exibe uma tabela com todas as mensagens recebidas via formulário.

Funcionalidades JavaScript.
Home: "Seja bem-vindo!"
Produtos: "Qual produto você gostaria de ver hoje?"
Contato: "Vamos preencher nosso formulário?"
Sobre: "Seja bem-vindo a conhecer nossa história."

Fases e Ajustes do Projeto.

 Criação da Estrutura Inicial
Estrutura básica HTML/CSS criada do zero.
Separadas as páginas principais (Home, Produtos, Contato, Sobre).
Definida a navegação entre elas.
 
 Estilização e Identidade Visual.
Adição de cores suaves e responsividade.
Tentativa inicial de carregar uma imagem de logo a partir de um PDF.
Como o PDF não continha imagem extraível, criamos uma logo textual temporária.
 
 Funcionalidade com JavaScript.
Mensagens dinâmicas foram adicionadas para melhorar a experiência do usuário.
O JavaScript detecta a página atual e exibe uma frase apropriada automaticamente.
 Integração com Banco de Dados.

Implementado formulário de contato com PHP e MySQL.
Criado banco de dados artecarton e tabela contatos com os seguintes campos:
id, nome, email, mensagem, data_envio

Testes Locais com WAMP.
Apareceram erros por usar o Live Server (porta 5500) que não executa PHP.
Resolvido com acesso via http://localhost no WAMP.

 Interface para Visualizar Mensagens.
Foi criado arquivo mensagens.php para exibir os dados armazenados no banco.
Visual simples em tabela com cor e organização para facilitar leitura.
 
 Melhorias Finais.
Verificação de funcionamento da página..
Criação e edição de imagens  para produtos.
Testes para captura de dados cadastrados através do formulário.

Conclusão da Sprint 01
Relatório.
https://cartonagem-unica.atlassian.net/browse/SCRUM-32




<p align="center">
<img loading="lazy" src="http://img.shields.io/static/v1?label=STATUS&message=EM%20DESENVOLVIMENTO&color=GREEN&style=for-the-badge"/>
</p>
