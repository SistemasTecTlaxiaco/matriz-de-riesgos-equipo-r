# Matriz de Riesgos - Herbamed

---

## Leyenda de Evaluación

**Probabilidad:** Alta (A) - Media (M) - Baja (B)  
**Impacto:** Crítico (C) - Alto (A) - Medio (M) - Bajo (B)  
**Prioridad:** P1 (Crítica) - P2 (Alta) - P3 (Media) - P4 (Baja)

---

## Matriz Principal de Riesgos

| ID | Riesgo | Categoría | Prob. | Impacto | Prioridad | Mitigación | Responsable |
|----|--------|-----------|-------|---------|-----------|------------|-------------|
| 1 | Falta de financiamiento adicional | Financiero | A | C | P1 | • Plan de implementación por fases<br>• Buscar inversionistas ángel<br>• Campaña de crowdfunding | Director Financiero |
| 2 | Información médica no verificada | Legal/Técnico | A | C | P1 | • Comité de validación con expertos UNAM<br>• Sistema de revisiones por pares<br>• Descargos de responsabilidad claros | Jefe de Contenido |
| 3 | Baja adopción de usuarios | Mercado | M | A | P2 | • Programa de early adopters con beneficios<br>• Alianzas con universidades<br>• Marketing de contenido especializado | Director de Marketing |
| 4 | Problemas de escalabilidad técnica | Técnico | M | A | P2 | • Arquitectura serverless desde inicio<br>• Pruebas de carga continuas<br>• Monitoreo proactivo de performance | CTO |
| 5 | Competencia de apps establecidas | Mercado | M | A | P2 | • Diferenciación por validación científica<br>• Enfoque en herbolaria mexicana específica<br>• Comunidad de usuarios activa | Director Estratégico |
| 6 | Regulaciones sanitarias cambiantes | Legal | M | A | P2 | • Asesor legal especializado en salud<br>• Monitoreo regulatorio constante<br>• Diseño modular adaptable | Compliance Officer |
| 7 | Fugas de datos de usuarios | Seguridad | M | A | P2 | • Encryption end-to-end<br>• Auditorías de seguridad trimestrales<br>• Políticas de privacidad estrictas | CISO |
| 8 | Calidad inconsistente del contenido | Operativo | A | M | P3 | • Guías de estilo y calidad<br>• Sistema de métricas de contenido<br>• Capacitación continua del equipo | Editor Jefe |
| 9 | Problemas con proveedores de pago | Operativo | B | A | P3 | • Múltiples gateways de pago<br>• Contratos con cláusulas de servicio<br>• Fondos de contingencia | CFO |
| 10 | Alta rotación del equipo técnico | Recursos Humanos | M | M | P3 | • Plan de carrera y desarrollo<br>• Cultura de trabajo flexible<br>• Participación en resultados | Director de RH |

---

## Plan de Acción por Prioridad

### P1 - RIESGOS CRÍTICOS (Acción Inmediata)

#### Riesgo #1: Falta de financiamiento
**Acciones específicas:**
- **Identificación de inversionistas:** Buscar 3 inversionistas potenciales antes del mes 2
- **Campaña de crowdfunding:** Preparar campaña Kickstarter con meta de $200,000 MXN
- **Plan de negocio:** Desarrollar plan para concursos de emprendimiento

**Responsable:** Director Financiero  
**Timeline:** Mes 1-2

#### Riesgo #2: Información no verificada
**Acciones específicas:**
- **Convenio académico:** Firmar convenio con facultad de medicina UNAM en mes 1
- **Protocolo de validación:** Diseñar protocolo completo en 2 semanas
- **Sistema de reportes:** Desarrollar sistema de banderas de contenido reportado

**Responsable:** Jefe de Contenido  
**Timeline:** Mes 1

---

### P2 - RIESGOS ALTOS (Planificación Activa)

#### Riesgo #3: Baja adopción de usuarios
**Acciones específicas:**
- **Programa de referidos:** Implementar "Trae un amigo" con beneficios específicos
- **Alianzas estratégicas:** Establecer alianzas con 5 influencers de wellness mexicano
- **Contenido viral:** Desarrollar contenido sobre plantas poco conocidas

**Responsable:** Director de Marketing  
**Timeline:** Mes 1-3

#### Riesgo #4: Escalabilidad técnica
**Acciones específicas:**
- **Infraestructura cloud:** Contrato con AWS con auto-scaling configurado
- **Pruebas de rendimiento:** Pruebas de carga con 10,000 usuarios simultáneos
- **Backup de datos:** Implementar backup de base de datos cada 12 horas

**Responsable:** CTO  
**Timeline:** Mes 1-2

---

### P3 - RIESGOS MEDIOS (Monitoreo Continuo)

#### Riesgo #8: Calidad de contenido
**Acciones específicas:**
- **Métricas de engagement:** Implementar sistema de métricas por artículo
- **Encuestas de satisfacción:** Realizar encuestas mensuales a usuarios
- **Programa de incentives:** Establecer programa de recompensas a colaboradores destacados

**Responsable:** Editor Jefe  
**Timeline:** Continuo

---

## Indicadores de Riesgo Clave (KRIs)

| Riesgo | KRI | Límite | Acción Disparadora |
|--------|-----|--------|-------------------|
| Financiero | Cash flow mensual | < $50,000 MXN | Activar plan de contingencia financiera |
| Adopción | Tasa de crecimiento usuarios | < 15% mensual | Revisar estrategia de marketing |
| Técnico | Tiempo de respuesta API | > 2 segundos | Optimizar consultas y cache |
| Legal | Reclamos por información | > 2 por mes | Revisar protocolos de validación |

---

## Matriz de Seguimiento

| Riesgo | Estado | Última Revisión | Próxima Revisión | Tendencia |
|--------|--------|-----------------|------------------|-----------|
| #1 Financiamiento | Crítico | [Fecha] | [Fecha+15d] | Empeorando |
| #2 Información verificada | En Mitigación | [Fecha] | [Fecha+30d] | Estable |
| #3 Adopción usuarios | En Mitigación | [Fecha] | [Fecha+30d] | Mejorando |
| #4 Escalabilidad | Controlado | [Fecha] | [Fecha+60d] | Mejorando |

---

## Conclusión de la Matriz de Riesgos

**Riesgos Totales Identificados:** 10

**Distribución por Prioridad:**
- Críticos (P1): 2 (20%)
- Altos (P2): 5 (50%)
- Medios (P3): 3 (30%)
- Bajos (P4): 0 (0%)

**Estado General:** MODERADO  
El proyecto es viable pero requiere gestión activa de riesgos, especialmente en áreas financieras y de contenido. Se recomienda revisión quincenal de los riesgos P1 y mensual de los P2.
