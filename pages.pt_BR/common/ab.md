# ab

> Ferramenta da Apache para realizar benchmarking e testes de carga em servidores web.
> Mais informações: <https://httpd.apache.org/docs/current/programs/ab.html>.

- Executa 100 requisições HTTP do tipo GET para uma determinada URL:

`ab -n {{100}} {{url}}`

- Executa 100 requisições HTTP do tipo GET para uma determinada URL, executando 10 requisições simultâneas de cada vez:

`ab -n {{100}} -c {{10}} {{url}}`

- Utiliza a funcionalidade HTTP Keep Alive, permitindo que várias requisições sejam feitas em uma sessão HTTP:

`ab -k {{url}}`

- Define o tempo total do benchmarking, em segundos:

`ab -t {{60}} {{url}}`
