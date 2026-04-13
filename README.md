# Claude Code Subagents Collection

A comprehensive collection of specialized AI subagents for [Claude Code](https://docs.anthropic.com/en/docs/claude-code), designed to enhance development workflows with domain-specific expertise.

## Overview

This repository contains 100+ specialized subagents that extend Claude Code's capabilities. Each subagent is an expert in a specific domain, automatically invoked based on context or explicitly called when needed. All agents are configured with specific Claude models based on task complexity for optimal performance and cost-effectiveness.

## Available Subagents

### Programming Languages & Frameworks
- **[bash-expert](agents/bash-expert.md)** - Master of defensive Bash scripting for production automation, CI/CD pipelines, and system utilities
- **[python-expert](agents/python-expert.md)** - Master advanced Python features, optimize performance, and ensure code quality
- **[javascript-expert](agents/javascript-expert.md)** - Modern JavaScript development with ES6+, async patterns, and Node.js APIs
- **[typescript-expert](agents/typescript-expert.md)** - TypeScript development with type safety, interfaces, and advanced features
- **[java-expert](agents/java-expert.md)** - Java development with Spring Boot, enterprise patterns, and JVM optimization
- **[go-expert](agents/go-expert.md)** - Go development with concurrency, channels, and idiomatic patterns
- **[rust-expert](agents/rust-expert.md)** - Rust development with memory safety, ownership patterns, and systems programming
- **[c-expert](agents/c-expert.md)** - C programming with memory management, system calls, and performance optimization
- **[cpp-expert](agents/cpp-expert.md)** - Modern C++ with STL, templates, RAII, and smart pointers
- **[php-expert](agents/php-expert.md)** - PHP development with modern features, Laravel, and performance optimization
- **[ruby-expert](agents/ruby-expert.md)** - Ruby development with Rails, metaprogramming, and elegant syntax
- **[scala-expert](agents/scala-expert.md)** - Scala development with functional programming, Akka, and JVM integration
- **[kotlin-expert](agents/kotlin-expert.md)** - Kotlin development with Android, Spring Boot, and coroutines
- **[swift-expert](agents/swift-expert.md)** - Swift development with iOS, macOS, and Apple ecosystem
- **[dart-expert](agents/dart-expert.md)** - Dart development with Flutter, mobile apps, and cross-platform solutions
- **[lua-expert](agents/lua-expert.md)** - Lua development with game scripting, embedded systems, and performance
- **[haskell-expert](agents/haskell-expert.md)** - Haskell development with functional programming, monads, and type theory
- **[ocaml-expert](agents/ocaml-expert.md)** - OCaml development with functional programming and systems programming
- **[perl-expert](agents/perl-expert.md)** - Perl development with text processing, system administration, and automation
- **[csharp-expert](agents/csharp-expert.md)** - C# development with .NET ecosystem, LINQ, and enterprise patterns
- **[clojure-expert](agents/clojure-expert.md)** - Clojure development with functional programming and Lisp syntax
- **[elixir-expert](agents/elixir-expert.md)** - Elixir development with functional programming and Erlang VM
- **[erlang-expert](agents/erlang-expert.md)** - Erlang development with concurrent programming and fault tolerance

### Web Development & Frontend
- **[react-expert](agents/react-expert.md)** - React development with hooks, state management, and component architecture
- **[vue-expert](agents/vue-expert.md)** - Vue.js development with composition API, state management, and SFC
- **[angular-expert](agents/angular-expert.md)** - Angular development with TypeScript, RxJS, and enterprise patterns
- **[svelte-expert](agents/svelte-expert.md)** - Svelte development with reactive components and minimal boilerplate
- **[solidjs-expert](agents/solidjs-expert.md)** - SolidJS development with fine-grained reactivity and performance
- **[nextjs-expert](agents/nextjs-expert.md)** - Next.js development with SSR, SSG, and React optimization
- **[remix-expert](agents/remix-expert.md)** - Remix development with nested routing, data loading, and web standards
- **[nestjs-expert](agents/nestjs-expert.md)** - NestJS development with decorators, modules, and enterprise patterns
- **[express-expert](agents/express-expert.md)** - Express.js development with middleware, routing, and Node.js APIs
- **[fastapi-expert](agents/fastapi-expert.md)** - FastAPI development with async/await, Pydantic, and OpenAPI
- **[flask-expert](agents/flask-expert.md)** - Flask development with blueprints, extensions, and Python web patterns
- **[rails-expert](agents/rails-expert.md)** - Ruby on Rails development with MVC, ActiveRecord, and conventions
- **[laravel-expert](agents/laravel-expert.md)** - Laravel development with Eloquent, Blade, and PHP web patterns
- **[gin-expert](agents/gin-expert.md)** - Gin framework development with Go web APIs and middleware
- **[fiber-expert](agents/fiber-expert.md)** - Fiber framework development with Go web development and performance
- **[aspnet-core-expert](agents/aspnet-core-expert.md)** - ASP.NET Core development with C# web APIs and .NET ecosystem
- **[actix-expert](agents/actix-expert.md)** - Actix-web development with Rust web frameworks and async patterns
- **[phoenix-expert](agents/phoenix-expert.md)** - Phoenix framework development with Elixir and real-time features
- **[html-expert](agents/html-expert.md)** - HTML development with semantic markup, accessibility, and web standards
- **[css-expert](agents/css-expert.md)** - CSS development with modern layouts, animations, and responsive design
- **[tailwind-expert](agents/tailwind-expert.md)** - Tailwind CSS development with utility-first design and customization
- **[angularjs-expert](agents/angularjs-expert.md)** - AngularJS development with legacy support, directives, and migration strategies
- **[astro-expert](agents/astro-expert.md)** - Astro development with static site generation and component islands
- **[django-expert](agents/django-expert.md)** - Django development with Python web framework, ORM, and admin interface
- **[fastify-expert](agents/fastify-expert.md)** - Fastify development with high-performance Node.js web framework
- **[jquery-expert](agents/jquery-expert.md)** - jQuery development with DOM manipulation and legacy browser support
- **[spring-boot-expert](agents/spring-boot-expert.md)** - Spring Boot development with Java microservices and enterprise patterns

### Mobile & Desktop Development
- **[react-native-expert](agents/react-native-expert.md)** - React Native development with cross-platform mobile apps
- **[flutter-expert](agents/flutter-expert.md)** - Flutter development with Dart and cross-platform mobile apps
- **[ios-expert](agents/ios-expert.md)** - iOS development with Swift, UIKit, and Apple ecosystem
- **[swiftui-expert](agents/swiftui-expert.md)** - SwiftUI development with declarative UI and modern iOS patterns
- **[android-expert](agents/android-expert.md)** - Android development with Kotlin, Jetpack Compose, and Material Design
- **[electron-expert](agents/electron-expert.md)** - Electron development with cross-platform desktop apps
- **[tauri-expert](agents/tauri-expert.md)** - Tauri development with Rust backend and web frontend
- **[expo-expert](agents/expo-expert.md)** - Expo development with React Native and managed workflow
- [CCHub](https://github.com/Moresl/cchub) - A desktop control panel for the Claude Code / Codex / Gemini CLI ecosystem. Manage MCP servers, config profiles, agent skills, CLAUDE.md, hooks, and workflow templates from a single Tauri app (Windows / macOS / Linux).

### Databases & Data Management
- **[sql-expert](agents/sql-expert.md)** - SQL development with complex queries, optimization, and database design
- **[postgres-expert](agents/postgres-expert.md)** - PostgreSQL development with advanced features, extensions, and optimization
- **[mysql-expert](agents/mysql-expert.md)** - MySQL development with InnoDB, replication, and performance tuning
- **[sqlite-expert](agents/sqlite-expert.md)** - SQLite development with embedded databases and mobile apps
- **[mariadb-expert](agents/mariadb-expert.md)** - MariaDB development with MySQL compatibility and enterprise features
- **[mssql-expert](agents/mssql-expert.md)** - Microsoft SQL Server development with T-SQL and enterprise features
- **[mongodb-expert](agents/mongodb-expert.md)** - MongoDB development with NoSQL patterns, aggregation, and sharding
- **[redis-expert](agents/redis-expert.md)** - Redis development with caching, pub/sub, and data structures
- **[neo4j-expert](agents/neo4j-expert.md)** - Neo4j development with graph databases and Cypher queries
- **[cassandra-expert](agents/cassandra-expert.md)** - Cassandra development with distributed databases and CQL
- **[cockroachdb-expert](agents/cockroachdb-expert.md)** - CockroachDB development with distributed SQL and consistency
- **[dynamodb-expert](agents/dynamodb-expert.md)** - DynamoDB development with NoSQL patterns and AWS integration
- **[elasticsearch-expert](agents/elasticsearch-expert.md)** - Elasticsearch development with search, analytics, and ELK stack
- **[opensearch-expert](agents/opensearch-expert.md)** - OpenSearch development with search and analytics
- **[vector-db-expert](agents/vector-db-expert.md)** - Vector database development with embeddings and similarity search

### ORMs & Query Builders
- **[prisma-expert](agents/prisma-expert.md)** - Prisma development with type-safe database access and migrations
- **[sequelize-expert](agents/sequelize-expert.md)** - Sequelize development with Node.js ORM and database management
- **[typeorm-expert](agents/typeorm-expert.md)** - TypeORM development with TypeScript ORM and decorators
- **[knex-expert](agents/knex-expert.md)** - Knex.js development with query builder and migrations
- **[mongoose-expert](agents/mongoose-expert.md)** - Mongoose development with MongoDB ODM and schemas

### Infrastructure & DevOps
- **[docker-expert](agents/docker-expert.md)** - Docker development with containerization, images, and orchestration
- **[kubernetes-expert](agents/kubernetes-expert.md)** - Kubernetes development with container orchestration and scaling
- **[terraform-expert](agents/terraform-expert.md)** - Terraform development with infrastructure as code and cloud provisioning
- **[pulumi-expert](agents/pulumi-expert.md)** - Pulumi development with infrastructure as code and multi-language support
- **[jenkins-expert](agents/jenkins-expert.md)** - Jenkins development with CI/CD pipelines and automation
- **[github-actions-expert](agents/github-actions-expert.md)** - GitHub Actions development with workflows and automation
- **[gitlab-ci-expert](agents/gitlab-ci-expert.md)** - GitLab CI development with pipelines and DevOps automation
- **[circleci-expert](agents/circleci-expert.md)** - CircleCI development with continuous integration and deployment
- **[ansible-expert](agents/ansible-expert.md)** - Ansible development with configuration management and automation

### Services
- **[stripe-expert](agents/stripe-expert.md)** - Stripe development with payment processing and webhooks
- **[braintree-expert](agents/braintree-expert.md)** - Braintree development with payment processing and PayPal integration
- **[sns-expert](agents/sns-expert.md)** - AWS SNS development with messaging and notifications
- **[sqs-expert](agents/sqs-expert.md)** - AWS SQS development with message queuing and distributed systems
- **[openai-api-expert](agents/openai-api-expert.md)** - OpenAI API development with GPT models and AI integration
- **[auth0-expert](agents/auth0-expert.md)** - Auth0 development with authentication and authorization
- **[keycloak-expert](agents/keycloak-expert.md)** - Keycloak development with identity and access management

### Messaging & Communication
- **[rabbitmq-expert](agents/rabbitmq-expert.md)** - RabbitMQ development with message queuing and AMQP
- **[kafka-expert](agents/kafka-expert.md)** - Apache Kafka development with event streaming and distributed systems
- **[nats-expert](agents/nats-expert.md)** - NATS development with lightweight messaging and pub/sub
- **[mqtt-expert](agents/mqtt-expert.md)** - MQTT development with IoT messaging and lightweight protocols
- **[websocket-expert](agents/websocket-expert.md)** - WebSocket development with real-time communication
- **[grpc-expert](agents/grpc-expert.md)** - gRPC development with high-performance RPC and protocol buffers
- **[graphql-expert](agents/graphql-expert.md)** - GraphQL development with schemas, resolvers, and federation
- **[rest-expert](agents/rest-expert.md)** - REST API development with HTTP standards and best practices
- **[openapi-expert](agents/openapi-expert.md)** - OpenAPI development with API documentation and specifications
- **[trpc-expert](agents/trpc-expert.md)** - tRPC development with end-to-end type safety and TypeScript APIs

### Testing & Quality Assurance
- **[jest-expert](agents/jest-expert.md)** - Jest development with JavaScript testing and mocking
- **[vitest-expert](agents/vitest-expert.md)** - Vitest development with Vite-based testing and modern tooling
- **[mocha-expert](agents/mocha-expert.md)** - Mocha development with JavaScript testing and flexible frameworks
- **[jasmine-expert](agents/jasmine-expert.md)** - Jasmine development with BDD testing and behavior-driven development
- **[ava-expert](agents/ava-expert.md)** - AVA development with concurrent testing and modern JavaScript
- **[cypress-expert](agents/cypress-expert.md)** - Cypress development with end-to-end testing and web automation
- **[playwright-expert](agents/playwright-expert.md)** - Playwright development with cross-browser testing and automation
- **[selenium-expert](agents/selenium-expert.md)** - Selenium development with web automation and browser testing
- **[testcafe-expert](agents/testcafe-expert.md)** - TestCafe development with end-to-end testing and modern web apps
- **[puppeteer-expert](agents/puppeteer-expert.md)** - Puppeteer development with Chrome automation and headless browsing

### Data Science & Machine Learning
- **[pandas-expert](agents/pandas-expert.md)** - Pandas development with data manipulation and analysis
- **[numpy-expert](agents/numpy-expert.md)** - NumPy development with numerical computing and array operations
- **[scikit-learn-expert](agents/scikit-learn-expert.md)** - Scikit-learn development with machine learning and data science
- **[tensorflow-expert](agents/tensorflow-expert.md)** - TensorFlow development with deep learning and neural networks
- **[pytorch-expert](agents/pytorch-expert.md)** - PyTorch development with deep learning and dynamic computation graphs
- **[langchain-expert](agents/langchain-expert.md)** - LangChain development with LLM applications and RAG systems

### Monitoring & Observability
- **[prometheus-expert](agents/prometheus-expert.md)** - Prometheus development with metrics collection and monitoring
- **[grafana-expert](agents/grafana-expert.md)** - Grafana development with visualization and dashboard creation
- **[loki-expert](agents/loki-expert.md)** - Loki development with log aggregation and querying
- **[elk-expert](agents/elk-expert.md)** - ELK stack development with Elasticsearch, Logstash, and Kibana
- **[opentelemetry-expert](agents/opentelemetry-expert.md)** - OpenTelemetry development with observability and tracing

### Security & Authentication
- **[owasp-top10-expert](agents/owasp-top10-expert.md)** - OWASP Top 10 expert for web application security
- **[jwt-expert](agents/jwt-expert.md)** - JWT development with token-based authentication and security
- **[oauth-oidc-expert](agents/oauth-oidc-expert.md)** - OAuth 2.0 and OpenID Connect development with identity protocols

### Build Tools & Bundlers
- **[webpack-expert](agents/webpack-expert.md)** - Webpack development with module bundling and optimization
- **[rollup-expert](agents/rollup-expert.md)** - Rollup development with ES module bundling and tree shaking

### Database Migration & Schema Management
- **[flyway-expert](agents/flyway-expert.md)** - Flyway development with database migrations and version control
- **[liquibase-expert](agents/liquibase-expert.md)** - Liquibase development with database change management
- **[prisma-expert](agents/prisma-expert.md)** - Prisma development with database migrations and schema management

### Background Jobs & Task Queues
- **[celery-expert](agents/celery-expert.md)** - Celery development with distributed task queues and Python
- **[sidekiq-expert](agents/sidekiq-expert.md)** - Sidekiq development with background job processing and Ruby
- **[bullmq-expert](agents/bullmq-expert.md)** - BullMQ development with Redis-based job queues and Node.js

### Runtime & Package Managers
- **[nodejs-expert](agents/nodejs-expert.md)** - Node.js development with runtime, packages, and ecosystem
- **[bun-expert](agents/bun-expert.md)** - Bun development with fast JavaScript runtime and package manager
- **[deno-expert](agents/deno-expert.md)** - Deno development with secure JavaScript runtime and TypeScript

## Installation

These subagents are automatically available when placed in `~/.claude/agents/` directory.

```bash
cd ~/.claude
git clone https://github.com/0xfurai/claude-code-subagents.git
```

## Usage

### Automatic Invocation
Claude Code will automatically delegate to the appropriate subagent based on the task context and the subagent's description.

### Explicit Invocation
Mention the subagent by name in your request:
```
"Use the python-expert to optimize this algorithm"
"Get the react-expert to refactor this component"
```

## Contributing

To add a new subagent:
1. Create a new `.md` file in the `agents/` directory
2. Use lowercase, hyphen-separated names
3. Write clear descriptions for when the subagent should be used
4. Include specific instructions in the system prompt
5. Follow the established format with focus areas, approach, quality checklist, and output

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Learn More

- [Claude Code Documentation](https://docs.anthropic.com/en/docs/claude-code/overview)
- [Subagents Documentation](https://docs.anthropic.com/en/docs/claude-code/sub-agents)
- [Claude Code GitHub](https://github.com/anthropics/claude-code)
