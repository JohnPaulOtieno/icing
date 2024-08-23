# Achola's Icing
A simple cake-commerce website

## Features
- Cakes (as products) Categories
- Ability to make and fulfill cake orders
- User Management, anonymous and aunthenticated user actions on the app
- Social Media and contact information for correspondence

## Built With

- [Django](https://www.djangoproject.com/) - The web framework used
- [Python](https://www.python.org/) - Programming Language

## For us, nerds

- Simple product catalogue
- Cart functionality with orders powered my [Celery](https://docs.celeryq.dev/en/stable/index.html) and [RabbitMQ](https://www.rabbitmq.com/docs/download) and [flower](https://flower.readthedocs.io/) for background tasks and messaging
- International ([Stripe](https://dashboard.stripe.com/login)) and local (hopefully, MPESA, provided by [Daraja](https://developer.safaricom.co.ke/APIs)) payment gateways
- PDF invoices with [WeasyPrint](https://doc.courtbouillon.org/weasyprint/stable/first_steps.html)
- Recommendation of products powered by [Redis](https://redis.io/)
- Internationalization and localization using [gettext](https://docs.djangoproject.com/en/5.0/ref/settings/#globalization-i18n-l10n)

## Contributors
- [JP](https://github.com/JohnPaulOtieno)
- [Wechuli Simiyu](https://github.com/wechulisimiyu)