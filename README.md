<h1 align="center">
  <br>
  <br>
  Consulta CEP
</h1>

<h4 align="center">
   App desenvolvido com React Native + NodeJS + Android Studio 
</h4>

<h6 align="center">
  bootcamp SujeitoProgramador
</h6>

<br/>

<p align="center">
  <a href="#Pre-Requisitos">Pre-requisitos</a> |
  <a href="#Instalação">Instalação</a> |
  <a href="#Usabilidade">Usabildiade</a>
</p>

# Pre-Requisitos

* [React-Native](https://reactnative.dev/)
* [Android Studio](https://developer.android.com/studio) 
* [Node.JS](https://nodejs.org/)
* [Yarn](https://classic.yarnpkg.com/) or [npm](https://www.npmjs.com/get-npm)

# Instalação
```
# Primeiro clone o repositorio do Git para seu computador. Execute o comando; 
git clone https://github.com/SandroFrazaoS/zipcode.git

# Acesse a pasta criado atraves do comando; 
cd zipcode

# Instale todas as dependencias do projeto, acesse a pasta zipcode e execute o comando;
yarn

# Para start do App execute dentro da pasta zipcode o comando;
npx react-native run-android
```

# Usabilidade

O aplicativo consulta o CEP atraves de uma Api do site https://viacep.com.br


![1][tela1]

Ao digitar o CEP é visualizado as informações da rua, cidade, bairro, codigo IBGE, etc. 

![2][tela2]

Caso o CEP informado for invalido e emitido um alerta.

![3][tela3]



[tela1]: Tela1.png
[tela2]: Tela2.png
[tela3]: Tela3.png
