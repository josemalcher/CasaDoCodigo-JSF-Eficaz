# JSF Eficaz

https://www.casadocodigo.com.br/products/livro-jsf-eficaz

As melhores práticas para o desenvolvedor web Java 

## <a name="indice">Índice</a>

1. [Escolhas que afetam o desenvolvimento da aplicação](#parte1)     
2. [@RequestScoped para escopos curtos](#parte2)     
3. [Mantenha o bean na sessão com @SessionScoped](#parte3)     
4. [Entenda o novo @ViewScoped](#parte4)     
5. [Crie escopos longos e customizáveis com @ConversationScoped](#parte5)     
6. [A praticidade do escopo @Dependent](#parte6)     
7. [Guarde dados para toda a aplicação com o @ApplicationScoped](#parte7)     
8. [Quando usar o @NoneScoped?](#parte8)     
9. [Exibindo Objetos e Mensagens após Redirect e o FlashScoped](#parte9)     
10. [Colocando lógica de rendered no MB](#parte10)     
11. [Inicializando Objetos](#parte11)     
12. [Injetando ManagedBeans](#parte12)     
13. [Target Unreachable: Enfrente a NullPointerException do JSF](#parte13)     
14. [Cuidado com o "Value is not valid"](#parte14)     
15. [Utilizar JSP ou xhtml?](#parte15)     
16. [Utilizando imagens/css/javascript de modos simples](#parte16)     
17. [Boa utilização do Facelets](#parte17)     
18. [Enviar valores para o ManagedBean](#parte18)     
19. [Temas dinâmicos](#parte19)     
20. [O que eu uso? Action ou ActionListener?](#parte20)     
21. [Primefaces](#parte21)     
22. [Temas Dinâmicos com Primefaces](#parte22)     
23. [Componentes do Primefaces não Aparecem](#parte23)     
24. [Richfaces](#parte24)     
25. [Icefaces](#parte25)     
26. [Evite misturar as Implementações/Bibliotecas de Componentes](#parte26)     
27. [Não faça paginação no lado do servidor](#parte27)     
28. [Facilitando o uso do Ajax](#parte28)     
29. [Internacionalização e Localização da sua aplicação](#parte29)     
30. [Utilizando recursos dentro de um Converter](#parte30)     
31. [CDI com JSF](#parte31)     
32. [Evite o "Cross Site Scripting" em seu sistema](#parte32)     
33. [Otimizando a navegação e performance](#parte33)     
34. [Limpeza de comentários e debug](#parte34)     
35. [Organize funcionalidades por ambiente do projeto](#parte35)     
36. [Refresh automático dos Arquivos](#parte36)     
---


## <a name="parte1">1 - Escolhas que afetam o desenvolvimento da aplicação</a>



[Voltar ao Índice](#indice)

---


## <a name="parte2">2 - @RequestScoped para escopos curtos</a>



[Voltar ao Índice](#indice)

---


## <a name="parte3">3 - Mantenha o bean na sessão com @SessionScoped</a>



[Voltar ao Índice](#indice)

---


## <a name="parte4">4 - Entenda o novo @ViewScoped</a>



[Voltar ao Índice](#indice)

---


## <a name="parte5">5 - Crie escopos longos e customizáveis com @ConversationScoped</a>



[Voltar ao Índice](#indice)

---


## <a name="parte6">6 - A praticidade do escopo @Dependent</a>



[Voltar ao Índice](#indice)

---


## <a name="parte7">7 - Guarde dados para toda a aplicação com o @ApplicationScoped</a>



[Voltar ao Índice](#indice)

---


## <a name="parte8">8 - Quando usar o @NoneScoped?</a>



[Voltar ao Índice](#indice)

---


## <a name="parte9">9 - Exibindo Objetos e Mensagens após Redirect e o FlashScoped</a>



[Voltar ao Índice](#indice)

---


## <a name="parte10">10 - Colocando lógica de rendered no MB</a>



[Voltar ao Índice](#indice)

---


## <a name="parte11">11 - Inicializando Objetos</a>



[Voltar ao Índice](#indice)

---


## <a name="parte12">12 - Injetando ManagedBeans</a>



[Voltar ao Índice](#indice)

---


## <a name="parte13">13 - Target Unreachable: Enfrente a NullPointerException do JSF</a>



[Voltar ao Índice](#indice)

---


## <a name="parte14">14 - Cuidado com o "Value is not valid"</a>



[Voltar ao Índice](#indice)

---


## <a name="parte15">15 - Utilizar JSP ou xhtml?</a>



[Voltar ao Índice](#indice)

---


## <a name="parte16">16 - Utilizando imagens/css/javascript de modos simples</a>



[Voltar ao Índice](#indice)

---


## <a name="parte17">17 - Boa utilização do Facelets</a>



[Voltar ao Índice](#indice)

---


## <a name="parte18">18 - Enviar valores para o ManagedBean</a>



[Voltar ao Índice](#indice)

---


## <a name="parte19">19 - Temas dinâmicos</a>



[Voltar ao Índice](#indice)

---


## <a name="parte20">20 - O que eu uso? Action ou ActionListener?</a>



[Voltar ao Índice](#indice)

---


## <a name="parte21">21 - Primefaces</a>



[Voltar ao Índice](#indice)

---


## <a name="parte22">22 - Temas Dinâmicos com Primefaces</a>



[Voltar ao Índice](#indice)

---


## <a name="parte23">23 - Componentes do Primefaces não Aparecem</a>



[Voltar ao Índice](#indice)

---


## <a name="parte24">24 - Richfaces</a>



[Voltar ao Índice](#indice)

---


## <a name="parte25">25 - Icefaces</a>



[Voltar ao Índice](#indice)

---


## <a name="parte26">26 - Evite misturar as Implementações/Bibliotecas de Componentes</a>



[Voltar ao Índice](#indice)

---


## <a name="parte27">27 - Não faça paginação no lado do servidor</a>



[Voltar ao Índice](#indice)

---


## <a name="parte28">28 - Facilitando o uso do Ajax</a>



[Voltar ao Índice](#indice)

---


## <a name="parte29">29 - Internacionalização e Localização da sua aplicação</a>



[Voltar ao Índice](#indice)

---


## <a name="parte30">30 - Utilizando recursos dentro de um Converter</a>



[Voltar ao Índice](#indice)

---


## <a name="parte31">31 - CDI com JSF</a>



[Voltar ao Índice](#indice)

---


## <a name="parte32">32 - Evite o "Cross Site Scripting" em seu sistema</a>



[Voltar ao Índice](#indice)

---


## <a name="parte33">33 - Otimizando a navegação e performance</a>



[Voltar ao Índice](#indice)

---


## <a name="parte34">34 - Limpeza de comentários e debug</a>



[Voltar ao Índice](#indice)

---


## <a name="parte35">35 - Organize funcionalidades por ambiente do projeto</a>



[Voltar ao Índice](#indice)

---


## <a name="parte36">36 - Refresh automático dos Arquivos</a>



[Voltar ao Índice](#indice)

---

