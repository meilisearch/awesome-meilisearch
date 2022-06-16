# Awesome Meilisearch
A curated list of awesome Meilisearch resources\
Inspired by [Awesome Go](https://github.com/avelino/awesome-go) and [Awesome Python](https://github.com/vinta/awesome-python)

## Contributing

Please take a look at the [Contribution Guidelines](https://github.com/meilisearch/awesome-meilisearch/blob/main/CONTRIBUTING.md)

## Table of Contents

- [Guides, Tutorials and Courses](#guides-tutorials-and-courses)
    - [Official Guides](#official-guides)
    - [Community Guides](#community-guides)
- [Integrations](#integrations)
    - [Official Integrations](#official-integrations)
    - [Community Integrations](#community-integrations)
- [Tools](#tools)
    - [Official Tools](#official-tools)
    - [Community Tools](#community-tools)
- [Demos](#demos)
- [Talks](#talks)
- [Blog Posts](#blog-posts)
    - [Meilisearch Blog Posts](#meilisearch-blog-posts)
    - [Community Blog Posts](#community-blog-posts)
- [Resources](#resources)
    - [Websites](#websites)
    - [Social Networks](#social-networks)
- [Other](#other)

**[⬆ back to top](#table-of-contents)**

## Guides, Tutorials and Courses

*Learn Meilisearch*

### Official Guides

#### Basics
* [Quick Start](https://docs.meilisearch.com/learn/getting_started/quick_start.html)
* [Installation](https://docs.meilisearch.com/learn/getting_started/quick_start.html#setup-and-installation)
* [Update](https://docs.meilisearch.com/create/how_to/updating.html) - Update to the latest Meilisearch version
* [Run Meilisearch in production](https://docs.meilisearch.com/create/how_to/running_production.html)

#### Deploy
* [Deploy on AWS](https://docs.meilisearch.com/create/how_to/aws.html) - Deploy a Meilisearch instance on Amazon Web Services (AWS)
* [Deploy on GCP](https://docs.meilisearch.com/create/how_to/gcp.html) - Deploy a Meilisearch instance on Google Cloud Platform (GCP) Compute Engine
* [Deploy on DigitalOcean](https://docs.meilisearch.com/create/how_to/digitalocean_droplet.html) - Deploy a Meilisearch instance on DigitalOcean
* [Deploy on Qovery](https://docs.meilisearch.com/create/how_to/qovery.html) - Deploy a Meilisearch instance on Qovery
* [Deploy on Azure](https://docs.meilisearch.com/learn/cookbooks/azure.html) - Deploy a Meilisearch instance on Azure
* [Deploy on Koyeb](https://docs.meilisearch.com/learn/cookbooks/koyeb.html) - Deploy a Meilisearch instance on Koyeb


#### Miscellaneous
* [Use Postman with Meilisearch](https://docs.meilisearch.com/create/how_to/postman_collection.html) - Postman collection for Meilisearch
* [Integrate a relevant search bar to your documentation](https://docs.meilisearch.com/create/how_to/search_bar_for_docs.html)
* [Use HTTP/2 and SSL with Meilisearch](https://docs.meilisearch.com/create/how_to/http2_ssl.html)

### Community Guides
* [Searching with Laravel Scout and Meilisearch](https://codecourse.com/courses/searching-with-laravel-scout-and-meilisearch) -  Build a search experience for any database data by combining Laravel Scout and Meilisearch
* [Setting up Meilisearch on Production Ubuntu for Laravel project](https://postsrc.com/posts/setting-up-meilisearch-on-production-ubuntu-for-laravel-project) - How to set up Meilisearch for a Laravel project
* [Adding Search to Rails with Meilisearch](https://blog.cloud66.com/adding-search-to-rails-with-meilisearch/) - How to integrate Meilisearch in a Rails app
* [How to Install a Specific Version of Meilisearch](https://medium.com/@biarosenbaum/how-to-install-a-specific-version-of-meilisearch-2552bee8c351)
* [How I implemented full-text search on Firebase with Meilisearch for Secrets App](https://medium.com/@stevapps256/how-i-implemented-full-text-search-on-firebase-with-meilisearch-for-secrets-app-6b853484c999) - How to integrate Meilisearch on Firebase
* [Deploy Meilisearch with Dokku for production](https://okhlopkov.com/deploy-meilisearch-with-dokku-for-production/) - How to deploy Meilisearch with Dokku
* [How to Deploy Meilisearch on Laravel Forge](https://postsrc.com/posts/how-to-deploy-meilisearch-on-laravel-forge)
* [Master Full Text Search with Meilisearch on MinIO](https://blog.min.io/master-full-text-search-with-meilisearch-on-minio/) - How to use MinIO with Meilisearch
* [Serverless search with Meilisearch and Google Cloud Run](https://blog.simonireilly.com/posts/serverless-search)
* [Meilisearch: A definitive guide](https://blog.logrocket.com/meilisearch-a-definitive-guide/) - How to interact with an instance through the API client for JavaScript developers
* [Meilisearch under Windows](http://www.skrejci.com/2021/05/meilisearch-under-windows/) - Installing on Windows
* [A Comprehensive Guide to Meilisearch](https://www.atatus.com/blog/a-comprehensive-guide-to-meilisearch/)
* [How to add Search in Rails using Meilisearch](https://gorails.com/episodes/how-to-use-meilisearch-rails)
* [Integrate Rails, React and MeiliSearch using Docker](https://dev.to/rodrigoodhin/integrate-rails-react-and-meilisearch-using-docker-52ho)
* [A series of guide on how to use Meilisearch with Laravel Scout](https://serversideup.net/search/?type=posts&tags=meilisearch+laravel)
* [How To Deploy and Configure Meilisearch on Ubuntu 22.04](https://www.digitalocean.com/community/tutorials/how-to-deploy-and-configure-meilisearch-on-ubuntu-22-04)
* [How To Run a Meilisearch Frontend Using InstantSearch on Ubuntu 22.04](https://www.digitalocean.com/community/tutorials/how-to-run-a-meilisearch-frontend-using-instantsearch-on-ubuntu-22-04)

**[⬆ back to top](#table-of-contents)**

## Integrations

*Meilisearch integrations created by Meilisearch or the community*

### Official Integrations
* [Meilisearch official Integrations](https://github.com/meilisearch/integration-guides) - Central reference for Meilisearch integrations

#### SDK

* [.Net](https://github.com/meilisearch/meilisearch-dotnet)
* [Dart](https://github.com/meilisearch/meilisearch-dart)
* [Golang](https://github.com/meilisearch/meilisearch-go)
* [Java](https://github.com/meilisearch/meilisearch-java)
* [JavaScript](https://github.com/meilisearch/meilisearch-js)
* [PHP](https://github.com/meilisearch/meilisearch-php)
* [Python](https://github.com/meilisearch/meilisearch-python)
* [Ruby](https://github.com/meilisearch/meilisearch-ruby)
* [Rust](https://github.com/meilisearch/meilisearch-rust)
* [Swift](https://github.com/meilisearch/meilisearch-swift)

#### Framework Integrations

* [Laravel](https://github.com/laravel/scout) - Official Laravel-Scout package
* [Ruby on Rails](https://github.com/meilisearch/meilisearch-rails)
* [Symfony](https://github.com/meilisearch/meilisearch-symfony)

#### Front-End Integrations

* [Angular](https://github.com/meilisearch/meilisearch-angular)
* [React](https://github.com/meilisearch/meilisearch-react)
* [Vue](https://github.com/meilisearch/meilisearch-vue)

#### Platform Plugins

- [VuePress](https://github.com/meilisearch/vuepress-plugin-meilisearch)
- [Strapi](https://github.com/meilisearch/strapi-plugin-meilisearch)
- [Gatsby](https://github.com/meilisearch/gatsby-plugin-meilisearch/)
- [Firestore](https://github.com/meilisearch/firestore-meilisearch/)

### Community Integrations
* [MongoMeili](https://github.com/loophole-labs/mongomeili) - Sync MongooseJS Schemas with Meilisearch
* [YunoHost](https://github.com/YunoHost-Apps/meilisearch_ynh) - Meilisearch on a YunoHost server
* [D](https://github.com/aberba/meilisearch) - A Meilisearch API for D
* [Craft CMS](https://github.com/unionco/craft-meilisearch) - Plugin for Craft CMS 3.x
* [Airbyte](https://airbyte.io/connectors/meilisearch) - Connector for Airbyte
* [Statamic Meilisearch](https://statamic.com/addons/elvenstar/statamic-meilisearch) - Driver for Statamic 3
* [Medusa](https://github.com/medusajs/medusa/tree/master/packages/medusa-plugin-meilisearch) - Plugin for Medusa
* [Kotlin](https://github.com/nemoengineering/meilisearch-kotlin) - A Kotlin wrapper
* [Meili Ktr](https://github.com/JonathanxD/meili-ktr) - A multiplatform Kotlin client
* [Yii2](https://github.com/zhuzixian520/yii2-meilisearch) - Yii2 framework extension
* [Async Python SDK](https://github.com/sanders41/meilisearch-python-async) - An asynchronous Python client
* [FastAPI](https://github.com/sanders41/meilisearch-fastapi) - Provides FastAPI routes for interacting with Meilisearch
* [Elixir](https://github.com/robottokauf3/meilisearch-elixir) - A lightweight Elixir client
* [Nuxt](https://github.com/xlanex6/nuxt-meilisearch) - A Nuxt 3 module
* [cbMeilisearch](https://github.com/michaelborn/cbMeilisearch) - An API wrapper written in CFML for the ColdBox platform


**[⬆ back to top](#table-of-contents)**

## Tools

*Tools created by Meilisearch or the community*

### Official Tools
* [Meilisearch Version Migration Script](https://github.com/meilisearch/meilisearch-migration) - A script to migrate to a newer version without losing data nor settings

#### DevOps Tools

* [meilisearch-digitalocean](https://github.com/meilisearch/meilisearch-digitalocean) - Deploy on DigitalOcean
* [meilisearch-aws](https://github.com/meilisearch/meilisearch-aws) - Deploy on AWS
* [meilisearch-gcp](https://github.com/meilisearch/meilisearch-gcp) - Deploy on GCP
* [meilisearch-kubernetes](https://github.com/meilisearch/meilisearch-kubernetes) - Deploy on Kubernetes
* [Cloud Scripts](https://github.com/meilisearch/cloud-scripts) - A set of cloud-agnostic tools and scripts to improve deployment on the cloud

#### Miscellaneous
* [instant-meilisearch](https://github.com/meilisearch/instant-meilisearch) - A plugin to establish the communication between Meilisearch and the open-source [InstantSearch](https://github.com/algolia/instantsearch.js) tools (powered by Algolia)
* [docs-searchbar.js](https://github.com/meilisearch/docs-searchbar.js) - A search bar integration for all kinds of documentation
* [docs-scraper](https://github.com/meilisearch/docs-scraper) -  A scraper tool to automatically read the content of your documentation and store it into Meilisearch.

### Community Tools
* [AIO_MEILISEARCH](https://github.com/devtud/aio_meilisearch) - Async Wrapper over Meilisearch REST API
* [mieli](https://github.com/irevoire/mieli) - A wrapper
* [Meilisearch CLI](https://github.com/sanders41/meilisearch-cli) - A CLI
* [UIRecord](https://github.com/SaraVieira/uirecord) -  A UI to manage instances
* [meilisearch-prompt](https://github.com/leopku/meilisearch-prompt) - A command-line kit to manage a Meilisearch server
* [Meilisearch GitHub Action](https://github.com/moy2010/meilisearch-github-action) - Start a Meilisearch server from your GH Actions with this action.


**[⬆ back to top](#table-of-contents)**

## Demos

*See Meilisearch in action*

* [Meilisearch Demos](https://github.com/meilisearch/demos)
* [Meilisearch x MoMA](https://github.com/meilisearch/demos/tree/main/src/MoMA) - Search through the Museum Of Modern Art Collection
* [Search in Nobel Prizes with Meilisearch](https://github.com/meilisearch/demos/tree/main/src/nobel-prizes) - Search through all Nobel Prize winners and their details
* [Meilisearch finds RubyGems](https://github.com/meilisearch/demos/tree/main/src/finding-rubygems) - Find Ruby gems
* [Finding Crates](https://github.com/meilisearch/demos/tree/main/src/finding-crates) - Find Rust crates
* [Meilisearch finds PyPI packages](https://github.com/meilisearch/demos/tree/main/src/finding-pypi) - Find Python packages
* [Search in world cities](https://github.com/meilisearch/demos/tree/main/src/geo-javascript) - Play with Geosearch features and find info about large cities
* [Tenant token demo](https://github.com/meilisearch/demos/tree/main/src/tenant-token) - Learn how to use the multi-tenant token feature
* [Typo tolerance demo](https://github.com/meilisearch/demos/tree/main/src/typo-tolerance) - Play with the typo tolerance feature and browse through a book collection

**[⬆ back to top](#table-of-contents)**

## Talks

*Talks about Meilisearch*

* [Rawkode Live: Introduction to Meilisearch](https://www.youtube.com/watch?v=SJl2UWfy1nk)
* [Strapi conf 2021: Integrate open-source search into your Strapi project](https://www.youtube.com/watch?v=brG3738V2bU)
* [Strapi webinar: Modern Search Solutions for the Jamstack with Meilisearch](https://www.youtube.com/watch?v=mO_I02ZAfmM&t=4s) -


**[⬆ back to top](#table-of-contents)**

## Blog Posts

*Read what the Meilisearch's team has written or what others say about us*

### Meilisearch Blog Posts
* [Latest's release blog post](https://blog.meilisearch.com/whats-new-in-v0-27/) - version 0.27

### Community Blog Posts
* [Meilisearch: A Minimalist Full-Text Search Engine](https://tech.marksblogg.com/meilisearch-full-text-search.html)

**[⬆ back to top](#table-of-contents)**

## Resources

*Various resources*

### Repositories
* [Meilisearch](https://github.com/meilisearch/Meilisearch)
* [milli](https://github.com/meilisearch/milli/) - Meilisearch's core engine
* [Product repository](https://github.com/meilisearch/product)

### Websites
* [Website](https://www.meilisearch.com/) - The official Meilisearch website
* [Blog](https://blog.meilisearch.com/) - The official Meilisearch blog
* [Documentation](https://docs.meilisearch.com/) - The official Meilisearch documentation
* [Roadmap](https://roadmap.meilisearch.com/) - The official Meilisearch roadmap

### Social Networks
* [Twitter](https://twitter.com/meilisearch) - The official Meilisearch Twitter account
* [LinkedIn](https://www.linkedin.com/company/meilisearch/) - The official Meilisearch LinkedIn account
* [Slack](https://slack.meilisearch.com/) - The community Slack

**[⬆ back to top](#table-of-contents)**

## Other
*Miscellaneous*
* [Official FAQ](https://docs.meilisearch.com/faq.html)

**[⬆ back to top](#table-of-contents)**
