### Django Basics:
- **Model-View-Template (MVT) architecture:** Understanding the separation of concerns in Django and the flow of data.
- **Django ORM:** CRUD operations, filtering, annotations, aggregations, raw SQL queries, transactions.
- **Class-based views:** Inheritance, mixins, method-based views, generic class-based views (ListView, DetailView, etc.).
- **Function-based views:** Request and response objects, decorators, context.
- **URL routing:** Regular expressions, named groups, namespaces, includes.
- **Django Admin:** Custom admin actions, list display, search fields, list filters, readonly fields.

### Database:
- **SQLite, PostgreSQL, MySQL:** Installation, configuration, differences, data types, constraints, indexing, transactions.
- **Database modeling:** Fields (CharField, IntegerField, etc.), relationships (OneToOneField, ForeignKey, ManyToManyField), model inheritance.
- **Query optimization:** Indexes, select_related(), prefetch_related(), querysets, database hints.
- **Transactions and Commit:** Understand how transactions work in Django, how to start, commit, or rollback transactions, and ensure data consistency.

### RESTful APIs:
- **Django Rest Framework (DRF):** Serializers, ViewSets, routers, permissions, throttling, versioning, content negotiation.
- **Serialization and Deserialization:** Nested serializers, custom serializer fields, SerializerMethodField.
- **Authentication and Authorization:** Token authentication, OAuth2, custom authentication classes, object-level permissions.
- **Pagination, Filtering, Searching:** PageNumberPagination, LimitOffsetPagination, DjangoFilterBackend, SearchFilter.

### Security:
- **Authentication methods:** JWT authentication, session authentication, OAuth2 flows, social authentication.
- **CSRF protection:** CSRF token middleware, CSRF cookie, CSRF exempt views.
- **CORS:** CORS headers, CORS middleware, CORS decorators.
- **SQL injection prevention:** Query parameterization, parameterized queries, ORMs, input validation.
- **Security best practices:** HTTPS, secure cookies, security headers, rate limiting, content security policy.

### Testing:
- **Unit tests:** setUp(), tearDown(), test case classes, assertions (assertEqual, assertTrue, etc.).
- **Integration tests:** Database setup, client requests, response assertions, fixtures.
- **Test-driven development (TDD):** Red-Green-Refactor cycle, writing failing tests, writing code to pass tests, refactoring.
- **Mocking:** patch(), MagicMock, side_effect, return_value, MagicMock.assert_called_once().
- **Fixtures:** setUpTestData(), setUp(), tearDown(), Django TestCase, managing test data.
- **Debugging Tools:** pdb, Django Debug Toolbar, Logging

### Frontend Integration:
- **React, Angular, Vue.js:** API integration, single-page applications, client-side routing, state management.
- **Django templating language (DTL):** Template inheritance, template tags, filters, includes.
- **Static files:** Static file finders, static file storage, collectstatic command.
- **AJAX:** XMLHttpRequest, fetch API, Axios, handling JSON responses.

### Performance Optimization:
- **Caching:** Cache decorators, cache middleware, caching strategies (per-view, per-site, template fragment caching).
- **Load balancing:** Round-robin, least connections, session persistence, health checks.
- **Scaling:** Horizontal scaling, vertical scaling, database sharding, database replication, read replicas.
- **Middleware:** Process_request(), process_response(), custom middleware classes, middleware order.

### Deployment:
- **Heroku, AWS, DigitalOcean:** Deployment platforms, server setup, domain configuration, SSL certificates.
- **Docker:** Dockerfile, docker-compose.yml, Docker images, Docker registries, Docker Swarm, Kubernetes.
- **CI/CD pipelines:** Automated testing, continuous integration, continuous deployment, deployment scripts.
- **Server configuration:** Nginx configuration, Gunicorn configuration, systemd services, virtual hosts.

### Asynchronous Tasks:
- **Celery:** Celery workers, Celery beat, task queues, task routing, task retrying, task monitoring.
- **Message brokers:** RabbitMQ, Redis, Kafka, message queues, message topics, message routing.
- **Background tasks:** Celery tasks, periodic tasks, task states, task results, task chaining.

### Websockets and Real-Time Communication:
- **Django Channels:** Websocket consumers, routing, authentication, channels layers, asynchronous consumers.
- **Real-time applications:** Chat applications, notifications, presence tracking, live updates.
- **Broadcasting events:** Group communication, broadcasting messages, message persistence.

### Django Signals:
- **Custom signal handling:** Signal receivers, pre-save signals, post-save signals, pre-delete signals, post-delete signals.

### Third-Party Packages:
- **django-crispy-forms:** Form layouts, form styling, form helper tags, crispy-forms templates.
- **django-filter:** FilterSets, filter backends, filter fields, custom filters, method filters.
- **django-allauth:** Social authentication, email verification, password reset, user registration.
- **REST API Documentation:** Swagger, DRF Docs: API schemas, API endpoints, API authentication, API request/response examples.
- **Django Middleware:** Custom middleware: Process_request(), process_response(), middleware classes, middleware order, middleware exceptions.

### Version Control:
- **Git:** Branches, commits, merges, rebases, remote repositories, pull requests, merge conflicts, gitignore.

### Code Quality:
- **PEP 8 standards:** Naming conventions, indentation, line length, imports, whitespace.
- **Linting:** Flake8, pylint, code analysis, static code analysis, code quality reports.
- **Code formatting:** Black, autopep8, code formatting rules, configuration options.
- **Code reviews:** Pull requests, code reviews, code review comments, code review feedback.

### Python:
- **Decorators, Generators, Context managers:** Function decorators, generator functions, contextlib, with statement.
