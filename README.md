<h1 align="center"><img height="40" src="https://github.com/Aquiles369/iconos/blob/main/img/lobo1.gif"><img height="40" src="https://media4.giphy.com/media/v1.Y2lkPTc5MGI3NjExNWx4YTl1dW9scXlqZDk2cTdyY2VvcXQwMG40OGoxY25rZzV0MDZhcCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/peSyJWjNTRfzaWh49M/giphy.gif">"Promt ia codificación de payload"<img height="40" src="https://media4.giphy.com/media/v1.Y2lkPTc5MGI3NjExNWx4YTl1dW9scXlqZDk2cTdyY2VvcXQwMG40OGoxY25rZzV0MDZhcCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/peSyJWjNTRfzaWh49M/giphy.gif"><img height="40" src="https://github.com/Aquiles369/iconos/blob/main/img/lobo1.gif"></h1>	


<br>


<p align="center">
 <img  height="470rem" alt="GIF" src="https://media0.giphy.com/media/v1.Y2lkPTc5MGI3NjExNmdob2hwOHloeTJ2dm56cm52NXlpM3FpZnBua3ZqeTV5b21vOWs1biZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/CCqJCuNfKmpQNESLVA/giphy.gif"/>
</p>


<picture> <img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">  </picture>

 ### <picture> <img src = "https://media0.giphy.com/media/v1.Y2lkPTc5MGI3NjExc3BlcDcwN3ptczRxbDJyZ2J6MGMyeXAxNmQ2bnphbGZoN3Z5ZXZleSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/D34Wn98AYstonHXdU0/giphy.gif" width = 75px>  </picture> Promt ia codificación de payload
<br>

 **Generador avanzado de variantes ofuscadas de payloads XSS diseñado para uso en laboratorios de seguridad web, que transforma strings e identificadores sin romper la ejecución ni la sintaxis del payload original.** 
<br><br> 

<p align="center">
 <img  height="420rem" alt="GIF" src="https://github.com/Aquiles369/iconos/blob/main/promt_ofuscacion.gif"/>
</p>

<br>
<picture> <img src="https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif" width ="1050" > </picture>
<br>

### <picture> <img src = "https://media0.giphy.com/media/v1.Y2lkPTc5MGI3NjExM3UydGttc3VxcmJudWNzMzQ2N3NmcTUwdHI2MnUwYXFoYm1yd3ZjMyZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/O0CmQdUr0IY1i/giphy.gif" width = 75px>  </picture> Problema que resuelve<br><br>
**• Encontrar XSS hoy no es solo cuestión de inyectar <script>alert(1)</script>. Los WAF modernos, filtros de contenido y validadores detectan y bloquean payloads tradicionales. Esta herramienta soluciona ese obstáculo al generar múltiples variantes funcionales, ofuscadas y evasivas, listas para probar contra filtros y parsers avanzados.** 

<br>

### <picture> <img src = "https://media1.giphy.com/media/v1.Y2lkPTc5MGI3NjExdDhyZGR4OThlcGM4YTQ3MTZjamh5ZTM5b2FodWNicXVvdGJ5cjg2eCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/MWHiGvNPMm0GJ22FHy/giphy.gif" width = 75px>  </picture> Qué aporta y cómo beneficia <br><br>

• Ofuscación profunda por bloques Unicode (ASCII, Greek, Cyrillic, Math, etc.) sin romper ejecución.<br>

• Variantes únicas por payload con entropía controlada y reproducción garantizada gracias al seed.<br>

