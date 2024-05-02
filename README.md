# Gerenciamentodemembros
Conte a seguinte estrutura:

Meu site
css(pasta)


styles.css:
/* Reset de estilos */
html, body, div, span, applet, object, iframe,
h1, h2, h3, h4, h5, h6, p, blockquote, pre,
a, abbr, acronym, address, big, cite, code,
del, dfn, em, img, ins, kbd, q, s, samp,
small, strike, strong, sub, sup, tt, var,
b, u, i, center,
dl, dt, dd, ol, ul, li,
fieldset, form, label, legend,
table, caption, tbody, tfoot, thead, tr, th, td,
article, aside, canvas, details, embed,
figure, figcaption, footer, header, hgroup,
menu, nav, output, ruby, section, summary,
time, mark, audio, video {
    margin: 0;
    padding: 0;
    border: 0;
    font-size: 100%;
    font: inherit;
    vertical-align: baseline;
}

}

header {
    background-color: #1e1e2e;
    color: #fff;
    padding: 20px;
}


body {
  font-family: var(--font-fanav ul {
  list-style-type: none;
  padding: 0;
  margin: 0;
}


mily);
  line-height: var(--:root {
  --font-family: "Arial", sans-serif;
  --line-height: 1.6;
  --background-color: #1e1e2e; /* Dark blue */
  --text-color: #ffffff; /* White */
}

-style: none;
}

nav ul li {body {
  font-family: var(--font-family);
  line-height: var(--line-height);
  background-color: var(--background-color);
  color: var(--text-color);
}




instance(pasta)

js:
// Função para validar o formulário de login
function validarLogin() {
    var username = document.getElementById('username').value;
    var password = document.getElementById('password').value;

    // Verificar se os campos estão vazios
    if (username.trim() === '' || password.trim() === '') {
        alert('Por favor, preencha todos os campos.');
        return false;
    }

    return true;
}

// Adicionar um ouvinte de evento ao formulário de login
document.getElementById('loginForm').addEventListener('submit', function(event) {
    if (!validarLogin()) {
        // Impedir o envio do formulário se a validação falhar
        event.preventDefault();
    }
});

Static
styles.css
templates
criarconta.html
index.html
login.html
templates.html
app.py
apps.py
arquivo.php
criarconta.html
index.html
login.html
venv




Repositorio atende aos seguintes requesitos



Requisitos do site:
Login
Banco de dados com os seguintes dados:
Novos convertidos:
Nome:
Numero:
Endereço:

Membros de casa:
crianças-jovens-homens-mulheres-casais-louvor-Ebd:
Todos devem conter:
Nome:
Numero:
Endereço:
Visitante:
Nome:
Numero
Tipos de acesso
Administrator
Pastor 
Lideres dos seguintes departamnetos:
Ministério de Crianças
Ministério de Homens
Ministério de Mulheres
Ministério de Casais:
Ministério de Louvor e Adoração
Ministério Escola Bíblica:

Tipos de acesso para cada lider de departamento:
Ministério de Jovens:
Acesso: Novos membros, visitantes, membros de casa

Ministério de Crianças
Acesso: Novos membros, visitantes, membros de casa

Ministério de Adultos
Acesso: Novos membros, visitantes, membros de casa

Ministério de Mulheres e Homens
Acesso: Novos membros, visitantes, membros de casa

Ministério de Casais:
Acesso: Novos membros, visitantes, membros de casa

Ministério de Louvor e Adoração
Acesso: Novos membros, visitantes, membros de casa

Ministério Escola Bíblica:
Acesso: Novos membros, visitantes, membros de casa


Usuario:
 
Senha:

Cadastrar nova conta

Criar conta:
Nome:
Cpf:
Departamento:


Dependendo do departamento ter o seguintes acesso:
Administrator total|

pastor parcialmente total

Lideres de departamentos:
Ministério de Crianças
Ministério de Homens
Ministério de Mulheres
Ministério de Casais:
Ministério de Louvor e Adoração
Ministério Escola Bíblica:
