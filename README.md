<h1>Eu fiz esses passos aqui</h1>
  <ol>
    <li>Entrar no link <a href="https://github.com/ericthmoritsuka/testesemgh">https://github.com/ericthmoritsuka/testesemgh</a></li>
    <li>
      Fazer um fork do repositorio
      <img src="./img/1.PNG" alt="">
    </li>
    <li>
      Criar um clone fo repositorio na maquina: <br>
      <span class="code">git clone https://github.com/nomedousuariodevoces/nomequevocesderamprofork</span>
    </li>
    <li>Aqui eu não entendi exatamente se tinha que dar um <span class="code">git init</span> mas teve uma hora que eu fiz sem e ele disse que não era um repositório, então acabei colocando o comando.</li>
    <li>
      Criar um novo branch: <br>
      <span class="code">git checkout -b nomedobranch</span>
    </li>
    <li>
      Criar um novo remote para o repositorio upstream (o original de onde fizemos o fork): <br>
      <span class="code">git remote add upstream https://github.com/ericthmoritsuka/testesemgh</span>
    </li>
    <li>Fazer mudanças</li>
    <li>
      Checar se esta no mesmo pe que o repositorio upstream: <br>
      <span class="code">git status</span>
    </li>
    <li>
      Adicionar as modificações: <br>
      <span class="code">git add nomedoarquivo</span><br>
      <span class="code">git add . (tudo)</span><br>
      <span class="code">git add -A (tudo)</span>
    </li>
    <li>
      Fazer o commit: <br>
      <span class="code">git commit -m 'mensagem do commit'</span><br>
      <span class="aviso">Aqui o git pediu pra eu me identificar, nao sei se o cara do treinamento que eu vi que fez ou se o proprio git faz isso, imgino que seja o git</span><br>
      <span class="aviso code">git config --global user.email emaildapessoa<br>
        git config --global user.name nomedousuario
      </span>
    </li>
    <li>
      Fazer o push para o origin: <br>
      <span class="code">git push origin nomedobranch</span><br>
    </li>
    <li>
      Aparece esse botao no github: <br>
      <img src="./img/2.PNG" alt="">
    </li>
    <li>
      Depois de clicar nele aparece essa tela onde da pra ver os commits, alteracoes feitas e comparacoes e onde da pra criar o pull request: <br>
      <img src="./img/3.PNG" alt="">
    </li>
    <li>
      Depois disso eu não vi ainda. Mas o dono do repositório deve analisar o pull request pra ver se o merge vai acontecer ou não, deve ser isso...
    </li>
  </ol>