• Bypass de WAF y parsers gracias a técnicas de sustitución, homoglifos y manipulación por carácter (#**).<br>

• Entorno de laboratorio realista para probar payloads en aplicaciones vulnerables sin riesgos.<br>

• Automatización total: ingresás un payload y obtenés cientos o miles de variantes sin esfuerzo.<br><br>



<picture> <img src="https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif" width ="1050" > </picture>
<br>

### <picture> <img src = "https://media2.giphy.com/media/v1.Y2lkPTc5MGI3NjExMTByazliMmd2MHdheHUzNjFvY3hnd3J4bHljeXU2dG1obThqM3Q3ayZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/4LFhpEqZQvmKsYcSPI/giphy.gif" width = 80px>  </picture> Resumen rápido
<br><br>

- Una herramienta que toma un payload XSS y lo muta en variantes ofuscadas funcionales, aplicando técnicas modernas de evasión, homoglifos, combinaciones Unicode y validación estricta. Ideal para bug bounty, investigación avanzada y bypass de filtros.<br><br>
 
#1 — Promt de ia + Ofuscacion de payload.

 ```yaml
[PROPÓSITO]
Generar variantes codificadas de payloads XSS (LAB) usando x18_codificaciones. Mantener ejecución funcional y sintaxis intacta. Salida mínima: SOLO la lista de payloads, uno por línea, sin títulos ni metadatos.

[INPUTS DEL USUARIO]
- payloads: (A) un payload único, o (B) lista de N payloads (uno por línea).
- seed: entero opcional (reproducibilidad).
- variants_per_payload: número de variantes por payload.
- x18_list: IDs de codificaciones a aplicar (ver lista).
- apply_scope: "special_only" | "all" | "mixed"
  - special_only: transformar SOLO caracteres especiales: < > / = ' " + ( ) { } [ ] . , ; : % # & ? ` ~ ^ | \ .
  - all: transformar todo el contenido susceptible (texto/identificadores/URLs) preservando tokens críticos.
  - mixed: mezcla por secciones (p.ej., URL en URL-encode, texto en entidades, JS en \xNN).
- combo_flags: lista con 0+ de {#*, #**, #a}
  - #*: reutilizar la última codificación aplicada en la siguiente sección (memoria local).
  - #**: aplicar codificación SOLO a caracteres no reservados (letras/números/espacios), dejando especiales intactos.
  - #a: mezclar múltiples codificaciones en distintas partes del payload (segmentación inteligente).
- modo_validación: "estricto" | "relajado" (por defecto: estricto).

[x18_codificaciones — DISPONIBLES]
#1 base64
#2 hex (\x41\x6c\x65...)
#3 HTML entities (&lt; &gt; &quot;)
#4 URL encoding (%3Cscript%3E)
#5 JS unicode escape (\u003C\u0073\u0063)
#6 octal (\101\154\145)
#7 decimal HTML (&#60;&#62;)
#8 hex HTML (&#x3C;&#x3E;)
#9 mixed entities (&#x3C;&#60;)
#10 punycode (xn--)
#11 MIME quoted-printable
#12 CSS escapes (\00003C\000073)
#13 UTF-16 escape (\u003C)
#14 UTF-32 escape (\U0000003C)
#15 JS hex escapes (\x3c\x73\x63)
#16 JS octal escapes (\074\163\143)
#17 JS decimal escapes (\060\071)
#18 URL double-encode (%253Cscript%253E)
#19 URL mixed case (%3c%53%43)
#20 URL overlong (%c0%bc)
#21 URL UTF-16 surrogate (%u003C)
#22 URL UTF-7 style (+ADw-script+AD4-)
#23 UTF-7 direct (+ADw+)
#24 HTML numeric padded (&#00060;)
#25 NCR mixed case (&#X3c;)
#26 JS hex in-string ("\\x3c\\x73")
#27 JS unicode in-string ("\\u003c")
#28 mixed escape & entity (\x3c&#115;)
#29 mixed escape & unicode (\x3c\u0073)
#30 Base32
#31 Base36
#32 Base58
#33 Base62
#34 Base85 (Ascii85)
#35 Base91
#36 Base100 (emoji)
#37 ZWSP-delimited binary
#38 Braille unicode encoding
#39 Morse (.--.)
#40 Binary (01001000)
#41 Binary HTML entities (&#b01001000;)
#42 ROT13
#43 ROT47
#44 Caesar
#45 Atbash
#46 UUencode
#47 yEnc
#48 BinHex
#49 Quoted-printable hex
#50 XML entities (&lt;script&gt;)
#51 nested base64
#52 nested URL encoding (%25253C)
#53 HTML entity in URL (%26lt%3B)
#54 URL in HTML entity (&#x25;3C)
#55 base64 + URL (mixto)
#56 base64 + HTML entities (mixto)
#57 JS eval-string escaped
#58 JS bracket access ["\x61\x6c\x65"]
#59 JS constructor escape (Function("al"+"ert"))
#60 template literal escapes (\x61${'\x6c\x65'})
#61 backtick unicode (\u0060)
#62 overlong UTF-8 (%c0%af...)
#63 CESU-8 JS
#64 WTF-8 surrogate pairs
#65 UTF-16-BE inline BOM
#66 UTF-16-LE inline BOM
#67 UTF-32-BE inline BOM
#68 UTF-32-LE inline BOM
#69 Java-style unicode (\u0061)
#70 C trigraphs (??=)
#71 HTML comment wrap (<!--<script>-->)
#72 CDATA wrap (<![CDATA[<script>]]>)
#73 XML-style encoded CDATA
#74 SGML shortrefs
#75 EBCDIC→ASCII remap (teórico)
#76 BCD
#77 Baudot
#78 Radix-64 variant
#79 hex→base64 chain
#80 HTML5 named entities mix (&amp;#x3C;)
#81 Java properties unicode (\u003c)
#82 CSS url() escapes (url(\2f\2f))
#83 CSS string escapes ("ab\000063")
#84 CSS content encoding (counter())
#85 JSON unicode escapes (\u0061)
#86 YAML folded unicode
#87 Markdown entity escaping
#88 LaTeX math mode entities
#89 PDF hex string (<48656c6c6f>)
#90 PDF octal string (\110\145)
#91 Email punycode display-name
#92 MIME encoded-word (=?UTF-8?B?xxx?=)
#93 Domain literal escapes ([127\056\0x31])
#94 SQL CHAR() (CHAR(60,115))
#95 SQL hex (0x3c7363)
#96 Shell printf ('\x3c')
#97 PowerShell unicode (`u003c)
#98 Batch caret (^<)
#99 VBScript chr(60)
#100 HTML5 misnested (<scr\0ipt>)

[REGLAS DURAS]
1) NO tocar tokens críticos ASCII: < > = + ( ) { } [ ] . , ; : ' " / ? ! & # % * ` ~ ^ | \ 
2) NO cambiar nombres de etiquetas/eventos (script, img, onerror...).
3) Si apply_scope="special_only": SOLO transformar los caracteres especiales listados arriba.
4) Si apply_scope="all": codificar texto/identificadores/URLs, preservando tokens críticos y balanceo.
5) Si apply_scope="mixed": segmentar el payload y aplicar codificaciones distintas por sección (p.ej., URL con #4/#18, texto con #3/#7, JS con #2/#5/#15), sin romper ejecución.
6) Balancear comillas y paréntesis; no introducir BIDI/invisibles en tokens (ZWSP solo permitido en secciones de datos si no cambia parseo).
7) Validar que la variante siga invocando la primitiva de ejecución esperada (ej.: onerror/alert/confirm/bracket notation).
8) Si una codificación rompe ejecución → descartar y regenerar (máx 3 intentos/variante).

