<body>
    <main>
        <h1 align="center">Comandos git</h1>
            <p align="center">
        <img src="img_readme/git.png" width="400">
    </p>
    </main>
    <h2>Como usar comandos git? Aprenda os básicos!</h2>
    <p>
    <p>
        Existe uma máxima hoje em qualquer ambiente que se trabalhe com TI que é: “Em caso de incêndio:
    </p>
    <p>👉1 - git commit,</p>
    <p>👉2 - git push,</p>
    <p>👉3 - Saia do recinto”.</p>
    Apesar do ar cômico, esses dois comandos (acompanhados de um terceiro) são os responsáveis por salvar muitos projetos (ou pelo arrependimento de quem esqueceu de usá-los) e eu vou te explicar o que cada um deles faz.
    </p>
    <p align="center">
        <img src="img_readme/fire.png" width="300">
    </p>
    <h3><strong>✔️Git init</strong></h3>
    <p>
        O comando git init cria um novo repositório do Git. Ele pode ser usado para converter um projeto existente e não versionado em um repositório do Git ou inicializar um novo repositório vazio. A maioria dos outros comandos Git não está disponível fora de um repositório inicializado, portanto, este costuma ser o primeiro comando que você executa em um novo projeto.
    </p>
    <h3><strong>✔️Git add</strong></h3>
    <p>
        Este comando adiciona os arquivos solicitados ao ambiente de stage, é uma forma de dizer para o git que você deseja que as modificações daquele arquivo sejam gravadas na próxima remessa. Um exemplo de utilização é: git add . onde o ponto representa todos os arquivos na pasta.
    </p>
    <h3><strong>✔️Git commit</strong></h3>
    <p>
        Agora fazemos a gravação em si das modificações, desta forma criamos um snapshot do estado atual do nosso
        projeto. Uma forma muito usada é o git commit -m “descrição das atualizações do projeto” onde o -m é uma flag que aponta para a mensagem de descrição.
    </p>
    <h3><strong>✔️Git remote</strong></h3>
    <p>
        Nada mais é do que apontar o caminho(repositório) para aonde você ira subir o seu projeto, por exemplo (git remote add origin "endereço do repositório"). 
    </p>
    <h3><strong>✔️Git push</strong></h3>
    <p>
        Por fim precisamos subir essas modificações no nosso repositório remoto, para isso basta utilizar o comando git push e, se já estiver tudo devidamente configurado, os arquivos serão salvos no repositório remoto correspondente ao seu repositório local!
    </p>
    <h3><strong>✔️Git status</strong></h3>
    <p>
        Este comando permite ver quais arquivos estão sendo “rastreados” pelo git e quais modificações já foram enviadas para o stage. É bem útil para quando se tem dúvidas sobre o que está sendo enviado
    </p>
    <h3><strong>✔️Git branch</strong></h3>
    <p>
        É usado para verificar todas as branches presentes no repositório. Ao utilizar a flag -r no final do comando é possível ver todas as branches presentes no repositório remoto e se você quiser criar uma nova branch basta utilizar este comando: git branch (branch_name).
    </p>
    <h3><strong>✔️Git stash</strong></h3>
    <p>
        Git stash arquiva (ou faz o stash) de alterações que você fez na cópia de trabalho durante um determinado período, para que você possa trabalhar em outra coisa, depois voltar e fazer a reaplicação mais tarde. O stashing é útil quando você precisa alternar com rapidez o contexto e trabalhar em outra coisa, mas está no meio da alteração de código e não está pronto para fazer commit.
    </p>
    <h3><strong>✔️Git checkout</strong></h3>
    <p>
        É o comando utilizado para trocar de branch passando o nome da branch destino no final do comando. Caso a flag -b seja colocada após o “checkout” é possível criar a branch em questão e já trocar para esta imediatamente.
    </p>
    <h3><strong>✔️Git merge</strong></h3>
    <p>
        Então o merge é local sempre. Quando você deseja atualizar outro repositório você traz seu conteúdo para o seu repositório local atual, faz o merge e manda de volta o conteúdo do seu repositório para o repositório original, possivelmente remoto.
    </p>
    <h3><strong>✔️Git clone</strong></h3>
    <p>
        Este comando irá clonar o projeto remoto na sua máquina local, exemplo git clone (endereço do projeto remoto que ira clonar).
    </p>
    <p>
    <footer>
        <address>👨🏻‍💻 Tom Mereles</address>
    </footer>
    </p>
</body>
