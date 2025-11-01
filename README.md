<p align="center"><b>📝 Lista de Tarefas (To-Do List)</b> </p>
<br>
Este é um projeto simples de uma Lista de Tarefas (To-Do List) desenvolvida com HTML, CSS e JavaScript puro. Ele permite aos usuários adicionar novas tarefas, marcar tarefas como concluídas e deletá-las.
<br>
<p align="center"><b>✨ Funcionalidades</b>

    Adicionar Tarefa: Insira um texto e clique em "Adicionar" ou pressione a tecla Enter para incluir uma nova tarefa na lista.

    Marcar como Concluída: Clique no ícone de círculo ou no nome da tarefa para marcá-la como concluída (visualizada com um risco, cor de fundo diferente e um ícone de check verde).

    Desmarcar Tarefa: Clique novamente em uma tarefa concluída para desmarcá-la.

    Deletar Tarefa: Utilize o botão "Deletar" vermelho para remover permanentemente uma tarefa da lista.

    Organização: Tarefas marcadas como concluídas são movidas para o final da lista (implementado no JavaScript).
<br>
<p align="center"><b>🚀 Tecnologias Utilizadas</b>
O projeto é construído com as seguintes tecnologias front-end básicas:

    HTML5: Para a estrutura básica da aplicação.

    CSS3: Para a estilização e layout responsivo.

    JavaScript: Para a manipulação do DOM e a lógica da aplicação (adicionar, deletar e marcar tarefas).

    Material Design Icons (MDI): Utilizado para os ícones de círculo (∘) e check (✓) nas tarefas. (Note-se que o link para a biblioteca MDI não está explícito no seu HTML, mas as classes (mdi mdi-circle-outline, mdi mdi-delete, etc.) indicam seu uso.)
</p>
🛠️ Estrutura do Projeto

O projeto é composto por três arquivos principais:

    index.html: A estrutura principal da página.

    style.css: As regras de estilo para a aparência da lista.

    script.js: A lógica de funcionamento da lista de tarefas.

💡 Como Funciona o JavaScript

O arquivo script.js gerencia o estado da lista e as interações do usuário:

    addTarefa():

        Verifica se o campo de input não está vazio.

        Cria uma nova estrutura HTML (div com a classe item) para a tarefa, incluindo ícones e botão de deletar.

        Adiciona a nova estrutura ao elemento main (areaLista) e limpa o campo de input.

    deletar(id):

        Encontra o elemento da tarefa usando seu id e o remove do DOM.

    marcarTarefa(id):

        Alterna a classe do item entre "item" e "item clicado".

        Atualiza o ícone (de círculo para check e vice-versa).

        Se a tarefa for marcada, ela é movida para o final da lista (item.parentNode.appendChild(item)).

    Escuta de Evento keyup:

        Detecta a tecla Enter (código 13) no campo de input e simula um clique no botão "Adicionar".

📂 Como Executar o Projeto

É muito simples executar este projeto:

    Clone este repositório para sua máquina local.

    Abra o arquivo index.html em qualquer navegador web moderno.

    Comece a adicionar suas tarefas!
