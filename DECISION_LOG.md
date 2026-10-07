# DECISION LOG

Formato: Situación → Evidencia → Opciones → Riesgos → Recomendación → Decisión.

---

## D-001 · Adoptar sistema de Gates y archivos de control · 2026-10-07 · ✅ Tomada
- **Decisión:** el negocio avanza por Gates 0–13; los archivos de control viven en la raíz del repositorio.
- **Por qué:** sin criterio explícito de aprobación, el avance se mide por actividad y no por evidencia.

## D-002 · El plan previo pasa a ser referencia, no plan vigente · 2026-10-07 · ✅ Tomada (reversible)
- **Situación:** existe `plan/referencia-arranque-90-dias.html`.
- **Evidencia (DATO):** asume 4–6 h/día por persona (≈20–30 h/sem c/u) y salto a EE.UU.; el contexto actual es 12–15 h/sem c/u y mercado Chile.
- **Consecuencia (INFERENCIA):** su ritmo (40 contactos/día, 13 semanas) es ~2× nuestra capacidad real. Ejecutarlo tal cual produce incumplimiento y desgaste.
- **Decisión:** sus servicios, precios y reglas se usan como **hipótesis de entrada** para el Gate 1, no como compromiso.

## D-003 · Reordenar Gates 2–5 · ⏳ PENDIENTE (decisión de Juan y Yussra)
- **Situación:** el orden actual es Capacidades → Laboratorio → Oferta → Demo.
- **Problema:** construir laboratorio antes de definir oferta contradice la regla principal (problema → oferta antes de tecnología). Riesgo de estudiar y construir sin comprador.
- **Opciones:**
  - A) Mantener orden actual.
  - B) Gate 1 incluye conversaciones con clientes → Oferta (borrador) → Capacidades + Laboratorio **solo de lo que exige esa oferta** → Demo.
- **Ganamos con B:** cada hora de aprendizaje apunta a algo vendible. **Sacrificamos:** algo de exploración técnica libre.
- **Recomendación:** B.

## D-004 · Política de nicho · ⏳ PENDIENTE
- **Situación:** ustedes no quieren encerrarse en un nicho; el plan previo exige uno solo.
- **Tensión real:** las plantillas reutilizables (fuente del margen) requieren clientes parecidos; explorar muchos rubros con 27 h/sem diluye todo.
- **Recomendación:** separar **exploración** (Gate 1: comparar 3–5 segmentos) de **compromiso** (Gate 4: una sola oferta para un segmento durante 90 días, revisable). El nicho es un experimento con fecha, no una identidad.

## D-005 · Definición de utilidad neta · ⏳ PENDIENTE (confirmar con contador)
- **Propuesta:** ingresos sin IVA − todos los costos del negocio − impuesto de la empresa = utilidad neta. Los 6M se miden así.
