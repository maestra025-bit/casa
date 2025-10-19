graph TD
    A[Teorías Clásicas de la Motivación] --> B{Enfoque en las Necesidades}
    A --> C{Enfoque en los Resultados / Comportamiento}
    A --> D{Enfoque en el Contexto Laboral}

    %% Enfoque en las Necesidades
    B --> B1[Maslow: Jerarquía de Necesidades]
    B1 --> B1a[1. Fisiológicas]
    B1 --> B1b[2. Seguridad]
    B1 --> B1c[3. Sociales / Pertenencia]
    B1 --> B1d[4. Estima]
    B1 --> B1e[5. Autorrealización]

    B --> B2[Herzberg: Teoría de los Dos Factores]
    B2 --> B2a[Factores de Higiene<br>(Evitan Insatisfacción)]
    B2a --> B2a1[Salario, Condiciones, Seguridad Laboral]
    B2a --> B2a2[Políticas de la Empresa, Supervisión]
    B2 --> B2b[Factores Motivacionales<br>(Generan Satisfacción)]
    B2b --> B2b1[Reconocimiento, Logro, Responsabilidad]
    B2b --> B2b2[Crecimiento Personal, El Trabajo en Sí]

    B --> B3[McClelland: Necesidades Adquiridas]
    B3 --> B3a[Necesidad de Logro (nAch)]
    B3 --> B3b[Necesidad de Poder (nPow)]
    B3 --> B3c[Necesidad de Afiliación (nAff)]

    %% Enfoque en Resultados
    C --> C1[Vroom: Teoría de las Expectativas]
    C1 --> C1a[Expectativa<br>(Esfuerzo → Desempeño)]
    C1 --> C1b[Instrumentalidad<br>(Desempeño → Recompensa)]
    C1 --> C1c[Valencia<br>(Valor de la Recompensa)]

    C --> C2[Adams: Teoría de la Equidad]
    C2 --> C2a[Inputs (Aportaciones)<br>Esfuerzo, Habilidades]
    C2 --> C2b[Outputs (Resultados)<br>Salario, Reconocimiento]
    C2 --> C2c[Percepción de Justicia vs. Injusticia]

    %% Enfoque en el Contexto
    D --> D1[McGregor: Teoría X e Y]
    D1 --> D1a[Teoría X<br>(Empleados Evitan Trabajar)]
    D1 --> D1b[Teoría Y<br>(Empleados Buscan Responsabilidad)]

    %% Estilos para el diagrama (opcional pero recomendado)
    classDef main fill:#f9f,stroke:#333,stroke-width:2px;
    classDef group fill:#ccf,stroke:#333;
    classDef keypoint fill:#fee,stroke:#333;

    class A main
    class B, C, D group
    class B1, B2, B3, C1, C2, D1 keypoint