## 1.3 Instalación de zonas secundarias - Alejandro Rey Otero

---

**1**. Tomaremos a máquina darthsidious, e configuraremola para ser servidor secundario, tanto da zona primaria de resolución directa como de resolución inversa. Captura os ficheiros de configuración en ambalas dúas máquinas. Fai unha captura onde se vexa o reinicio da máquina darthsidious, no que se vexa no log dos dous equipos e que se fixo a transferencia de zona.

- Resultado del fichero de configuración del servidor primario (darthvader):

  ![Imagen Ejer1_1.png](/imagenes/Ejer1_1.png)

---

- Resultado del fichero de configuración del servidor secundario (darthsidious):

  ![Imagen Ejer1_2.png](/imagenes/Ejer1_2.png)

---

- Resultado reinicio de la máquina darthsidious:
  
  ![Imagen Ejer1_3.png](/imagenes/Ejer1_3.png)

---

- Resultado del log del servidor primario (darthvader):
  
  ![Imagen Ejer1_4.png](/imagenes/Ejer1_4.png)

---

- Resultado del log del servidor primario (darthsidious):
  
  ![Imagen Ejer1_5.png](/imagenes/Ejer1_5.png)

---

**2**. Engade un rexistro tipo A (Chewbacca 192.168.20.28) na zona de resolución directa e tamén na de resolución inversa.  Fai unha captura no momento do reinicio do equipo darthvader, no que se vexa o log dos dous equipos e que se amose que se fixo a transferencia de zona. Adxunta tamén unha captura do ficheiro de zona no servidor secundario.

- Resultado reinicio de la máquina darthvader:

  ![Imagen Ejer2_1.png](/imagenes/Ejer2_1.png)

- Resultado del log del servidor primario (darthvader):
  
  ![Imagen Ejer2_2.png](/imagenes/Ejer2_2.png)

---

- Resultado del log del servidor primario (darthsidious):
  
  ![Imagen Ejer2_3.png](/imagenes/Ejer2_3.png)

---

- Resultado fichero de zona del servidor secundario (darthsidious):

  ![Imagen Ejer2_4.png](/imagenes/Ejer2_4.png)

---

**3**. Comproba que o servidor secundario pode resolver ese nome.

- Resultado del comando **nslookup chewbacca.starwars.lan 192.168.20.10**

  ![Imagen Ejer3_1.png](/imagenes/Ejer3_1.png)

---

**4**. Fai os cambios necesarios para que as trasferencias se fagan de forma segura empregando chaves.  Repite as capturas e vídeos do punto 2, engadindo o rexistro r2d2 (192.168.20.29)

 Resultado reinicio de la máquina darthvader:

  ![Imagen Ejer4_1.png](/imagenes/Ejer4_1.png)

- Resultado del log del servidor primario (darthvader):
  
  ![Imagen Ejer4_2.png](/imagenes/Ejer4_2.png)

---

- Resultado del log del servidor primario (darthsidious):
  
  ![Imagen Ejer4_3.png](/imagenes/Ejer4_3.png)

---

- Resultado fichero de zona del servidor secundario (darthsidious):

  ![Imagen Ejer4_4.png](/imagenes/Ejer4_4.png)

---

