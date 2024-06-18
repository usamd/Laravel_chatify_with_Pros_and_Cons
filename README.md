# Chatify

## Pros:
- **Extremely easy setup**: Installation with a single command and minimal configuration.
- **Fast integration**: Integrates seamlessly into your Laravel app.
- **Real-time features**: Built-in functionality for real-time messages, user status, and typing indicators.

## Cons:
- **Limited scalability**: Not ideal for very large-scale chat applications.
- **Customization limitations**: May not offer as much customization as building from scratch.

## Comparison with Other Methods

| Method             | Ease of Setup | Speed (Real-time) | Scalability | Customization |
|--------------------|---------------|-------------------|-------------|---------------|
| Laravel Echo/Pusher| Moderate      | Fast              | High        | Moderate      |
| WebSockets         | Complex       | Fast              | High        | High          |
| Chatify            | Very Easy     | Fast              | Moderate    | Low           |


###To run: Use these commands
composer install 
cp .env.example .env 
Create database 
modify .env with your DB name and Pusher credentials
php artisan migrate --seed
php artisan key:generate
npm install && npm run dev
php artisan storage:link
php artisan serve

References : https://github.com/munafio/chatify-demo
