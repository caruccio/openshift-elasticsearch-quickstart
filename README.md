# ElasticSearch Openshift Quickstart

Instalação do ElasticSearch em forma de quickstart.

- Cadastre-se em [http://getupcloud.com/](http://getupcloud.com/#/sign-up) e ganhe 750hs para fazer um test-drive.
- [Instale o rhc](https://getup.zendesk.com/entries/23056511) em seu ambiente.
- Crieuma aplicação Do-It-Yourself usando o códig deste quickstart: 

```
$ rhc app create elasticsearch -t diy --from-code https://github.com/caruccio/openshift-elasticsearch-quickstart.git
```

Agora é só apontar seu navegador para `http://elasticsearch-$namespace.getup.io`.


Para atualizar o código, baixe a nova versao em http://www.elasticsearch.org/ e substitua o conteúdo do diretorio `elasticsearch`.

Ainda não existe suporte para cluster. Voluntários?
