## Resume ##
## Junior Frontend Developer ##
#### > 1. First Name, Last Name #### 
Hello, world! My name is __Viktor Bashincheev__
#### > 2. Contact Info ####
reagent03@gmail.com , +7 902 1616 999 , [hh.ru](https://spb.hh.ru/resume/04cd0dbdff0806d24b0039ed1f376169746c41)
#### > 3. Summary (your goal, wishes, reveal what is important for you, what do you want and why. ####
My purpose - to became a developer because at the moment programming is my hobby and I like it. I do love solve logical tasks)) Mostly I like algorithm tasks on codewars.
#### > 4. Skills ####
I learn Frontend-developing since February 2020. Javascript is my main programming language. I can typeset (вёрстка). Also, I use BEM-methodology, bootstrap and scss. I had started to study framework react, but realized that it was too early... I will go back to react in the future))
#### > 5. Code examples (LATEST) ####
```
function calcExchangeRate(currency1, currency2) {
    const api = `https://api.exchangeratesapi.io/latest?symbols=${currency1},${currency2}`;
    async function getCurrency() {
        const response = await fetch(api);
        const val = await response.json();
        return val;
    }
    getCurrency().then(val => {
        let res = val.rates[currency2] / val.rates[currency1];
        res = Math.round(res * 100) / 100;
        console.log(res); // <--------------------------------------------------> 76.39 (1 USD == 76.39 RUB)
    });
}
calcExchangeRate('USD', 'RUB');
```
#### > 6. Experience ####
You can look at my code examples in [repositories](https://github.com/reagentJS?tab=repositories)
#### > 7. Education ####
Unfortunately, I haven't serious education expierence in programming except self-education (it was honestly, at least :))
#### > 8. English ####
My English level - B1 (I get а sertificate of the school _English tochka_)
