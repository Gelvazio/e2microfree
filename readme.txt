    FROM php:7.4-apache
    COPY . /var/www/html/
	
Comandos pra rodar projeto na nuvem

Após criar e salvar o arquivo (por exemplo, $ \text{/etc/nginx/sites-available/meu_site.conf} $), siga estes passos:



sudo ln -s /etc/nginx/sites-available/meusite.conf /etc/nginx/sites-enabled/	
	
	