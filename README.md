<p align="center">
    <image src="nestpluslogo.svg">
</p>

<p align="center">
A collection of Badass modules and utilities to help you level up your NestJS application. 
</p>

<p align="center">
</p>

<span align="center">

[![Build Status](https://dev.azure.com/golevelup/nestjs/_apis/build/status/golevelup.nestjs?branchName=master)](https://dev.azure.com/golevelup/nestjs/_build/latest?definitionId=1&branchName=master)

</span>

## Packages

The various packages are managed using Yarn Workspaces and Lerna and published under the `@golevelup` organization on NPM.

#### [Common - @golevelup/nestjs-common](packages/common/README.md)

- Mixin Utilities

#### [Discovery - @golevelup/nestjs-discovery](packages/discovery/README.md)

- `DiscoveryModule` for finding providers, controllers and method handlers from your NestJS app that have certain metadata

#### [RabbitMQ - @golevelup/nestjs-rabbitmq](packages/rabbitmq/README.md)

- A NestJS native module for RabbitMQ that supports both RPC and Publish/Subscribe messaging patterns

#### [Modules - @golevelup/nestjs-modules](packages/modules/README.md)

- A NestJS Dynamic Module helper. Useful for configuring once and importing anywhere else.

#### [Typescript & Jest Testing - @golevelup/ts-jest](packages/testing/README.md)

- Testing utilities that bring additional productivity and type saftey to Jest and Typescript.
