# Table Of Contents
  
 ​​1.​ [​​Framework CSS yang pernah digunakan ?](#types)

 2.​ [​Framework JavaScript?​](#references)

 ​​3.​ [​Http call yang lebih baik di JavaScript FetchApi, jQuery, atau AXIOS ?](#objects)

 ​​4.​ [​Mthode request Http, sebutkan dan jelaskan ?](#arrays) 

 ​5.​ [Aplikasi login-tampillist-tambah​​](#destructuring)

 
 ​##​ ​Types 
  
 ​  <a name="types--primitives"></a><a name="1.1"></a> 
 ​  ​-​ [​1.1​](#types--primitives) ​**Primitives**​: When you access a primitive type you work directly on its value. 
  
 ​    ​-​ ​`string` 
 ​    ​-​ ​`number` 
 ​    ​-​ ​`boolean` 
 ​    ​-​ ​`null` 
 ​    ​-​ ​`undefined` 
 ​    ​-​ ​`symbol` 
 ​    ​-​ ​`bigint` 
  
 ​    ```javascript 
 ​    ​const​ ​foo​ ​=​ ​1​; 
 ​    ​let​ bar ​=​ foo; 
  
 ​    bar ​=​ ​9​; 
  
 ​    ​console​.​log​(foo, bar); ​//​ => 1, 9 
 ​    ``` 
  
 ​    ​-​ Symbols and BigInts cannot be faithfully polyfilled, so they should not be used when targeting browsers/environments that don’t support them natively. 
  
 ​  <a name="types--complex"></a><a name="1.2"></a> 
 ​  ​-​ [​1.2​](#types--complex)  ​**Complex**​: When you access a complex type you work on a reference to its value. 
  
 ​    ​-​ ​`object` 
 ​    ​-​ ​`array` 
 ​    ​-​ ​`function` 
  
 ​    ```javascript 
 ​    ​const​ ​foo​ ​=​ [​1​, ​2​]; 
 ​    ​const​ ​bar​ ​=​ foo; 
  
 ​    bar[​0​] ​=​ ​9​; 
  
 ​    ​console​.​log​(foo[​0​], bar[​0​]); ​//​ => 9, 9 
 ​    ``` 
  
 ​**[​⬆ back to top​](#table-of-contents)** 
 
  

