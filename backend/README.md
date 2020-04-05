<p align="center"><a target="_blank" href="https://matheus.sgomes.dev"><img src="https://matheus.sgomes.dev/img/logo_azul.png"></a></p>


👤 **Matheus S. Gomes** 

* Website: https://matheus.sgomes.dev
* Github: [@Matheussg42](https://github.com/Matheussg42)
* LinkedIn: [@matheussg](https://linkedin.com/in/matheussg)

---

<p align="center">
<img src="../frontend/src/assets/logo.svg" style='width: 300px'>
</p>



<p align="center">
 <img src="https://img.shields.io/static/v1?label=OmniStack&message=11&color=7159c1&labelColor=444444" alt="OmniStack 11!" />

  <img alt="Documentation" src="https://img.shields.io/static/v1?label=Documentation&message=V1.0&color=f1c40f&labelColor=444444"> 
  
  <img alt="Back-end" src="https://img.shields.io/static/v1?label=Back-end&message=Ok&color=27ae60&labelColor=444444">
  
  <img alt="Node" src="https://img.shields.io/static/v1?label=Node.js&message=13.6.0&color=27ae60&labelColor=444444"> 
  
  <img alt="Yarn" src="https://img.shields.io/static/v1?label=Yarn&message=1.21.1&color=27ae60&labelColor=444444">
</p>

<p align="center">
  <a href="/">Home</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="/backend">Back-end</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="/frontend">Front-end</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="/mobile">Mobile</a>
</p>

#### Nesta Página:

* [Projeto](#projeto)
* [Instalando dependências](#dependencias)
* [Subindo a aplicação](#aplicacao)
* [Endpoints](#endpoints)

<span id="projeto"></span>
## Projeto

O BeTheHero é um projeto que visa conectar pessoas que desejam fazer contribuições monetárias a ONG's (Organizações não governamentais) que precisam de ajuda.

<span id="dependencias"></span>
## Instalando dependências

Acesse a raiz da pasta `backend` pelo _terminal_, e instale as dependências usando o comando `yarn`, ou `npm`.

```js
yarn install
```

```js
npm install
```


<span id="aplicacao"></span>
## Subindo a aplicação

Acesse a raiz da pasta `backend` pelo _terminal_, digite o comando `yarn start`.

```js
yarn start
```


<span id="endpoints"></span>
## Endpoints

#### POST - Session

```json
http://localhost:3333/sessions
```

```json
Body: {
  "id": "dd6fa8b4"
}
```

#### GET - profile

```json
http://localhost:3333/profile
```

#### POST - Ongs

```json
http://localhost:3333/ongs
```

```json
Body: {
  "name": "Nome da Ong",
  "email": "ong@email.com.br",
  "whatsapp": "11911111111",
  "city": "Belo Horizonte",
  "uf": "MG"
}
```

#### GET - Ongs

```json
http://localhost:3333/ongs
```

#### POST - Incidents

```json
http://localhost:3333/incidents
```

```json
Body: {
  "title": "Titulo",
  "description": "Descrição",
  "value": 1000
}
```

#### DELETE - Incidents

```json
http://localhost:3333/incidents/1
```

#### GET - Incidents

```json
http://localhost:3333/incidents
```