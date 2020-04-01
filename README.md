# Jekyll with Tailwind

Barebone minimal jekyll starter with tailwind css

## About

This project uses [jekyll-postcss](https://github.com/mhanberg/jekyll-postcss) to manage compiling your Tailwind. You can use any [PostCSS](https://postcss.org) plugin by installing it with `yarn` or `npm` and adding it to your `postcss.config.js`.

[jekyll-purgecss](https://github.com/mhanberg/jekyll-purgecss) is used to integrate Purgecss (only in production).

## Usage

### Locally

`bundle exec jekyll serve`

### Production

`JEKYLL_ENV=production bundle exec jekyll build`

## Install

Once you configure the following files, run:

```shell
$ bundle install
$ yarn install

```
