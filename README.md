### Haloo, Aku <a href="https://gkassym.netlify.app" target="_blank">Faizol Ama</a> <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="25px">
[![Linkedin Badge](https://img.shields.io/badge/-LinkedIn-0e76a8?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/faizol-ama-955a13195)
[![Website Badge](https://img.shields.io/badge/Website-3b5998?style=flat-square&logo=google-chrome&logoColor=white)](https://www.javazol.com)
[![Twitter Badge](https://img.shields.io/badge/-Twitter-00acee?style=flat-square&logo=Twitter&logoColor=white)](https://twitter.com/Izol56483927)
[![Instagram Badge](https://img.shields.io/badge/-Instagram-e4405f?style=flat-square&logo=Instagram&logoColor=white)](https://instagram.com/zzzzzooolll/)
![visitors](https://visitor-badge.glitch.me/badge?page_id=page.id)
<img height="180em" src="https://github-readme-stats.vercel.app/api?username=izolama&show_icons=true&hide_border=true&&count_private=true&include_all_commits=true" />



### Sangat senang sudah berkunjung! &nbsp; ![](https://visitor-badge.glitch.me/badge?page_id=izolama.izolama)

Saya membuat ini untuk mengikuti tes di PT. Mega Giga Solusindo [![Website Badge](https://img.shields.io/badge/Website-3b5998?style=flat-square&logo=google-chrome&logoColor=white)](https://https://megagigasolusindo.co.id/)
<img align="right" alt="GIF" src="https://github.com/Gapur/Gapur/blob/master/coding.gif?raw=true" width="408" height="318" />
  
Berikut Hasil jawaban yang sudah saya kerjakan dalam
Waktu 6 jam 

[![Build Status](https://travis-ci.org/ekalinin/github-markdown-toc.svg?branch=master)](https://travis-ci.org/ekalinin/github-markdown-toc)

<a name="top"></a>
Table of contents
=================

1. [ Framework Css. ](#desc)
2. [ Framework JavaScript. ](#usage)
   - [React Tutorial. ](#tuto)
   - [To Use. ](#use)
   - [Node. ](#node)
   - [Python. ](#py)
   - [Ruby. ](#ruby)
   - [PHP. ](#php)
   - [Go. ](#go)
   - [Perl. ](#perl)
   - [Changing The Port. ](#change)
3. [ Request Http Call. ](#call)
   - [FetchApi. ](#fetch)  
   - [AXIOS. ](#axios)
3. [ Methode Request Http. ](#req)
   - [Get. ](#a)
   - [Post. ](#b)
   - [Put. ](#c)
   - [Head. ](#d)
   - [Delete. ](#e)
   - [Patch. ](#f)
   - [Options. ](#g)

<a name="desc"></a>
Framework Css
============

Framework yang pernah digunakan , panduan 
[TaiwindCss](https://tailwindcss.com/) dan 
[Bootstrap](https://getbootstrap.com/)

```bash
 - Taiwind CSS
 - Bootstrap
```

<a name="usage"></a>
Framework JavaScript
============

Framework JavaScript favoritku [ReactJs](https://reactjs.org/)

```bash
 - React Js
```
[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy)

<a name="tuto"></a>
# React Tutorial

This is the React comment box example from [the React tutorial](http://facebook.github.io/react/docs/tutorial.html).

<a name="use"></a>
## To use

There are several simple server implementations included. They all serve static files from `public/` and handle requests to `/api/comments` to fetch or add data. Start a server with one of the following:

<a name="node"></a>
### Node

```sh
npm install
node server.js
```

<a name="py"></a>
### Python

```sh
pip install -r requirements.txt
python server.py
```

<a name="ruby"></a>
### Ruby
```sh
ruby server.rb
```

<a name="php"></a>
### PHP
```sh
php server.php
```

<a name="go"></a>
### Go
```sh
go run server.go
```

<a name="perl"></a>
### Perl

```sh
cpan Mojolicious
perl server.pl
```

And visit <http://localhost:3000/>. Try opening multiple tabs!

<a name="change"></a>
## Changing the port

You can change the port number by setting the `$PORT` environment variable before invoking any of the scripts above, e.g.,

```sh
PORT=3001 node server.js
```


**[ ∆ back to top ](#top)**


<a name="call"></a>
Http Call antara Fetch & AXIOS
============
Http call yang lebih baik dalam penerapan
[FetchApi](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API) dan 
[AXIOS](https://axios-http.com/docs/intro) 

<a name="fetch"></a>
Fetch Api , adalah native web Api untuk melakukan HTTP Call dari
External network. Untuk Fetch di MDN terjadi dokumentasi yang
Bertumpuk .

```js
const url = 'https://yantek.padipresence.id/api/ticket/support/';
 fetch(url, {
   headers : {
    'Accept' : 'application/Json'
      }
    }).then(res => console.log(res));
```
### console fetchApi

```populate
  [ObjectResponse]{
   ArrayBuffer: function arrayBuffer (){},
   Blob: function blob(){},
   Body: [objectReadableStream]{},
   Bodyused: false,
   Clone: function clone(){},
   FormData: function clone(){},
   Headers: [objectHeaders]{},
   Json: function json(){},
   Ok: true,
   Redirected: false,
   Status: 200,
   StatusText: "";
   Text: function text(){},
   Text: "is_01",
   Url: 'https://yantek.padipresence.id/api/ticket/support/';

  }
```

Terdapat `Console.log()` di `json ()` yang convert dengan hasil
response ke raw JSON , untuk FetchApi yang harus dilakukan adalah

```js
const url = 'https://yantek.padipresence.id/api/ticket/support/';
 fetch(url, {
   headers : {
    'Accept' : 'application/Json'
      }
    })
  .then(res => res.json());
  .then(data => console.log(data));
```
Melakukan sekali lagi pemanggilan dengan fungsi `.then` untuk 
Mendapatkan data `response` yang diinginkan .

```populate
 Object{
  User : "is_01",
  Pass : "1234",
  Imei : "imei1234",
  Status : 200
```

**[ ∆ back to top ](#top)**


<a name="axios"></a>
Sedangkan dengan `AXIOS`
```js
const url = 'https://yantek.padipresence.id/api/ticket/support/';
 AXIOS.get(url {
  headers : {
   'Accept' : 'application/json'
  }
 }.then(res => console.log(res));
   
```
Menampilkan di console 
```populate
 Object{
  Config : object{},
  Data: Object{
    User : "is_01",
    Pass : "1234",
    Imei : "imei1234",
    Status : 200
 },
 Headers : object{},
 Request : [object xmlHttpRequest]{},
 Status : 200,
 StatusText : " "
}
```
AXIOS tidak membutuhkan fungsi convert `.json()` . Karena  `response` 
AXIOS otomatis `return as a JSON` hanya melakukan pemanggilan 
`res.data` untuk mendapatkan response yang diinginkan.

**[ ∆ back to top ](#top)**


<a name="req"></a>
Methode Request Http
============
<a name="a"></a>
`GET` ~ digunakan untuk meminta data dari sumber daya tertentu.

```js
const axios = require('axios');

// Make a request for a user with a given ID
axios.get('/user?ID=12345')
  .then(function (response) {
    // handle success
    console.log(response);
  })
  .catch(function (error) {
    // handle error
    console.log(error);
  })
  .then(function () {
    // always executed
  });

// Optionally the request above could also be done as
axios.get('/user', {
    params: {
      ID: 12345
    }
  })
  .then(function (response) {
    console.log(response);
  })
  .catch(function (error) {
    console.log(error);
  })
  .then(function () {
    // always executed
  });  

// Want to use async/await? Add the `async` keyword to your outer function/method.
async function getUser() {
  try {
    const response = await axios.get('/user?ID=12345');
    console.log(response);
  } catch (error) {
    console.error(error);
  }
}
```
**[ ∆ back to top ](#top)**

<a name="b"></a>

`POST` ~ digunakan untuk mengirim data ke server , dan server membuat atau memperbarui
sumber daya. Data yang dikirim ke server dengan `post` disimpan di `request` body permintaan `Http`
```js
function getUserAccount() {
  return axios.get('/user/12345');
}

function getUserPermissions() {
  return axios.get('/user/12345/permissions');
}

Promise.all([getUserAccount(), getUserPermissions()])
  .then(function (results) {
    const acct = results[0];
    const perm = results[1];
  });
```
**[ ∆ back to top ](#top)**

<a name="c"></a>

`PUT` ~ Mengirim data ke server , dan server membuat atau memperbarui
sumber daya. Perbedaan `POST` dan `PUT` , `PUT` memanggil permintaan
berulang dengan hasil yang sama. Sedang `POST` memanggil permintaan berulang 
dan memiliki efek samping berupa pembuatan sumber daya yang sama beberapa kali.

```js
axios.put(
  '/yantek.padipresence.id/api/ticket/support/',
  {
    title: title,
    description: description,
    published: true,
  },
  {
    headers: {
      "x-access-token": "token-value",
    },
  }
);
```
**[ ∆ back to top ](#top)**


<a name="d"></a>
`Headers` ~ memeriksa Methode `GET` dengan apa yang dilakukan akan
dikembangkan sebelum benar - benar membuat permintaan `GET` seperti sebelum 
mengunduh file besar atau isi `response`

```js
const axios = require('axios');

const res = await axios.get('https://yantek.yadipresence.id/api/ticket/support/', {
  headers: {
    'Test-Header': 'test-value'
  }
});

res.data.headers['Test-Header']; 
```
**[ ∆ back to top ](#top)**

<a name="e"></a>

`Delete` ~ untuk menghapus sumber daya yang ditentukan

```js
const res = await axios.delete('https://yantek.yadipresence.id/api/ticket/support/', { data: { id: 10} });

res.data.json; // { answer: 42 }
```
**[ ∆ back to top ](#top)**



**Test yang saya lakukan:**

- [x] Framework CSS yang pernah digunakan
- [x] Framework JavaScript yang sering digunakan
- [x] Analisa jawaban fetchApi & AXIOS
- [x] Methode request Http
- [ ] aplikasi login - list - add 

