### Hey there 👋
### This is Jhonnatha Solsona!

> Majoring in bachelor of Science and Technology from the <a href="https://ufrn.br/en">Federal University of Rio Grande do Norte</a>!

[![Github](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/yJFelipeSS)
[![Linkedin: jhonnathasolsona](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jhonnatha-solsona-405064178/)

### A little bit about me (personal Me.class)...
```javascript
package br.com.felipess.worldocupants;

import java.util.Collections;

import br.com.felipess.model.Me;
import br.com.felipess.model.Parents;

import br.com.felipess.utils.BeautyLevel;
import br.com.felipess.utils.Skills;

public class Me {

  private final Parents mommy;
  private final Parents daddy;
  
  private BeautyLevel beauty;
  private Skills skills;
  
  private boolean born;
  
  private LocalDate birthDate;

  public Me(@NotNull Parents mommy, @NotNull Parents daddy) {
    this.mommy = mommy;
    this.daddy = daddy;
    
    born = false;
    
    beauty.setAlmostNone();
    
    setSkills();
    setBirthDate();
  }
  
  private void setSkills() {
    skills.setFrontEndLanguages("HTML", "CSS", "JavaScript", "React");
    skills.setBackEndLanguages("Java", "C++", "Python");
    skills.setMobileProgrammingLanguages("React Native", "Flutter");
    skills.setAutomationSkills("Selenium IDE", "Selenium");
    
    skills.setSportsSkills(Collections.singleton("Jiu Jitsu"));
  }
  
  private void setBirthDate() {
    LocalDate now = LocalDate.now();
    this.birthDate = now.plusMonths(9);
  }
  
}

```


> This README file is still in building procress
<img src="https://media3.giphy.com/media/f7b9ltJ4FrhnsKjYx2/giphy.gif">
