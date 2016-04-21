# heroku-buildpack-bower

- Adicionando pelo terminal:<br/>
heroku buildpacks:set --index 2 https://github.com/clezioalves/heroku-buildpack-bower.git

- Adicionar a dependência e script no arquivo package.json<br/>

"dependencies": {<br/>
	"bower": "^1.7.9"<br/>
},<br/>
"scripts": {<br/>
	"postinstall": "bower install"<br/>
}<br/>
