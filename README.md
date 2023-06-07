## Teste Front-end React


**Descrição da Tarefa:**

1.  **Crie um aplicativo React básico**
    
    Inicie um novo projeto React usando Vite, Next.js ou outra ferramenta à sua escolha.
    
2.  **Implemente a funcionalidade de auto-completar pesquisa**
    
    O aplicativo deve ter um campo de entrada que permita ao usuário digitar o nome de um personagem da série Rick e Morty. Enquanto o usuário digita, o aplicativo deve buscar automaticamente personagens que correspondam ao nome digitado na API de Rick e Morty e exibir os resultados em uma lista abaixo do campo de entrada.
    
3.  **Implemente a funcionalidade de destaque de texto**
    
    Na lista de resultados de pesquisa, o aplicativo deve destacar a parte do nome do personagem que corresponde à consulta de pesquisa. Por exemplo, se o usuário digitar "ri", todos os personagens cujos nomes contêm "ri" devem ser exibidos, e o "ri" deve ser destacado de alguma forma (por exemplo, com uma cor de fundo diferente).
4. **Otimização de Performance**

	Utilize os Hooks `useMemo` e `useCallback` ou outras estrategias de performance quando necessario para otimizar a performance do seu aplicativo.
    
5.  **Implemente a funcionalidade de seleção de personagem**
    
    Quando um personagem é selecionado na lista, o nome dele deve ser preenchido no campo de entrada e o aplicativo deve exibir informações detalhadas sobre o personagem em um card simples abaixo contendo nome do personagem, status, specie e image.
    
6.  **Estilize o aplicativo**
 
    Aplique estilos ao aplicativo para torná-lo apresentável. Você pode usar CSS puro, CSS-in-JS, ou um framework de CSS à sua escolha, mas mantenha a simplicidade e o minimalismo.
    
7.  **Publique o código no GitHub**
    
    Crie um novo repositório no GitHub e publique seu código lá. Certifique-se de incluir um arquivo README.md com instruções sobre como instalar e executar o aplicativo.
    

**Requisitos:**

-	Functional Components
-   Usar funções assíncronas para realizar chamadas de API.
-   Usar Hooks para gerenciar o estado do componente.
-   Os componentes de auto-completar pesquisa e seleção de personagem deve ser reutilizável e não depender somente do contexto da API de Rick e Morty.
-   Escrever código limpo e legível.
-   Tratar todos os possíveis erros e garantir que o aplicativo nunca quebre devido a uma chamada de API mal sucedida.

**APIs de Rick e Morty para usar:**
- [Documentação](https://rickandmortyapi.com/documentation)
-   Busca de personagens: `https://rickandmortyapi.com/api/character/?name={name}`
-   Detalhes do personagem: `https://rickandmortyapi.com/api/character/{id}`
