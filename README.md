# GreatPages-Automatic-Copyright

<a href="https://www.buymeacoffee.com/claitonllemes" target="_blank" rel="noopener noreferrer"><img src="https://user-images.githubusercontent.com/99222756/210368404-216273fb-c930-453e-b32b-e3614872eba3.png" width="100%"/></a><br>

## **Configurações**
O código abaixo adiciona informações de copyright ao rodapé de uma página na plataforma Greatpages. Copie e cole no menu de configurações da página.

<br><a href="https://www.buymeacoffee.com/claitonllemes" target="_blank" rel="noopener noreferrer"><img src="https://user-images.githubusercontent.com/99222756/210372197-a1d41894-8acc-470b-ac38-2bd1ee0a4ed9.png" width="100%"/></a><br>

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
