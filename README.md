# 🔍 SELENIUM INTRO TEST – WIKIPEDIA SEARCH AUTOMATION

Este script es una prueba básica utilizando **Selenium WebDriver con Python**. Automatiza una búsqueda en [Wikipedia](https://www.wikipedia.org/) y valida que el resultado sea correcto.

---

## ⚙️ ¿QUÉ HACE EL SCRIPT?

1. Abre la página principal de Wikipedia.
2. Introduce el texto “Selenium (software)” en el campo de búsqueda.
3. Da clic en el botón de búsqueda.
4. Valida que el título de la página cargada contenga la palabra **“Selenium”**.

---

## ✅ ¿QUÉ VALIDACIONES SE AUTOMATIZAN?

- Verifica que el campo de búsqueda esté disponible (espera explícita).
- Verifica que el botón de búsqueda sea clickeable.
- Valida que el resultado contenga el título esperado.
- Imprime el título si todo sale bien; si no, lanza un error y lo imprime.

---

## 📦 REQUISITOS

- Python 3.x  
- Selenium → `pip install selenium`  
- ChromeDriver (agregado al PATH del sistema)  
  *(o adapta el script para usar Firefox, Edge u otro navegador compatible)*

---


## 👨‍💻 AUTOR

Víctor Cardoso Fernández  
[LinkedIn](https://www.linkedin.com/in/victor-cardoso-datascientist/) | [GitHub](https://github.com/victorpython)

---

## 🚀 PRÓXIMOS PASOS

Este es el primer paso de una serie de pruebas automatizadas que simularán flujos de interacción con modelos de inteligencia artificial en interfaces web. ¡Mantente atento!

