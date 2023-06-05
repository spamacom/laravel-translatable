# Introduction

[![Latest Version](http://img.shields.io/packagist/v/astrotomic/laravel-translatable.svg?label=Release&style=for-the-badge)](https://packagist.org/packages/astrotomic/laravel-translatable)
[![MIT License](https://img.shields.io/github/license/Astrotomic/laravel-translatable.svg?label=License&color=blue&style=for-the-badge)](https://github.com/Astrotomic/laravel-translatable/blob/master/LICENSE)
[![Offset Earth](https://img.shields.io/badge/Treeware-%F0%9F%8C%B3-green?style=for-the-badge)](https://plant.treeware.earth/Astrotomic/laravel-translatable)
[![Larabelles](https://img.shields.io/badge/Larabelles-%F0%9F%A6%84-lightpink?style=for-the-badge)](https://www.larabelles.com/)

[![GitHub Workflow Status](https://img.shields.io/github/workflow/status/Astrotomic/laravel-translatable/run-tests?style=flat-square&logoColor=white&logo=github&label=Tests)](https://github.com/Astrotomic/laravel-translatable/actions?query=workflow%3Arun-tests)
[![StyleCI](https://styleci.io/repos/192333549/shield)](https://styleci.io/repos/192333549)
[![Codecov Coverage](https://img.shields.io/codecov/c/github/Astrotomic/laravel-translatable?logo=codecov&logoColor=white&label=Codecov&style=flat-square)](https://codecov.io/gh/Astrotomic/laravel-translatable)
[![Total Downloads](https://img.shields.io/packagist/dt/astrotomic/laravel-translatable.svg?label=Downloads&style=flat-square)](https://packagist.org/packages/astrotomic/laravel-translatable)
[![GitBook](https://img.shields.io/badge/GitBook-Astrotomic-7e57c2.svg?style=flat-square)](https://docs.astrotomic.info/laravel-translatable)

<p align="center">
    <img src="/art/socialcard.png" alt="laravel-translatable socialcard">
</p>

**If you want to store translations of your models into the database, this package is for you.**

This is a Laravel package for translatable models. Its goal is to remove the complexity in retrieving and storing multilingual model instances. With this package you write less code, as the translations are being fetched/saved when you fetch/save your instance.

The full documentation can be found at [GitBook](https://docs.astrotomic.info/laravel-translatable).

## Installation

```bash
composer require spamacom/laravel-translatable
```

## Quick Example

Model()->whereTranslationFullText('name','any word',['mode'=>'boolean'])->orWhereTranslationFullText('name','any word',['mode'=>'boolean'])

Visit the totorial for more details how you can use fulltext search function [Boolean Full-Text Searches](https://dev.mysql.com/doc/refman/8.0/en/fulltext-boolean.html).
