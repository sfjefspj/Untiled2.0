# Untitled Site 2.0

## Paragraph Section
Simple bypass method using embed tags. Because of embeds, not all sites work (CORS Policy).

---

## Copy and paster into your browser
```txt
data:text/html;charset=utf-8,%3C!DOCTYPE%20html%3E%0A%3Chtml%20lang%3D%22en%22%3E%0A%3Chead%3E%0A%20%20%20%20%3Cmeta%20charset%3D%22UTF-8%22%3E%0A%20%20%20%20%3Cmeta%20name%3D%22viewport%22%20content%3D%22width%3Ddevice-width%2C%20initial-scale%3D1.0%22%3E%0A%20%20%20%20%3Clink%20rel%3D%22icon%22%20href%3D%22https%3A%2F%2Fupload.wikimedia.org%2Fwikipedia%2Fcommons%2Fthumb%2F1%2F1f%2FBlank_square.svg%2F240px-Blank_square.svg.png%22%20type%3D%22image%2Fx-icon%22%3E%0A%20%20%20%20%3Ctitle%3E%E2%A0%80%3C%2Ftitle%3E%0A%3C%2Fhead%3E%0A%3Cbody%3E%0A%20%20%20%20%3Cdiv%20id%3D%22output%22%3E%3C%2Fdiv%3E%0A%0A%20%20%20%20%3Cscript%3E%0A%20%20%20%20%20%20%20%20fetch(%22https%3A%2F%2Fgist.githubusercontent.com%2Fsfjefspj%2F2ce05b5f2a5f477cba596d879e40a6cb%2Fraw%2Fcb9de12dfe81ca4a5afc948730f7ada3cbb095d9%2Funtitledsite2point0api.txt%22)%0A%20%20%20%20%20%20%20%20%20%20%20%20.then(response%20%3D%3E%20response.text())%0A%20%20%20%20%20%20%20%20%20%20%20%20.then(html%20%3D%3E%20%7B%0A%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%2F%2F%20Insert%20the%20HTML%20content%0A%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20document.getElementById(%22output%22).innerHTML%20%3D%20html%3B%0A%0A%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%2F%2F%20Execute%20any%20embedded%20scripts%0A%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20const%20scripts%20%3D%20document.getElementById(%22output%22).getElementsByTagName(%22script%22)%3B%0A%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20for%20(let%20script%20of%20scripts)%20%7B%0A%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20const%20newScript%20%3D%20document.createElement(%22script%22)%3B%0A%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20newScript.textContent%20%3D%20script.innerText%3B%0A%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20document.body.appendChild(newScript)%3B%0A%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%7D%0A%20%20%20%20%20%20%20%20%20%20%20%20%7D)%0A%20%20%20%20%20%20%20%20%20%20%20%20.catch(error%20%3D%3E%20%7B%0A%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20console.error(%22Error%20fetching%20the%20text%3A%20%22%2C%20error)%3B%0A%20%20%20%20%20%20%20%20%20%20%20%20%7D)%3B%0A%20%20%20%20%3C%2Fscript%3E%0A%3C%2Fbody%3E%0A%3C%2Fhtml%3E%0A

