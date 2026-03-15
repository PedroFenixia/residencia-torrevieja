# Carta de reclamación de dominio - Dinahosting

## Opción 1: Email a Dinahosting (soporte@dinahosting.com)

---

**Asunto:** Solicitud de código de autorización (Auth/EPP) para transferencia del dominio residenciamarbella.com

Estimados señores de Dinahosting,

Me dirijo a ustedes como representante legal del **Centro de Mayores Mar Bella**, titular del dominio **residenciamarbella.com** (Registry Domain ID: 99925426_DOMAIN_COM-VRSN), registrado a través de su plataforma desde el 1 de julio de 2003.

Por la presente, solicito formalmente:

1. **El código de autorización (Auth-Code / EPP Code)** del dominio residenciamarbella.com para proceder a su transferencia a otro registrador antes de la fecha de expiración (1 de julio de 2026).

2. **La eliminación del bloqueo de transferencia** (clientTransferProhibited) actualmente activo en el dominio.

3. **Confirmación por escrito** de que el dominio será desbloqueado en un plazo máximo de 5 días naturales, conforme a la política de transferencias de ICANN.

**Datos del titular:**
- Razón social: [NOMBRE DE LA EMPRESA / AUTÓNOMO]
- CIF/NIF: [CIF/NIF]
- Domicilio: Avda. Alfredo Nobel, 8, 03183 Torrevieja, Alicante
- Teléfono de contacto: 965 710 828
- Email de contacto: residencia@residenciamarbella.com

Adjunto a este email copia del [CIF/DNI del titular] para verificación de identidad.

Les recuerdo que, conforme a la **Política de Transferencia de Dominios de ICANN** (Inter-Registrar Transfer Policy), el registrador está obligado a:
- Proporcionar el código de autorización al titular registral en un plazo razonable.
- No impedir ni retrasar la transferencia salvo por las causas expresamente previstas en la política.
- Desbloquear el dominio a petición del titular.

El incumplimiento de estas obligaciones puede dar lugar a una **reclamación formal ante ICANN** a través del formulario de quejas por problemas de transferencia (https://www.icann.org/complaints/transfer).

**IMPORTANTE:** Si el dominio está siendo gestionado por un tercero (por ejemplo, Tecnoworld) como intermediario, les informo de que la relación contractual con dicho tercero no afecta a mi derecho como titular a solicitar directamente el código de transferencia al registrador. La titularidad del dominio corresponde al registrante, no al intermediario.

Quedo a la espera de su respuesta en un plazo máximo de 5 días laborables.

Atentamente,

[NOMBRE Y APELLIDOS]
[CARGO]
Centro de Mayores Mar Bella
Avda. Alfredo Nobel, 8
03183 Torrevieja, Alicante
Tel: 965 710 828
Email: residencia@residenciamarbella.com

---

## Opción 2: Si Dinahosting no responde o se niega (carta más formal)

---

**Asunto:** REQUERIMIENTO FORMAL - Transferencia del dominio residenciamarbella.com - Último aviso antes de reclamación ante ICANN

Estimados señores,

En relación con mi anterior comunicación de fecha [FECHA DEL PRIMER EMAIL], y no habiendo recibido respuesta satisfactoria / habiéndoseme denegado la solicitud de transferencia del dominio **residenciamarbella.com**, les comunico lo siguiente:

**PRIMERO.** Que el dominio residenciamarbella.com fue registrado el 1 de julio de 2003 y el titular registral es [NOMBRE/EMPRESA], con CIF [CIF], con domicilio en Torrevieja (Alicante).

**SEGUNDO.** Que conforme al artículo 8 de la Política de Transferencia entre Registradores de ICANN, el registrador perderá (losing registrar) está obligado a facilitar la transferencia y no puede denegarla salvo en los supuestos taxativamente enumerados (fraude, disputa judicial, impago al registrador actual, o dominio registrado en los últimos 60 días).

**TERCERO.** Que la retención injustificada de un dominio constituye una práctica contraria a las políticas de ICANN y puede dar lugar a:
- Reclamación ante ICANN (Transfer Complaint)
- Denuncia ante la Oficina Municipal de Información al Consumidor (OMIC) de Torrevieja
- Reclamación ante Red.es (si aplica al .es)
- Acciones legales por retención indebida de un activo digital

**CUARTO.** Que por la presente les REQUIERO formalmente para que, en un plazo máximo de **5 días naturales** desde la recepción de esta comunicación, procedan a:
1. Desbloquear el dominio (eliminar clientTransferProhibited)
2. Facilitar el código Auth/EPP al email residencia@residenciamarbella.com

En caso de no obtener respuesta, procederé a presentar reclamación ante ICANN y ante las autoridades de consumo correspondientes.

Atentamente,

[NOMBRE Y APELLIDOS]
[CARGO]
Centro de Mayores Mar Bella

---

## Pasos para transferir a OVH una vez tengáis el código EPP

1. **Ir a OVH**: https://www.ovh.es/dominios/ → "Transferir un dominio"
2. **Introducir** residenciamarbella.com
3. **Pegar el código EPP/Auth** que os dé Dinahosting
4. **Pagar** la transferencia (~10-12€, incluye 1 año de renovación)
5. **Confirmar** el email de verificación que llegará
6. La transferencia tarda **5-7 días** (Dinahosting puede aceptarla antes)
7. Una vez en OVH, configurar los DNS para apuntar a GitHub Pages:

```
Tipo A     →  @    →  185.199.108.153
Tipo A     →  @    →  185.199.109.153
Tipo A     →  @    →  185.199.110.153
Tipo A     →  @    →  185.199.111.153
Tipo CNAME →  www  →  pedrofenixia.github.io
```

## Calendario recomendado

| Fecha | Acción |
|-------|--------|
| Hoy | Enviar email Opción 1 a soporte@dinahosting.com |
| +5 días | Si no responden, enviar Opción 2 |
| +10 días | Si siguen sin responder, reclamación en ICANN + OMIC |
| Mayo 2026 | Iniciar transferencia a OVH (antes de julio) |
| Julio 2026 | Dominio ya en OVH, no se renueva en Dinahosting |
