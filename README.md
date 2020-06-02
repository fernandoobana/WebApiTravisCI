# Exemplo de CI com Travis e WebApi DotNet Core 3.1

status do CI no Travis: [![Build Status](https://travis-ci.org/fernandoobana/WebApiTravisCI.svg?branch=master)](https://travis-ci.org/fernandoobana/WebApiTravisCI)

Criado projeto API no Dotnet Core 3.1 para testar o deploy automático.

Ao realizar um push no GitHub, automaticamente é criado (caso não exista) ou atualizada a versão no repositório do Docker Hub.

 No arquivo yml podemos ver que utilizei a versão 3.1 do dotnet core. Está funcionando normalmente.
 
 As variáveis DOCKER_USERNAME e DOCKER_PASSWORD correspondem, respectivamente, ao seu usuário e senha no Docker Hub.
 
 Em branch você pode especificar de qual branch será enviado o pacote.
 
 Deixei marcado para não enviar e-mail após o deploy, podendo ser alterado.
 
 * DICA: caso ocorra algum problema no Travis, clique sobre as linhas. Algumas delas irão expandir, dando mais detalhes sobre o erro.
