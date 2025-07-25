
<body>

  <h1>🧠 Arquitectura Modular y Separación de Lógica en Proyectos Web</h1>
  <p><strong>Desarrollado por:</strong> Anderson Bernal</p>

  <h2>📌 Objetivo</h2>
  <p>Aplicar principios de arquitectura limpia para mantener un proyecto web escalable, legible y fácilmente mantenible, organizando adecuadamente los archivos y separando responsabilidades.</p>

  <h2>🏗️ Estructura del Proyecto</h2>
  <div class="highlight">
    <pre>
src/
│
├── components/        ← Componentes reutilizables (Navbar, Footer, Cards)
│   └── Footer.jsx
│
├── pages/             ← Vistas principales (Home, Contact, About)
│   └── Home.jsx
│
├── services/          ← Funciones para acceder a APIs o lógica externa
│   └── Api.jsx
│
├── hooks/             ← Hooks personalizados (como useGlobalReducer)
│   └── useGlobalReducer.jsx
│
├── store/             ← Reducer y estado global del proyecto
│   └── store.js
│
├── App.jsx            ← Componente principal que orquesta todo
└── index.js           ← Punto de entrada de React
    </pre>
  </div>

  <h2>🧩 Principios Aplicados</h2>
  <ul>
    <li><strong>Separación de Responsabilidades:</strong> cada carpeta y archivo tiene una única función clara.</li>
    <li><strong>Reutilización:</strong> componentes como <code>Footer</code> pueden usarse en varias páginas sin duplicar código.</li>
    <li><strong>Escalabilidad:</strong> al crecer el proyecto, se pueden añadir módulos sin romper la estructura base.</li>
    <li><strong>Legibilidad:</strong> el código está dividido de forma que otros desarrolladores puedan entenderlo fácilmente.</li>
  </ul>

  <h2>⚙️ Tecnologías utilizadas</h2>
  <ul>
    <li>React.js</li>
    <li>JavaScript ES6+</li>
    <li>CSS Modules</li>
    <li>React Router DOM</li>
  </ul>

  <h2>✅ Buenas Prácticas</h2>
  <ul>
    <li>Importar solo lo necesario en cada archivo.</li>
    <li>Evitar lógica repetida (uso de hooks y servicios).</li>
    <li>Nombrar carpetas y archivos con claridad y coherencia.</li>
    <li>Usar componentes funcionales y hooks para el manejo de estado y efectos.</li>
  </ul>

  <h2>🧪 Resultado Esperado</h2>
  <p>Una aplicación web organizada, funcional y fácil de mantener, donde cada módulo puede ser trabajado, testeado o escalado de manera independiente.</p>

  <h2>🧾 ¿
    Por que la estructura modular?</h2>
  <p>
    Implementar una arquitectura modular en proyectos web mejora drásticamente la productividad, la colaboración en equipo y la facilidad de mantenimiento. Esta práctica es fundamental para cualquier desarrollador que busque profesionalizar su código y prepararse para entornos de desarrollo reales.
  </p>

</body>
</html>
