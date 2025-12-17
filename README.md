
MOTOR DE BÚSQUEDA SEMÁNTA (v1)
=============================================================================
Desarrollo de un sistema de Busqueda Inteligente. Experimental.

1. ARQUITECTURA:
   - Implementación de un sistema de "Dense Retrieval" (Recuperación Densa).
   - Patrón de diseño orientado a objetos (Clase SemanticEngine) con principios 
     de encapsulamiento para el modelo y la base de conocimiento.

2. MATEMÁTICA APLICADA:
   - Transformación de texto no estructurado a Vectores en R^384 (Embeddings).
   - Cálculo de similitud mediante Similitud del Coseno (Cosine Similarity).
   - Uso de Álgebra Lineal (Producto Punto y Normas L2) sobre matrices NumPy 
     para ranking de relevancia.

3. STACK TECNOLÓGICO:
   - Python 3.10+ (Type Hinting).
   - PyTorch (Backend de tensores).
   - Sentence-Transformers (Modelo: all-MiniLM-L6-v2).
   - NumPy (Operaciones vectoriales de alto rendimiento).

4. RESULTADO:
   - Capacidad de "Semantic Search": El motor recupera documentos basados en 
     el significado conceptual y no solo en coincidencia exacta de palabras clave.
