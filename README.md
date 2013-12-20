# ElasticSearch Openshift Quickstart

Instalação do ElasticSearch em forma de quickstart. Para criar uma aplicação ES, execute o comando:

```
$ rhc app create elasticsearch -t diy --from-code https://github.com/caruccio/openshift-elasticsearch-quickstart.git
```

Para atualizar, baixe a nova versao em http://www.elasticsearch.org/ e substitua o conteúdo do diretorio `elasticsearch`.

Ainda não existe suporte para cluster. Voluntários?
