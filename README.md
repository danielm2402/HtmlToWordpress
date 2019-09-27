# HtmlToWordpress
Ejemplo de configuración de una plantilla html a wordpress

1. Crear pagina de inicio en wordpress
2. Pasar la plantilla a la carpeta wordpress/wp-content/themes
3. el index pasarlo a un archivo template-home.php
4. Crear header .php y footer.php 
5. Cortar el header desde doctype hasta <body> del template-home.php a header.php
6. Agregar la función "<?php echo get_template_directory_uri();?>/" en los href necesarios
7. Agregar función de la cabecera en el header, debajo del title: <?php wp_head();?>
8. Los mismo con el footer desde <footer> hasta </html>, agregar la función de los href y <?php wp_footer();?> .
9. <?php get_header();?> para obtener la cabecera creada
10. <?php get_footer();?> para obtener el footer creado
11. Crear archivo functions, codigo en este repositorio
