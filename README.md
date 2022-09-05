# Modelo-Ecommerce
 * Construção básica de plataforma ecommerce para testes em Django

 * Bibliotecas utilizadas:
    - Python 3.10.5
    - Django 4.1
    - Front end pré construido em HTML5, CSS, Java e Bootstrap (Distribuido por "Curso de Python 3 do Básico Ao Avançado (com projetos reais)")

 * Como executar no terminal:
    - Instalar bibliotecas Django e Pillow
        -- pip install Django
        -- pip install Pillow
        -- pip install django-crispy-forms
    - Criar login no admin para acesso do banco de dados:
        -- python manage.py createsuperuser:
    - Executar comando no terminal
        -- python manage.py runserver


 * Estrutura do banco de dados:
    - Perfil do usuário
        -- Variação de adição de novos endereços
        -- Validação básica de CPF do usuário

    - Produtos
        -- Possibilidades de aplicar promoções e variações dos produtos

    - Pedidos
        -- Atualização do status de entrega do pedido


 * A adicionar para se tornar funcional:
    - Consulta de endereço rápida por CEP
    - Adicionar plataforma de pagamentos
    - Validação de dados por CPF
