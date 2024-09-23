# CURSO: APRENDE BLAZOR

# LECCIÓN 5: Explicación del Flujo de la aplicación Blazor

![image](https://github.com/user-attachments/assets/c860d1be-c6d7-48a8-8db1-3ab67dbeb09d)

1. **App.razor**: es el punto de entrada de la aplicación. Gestiona el ruteado de las páginas y el layout

2. **Routes.razor**: define cómo identificar las URLs de los componente con sus archivos

3. Cuando ejecutamos la aplicación, utilizamos el archivo MainLayout.razor para proporcional el layout principal de la aplicación, que incluye el componente **NavMenu** para la navegación entre páginas

4. Dependiendo de los vínculos de navegación elegidos por el usuario Based on user interaction (clicking links in **NavMenu**), el **router** carga el componente apropiado (e.g., Home.razor or other pages)

5. El middleware (**program.cs**) garantiza que la configuración de la aplicación es la apropiada, incluyendo las capacidades de ruteado y renderizado de páginas/componentes
