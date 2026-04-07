# Differences Between Different Frameworks
# Flask vs Django vs FastAPI — Full Feature Comparison

| Feature / Spec | Flask | Django | FastAPI |
|----------------|------|--------|--------|
| **Type** | Microframework | Full-stack framework | Modern API-first framework |
| **Philosophy** | Minimal, flexible | Batteries-included | Performance + type-driven |
| **Primary Use Case** | Small apps, custom APIs | Large apps, admin-heavy systems | High-performance APIs, microservices |
| **Async Support** | Limited (via extensions) | Partial (ASGI support newer) | Native async-first |
| **Performance** | Medium | Lower (heavier) | Very high (near Node/Go) |
| **Learning Curve** | Easy | Moderate–High | Easy–Moderate |
| **Routing** | Decorators (`@app.route`) | URLs.py (central routing) | Decorators (`@app.get`) |
| **Request Handling** | WSGI | WSGI + ASGI | ASGI |
| **Data Validation** | Manual / Marshmallow | Forms / DRF serializers | Built-in via Pydantic |
| **Serialization** | Manual | Django REST Framework | Automatic |
| **Type Safety** | ❌ | ❌ | ✅ Strong typing |
| **Auto API Docs** | ❌ | ❌ (needs DRF) | ✅ Swagger + ReDoc auto |
| **Dependency Injection** | ❌ | ❌ | ✅ Built-in |
| **ORM** | Optional (SQLAlchemy) | Built-in ORM | Optional (SQLAlchemy, Tortoise) |
| **Migrations** | Via Alembic | Built-in | Via Alembic |
| **Authentication** | Extensions (Flask-Login) | Built-in auth system | OAuth2/JWT built-in patterns |
| **Authorization** | Manual | Built-in permissions | Manual / libraries |
| **Admin Panel** | ❌ | ✅ Powerful built-in | ❌ |
| **Middleware Support** | Basic | Strong | Strong |
| **Session Management** | Built-in (cookies) | Built-in | Minimal |
| **Template Engine** | Jinja2 | Django Templates | Jinja2 optional |
| **Static Files Handling** | Basic | Built-in | Basic |
| **WebSockets** | ❌ (needs extensions) | Via Channels | Native support |
| **Background Tasks** | Celery (external) | Celery (common) | BackgroundTasks built-in |
| **File Uploads** | Basic | Built-in | Built-in |
| **Form Handling** | WTForms | Django Forms | Not built-in |
| **Pagination** | Manual | Built-in (DRF) | Manual |
| **Caching** | Extensions | Built-in caching system | Via Starlette |
| **Rate Limiting** | Extensions | Middleware/plugins | Middleware/plugins |
| **API Versioning** | Manual | DRF supports | Manual / router-based |
| **Testing Support** | Basic (pytest) | Strong built-in | Strong (TestClient) |
| **CLI Tools** | Basic | Strong (`manage.py`) | Basic |
| **Project Structure** | Flexible | Opinionated | Flexible |
| **Scalability** | Medium | High | Very high |
| **Concurrency Model** | Sync (WSGI) | Sync + Async hybrid | Async (event loop) |
| **Integration with Frontend** | Easy | Good | Excellent for SPA backends |
| **GraphQL Support** | Via libraries | Via libraries | Via libraries |
| **Microservices Friendly** | ✅ | ❌ (heavy) | ✅✅ |
| **Startup Time** | Fast | Slower | Fast |
| **Community** | Large | Very large | Fast growing |
| **Best For APIs** | Good | Good (with DRF) | Excellent |
| **Best For Full Apps** | Limited | Excellent | Limited |
