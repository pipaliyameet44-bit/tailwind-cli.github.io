method 1:
git - repo create<br>
<br>enter
<br>git clone <link>
<br>enter
<br>git add . / git add index.html
<br>enter
<br>git commit -m "msg"
<br>enter
<br>git push origin main
enter
methos 2:
folder-computer
git init
enter 
git remote add <link>
enter
git add .
enter
git commit -m "msg"
enter 
git push origin main
enter
<h1>website</h1>
1.npm install tailwindcss @tailwindcss/cli
2.@import "tailwindcss";
3.run:npx @tailwindcss/cli -i ./input.css -o ./src/output.css --watch

<h1>vs code</h1>
1.openterminal
<br>2.paste cmd
<br>3.enter
<br>4.create index.html and input.css
<br>5.index.html --><link rel="stylesheet" href="./output.css">
<br>6.paste into input.css -->@import "tailwindcss";
<br>7.package.json-->
<code>
"scripts": {
    "dev": "npx @tailwindcss/cli -i ./input.css -o ./output.css --watch"
  }
</code>
<br>8.in terminal start --> npm run dev 
method 3:
1.git branch
2.git branch <branchname>
3.exmple:git branch devlopment
4.git branch
5.git checkout <branchname>
6.example:git checkout devlopment
