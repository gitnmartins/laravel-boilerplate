# 🚀 Laravel Boilerplate com Livewire + Tailwind

Este é um boilerplate moderno para aplicações Laravel, já configurado com Livewire e Tailwind CSS. Ideal para projetos que precisam de interatividade sem complicações e um design responsivo desde o início.

## 🧰 Tecnologias incluídas

- [Laravel](https://laravel.com/) 10+
- [Livewire](https://livewire.laravel.com/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Vite](https://vitejs.dev/) para build frontend rápido
- Autenticação pronta com Laravel Breeze (opcional)

## 📦 Instalação

```bash
git clone https://github.com/gitnmartins/laravel-boilerplate.git
cd NOME_REPOSITORIO
composer install
cp .env.example .env
php artisan key:generate
npm install && npm run dev
php artisan migrate
```

## Usar como Laravel Template
```php
laravel new minha-app --git https://github.com/gitnmartins/laravel-boilerplate.git
```
