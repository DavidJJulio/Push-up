<h1>Descripción del Proyecto</h1>
<p>La <strong>Weather App</strong> es una aplicación diseñada para proporcionar información meteorológica actualizada y precisa a los usuarios. A través de una interfaz intuitiva y amigable, la app ofrecerá datos sobre la temperatura, humedad, pronóstico a corto y largo plazo, y alertas meteorológicas para diversas ubicaciones en todo el mundo. Utilizando <strong>WeatherAPI</strong> para obtener datos meteorológicos en tiempo real, la aplicación se asegurará de que los usuarios tengan acceso a información relevante sobre el clima en su área y en cualquier otro lugar que deseen consultar.</p>
<h2>Problemática</h2>
<p>En la actualidad, muchas personas dependen de información meteorológica precisa para planificar sus actividades diarias. Sin embargo, a menudo enfrentan los siguientes problemas:</p>
<ol>
<li><strong>Inexactitud de los Datos:</strong> Las aplicaciones actuales pueden ofrecer pronósticos poco precisos o desactualizados, lo que puede llevar a decisiones incorrectas, como salir sin abrigo en un día lluvioso.</li>
<li><strong>Interfaz Confusa:</strong> Algunas aplicaciones meteorológicas presentan información de manera compleja y no intuitiva, dificultando que los usuarios encuentren rápidamente la información que buscan.</li>
<li><strong>Falta de Personalización:</strong> Muchas aplicaciones no permiten a los usuarios configurar alertas o seguir el clima en ubicaciones específicas que les interesan, lo que limita su utilidad.</li>

</ol>
<h2>Características Principales</h2>
<ol>
<li><p><strong>Interfaz de Usuario Intuitiva:</strong> La aplicación tendrá un diseño limpio y fácil de usar, con información claramente presentada sobre el clima actual y pronósticos futuros.</p>
</li>
<li><p><strong>Datos en Tiempo Real:</strong> Utilizando <strong>WeatherAPI</strong>, la app proporcionará actualizaciones instantáneas sobre condiciones climáticas, temperatura y precipitaciones.</p>
</li>
<li><p><strong>Búsqueda de Ubicaciones:</strong> Los usuarios podrán buscar manualmente ubicaciones específicas para consultar la información meteorológica de cualquier lugar del mundo.</p>
</li>
<li><p><strong>Pronóstico Extendido:</strong> Los usuarios podrán acceder a pronósticos a corto y largo plazo (7-14 días) para planificar actividades futuras.</p>
</li>
<li><p><strong>Alertas Personalizables:</strong> Los usuarios podrán configurar alertas para condiciones meteorológicas severas, como tormentas, nevada o altas temperaturas, asegurando que siempre estén informados.</p>
</li>
<li><p><strong>Información Histórica:</strong> La app ofrecerá datos históricos sobre el clima, permitiendo a los usuarios consultar condiciones pasadas para análisis o referencia.</p>
</li>
<li><p><strong>Compatibilidad Multiplataforma:</strong> Desarrollada para ser accesible tanto en dispositivos móviles (iOS y Android) como en versiones web, garantizando que los usuarios tengan acceso en cualquier momento y lugar.</p>
</li>
<li><p><strong>Sostenibilidad:</strong> Opciones para ver el impacto del clima en el medio ambiente, como pronósticos de calidad del aire y recomendaciones sobre actividades sostenibles.</p>
<p>&nbsp;</p>
</li>

</ol>
<h1>Tecnologías y Herramientas</h1>
<ul>
<li><p><strong>Front-end</strong>: </p>
<ul>
<li><strong>Figma</strong>: <a href='https://www.figma.com/community/file/1249443729401540968' target='_blank' class='url'>https://www.figma.com/community/file/1249443729401540968</a></li>
<li><strong>Recurso:</strong> <a href='https://drive.google.com/drive/folders/1ueatJSyXii4yl4XBRqRIrARamMn_ywJZ?usp=drive_link' target='_blank' class='url'>https://drive.google.com/drive/folders/1ueatJSyXii4yl4XBRqRIrARamMn_ywJZ?usp=drive_link</a></li>
<li><strong>Opción 1:</strong> React o Vue.js para construir una interfaz de usuario interactiva y dinámica.</li>
<li><strong>Opción 2:</strong> Desarrollo puro utilizando HTML, CSS y JavaScript para una implementación más sencilla.</li>

</ul>
</li>
<li><p><strong>GitHub</strong>: Para la gestión de versiones del código en el desarrollo, usando <strong>conventional commits.</strong></p>
</li>

