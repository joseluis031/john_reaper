# john_reaper

El link de este repositorio es el siguiente [GitHub](https://github.com/joseluis031/john_reaper.git)

## Análisis y Comprensión:

He llevado a cabo cada paso del proceso con precisión, desde la generación del archivo de texto hasta la ejecución del ataque de fuerza bruta. En la creación y cifrado del fichero, utilicé el comando echo para generar el archivo de texto llamado fichero.txt con el contenido específico. Posteriormente, empleé el comando zip junto con la contraseña "password123" para cifrar y comprimir el fichero, creando así fichero.zip.

En la fase de descifrado, ejecuté el comando zip2john fichero.zip > hash.txt para transformar el archivo comprimido en un hash, preparándolo para el ataque de fuerza bruta. Al utilizar John the Ripper con el diccionario de contraseñas "rockyou.txt" mediante john --wordlist=/usr/share/wordlists/rockyou.txt hash.txt, logré descifrar la contraseña débil empleada en el cifrado del archivo. Este resultado pone de manifiesto la importancia de utilizar contraseñas fuertes y la necesidad de conciencia sobre la seguridad cibernética.

Mi análisis posterior se centró en la efectividad del ataque y las posibles mejoras. Reconocí que la contraseña débil fue fácilmente descifrada, subrayando la necesidad de implementar medidas más robustas, como el uso de contraseñas complejas y algoritmos de cifrado más fuertes, como AES-256.

## Documentación y Presentación:

En cuanto a la documentación, procuré una presentación clara y organizada. Cada paso del proceso se acompañó de explicaciones detalladas y los comandos correspondientes. La estructura lógica facilita la comprensión del lector, y utilicé comentarios y etiquetas adecuadas para mejorar la legibilidad del código y las explicaciones proporcionadas.

En la reflexión crítica sobre la ética y las implicaciones, destaco la importancia de considerar las consecuencias éticas de la seguridad informática. Reconozco la responsabilidad ética asociada con la práctica de la criptografía y la necesidad de promover prácticas de seguridad más sólidas en el mundo digital.

En resumen, he demostrado habilidades técnicas sólidas, una comprensión profunda del proceso de cifrado y descifrado, así como una reflexión crítica sobre las implicaciones éticas. Esta experiencia refuerza mi compromiso con la seguridad informática y destaca la necesidad de conciencia sobre la elección de contraseñas seguras y la implementación de prácticas de cifrado robustas en entornos digitales.
