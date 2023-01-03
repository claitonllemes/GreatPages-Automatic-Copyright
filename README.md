# GreatPages-Automatic-Copyright
#### Código personalizado para criação de Copyright © para plataforma GreatPages.

<br>
<a href="https://www.buymeacoffee.com/claitonllemes"><img src="https://img.buymeacoffee.com/button-api/?text=Buy me a coffee&emoji=&slug=claitonllemes&button_colour=228636&font_colour=ffffff&font_family=Poppins&outline_colour=000000&coffee_colour=FFDD00" /></a>


<a href="https://www.buymeacoffee.com/claitonllemes"><img src="https://media3.giphy.com/media/7ssLleBvWvESbx0BuG/giphy.gif"/></a>

<br><br>

<img src="https://user-images.githubusercontent.com/99222756/207317647-1c517d05-a17f-4f25-bbf5-33cbb236e85e.jpg" width="100%"/>

<br>

```HTML

<script>

        // Name: Automatic Copyright for Greatpages. 
        // Version: 1.1.0 
        // Copyright: Claiton Lemes | Alisson Acioli

        let prefix = "© Copyright";
        let suffix = "All rights reserved";
        let cnpj = "CNPJ: 00.000.000/0000-00";
        let address = "";
        let developer = "<a href='LINK HERE' target='_blank'style='color: #268df3'> developer </a>"; // Backlink developer
        let terms = "<a href='LINK HERE' target='_blank' style='color: #268df3'> Terms of Use |</a>" // Terms of Use Page Link
        let privacy = "<a href='LINK HERE' target='_blank' style='color: #268df3'> Privacy Policy |</a>" // Privacy policy page link
        let cookies = "<a href='LINK HERE' target='_blank' style='color: #268df3'> Cookie Policy</a>" //Cookie policy page link
        let element = document.querySelector("#IDELEMENT"); // inspect element > right button on element > Copy > Copy Selector
        let smash = "<br>"
        let year = new Date().getFullYear();
        let space = " ";
        element.innerHTML = prefix + space + year + space + suffix + space + cnpj + space + address + space + developer + smash + terms + space + privacy + space + cookies;

</script>

```
