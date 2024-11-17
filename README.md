graph TD
    A[Inicio] --> B[Publicación de Información de Matrícula]
    B --> C[Recolección de Documentación del Postulante]
    C --> D{¿Se presentó toda la documentación requerida?}
    D -- Sí --> E[Inscripción del Postulante]
    D -- No --> F[Solicitar documentos faltantes]
    F --> C

    E --> G[Evaluación de Cumplimiento de Requisitos]
    G --> H{¿Los documentos son válidos y cumplen con los requisitos?}
    H -- Sí --> I{¿Hay vacantes disponibles?}
    H -- No --> J[Rechazar la solicitud y notificar al postulante]

    I -- Sí --> K[Pago de Derecho de Matrícula]
    I -- No --> L[Notificar al postulante sobre lista de espera o cierre de inscripciones]

    K --> M{¿Se realizó el pago de matrícula correctamente?}
    M -- Sí --> N[Confirmación de Matrícula]
    M -- No --> O[Notificar al postulante para completar el pago]

    N --> P[Entrega de Credenciales y Materiales (si aplica)]
    P --> Q[Fin]


