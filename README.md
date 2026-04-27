## Paradigmas de Programación

# Laboratorio 2 "Conecta 4" en Prolog

Implementación del clásico juego **Conecta 4** en lenguaje **Prolog**, desarrollado como laboratorio en el ramo de Paradigmas de Programación.

---
 
## 🔧 Instalación y Uso
 
### Requisitos previos

- **SWI-Prolog** (versión 8.0 o superior)
- Editor de texto o IDE compatible con Prolog (SWI-Prolog IDE, VS Code + extensión Prolog, etc.)

### 📚 Estructura del proyecto
 
```
Laboratorio-1-Paradigmas/
├── main_210821481_SofiaVergaraGodoy.pl
├── TDAboard_210821481_SofiaVergaraGodoy.pl
├── TDAgame_210821481_SofiaVergaraGodoy.pl
├── TDApiece_210821481_SofiaVergaraGodoy.pl
│── TDAplayer_210821481_SofiaVergaraGodoy.pl
├── script1_210821481_SOFIA_VERGARAGODOY.pl
├── script2_210821481_SOFIA_VERGARAGODOY.pl
├── script_base_210821481_SOFIA_VERGARAGODOY.pl
└── README.md
```

### Configuración inicial
 
 **Clonar o descargar el repositorio**:
```bash
cd Laboratorio-2-Paradigmas
git clone https://github.com/Friedemmm/Conecta4_Prolog.git
```

### Inicializar una partida

Ejecuta uno de los tres scripts que están estructurados como una partida:

**Pasos para ejecutar:**

1. Abre **SWI-Prolog**
2. Consulta el archivo principal: `main_210821481_SofiaVergaraGodoy.pl`
3. Abre el script en un editor de texto (bloc de notas, VS Code, etc.) y copia todo el contenido
4. Pega el código en la consola de consulta de SWI-Prolog
5. ¡Listo para jugar!
 
---
 
## ✨ Características principales
 
- 🎯 **Lógica de juego completa**: Inserción de piezas, validación de movimientos y detección de ganadores.
- 👥 **Soporte para 2 jugadores**: Turnos alternados entre jugadores.
- 🔴🟡 **Sistema de piezas por color**: Diferenciación visual mediante colores (rojo y amarillo).
- 📋 **Tablero dinámico**: Creación flexible de tableros con dimensiones personalizables.
- ✅ **Validación de dominios**: Todas las funciones respetan restricciones de dominio para funcionamiento correcto.
- 🏆 **Detección de victoria**: Identifica ganadores por línea horizontal, vertical o diagonal.
---
 
*© 2024 · Universidad de Santiago de Chile*
