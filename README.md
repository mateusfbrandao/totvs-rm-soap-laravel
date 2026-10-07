# totvs-rm-soap-laravel (deprecated)

Este pacote foi **unificado** em [`mateusfbi/totvs-rm-soap`](https://packagist.org/packages/mateusfbi/totvs-rm-soap).

## Migração

```bash
composer remove mateusfbi/totvs-rm-soap-laravel
composer require mateusfbi/totvs-rm-soap
```

Atualize os namespaces no código:

```diff
- use mateusfbi\TotvsRmSoap\Services\DataServer;
+ use TotvsRmSoap\Services\DataServer;
```

```diff
- use mateusfbi\TotvsRmSoap\Facades\TotvsRM;
+ use TotvsRmSoap\Facades\TotvsRM;
```

A API dos serviços permanece a mesma. Veja o README do pacote novo para uso em PHP puro e Laravel.
