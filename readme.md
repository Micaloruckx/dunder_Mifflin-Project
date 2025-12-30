3️⃣ background-attachment: fixed en mobile

En mobile muchas veces no funciona y puede romper el fondo.

➡️ Para probar, comentá esto:

/* background-attachment: fixed; */


Después lo activás solo en desktop:

@media (min-width: 1024px) {
  .main__hero {
    background-attachment: fixed;
  }
}


