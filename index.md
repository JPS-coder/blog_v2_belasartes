{% load static %}
<!DOCTYPE html>
<html lang="pt-br">
    <head>
        <meta charset="UTF-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>APBA</title>
        <link rel="stylesheet"  href="{% static 'css/blog_estilo.css' %}">
    </head>
    <body>
        <div class="borda">
            <div id="logo">
                <p><img src="{% static 'img/logo.jpg' %}"></p>
            </div>
            
            <div class="cabecalho">
                
                <h1>A.P.B.A</h1>
                <p>Associação Paulista de Belas Artes</p>
            </div>
            
            <div id="menu">
                <table>
                    <tr>
                        <th><a href="{% url 'formulario' %}" target="_blank" rel="next">Cadastro</a></th>
                    </tr>
            
                    <tr>
                        <th><a href="{% url 'curso' %}" target="_blank" rel="next"> Cursos</a></th>
                    </tr>
                            
                </table>
            </div>
            
            <div id="principal">
                
                <p class="texto">Desde 1942</p>
               
                <p class="texto">Levando a Arte até você</p>
                     
                <p class="texto">Venha nos conhecer</p>
                
                <p class="texto">Seja um Associado</p>
            </div>

            <div class="rodape">
                <h4>Rua Conselheiro Crispiniano, 53 - 13º andar - República</h4>
                <h4>Telefone: 11 3105-1660 / 3214-4711 / 98195-9148(whatsapp)</h4>
            </div>
        </div>    
    </body>
</html>
