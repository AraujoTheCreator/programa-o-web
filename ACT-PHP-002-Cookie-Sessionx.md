# Exercício 1 — Pergunta Conceitual <!-- Benjamin -->

No PHP, cookies e sessions são mecanismos para armazenar dados do usuário, mas funcionam de maneiras diferentes.  
Cookies são pequenos arquivos que ficam armazenados no computador do usuário, enquanto sessions guardam os dados no servidor, vinculados a um identificador único enviado ao navegador.  
Por isso, sessions são geralmente mais seguras, já que os dados não ficam expostos no cliente.  
Cookies podem ser úteis quando se quer lembrar informações entre visitas, como preferências de idioma, enquanto sessions são mais adequadas para manter informações temporárias, como o estado de login de um usuário durante a navegação.  
Em resumo, cookies oferecem persistência no cliente, mas menos segurança, e sessions oferecem segurança e controle centralizado no servidor, mas expiram quando o navegador é fechado ou a sessão termina.

# Exercício 2 — Pergunta de Aplicação <!-- Gabriel -->

Em uma loja virtual, sessions são ideais para manter o usuário logado durante a navegação, garantindo que as informações de autenticação fiquem no servidor e não sejam manipuladas.  
Já cookies podem ser usados para armazenar itens temporários no carrinho quando o usuário não está logado, permitindo que a informação persista mesmo se a página for fechada.  
Além disso, cookies podem registrar preferências de usuário, como tema claro ou escuro e idioma, porque são arquivos que ficam salvos no navegador e duram entre visitas.  
Dessa forma, combinamos segurança com persistência, usando cada mecanismo no contexto adequado.