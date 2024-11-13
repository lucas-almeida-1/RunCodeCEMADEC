# RunCodeDC

# Preparação inicial para escrever códigos em qualquer linguagem no VSCode.
## Python
Vamos supor que você queira fazer um projeto em Python na sua máquina.
Se você teve algum problema com códigos em Python, você precisa instalar o Python e adicionar a variável do sistema em PATH.

## Instalação do Python
Já considerando que você tenha alguma IDE, como o PyCharm ou o Visual Studio Code. Precisamos instalar a extensão Python na sua IDE:

Como o VSCode é mais usado, basta seguir as seguintes instruções:
<div align='center'>
  <img src='https://github.com/user-attachments/assets/703de849-2a29-42e4-9a73-12f18d4e88e3' alt='Interface do VSCode' >
  <p align='center'>Interface do VSCode</p>
</div>

Perceba na imagem e na sua IDE que você vai ter essa aba lateral esquerda com alguns botões.  
Olhando de cima a baixo, temos o 5º Elemento que gerencia extensões da sua IDE. Clique nesse ícone:
<div align='center'>
  <img src='https://github.com/user-attachments/assets/a6fa241c-300a-4e4b-a1da-ada048c543eb' alt='Botão que mostra as extensões da IDE' >
  <p align='center'>Botão que mostra as extensões da IDE</p>
</div>

Perceba que ao clicar no botão, temos uma nova aba listando algumas extensões. No topo da aba, temos uma caixa de pesquisa, procure por Python (Tem um selo da Microsoft embaixo).

<div align='center'>
  <img src='https://github.com/user-attachments/assets/3e85e653-2f92-4280-89e7-04cc61825b56' alt='Detalhes da extensão Python' >
  <p align='center'>Detalhes da extensão Python.</p>
</div>

Uma janela maior se abre detalhando o que a extensão pode fazer. Como queremos escrever códigos em Python, ela se faz necessária. Para isso, basta apertar no botão Install.  
OBS.: Se alguma janela relatar algum erro de segurança, é uma janela indicando que é uma extensão e que se não for confiável, não é seguro instalar. Python é amplamente utilizado e a extensão tem o selo Microsoft. Se julgar seguro, basta apertar na segunda opção 'Install anyway'.

<div align='center'>
  <img src='https://github.com/user-attachments/assets/2d643041-25ec-4a91-82e8-b39996577302' alt='Alerta de verificação de assinatura durante instalação da extensão' >
  <p align='center'>Alerta de verificação de assinatura durante instalação da extensão</p>
</div>

Com isso, ainda falta você ter o Python instalado na sua máquina. Antes de instalar, verifique se o Python está instalado.
Para isso, abra o cmd do Windows e digite ou copie e cole o seguinte código:
```
python -V
```
<div align='center'>
  <img src='https://github.com/user-attachments/assets/d873231d-7d4c-4b99-bb06-0d15e80356d8' alt='Comando para verificar a existência do Python em sua máquina digitado no prompt de comando do Windows' >
  <p align='center'>Comando para verificar a existência do Python em sua máquina digitado no prompt de comando do Windows</p>
</div>

Se gerar um erro, você não tem o Python na sua máquina.

## Contornando o problema da Microsoft Store
Você provavelmente já tentou instalar algo na Microsoft Store e deu algum erro, seja ao abrir a loja ou instalando algum aplicativo, certo?  
Infelizmente, a única forma de contornar este problema é tentando baixar seus aplicativos pelo próprio navegador.  
OBS.: A Microsoft Store Web também não é possível instalar nada, visto que redireciona o download para a Store instalada na máquina.  

