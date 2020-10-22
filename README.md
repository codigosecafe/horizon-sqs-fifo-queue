# horizon-sqs-fifo-queue

[![Latest Version on Packagist][ico-version]][link-packagist]
[![Software License][ico-license]](LICENSE.txt)
[![Build Status][ico-travis]][link-travis]
[![Coverage Status][ico-scrutinizer]][link-scrutinizer]
[![Quality Score][ico-code-quality]][link-code-quality]
[![Total Downloads][ico-downloads]][link-downloads]

Esse projeto tem com origem um fork do projeto: https://github.com/shiftonelabs/laravel-sqs-fifo-queue

Este pacote Laravel / Lumen fornece um driver de fila para as filas SQS FIFO da Amazon. Embora o Laravel funcione com as filas padrão SQS da Amazon fora da caixa, as filas FIFO são um pouco diferentes e não são tratadas corretamente pelo Laravel. É aí que entra este pacote.

## Versões

Este pacote foi testado no Laravel 4.1 até o Laravel 8.x, embora possa continuar a funcionar nas versões posteriores à medida que forem lançadas. Esta seção será atualizada para refletir as versões nas quais o pacote foi realmente testado.

## Instalação

Via Composer

``` bash
$ composer require codigosecafe/horizon-sqs-fifo-queue
```

Assim que o composer for atualizado e o pacote instalado, o provedor de serviços precisará ser carregado.

#### Laravel 5.5+, 6.x, 7.x, 8.x (5.5, 5.6, 5.7, 5.8, 6.x, 7.x, 8.x)

Este pacote usa descoberta automática de pacotes. O provedor de serviços será registrado automaticamente.
