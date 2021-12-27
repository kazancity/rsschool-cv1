# Artem Banderov

====
## Contacts
- Location: Kazan, Russia
- Phone: +79534858888
- E-mail: artem_75@bk.ru
- GitHub: Artem Banderov (https://github.com/kazancity)
- Discord: Artem Banderov (@kazancity)
- Telegram: @Tourbillon (https://t.me/Tourbillon)

====
## About me

I study FE Pre-School 2022 Stage 0 in RSSchool

**Skills**
- HTML
- CSS
- JS
- VBS

**Code Example on JS**
```
function myFunction02()
{
  var input = document.createElement("textarea");
  input.value = document.getElementById('btn02').innerText;
  input.id = 'inputID';
  document.body.appendChild(input);
  input.select();
  document.execCommand('copy');
  document.body.removeChild(input);
  document.getElementById('btn02').textContent = "Copied!";
  setTimeout(timerFunction, 400);
  function timerFunction() 
    {
      document.getElementById('btn02').textContent = "Department of Internal Affairs of the Kirovsky district of the city of Kazan";
    }
}
```