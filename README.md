### Lista de medicamentos aprovados pela Agência Nacional de Vigilância Sanitária (Anvisa)


Execute o seguinte comando no terminal para importar os dados dos medicamentos para o MongoDB:
```console 
$ mongoimport --db nomeDB --collection nomeCollection --file medicamentos-anvisa.json --jsonArray
```
