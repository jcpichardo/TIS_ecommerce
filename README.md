# TIS_ecommerce


CREAR PROYECTO MVC 

Correrlo, examinar la vista Índex y su controlador, modificar algunos textos para que vean los cambios

![image](https://github.com/user-attachments/assets/9f8fc6a8-763e-4e3b-b51e-7acad87ce79d)

Examinar el layout para ver el menú y los llamados a las vistas 

Analizar donde esta cada cosa 

CONECTAR CON LA BD


using Microsoft.EntityFrameworkCore; 

namespace DemoEcommerceMVC.Services
{
    public class ApplicationDbContext : DbContext
    {

        public ApplicationDbContext(DbContextOptions options) : base(options) { 
        
        }

    }
}        