Portanto, vá ao navegador e busque por uma versão do Python. A versão mais comum é a 3.11, que será instalada.
Cole o seguinte texto na barra de pesquisa:
```
python 3.11 download
```
Provavelmente o site do python.org aparecerá como primeira opção, mas se não foi o caso. Abra o site, [clicando aqui](https://www.python.org/downloads/release/python-3110/)

<div align='center'>
  <img src='https://github.com/user-attachments/assets/be5e1e58-cc6e-4929-8728-0741bd0695e4' alt='Primeiro resultado ao pesquisar no Google' >
  <p align='center'>Primeiro resultado ao pesquisar no Google</p>
</div>

Descendo toda a página, você verá as versões para instalar no computador. Considerando que você esteja no Windows, clique na opção Windows Installer (64-bit).  

<div align='center'>
  <img src='https://github.com/user-attachments/assets/02376aa6-cb02-4289-90cd-0db201da5a86' alt='Opções de instalação do Python 3.11' >
  <p align='center'>Opções de instalação do Python 3.11</p>
</div>

Abra o arquivo e instale no computador.

## Adicionando Python como variável do sistema
Após instalar o Python, adicione ele como variável do sistema. Caso não tenha visto durante a instalação qual foi o caminho que o Python foi instalado, te guiarei até lá.  
1. Abra o Microsoft Explorer
2. Vá em Este Computador
3. Disco Local (C:)
4. Usuários
5. Abra seu usuário

<div align='center'>
  <img src='https://github.com/user-attachments/assets/7d56c978-f8f4-4927-9aa3-2a55ad4f37da' alt='Parte superior do explorador de arquivos' >
  <p align='center'>Parte superior do explorador de arquivos</p>
</div>


6. Clique em Exibir

<div align='center'>
  <img src='https://github.com/user-attachments/assets/05992e8c-8876-4b4a-aa12-6113e0300774' alt='Em Mostrar/ocultar, clique em "Itens ocultos"' >
  <p align='center'>Em Mostrar/ocultar, clique em "Itens ocultos"</p>
</div>
7. Marque a opção "Itens Ocultos"
8. Agora, você verá pastas ocultas, procure pela pasta AppData no seu usuário.
9. Local
10. Programs
11. Python
12. Python311

<div align='center'>
  <img src='https://github.com/user-attachments/assets/1720f5f4-5b71-4829-acbb-493afa6bcd31' alt='Clique nesse caminho e copie ele com [CTRL] + [C]' >
  <p align='center'>Clique nesse caminho e copie ele com [CTRL] + [C]</p>
</div>

Agora, vamos adicionar este caminho como variável.
Digite "var" no menu iniciar e abra a opção de editar variáveis de ambiente do sistema.

<div align='center'>
  <img src='https://github.com/user-attachments/assets/9afdfcf7-ba20-4e0e-b09b-492db51287d9' alt='Primeiro resultado ao digitar "var" no menu iniciar' >
  <p align='center'>Primeiro resultado ao digitar "var" no menu iniciar</p>
</div>

Neste momento, você precisa de permissão de administrador. Chame qualquer pessoa do NTI que terá esse acesso.  
Após isso, clique no botão inferior direito "Variáveis do Ambiente..."
<div align='center'>
  <img src='https://github.com/user-attachments/assets/71d65cb7-0a79-42cd-be9d-92c38c40b28c' alt='Ao clicar em Variáveis do Ambiente, temos essas duas janelas.' >
  <p align='center'>Ao clicar em Variáveis do Ambiente, temos essas duas janelas.</p>
</div>

Você tem variáveis de usuário e as variáveis do sistema. No caso, procure por Path em Variáveis do sistema e clique duas vezes nele.  
Clique em uma linha em branco e cole aquele caminho que leva até o Python que você copiou anteriormente.
Aperte OK em todas as janelas.

Agora você pode abrir o cmd e digitar ou copiar o seguinte código:  
```
python -V
```
Agora, você deve estar vendo a versão do python sendo exibida pelo prompt de comando.
<div align='center'>
  <img src='https://github.com/user-attachments/assets/7e04c68a-6af5-4eac-98c7-09d7d49ef7fb' alt='Prompt de comando exibindo a versão do Python corretamente.' >
  <p align='center'>Prompt de comando exibindo a versão do Python corretamente.</p>
</div>

Recomendo que feche o VSCode e abra novamente.

Agora, o Python está funcionando corretamente! Bons estudos!  

<div align='center'>
  <img src='https://github.com/user-attachments/assets/9f6e9d01-f61c-4326-9002-b21025132c84' alt='Famoso Hello World! (Olá, mundo!) printado no console do VSCode.' >
  <p align='center'>Famoso Hello World! (Olá, mundo!) printado no console do VSCode.</p>
</div>

# C ou C++
Para C ou C++, ao invés de instalar o Python, você vai procurar por
```
mingw download
```
Ou simplesmente, abra [esse site](https://sourceforge.net/projects/mingw/)

<div align='center'>
  <img src='https://github.com/user-attachments/assets/60fa2f48-062c-4b78-8eaa-79266fbe0db5' alt='Página de instalação do MinGW' >
  <p align='center'>Página de instalação do MinGW.</p>
</div>

Aperte download e instale o software no "Padrão Windows": Next, Next, Next, Install.

<div align='center'>
  <img src='https://github.com/user-attachments/assets/41080d75-68f2-48a1-824e-a7da3e418dfc' alt='Para usar C/C++, selecione as opções mingw32-base junto com mingw32-gcc-g++. Caso queira programar em fortran, ada ou quiser uma instalação completa, marque as outras opções que desejar.' >
  <p align='center'>Para usar C/C++, selecione as opções mingw32-base junto com mingw32-gcc-g++. Caso queira programar em fortran, ada ou quiser uma instalação completa, marque as outras opções que desejar.</p>
</div>

Após isso, vá em Installation e aperte na opção "Apply Changes", seguido de um "Apply" na nova janela.

<div align='center'>
  <img src='https://github.com/user-attachments/assets/f99eb902-733c-4dc4-979f-7f3dd1876683' alt='Aqui sua instalação foi finalizada, basta apertar "Close" para fechar o instalador. Pode fechar também a janela do MinGW.' >
  <p align='center'>Aqui sua instalação foi finalizada, basta apertar "Close" para fechar o instalador. Pode fechar também a janela do MinGW.</p>
</div>

Após isso, basta adicionar o caminho da instalação como variável de ambiente.  
Para esta instalação, o caminho que o MinGW é instalado, caso não tenha sido alterado durante a instalação é o:
```
C:\MinGW\bin
```
Basta copiar este caminho e colocar como variável do ambiente.

<div align='center'>
  <img src='https://github.com/user-attachments/assets/500f30d9-7908-4dc1-93c3-d1b1ba6443c7' alt='Adicionando caminho comovariável de ambiente. Lembre que esse caminho deve ser adicionado em "Path" e em "Variáveis do Sistema".' >
  <p align='center'>Aqui sua instalação foi finalizada, basta apertar "Close" para fechar o instalador. Pode fechar também a janela do MinGW.</p>
</div>

Partindo para o VSCode, em extensões podemos instalar algumas que te auxiliarão enquanto programa em C/C++.  
1. C/C++:
<div align='center'>
  <img src='https://github.com/user-attachments/assets/e4088bc7-180b-4a14-9679-1b30f9e3cec4' alt='Primeira extensão do VSCode. Ela te auxiliará com o intelliSense, sugerindo estruturas e preenchendo automaticamente seu código à medida que você digita.' >
  <p align='center'>Aqui sua instalação foi finalizada, basta apertar "Close" para fechar o instalador. Pode fechar também a janela do MinGW.</p>
</div>

2. C/C++ Compile Run
<div align='center'>
  <img src='https://github.com/user-attachments/assets/de13762a-aaf1-4a8c-8fed-414af154640d' alt='Segunda extensão do VSCode. Ela te permite executar seu código C/C++ com a tecla [F6] ou apertando o botão '<img src='https://github.com/user-attachments/assets/ca5bfce4-00f8-42c5-b0e9-e56042709dc3' width='' height=''> >
  <p align='center'>Segunda extensão do VSCode. Ela te permite executar seu código C/C++ com a tecla [F6] ou apertando o botão '<img src='https://github.com/user-attachments/assets/ca5bfce4-00f8-42c5-b0e9-e56042709dc3</p>
</div>

Executando o famoso "Hello World!", temos o resultado corretamente printado no terminal.
<div align='center'>
  <img src='https://github.com/user-attachments/assets/057152ad-1f60-40a1-859d-88c098426be2' alt='Hello World em C++' width='' height=''> >
  <p align='center'>Aqui sua instalação foi finalizada, basta apertar "Close" para fechar o instalador. Pode fechar também a janela do MinGW.</p>
</div>

Dica: Para outras linguagens, é basicamente o mesmo procedimento, apenas voltado para outra linguagem, seja ela C#, Rust, Java etc.
