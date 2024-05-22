<h2>Criando um novo repositório</h2>
git init<br>
git add README.md<br>
git commit -m "first commit"<br>
git branch -M main<br>
git remote add origin https://github.com/alexpfaffen/utilizacaoDoGit.git<br>
git push -u origin main<br>
Caso alguém ao dar push, aparecer o erro "fatal: protocol 'https' not is supported", digite o seguinte comando ''git remote set-url origin + o seu link''<br>

<h2>Enviando um repositório existente</h2>
git remote add origin https://github.com/alexpfaffen/utilizacaoDoGit.git<br>
git branch -M main<br>
git push -u origin main<br>