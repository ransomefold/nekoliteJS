## NEKOLITE

---

![nekoliteJS](./assets/mascot.png)

**server ringan dan simpel**  
*entahlah gw gabut jir*

---

## KENAPA NEKOLITE?

- jelek dan aneh
- Super ringan, bahkan bisa dijalankan oleh kalkulator
- syntax-nya mirip express 
- bisa bikin kenyang ( kalau makan soto ) 
- **project gabut anjir 😭**  

> "Fun Fact: gak juga bingung gw ngapain buat kek beginian wkwkwk."  

---

![banner](./assets/banner.jpeg)

---

## INSTALASI

```bash
npm install https://github.com/ransomefold/nekoliteJS
```
---

## CARA PENGGUNAAN

```javascript
import Nekolite from "nekolite";
const app = Nekolite();

app.get("/", (req, res) => {
    res.send("hallo palkon!!")
});

app.listen(8080, () => console.log("server berhasil dijalankan"));
```