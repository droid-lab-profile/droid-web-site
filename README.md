# droid-web-site
Droid Lab WebSite.

## Paleta de Cores

```
$color-blue-light: #7BE0F1;
$color-blue-medium: #3DC2D8;
$color-blue-dark: #1B597F;
$color-purple-light: #755F89;
$color-purple-medium: #523866;
$color-purple-dark: #342442;
$color-green-light: #CED9D2;
$color-white: #EBF5EE;
```

## Fontes

```
<link href="https://fonts.googleapis.com/css?family=Montserrat:400,600,700|Roboto:400,700" rel="stylesheet">
font-family: 'Montserrat', sans-serif;
font-family: 'Roboto', sans-serif;
```

## Ajustes =====================================================================
================================================================================

---
Alguns ajustes:
A altura do logo deve ser 87px; Sua largura 507px. (isso pode variar em outras resolução)
O icone do droid deve ter 316x316px.

As fontes precisam ter em pixels:

Bem vindo... -> 43px;
Somos... -> 33px

O botão:
70x333px

Texto do botão 25px.

---

Além disso, essa seção deve possuir uma altura um pouco  'especial'

#home {
background-image: url(../../../images/home-header-bg.jpg);
padding: 5.5% 0% 2% 0%;
min-height: 100vh;

}

Para que a altura sempre tenha o mesmo tamanho do viewport (100vh = 100% do viewport heigth)

Por esse motivo, os posicionamentos também deve ser feitos de uma forma um pouco diferente.

O logo deve ficar do tipo:
#logo{
position:absolute;
top: 5%;
}

#middle-container{
position:absolute;
top:50%;
transform: translateX(-50%);
}

Ai colocar o droid e os escritos no middle container (para que eles fiquem alinhados ao centro)

#botao{
position:absolute;
bottom: 5%;
}

Também faltou o background azul para o menu. Que vai ser aberto de forma diferente ;)
Algo semelhante a isso: http://irrastudio.com/


========= AJUSTES 2 =======


Alguns ajustes podem ser feitos nessa área.
<div class="col-lg-2"></div>

Isso não é necessário. O layout prevê que o conteúdo esteja alinhado a esqueda.

E ainda mais uma dica. Você não precisa criar uma coluna vazia para "movimentá-la".

Poderia fazer da seguinte forma:
<div class="col-lg-6 col-offset-lg-2"></div>

---

O título  "Sobre" tem que ficar com um tamanho equivalente a 85px.
O sub-título deve ficar com o equivalente a 65px.
O sub-sub-título deve ficar com 31px.
O conteúdo deve ficar com 18px.

Para achar os valorem em "em" precisa fazer uma conta com base no font-size definido no body.

Acredito que esteja em 14px;

Então é 85/14 = 6.07em;
A mesma coisa para os outros.

-------------------------------

## GERAIS =============================================
Alterar título da página;
Alterar meta-tags da página;
Alterar a cor do scroll;
## ==================================================

A altura do logo deve ser 87px; Sua largura 507px. (isso pode variar em outras resolução)
O icone do droid deve ter 316x316px.

As fontes precisam ter em pixels:

Bem vindo... -> 43px;
Somos... -> 33px

O botão:
70x333px

Texto do botão 25px.


