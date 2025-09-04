aplicação web que permite explorar e organizar cursos online. Com uma interface simples e moderna, usuários podem buscar cursos, marcar seu progresso (A Fazer, Em Andamento, Realizado) e salvar essas informações localmente no navegador.


 Funcionalidades
 
 ---Exploração de cursos públicos via API (ou lista local fallback)
 ---Login e cadastro local (usando localStorage, sem backend)
 --- Marcar progresso nos cursos:
 ---A Fazer
 ---Em Andamento
 ---Realizado
 ---Busca e filtro por status
 ---Área "Meus Cursos" com controle total dos cursos selecionados
 ---Interface leve, responsiva e com estilo glassmorphism 

  Tecnologias Utilizadas

---HTML5, CSS3, JavaScript (ES6+)
---Sem bibliotecas/frameworks externos
---localStorage para persistência de dados local
---crypto.subtle.digest (SHA-256) para hashing de senhas

Modo de uso 

---Clique em "Carregar" para buscar cursos públicos (ou usar cursos padrões).
---Crie uma conta ou faça login para salvar o progresso.
---Marque os cursos conforme seu andamento.
---Acesse a aba "Meus Cursos" para visualizar e remover cursos marcados.

Observações

---As senhas são armazenadas localmente com hash SHA-256, mas não há criptografia avançada ou backend real.
---Os dados são perdidos ao limpar o cache/localStorage do navegador