[VALIDACIÓN (modo estricto)]
- A: tokens críticos preservados.
- B: balanceo ()[]{}''"".
- C: primitiva de ejecución conservada.
- D: codificaciones dentro de x18_list.
- E: apply_scope respetado.
- F: sin BIDI/invisibles en tokens.

[FORMATO DE SALIDA — ESTRICTO]
**Solo la lista de payloads resultantes**, uno por línea, sin títulos ni hashes ni descripciones.

[POLÍTICA DE USO]
Solo laboratorio ético, partir de payloads del usuario; nada de dominios reales.

[AHORA, PEDIR INSUMOS]
1) ¿Payload único o lista?
2) variants_per_payload
3) seed (opcional)
4) x18_list (IDs)
5) apply_scope: special_only | all | mixed
6) combo_flags (opcional): #*, #**, #a

```
<br>

#2 — Cómo usar los flags y el alcance.

 ```yaml
apply_scope="special_only": buena para PoC que debe ejecutar sí o sí (solo toca < > ' " = ... y similares).

apply_scope="all": máxima ofuscación del contenido, pero ojo con romper nombres/JS.

apply_scope="mixed": la más inteligente → URL con URL-encode/doble-encode, texto con entidades, JS con \x/\u, dejando tokens intactos.

#*: “repite la última codificación” (útil para cadenas largas con el mismo patrón).

#**: “solo codificar no-reservados” (no toca < > = ( ) ... aunque apply_scope sea amplio).

#a: “mezcla varias codificaciones por sección” (p. ej., entidad en HTML + URL-encode en query + \x dentro de string JS).
```


## — Ejemplo de comando solo payload

 ```yaml
payloads:
<img src=x onerror=alert(1)>

seed: 1337
variants_per_payload: 10
x18_list: #3,#4,#5,#7,#8,#15,#18,#26,#27
apply_scope: mixed
combo_flags: #a,#**
modo_validación: estricto

```


<br><br>

## 3 — Explicación del promt

INPUTS DEL USUARIO

 ```yaml
- payloads: (A) un payload único, o (B) lista de N payloads (uno por línea).
- seed: entero opcional (reproducibilidad).
- variants_per_payload: número de variantes por payload.
- x18_list: IDs de codificaciones a aplicar (ver lista).
- apply_scope: "special_only" | "all" | "mixed"
  - special_only: transformar SOLO caracteres especiales: < > / = ' " + ( ) { } [ ] . , ; : % # & ? ` ~ ^ | \ .
  - all: transformar todo el contenido susceptible (texto/identificadores/URLs) preservando tokens críticos.
  - mixed: mezcla por secciones (p.ej., URL en URL-encode, texto en entidades, JS en \xNN).
- combo_flags: lista con 0+ de {#*, #**, #a}
  - #*: reutilizar la última codificación aplicada en la siguiente sección (memoria local).
  - #**: aplicar codificación SOLO a caracteres no reservados (letras/números/espacios), dejando especiales intactos.
  - #a: mezclar múltiples codificaciones en distintas partes del payload (segmentación inteligente).
- modo_validación: "estricto" | "relajado" (por defecto: estricto).
```

<br>

#4 — Bloques de codificaciones disponibles 

 ```yaml
#1 base64
#2 hex (\x41\x6c\x65...)
#3 HTML entities (&lt; &gt; &quot;)
#4 URL encoding (%3Cscript%3E)
#5 JS unicode escape (\u003C\u0073\u0063)
#6 octal (\101\154\145)
#7 decimal HTML (&#60;&#62;)
#8 hex HTML (&#x3C;&#x3E;)
#9 mixed entities (&#x3C;&#60;)
#10 punycode (xn--)
#11 MIME quoted-printable
#12 CSS escapes (\00003C\000073)
#13 UTF-16 escape (\u003C)
#14 UTF-32 escape (\U0000003C)
#15 JS hex escapes (\x3c\x73\x63)
#16 JS octal escapes (\074\163\143)
#17 JS decimal escapes (\060\071)
#18 URL double-encode (%253Cscript%253E)
#19 URL mixed case (%3c%53%43)
#20 URL overlong (%c0%bc)
#21 URL UTF-16 surrogate (%u003C)
#22 URL UTF-7 style (+ADw-script+AD4-)
#23 UTF-7 direct (+ADw+)
#24 HTML numeric padded (&#00060;)
#25 NCR mixed case (&#X3c;)
#26 JS hex in-string ("\\x3c\\x73")
#27 JS unicode in-string ("\\u003c")
#28 mixed escape & entity (\x3c&#115;)
#29 mixed escape & unicode (\x3c\u0073)
#30 Base32
#31 Base36
#32 Base58
#33 Base62
#34 Base85 (Ascii85)
#35 Base91
#36 Base100 (emoji)
#37 ZWSP-delimited binary
#38 Braille unicode encoding
#39 Morse (.--.)
#40 Binary (01001000)
#41 Binary HTML entities (&#b01001000;)
#42 ROT13
#43 ROT47
#44 Caesar
#45 Atbash
#46 UUencode
#47 yEnc
#48 BinHex
#49 Quoted-printable hex
#50 XML entities (&lt;script&gt;)
#51 nested base64
#52 nested URL encoding (%25253C)
#53 HTML entity in URL (%26lt%3B)
#54 URL in HTML entity (&#x25;3C)
#55 base64 + URL (mixto)
#56 base64 + HTML entities (mixto)
#57 JS eval-string escaped
#58 JS bracket access ["\x61\x6c\x65"]
#59 JS constructor escape (Function("al"+"ert"))
#60 template literal escapes (\x61${'\x6c\x65'})
#61 backtick unicode (\u0060)
#62 overlong UTF-8 (%c0%af...)
#63 CESU-8 JS
#64 WTF-8 surrogate pairs
#65 UTF-16-BE inline BOM
#66 UTF-16-LE inline BOM
#67 UTF-32-BE inline BOM
#68 UTF-32-LE inline BOM
#69 Java-style unicode (\u0061)
#70 C trigraphs (??=)
#71 HTML comment wrap (<!--<script>-->)
#72 CDATA wrap (<![CDATA[<script>]]>)
#73 XML-style encoded CDATA
#74 SGML shortrefs
#75 EBCDIC→ASCII remap (teórico)
#76 BCD
#77 Baudot
#78 Radix-64 variant
#79 hex→base64 chain
#80 HTML5 named entities mix (&amp;#x3C;)
#81 Java properties unicode (\u003c)
#82 CSS url() escapes (url(\2f\2f))
#83 CSS string escapes ("ab\000063")
#84 CSS content encoding (counter())
#85 JSON unicode escapes (\u0061)
#86 YAML folded unicode
#87 Markdown entity escaping
#88 LaTeX math mode entities
#89 PDF hex string (<48656c6c6f>)
#90 PDF octal string (\110\145)
#91 Email punycode display-name
#92 MIME encoded-word (=?UTF-8?B?xxx?=)
#93 Domain literal escapes ([127\056\0x31])
#94 SQL CHAR() (CHAR(60,115))
#95 SQL hex (0x3c7363)
#96 Shell printf ('\x3c')
#97 PowerShell unicode (`u003c)
#98 Batch caret (^<)
#99 VBScript chr(60)
#100 HTML5 misnested (<scr\0ipt>)
```

<br>

#5 — Reglas duras — Siempre debe cumplir 

 ```yaml
1) NO tocar tokens críticos ASCII: < > = + ( ) { } [ ] . , ; : ' " / ? ! & # % * ` ~ ^ | \ 
2) NO cambiar nombres de etiquetas/eventos (script, img, onerror...).
3) Si apply_scope="special_only": SOLO transformar los caracteres especiales listados arriba.
4) Si apply_scope="all": codificar texto/identificadores/URLs, preservando tokens críticos y balanceo.
5) Si apply_scope="mixed": segmentar el payload y aplicar codificaciones distintas por sección (p.ej., URL con #4/#18, texto con #3/#7, JS con #2/#5/#15), sin romper ejecución.
6) Balancear comillas y paréntesis; no introducir BIDI/invisibles en tokens (ZWSP solo permitido en secciones de datos si no cambia parseo).
7) Validar que la variante siga invocando la primitiva de ejecución esperada (ej.: onerror/alert/confirm/bracket notation).
8) Si una codificación rompe ejecución → descartar y regenerar (máx 3 intentos/variante).
```


<br>

#6 — Validación automatica (modo_validación="estricto")

 ```yaml
- A: tokens críticos preservados.
- B: balanceo ()[]{}''"".
- C: primitiva de ejecución conservada.
- D: codificaciones dentro de x18_list.
- E: apply_scope respetado.
- F: sin BIDI/invisibles en tokens.
```

<br>

#7 — Formato de salida — impresión mínima.

 ```yaml
**Solo la lista de payloads resultantes**, uno por línea, sin títulos ni hashes ni descripciones.

```


<br>

#8 — Solicitar insumos

 ```yaml
1) ¿Payload único o lista?
2) variants_per_payload
3) seed (opcional)
4) x18_list (IDs)
5) apply_scope: special_only | all | mixed
6) combo_flags (opcional): #*, #**, #a
```




<picture> <img src="https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif" width ="1050" > </picture>
<br>

### <picture> <img src = "https://media4.giphy.com/media/v1.Y2lkPTc5MGI3NjExc3YwbG9zbmU1amprdTJsbmxzYnpobzd5eGtnazB6b2FmdnllaTRhZyZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/h8UlsEpqiCISTKUzvz/giphy.gif" width = 80px>  </picture> “Camuflaje quirúrgico para tus XSS: invisible al WAF, letal en ejecución.”


<picture> <img src="https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif" width ="1050" > </picture>
