# burguer-dev

## Instalações iniciais

1. Node -> npm init -y
2. Biblioteca de css -> npm i -D tailwindcss
3. Cria arquivo de configuração do tailwindcss -> npx tailwindcss init
4. Altera a propriedade content do arquivo gerado: tailwind.config -> content: ["./**/*.{html,js}"],
5. Acrescenta no style.css -> 
    @tailwind base;
    @tailwind components;
    @tailwind utilities;
6. Modifica script do package.json -> "dev": "npx tailwindcss -i ./styles/style.css -o ./styles/output.css --watch" 
    Nota: substitui: "test": "echo \"Error: no test specified\" && exit 1"
7. Finalizando com -> npm run dev
