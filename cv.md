# Mikita Moiseichyk
- Phone: +375 447157174
- Email: Doktornikita@gmail.com
- Skype: doktornikita
- Telegram: [@vromga](https://t.me/vromga)
- GitHub: [@vromga](https://github.com/Vromga)
## Summary
I run a small vet clinic in Staryya Darohi a small town for almost 7 years. Every single day as the
            doctor I
            need to manage risks, deal with uncertainty, and be able to absorb animal’s pain and anxieties without
            losing my focus.
            profession also requires from me being approachable, decisive, compassionate, and in
            some way – being a leader, the one who is confident about the standards and stands firm up to hold
            their
            values and beliefs. As a person, I am open-minded, and constantly broadening my horizons, either
            professional or personal. I am a team-player because I believe that in a team of like-minded people,
            we
            can
            achieve bigger and brighter successes. I enjoy my spare time, which I don’t have that much, reading
            or
            doing
            some sports. I also curious about technologies and the way they are developing. I got my second
            degree
            in
            web designing and computer graphics, and this have an important influence in my profession.
            Recently, I
            realized that I need a dosage calculator (calculation of medication dosages). Having a background in
            programming, I was able to develop a simple calculator, meeting my purposes. Therefore, I eager to
            advance
            my skills in web designing, polishing my skills and getting a new one, and combine my two passions –
            technologies and veterinary sciences.
## Skills
- Language: JavaScript
- Other technologies: HTML/HTML5, CSS/CSS3
- Frameworks: React
- CSS frameworks: SASS
- System of version manage: GitHub
- Software and Tools: WebStorm, VS Code
- OS: Windows, Linux (ubuntu)
- Search engines: Google.com, Stackoverflow.com
- Other experience of using languages: PHP, Golang
## Code examples

### Kata: Find the stray number
```javascript
function stray(numbers) {
            let uniqueArr = [];
            let uniqueArr2 = [];
            uniqueArr.push(numbers[0]);
            for (let i = 1; i < numbers.length; i++){
                if (uniqueArr[0] === numbers[i]) {
                    uniqueArr.push(numbers[i]);
                }else{uniqueArr2.push(numbers[i])}
            }
            if(uniqueArr2.length < uniqueArr.length){
                return uniqueArr2[0];
            }else {return uniqueArr[0];}
        }
```

### Kata: Disemvowel Trolls
```javascript
function disemvowel(str) {
            let arrStr = str.split("");
            let letterArr = ["a", "u", "e", "i", "o", "A", "U", "E", "I", "O"]
            let newStr = [];
            nextStep: for (let i = 0; i < arrStr.length; i++) {
                for (let y = 0; y < letterArr.length; y++) {
                    if (arrStr[i] === letterArr[y]) {
                        continue nextStep;
                    }
                }
                newStr.push(arrStr[i]);
            }
            return newStr.join("");
        }
```
## Education
- 2019 - You Don't Know JS Yet (book series) - 2nd Edition
- 2019 - up to now [The Modern JavaScript Tutorial](https://learn.javascript.ru)
- 2018 - up to now [HTML Academy](https://htmlacademy.ru/profile/vromga)
- 2009 - 2010 Belarus State University, School of Business - Web design and computer graphics.
- 2008 Scientific and Practical Center of the National Academy of Sciences of Belarus on Animal Husbandry - Cattle Embryo Transplantation.
- 2003 - 2008 Vitebsk State Academy of Veterinary Medicine - Obstetrics, gynecology and biotechnology of animal reproduction.

#### Professional seminars and workshops
- 12/09/2018 Methods of diagnosis and treatment of tumors of the skin and soft tissue.
- 12/03/2018 A modern look at the stages of general anesthesia. From patient preparation to withdrawal
                  from anesthesia.
- 30/03/2018 Participation in the seminar RS road show: skin disease.
- 21/03/2016 Dietary aspects of the diets ProPlan Veterinary.