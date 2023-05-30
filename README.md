### Using toLocalString() Fucntion

---

number.toLocaleString("en-US");

### Using number to string & regular expression

---

number.toString()
.replace(/\B(?=(\d{3})+(?!\d))/g, ",")
