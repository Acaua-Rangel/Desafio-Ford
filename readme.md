# **Ford <Enter> - Front-end**  

Este repositório contém o código-fonte do site promocional da Ford, desenvolvido com HTML, CSS e Tailwind CSS. O objetivo é apresentar a nova Ford Ranger, destacando seus modelos e especificações de forma dinâmica e responsiva.  

## **Tecnologias Utilizadas**  

- **HTML5** para estruturação do conteúdo  
- **Tailwind CSS** para estilização e responsividade  
- **JavaScript** para interatividade do select no contato

## **Como Rodar o Projeto**  

### **1. Instale as Dependências**  

Caso ainda não tenha instalado as dependencias do projeto, instale com o seguinte comando:  

```sh
npm install
```

### **2. Executando o Tailwind CSS**  

Para compilar as classes do Tailwind e monitorar mudanças no código-fonte, execute o seguinte comando:  

```sh
npx @tailwindcss/cli -i ./css/input.css -o ./css/output.css --watch
```

Isso garantirá que todas as alterações no CSS sejam aplicadas automaticamente durante o desenvolvimento.  

### **3. Iniciando Live Server**

Se estiver usando o Live Server para visualizar o projeto, você deve clicar em "Go Live" no canto inferior direito do VS Code para iniciar.

Caso o VS Code não abra automaticamento o projeto no navegador, você pode abrir a seguinte URL para visualizar o projeto:

[http://localhost:5500/home.html](http://localhost:5500/home.html)

Se a ```porta``` do Live Server constar diferente de **5500**, você pode alterar a URL da seguinte forma:

```
http://localhost:<port>/home.html
```

Substituindo o ```<port>``` pela respectiva porta.

## **Estrutura do Projeto**  

```
📂 Ford HTML-CSS
 ├── 📂 css
 │   ├── reset.css
 │   ├── input.css
 │   ├── output.css
 ├── 📂 img
 │   ├── facebook-50.png
 │   ├── favicon.ico
 │   ├── ford-96.png
 │   ├── imagem_1.jpg
 │   ├── info.png
 │   ├── instagram-logo-50.png
 │   ├── logo-ford-256.png
 │   ├── storm.jpg
 │   ├── XL Cabine.jpg
 │   ├── xls 2.2 diesel.jpg
 │   ├── youtube-squared-50.png
 ├── 📂 js
 │   ├── script.js
 ├── contato.html
 ├── home.html
 ├── lancamento.html
 ├── package-lock.json
 ├── package.json
 ├── README.md
```

## **Requisitos do Projeto**  

- Criar uma página responsiva destacando os modelos da Ford Ranger  
- Implementar um menu de navegação intuitivo  
- Exibir imagens e vídeos promocionais  
- Utilizar tabelas para comparação entre os modelos  

## **Licença**  

Este projeto foi desenvolvido para fins educacionais e promocionais da Ford.  