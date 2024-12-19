# Calculadora de Impuesto a la Renta Perú 2025 🇵🇪

Esta aplicación web permite calcular el Impuesto a la Renta de quinta categoría para trabajadores en Perú, basado en la nueva UIT (Unidad Impositiva Tributaria) aprobada para el año 2025.

## 🎯 Características

- Cálculo automático del impuesto anual
- Interfaz intuitiva y responsiva
- Implementación con HTML, JavaScript vanilla y TailwindCSS
- Sin dependencias adicionales
- Cálculos basados en la nueva UIT 2025 (S/ 5,350)

## 💡 Cómo Funciona

La calculadora implementa el siguiente proceso de cálculo:

1. **Ingreso Anual**: Multiplica el sueldo mensual por 14 (12 sueldos + 2 gratificaciones)
2. **Deducción del 20%**: Se resta automáticamente
3. **Deducción de 7 UIT**: Se resta el valor de 7 UIT (S/ 37,450)
4. **Cálculo del Impuesto**: Se aplica la tasa del 8% sobre el monto restante

## 📊 Rangos de Impuesto 2025

De acuerdo al MEF (Ministerio de Economía y Finanzas):

- Hasta 7 UIT (S/ 37,450): No pagan impuesto
- Más de 7 UIT hasta 12 UIT: 8%
- Más de 12 UIT hasta 27 UIT: 14%
- Más de 27 UIT hasta 42 UIT: 17%
- Más de 42 UIT hasta 52 UIT: 20%
- Más de 52 UIT: 30%

## 🚀 Novedades 2025

- Nueva UIT: S/ 5,350 (incremento de S/ 150)
- Los trabajadores que ganan hasta S/ 4,681 mensuales no pagarán impuesto
- Beneficia aproximadamente al 84% de los trabajadores formales

## 📝 Notas Importantes

- Los cálculos son referenciales y aproximados
- Se recomienda consultar con un contador para casos específicos
- La calculadora implementa solo el primer tramo (8%) por ser el más común

## 🔗 Fuente

Basado en la información publicada por el Ministerio de Economía y Finanzas (MEF) y reportada por [Infobae Perú](https://www.infobae.com/peru/2024/12/17/uit-2025-estos-trabajadores-ya-no-pagaran-impuesto-a-la-renta-por-el-nuevo-monto-aprobado-por-el-mef/).

## 💻 Tecnologías Utilizadas

- HTML5
- JavaScript Vanilla
- TailwindCSS
- FontAwesome (para íconos)

## 🤝 Contribuciones

Las contribuciones son bienvenidas. Por favor, sigue estos pasos:

1. Fork el repositorio
2. Crea una nueva rama (`git checkout -b feature/mejora`)
3. Realiza tus cambios
4. Commit tus cambios (`git commit -am 'Agrega nueva característica'`)
5. Push a la rama (`git push origin feature/mejora`)
6. Crea un Pull Request