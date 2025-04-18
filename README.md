# Selenium Automation Tests in Python 🧪

Este repositorio contiene tres notebooks con pruebas automatizadas utilizando Selenium en Python. Cada uno ejemplifica diferentes formas de trabajar con `chromedriver` y realizar validaciones sobre sitios web reales, como Wikipedia y selenium.dev.

---

## 📁 Archivos incluidos

- **selenium_test_with_path.ipynb**  
  Ejecuta una prueba en el sitio [selenium.dev](https://www.selenium.dev/), validando que el sitio cargue correctamente y que contenga la palabra “Selenium”. Usa una **ruta explícita** al ejecutable de `chromedriver`.

- **selenium_test_without_path.ipynb**  
  Misma prueba que el anterior, pero asume que `chromedriver` ya está instalado y disponible en el **PATH** del sistema.

- **selenium_wikipedia_search_test.ipynb**  
  Realiza una búsqueda en Wikipedia utilizando múltiples estrategias para encontrar elementos (`By.ID`, `By.XPATH`, `By.CSS_SELECTOR`), junto con esperas **implícitas** y **explícitas**. Valida que el título final contenga la palabra “Selenium”.

---

## ⚙️ Requisitos

- Python 3.7 o superior  
- Google Chrome  
- ChromeDriver (versión compatible con tu navegador)

Instala Selenium con:

```bash
pip install selenium
```bash

## 🚀 Cómo usar
Clona el repositorio:

```bash
git clone https://github.com/tu_usuario/tu_repositorio.git
cd tu_repositorio
```bash

Ejecuta los notebooks desde Jupyter o Visual Studio Code, según prefieras. Asegúrate de tener chromedriver:

- En selenium_test_with_path.ipynb, actualiza la variable ruta_chromedriver con la ruta exacta en tu equipo.
- En selenium_test_without_path.ipynb y selenium_wikipedia_search_test.ipynb, asegúrate de que chromedriver esté disponible en tu PATH.

## 📌 Características destacadas
Validación con assert del contenido y la URL

Navegación automática en páginas web

Uso combinado de:

- By.ID
- By.XPATH
- By.CSS_SELECTOR

Ejemplos de:

- Esperas implícitas (implicitly_wait)
- Esperas explícitas (WebDriverWait + expected_conditions)

## ✅ Ideal para:
Practicar automatización básica de interfaces web

Aprender localizadores y esperas en Selenium

Realizar pruebas controladas en sitios reales


## 👨‍💻 AUTOR

Víctor Cardoso Fernández  
[LinkedIn](https://www.linkedin.com/in/victor-cardoso-datascientist/) | [GitHub](https://github.com/victorpython)

---

## 🚀 PRÓXIMOS PASOS

Este es el primer paso de una serie de pruebas automatizadas que simularán flujos de interacción con modelos de inteligencia artificial en interfaces web. ¡Mantente atento!

