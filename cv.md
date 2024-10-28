# Sergey Meshcheryakov

### Contacts:

- Location: Voronezh, Russia
- Phone: +7 904-211-39-07
- Email: karoshop@mail.ru
- GitHub: [Nesheras](https://github.com/Nesheras)

---

### About Me:

I'm passionate about studying web technologies, and I genuinely enjoy the learning process. I love diving into the details of code, understanding how interfaces work, and uncovering what makes for a great user experience. Each new project or skill isn't just a step in my education—it's an opportunity to improve my craft and bring exciting ideas to life.

### Skills and Proficiency:

- HTML5, CSS3,CSS Modules
- JS,TS
- Git
- React,Redux
- Figma

---

### Code Example:

```
function topThreeWords(text) {
  let arrWords = text.match(/('?[A-Z]+'?([a-z]+)?'?)/ig);
let data ={}
if(!arrWords){
  return []
}
for(let i =0;i<arrWords.length;i++){
  let word = arrWords[i].toLowerCase()
  if(word in data){
    data[word]=data[word]+1
  }else{
    data[word]=1
  }
}
let result =Object.entries(data).sort((a,b)=>a[1]-b[1]).reverse().slice(0,3).map((el)=>el[0])
return result
}
```

---

### Education:

- VGAU

  - Specialty agroengineering

- Tomsk State University

  - Web Developer

---

### Languages:

- Russian - native speaker.
- English - A1
