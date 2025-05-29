# Taller: Modelado NoSQL Documental con MongoDB para una Pizzería

🚨 No se espera un modelo "perfecto", sino que se **atrevan a explorar, justificar sus decisiones y aprender en el proceso**.

---

### Enunciado del reto

La pizzería necesita un sistema para gestionar sus productos (pizzas, panzarottis, bebidas, postres, adiciones), combos, ngredientes, pedidos y clientes. Los pedidos pueden ser para comer en el lugar o para recoger, y los clientes pueden personalizar sus productos con adiciones.

Debes **imaginar cómo guardarías esta información si no tuvieras que usar tablas como en MySQL, sino documentos JSON como los que usa MongoDB.**

⚠️ El enunciado es idéntico a su examen favorito de MySql 1

---

### 🚀 Actividades del reto

### 1. Investigar en equipo (máximo 3 personas)

Respondan brevemente en un documento o en el README del repositorio:

- ¿Qué es una base de datos NoSQL?
- ¿Qué es MongoDB?
- ¿Qué diferencia hay entre una base de datos relacional (como MySQL) y una base de datos documental como MongoDB?
- ¿Qué son documentos y colecciones en MongoDB?

> Pista: Un documento en MongoDB es un objeto tipo JSON con la información que quieres guardar, como si fuera una ficha de algo (por ejemplo, una pizza, un pedido o un cliente).
> 

---

### 2. Diseñar su propuesta

- Imaginen y propongan **qué colecciones tendrían**.
- ¿Qué información tendría un documento de pedido? ¿Y un producto?
- ¿Qué iría dentro del documento y qué se referenciaría?
- ¿Qué campos serían listas, objetos u otros documentos incrustados?

> Por ejemplo: ¿Un pedido tendría todos los datos del cliente y los productos adentro, o solo un ID del cliente?
> 

Usen cualquier herramienta para dibujar (a mano, draw.io, papel y foto), o escriban ejemplos de documentos en formato JSON.

---

### 3. Crear ejemplos de documentos JSON

Creen al menos 3 documentos de ejemplo escritos a mano o con ayuda de un validador JSON online, que representen:

- Un producto (ej. pizza con ingredientes)
- Un combo
- Un pedido con un cliente y varios productos (algunos personalizados)

---

### 4. Reflexionar

En grupo, escriban una breve reflexión:

- ¿Qué fue lo más difícil de imaginar sin tablas?
- ¿Qué les gustó del enfoque con documentos?
- ¿Qué dudas les surgieron al pensar en este nuevo tipo de base de datos?

---

### 📦 Entregable

Un **repositorio en GitHub** con:

- Un `README.md` que incluya:
    - Las respuestas de la investigación
    - El diseño propuesto con explicación de las colecciones y su estructura
    - Los ejemplos de documentos JSON (pueden ir en el mismo README o en archivos aparte)
    - La reflexión grupal