</ul>
<p>&nbsp;</p>
<h1>Instrucciones de uso de weatherapi</h1>
<h2>Creación de la cuenta</h2>
<p>Ingresa al enlace <a href='https://www.weatherapi.com/' target='_blank' class='url'>https://www.weatherapi.com/</a> y crea una cuenta siguiendo estos pasos:</p>
<p><img src="https://i.ibb.co/TwHHCg4/image.png" referrerpolicy="no-referrer"></p>
<p>Debes crear una contraseña para acceder a la plataforma.</p>
<p><img src="https://i.ibb.co/DL4r2HG/image.png" referrerpolicy="no-referrer"></p>
<p>Una vez validado el correo electrónico.
<img src="https://i.ibb.co/vDGN7NG/image.png" referrerpolicy="no-referrer"></p>
<p>En el correo electrónico confirmaremos la creación de la cuenta. Al hacer clic en el enlace que se te envíe, serás redirigido a una página para la verificación. Luego, deberás iniciar sesión con tu correo electrónico y la contraseña que registraste.
<img src="https://i.ibb.co/47HFQY6/image.png" referrerpolicy="no-referrer"></p>
<p><img src="https://i.ibb.co/p3WyP5X/image.png" referrerpolicy="no-referrer"></p>
<p><img src="https://i.ibb.co/xzsnknV/image.png" referrerpolicy="no-referrer"></p>
<p>Una vez dentro copiaremos nuestro key para poder consumir las apis
<img src="https://i.ibb.co/xHkf5g0/image.png" referrerpolicy="no-referrer"></p>
<p>&nbsp;</p>
<hr />
<p>&nbsp;</p>
<h2>Como usar la documentacion</h2>
<p>Accedemos a este enlace <a href='https://www.weatherapi.com/docs/' target='_blank' class='url'>https://www.weatherapi.com/docs/</a> para consultar la documentación de las API.</p>
<p>Una vez dentro de la página de la documentación, busca el menú <strong>Introduction &gt; Authentication</strong>. Allí encontrarás las instrucciones para consumir la API. Ten en cuenta que, en este punto, deberás haber copiado el token previamente, ya que la página de documentación no lo proporcionará automáticamente.</p>
<p><strong>Ejemplo de uso:</strong>  <code>http://api.weatherapi.com/v1/current.json?key=[API Key]&amp;q=Floridablanca</code></p>
<p><strong>Nota:</strong> en esta parte <strong>[API Key]</strong> quita los paréntesis y coloca tu API, por ejemplo, si tu API es <strong>124685468</strong>, quedaría como <code>?key=124685468&amp;</code></p>
<p><img src="https://i.ibb.co/BVjwYPm/image.png" referrerpolicy="no-referrer"></p>
<p>Encontraremos una tabla de endpoints para obtener información sobre el clima, enfocándonos en los siguientes.</p>
<p><img src="https://i.ibb.co/mNKyrf9/image.png" referrerpolicy="no-referrer"></p>
<p>Esta opción nos proporciona la información del clima actual. Ten en cuenta que existen dos formatos disponibles: <strong>JSON</strong> y <strong>XML</strong>. En esta ocasión, utilizaremos <strong>JSON</strong>.
<img src="https://i.ibb.co/q5GrQqN/image.png" referrerpolicy="no-referrer"></p>
<p>Esta opción nos proporcionará el pronóstico del clima para el día siguiente.
<img src="https://i.ibb.co/QkDYS2D/image.png" referrerpolicy="no-referrer"></p>
<p>La siguiente opción ofrece información sobre el clima en un día específico.
<img src="https://i.ibb.co/Ctmb3jg/image.png" referrerpolicy="no-referrer"></p>
<p>&nbsp;</p>
<p><strong>Nota:</strong> Si quieres conocer el significado de cada dato, dirígete a la sección de <strong>APIs &gt; Realtime API</strong>.
<img src="https://i.ibb.co/SvnzZHy/image.png" referrerpolicy="no-referrer"></p>
<p>&nbsp;</p>
<hr />
<h1>Uso del api</h1>
<h2>Obtener información del clima actual</h2>
<p><strong>Method</strong> : <code>GET</code></p>
<p><strong>URL</strong> : <code>http://api.weatherapi.com/v1/current.json</code></p>
<p><strong>Auth required</strong> : <code>True</code></p>
<p><strong>URL Query</strong> : <code>?key=[API Key]&amp;q=Floridablanca&amp;lang=es</code></p>
<p><strong>Success Responses</strong></p>
<p><strong>Code</strong> : <code>200 OK</code></p>
<pre><code class='language-json' lang='json'>{
  &quot;location&quot;: {
    &quot;name&quot;: &quot;Floridablanca&quot;,
    &quot;region&quot;: &quot;Santander&quot;,
    &quot;country&quot;: &quot;Colombia&quot;,
    &quot;lat&quot;: 7.0647,
    &quot;lon&quot;: -73.0897,
    &quot;tz_id&quot;: &quot;America/Bogota&quot;,
    &quot;localtime_epoch&quot;: 1728508634,
    &quot;localtime&quot;: &quot;2024-10-09 16:17&quot;
  },
  &quot;current&quot;: {
    &quot;last_updated_epoch&quot;: 1728508500,
    &quot;last_updated&quot;: &quot;2024-10-09 16:15&quot;,
    &quot;temp_c&quot;: 23.1,
    &quot;temp_f&quot;: 73.5,
    &quot;is_day&quot;: 1,
    &quot;condition&quot;: {
      &quot;text&quot;: &quot;Ligeras precipitaciones&quot;,
      &quot;icon&quot;: &quot;//cdn.weatherapi.com/weather/64x64/day/353.png&quot;,
      &quot;code&quot;: 1240
    },
    &quot;wind_mph&quot;: 3.8,
    &quot;wind_kph&quot;: 6.1,
    &quot;wind_degree&quot;: 291,
    &quot;wind_dir&quot;: &quot;WNW&quot;,
     .....
  }
}
</code></pre>
<p>&nbsp;</p>
<h2>Obtener pronostico del clima</h2>
<p><strong>Method</strong> : <code>GET</code></p>
<p><strong>URL</strong> : <code>http://api.weatherapi.com/v1/forecast.json</code></p>
<p><strong>Auth required</strong> : <code>True</code></p>
<p><strong>URL Query</strong> : <code>?key=[API Key]&amp;q=Floridablanca&amp;lang=es&amp;days=14</code></p>
<p><strong>Success Responses</strong></p>
<p><strong>Code</strong> : <code>200 OK</code></p>
<pre><code class='language-json' lang='json'>{
  &quot;location&quot;: {
    &quot;name&quot;: &quot;Floridablanca&quot;,
    &quot;region&quot;: &quot;Santander&quot;,
    &quot;country&quot;: &quot;Colombia&quot;,
    &quot;lat&quot;: 7.0647,
    &quot;lon&quot;: -73.0897,
    &quot;tz_id&quot;: &quot;America/Bogota&quot;,
    &quot;localtime_epoch&quot;: 1728509020,
    &quot;localtime&quot;: &quot;2024-10-09 16:23&quot;
  },
  &quot;current&quot;: {
    &quot;last_updated_epoch&quot;: 1728508500,
    &quot;last_updated&quot;: &quot;2024-10-09 16:15&quot;,
    &quot;temp_c&quot;: 23.1,
    &quot;temp_f&quot;: 73.5,
    &quot;is_day&quot;: 1,
    &quot;condition&quot;: {
      &quot;text&quot;: &quot;Ligeras precipitaciones&quot;,
      &quot;icon&quot;: &quot;//cdn.weatherapi.com/weather/64x64/day/353.png&quot;,
      &quot;code&quot;: 1240
    },
    &quot;wind_mph&quot;: 3.8,
    &quot;wind_kph&quot;: 6.1,
    &quot;wind_degree&quot;: 291,
    &quot;wind_dir&quot;: &quot;WNW&quot;,
    .......
  },
  &quot;forecast&quot;: {
    &quot;forecastday&quot;: 
      [.......] // Pronóstico para los próximos 14 días
  }
}
</code></pre>
<p>&nbsp;</p>
<h2>Obtener el clima en un día específico </h2>
<p><strong>Method</strong> : <code>GET</code></p>
<p><strong>URL</strong> : <code>http://api.weatherapi.com/v1/forecast.json</code></p>
<p><strong>Auth required</strong> : <code>True</code></p>
<p><strong>URL Query</strong> : <code>?key=[API Key]&amp;q=Floridablanca&amp;lang=es&amp;dt=2024-10-01</code></p>
<p><strong>Success Responses</strong></p>
<p><strong>Code</strong> : <code>200 OK</code></p>
<pre><code class='language-json' lang='json'>{
  &quot;location&quot;: {
    &quot;name&quot;: &quot;Floridablanca&quot;,
    &quot;region&quot;: &quot;Santander&quot;,
    &quot;country&quot;: &quot;Colombia&quot;,
    &quot;lat&quot;: 7.0647,
    &quot;lon&quot;: -73.0897,
    &quot;tz_id&quot;: &quot;America/Bogota&quot;,
    &quot;localtime_epoch&quot;: 1728509416,
    &quot;localtime&quot;: &quot;2024-10-09 16:30&quot;
  },
  &quot;forecast&quot;: {
    &quot;forecastday&quot;: [
      {
        &quot;date&quot;: &quot;2024-10-01&quot;,
        &quot;date_epoch&quot;: 1727740800,
        &quot;day&quot;: {
          &quot;maxtemp_c&quot;: 23.6,
          &quot;maxtemp_f&quot;: 74.4,
          &quot;mintemp_c&quot;: 11.3,
          &quot;mintemp_f&quot;: 52.4,
          &quot;avgtemp_c&quot;: 18.9,
          &quot;avgtemp_f&quot;: 66.0,
          &quot;maxwind_mph&quot;: 5.6,
          &quot;maxwind_kph&quot;: 9.0,
          &quot;totalprecip_mm&quot;: 12.84,
          &quot;totalprecip_in&quot;: 0.51,
          &quot;totalsnow_cm&quot;: 0.0,
          &quot;avgvis_km&quot;: 9.8,
          &quot;avgvis_miles&quot;: 6.0,
          &quot;avghumidity&quot;: 86,
          &quot;daily_will_it_rain&quot;: 1,
          &quot;daily_chance_of_rain&quot;: 100,
          &quot;daily_will_it_snow&quot;: 0,
          &quot;daily_chance_of_snow&quot;: 0,
          &quot;condition&quot;: {
            &quot;text&quot;: &quot;Ligeras precipitaciones&quot;,
            &quot;icon&quot;: &quot;//cdn.weatherapi.com/weather/64x64/day/353.png&quot;,
            &quot;code&quot;: 1240
          },
          &quot;uv&quot;: 5.0
        },
        &quot;astro&quot;: {
          &quot;sunrise&quot;: &quot;05:41 AM&quot;,
          &quot;sunset&quot;: &quot;05:44 PM&quot;,
          &quot;moonrise&quot;: &quot;04:48 AM&quot;,
          &quot;moonset&quot;: &quot;05:08 PM&quot;,
          &quot;moon_phase&quot;: &quot;Waning Crescent&quot;,
          &quot;moon_illumination&quot;: 3
        },
        &quot;hour&quot;: [
          {
            &quot;time_epoch&quot;: 1727758800,
            &quot;time&quot;: &quot;2024-10-01 00:00&quot;,
            &quot;temp_c&quot;: 11.3,
            &quot;temp_f&quot;: 52.4,
            &quot;is_day&quot;: 0,
            &quot;condition&quot;: {
              &quot;text&quot;: &quot;Ligeras precipitaciones&quot;,
              &quot;icon&quot;: &quot;//cdn.weatherapi.com/weather/64x64/night/353.png&quot;,
              &quot;code&quot;: 1240
            },
            &quot;wind_mph&quot;: 1.8,
            &quot;wind_kph&quot;: 2.9,
            &quot;wind_degree&quot;: 80,
            &quot;wind_dir&quot;: &quot;E&quot;,
            &quot;pressure_mb&quot;: 1015.0,
            &quot;pressure_in&quot;: 29.99,
            &quot;precip_mm&quot;: 0.16,
            &quot;precip_in&quot;: 0.01,
            &quot;snow_cm&quot;: 0.0,
            &quot;humidity&quot;: 90,
            &quot;cloud&quot;: 68,
            &quot;feelslike_c&quot;: 11.4,
            &quot;feelslike_f&quot;: 52.4,
            &quot;windchill_c&quot;: 11.4,
            &quot;windchill_f&quot;: 52.4,
            &quot;heatindex_c&quot;: 11.4,
            &quot;heatindex_f&quot;: 52.4,
            &quot;dewpoint_c&quot;: 9.7,
            &quot;dewpoint_f&quot;: 49.5,
            &quot;will_it_rain&quot;: 1,
            &quot;chance_of_rain&quot;: 100,
            &quot;will_it_snow&quot;: 0,
            &quot;chance_of_snow&quot;: 0,
            &quot;vis_km&quot;: 10.0,
            &quot;vis_miles&quot;: 6.0,
            &quot;gust_mph&quot;: 3.8,
            &quot;gust_kph&quot;: 6.0,
            &quot;uv&quot;: 0.0
          },
          ....
        ]
      }
    ]
  }
}
</code></pre>
<p>&nbsp;</p>
