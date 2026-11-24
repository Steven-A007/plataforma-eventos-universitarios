POST   /api/auth/register
POST   /api/auth/login
GET    /api/eventos
POST   /api/eventos                 (organizador)
PUT    /api/eventos/:id             (organizador dueño)
DELETE /api/eventos/:id             (organizador dueño)
POST   /api/eventos/:id/inscribirse (estudiante)
DELETE /api/eventos/:id/inscripcion (estudiante, cancela)
GET    /api/eventos/:id/inscritos   (organizador dueño)
PATCH  /api/inscripciones/:id/asistencia (organizador)
GET    /api/mis-inscripciones       (estudiante)