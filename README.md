## GreatPages-Automatic-Copyright


<sub>código personalizado para criação de Copyright © para plataforma GreatPages.</sub>


```
<script>

// Name: Automatic Copyright for Greatpages. 
// Version: 1.0.0 
// Copyright: Claiton Lemes | Alisson Acioli

        let prefix = "Copyright ©";
        let sufix = "Sua Empresa - Todos os Direitos Reservados.";
        let cnpj = "CNPJ: 00.000.000/0000-00";
        let email = "e-mail - contato@suaempresa.com.br";
        let endereço = "Seu Endereço";
        let desenvolvedor = "- Desenvolvido por - <a href='https://www.empresadodesenvolvedor.com.br' target='_blank'> Nome do Desenvolvedor </a>"; // Backlink desenvolvedor
        let elemento = document.querySelector("#ID_ELEMENTO"); // Inspecionar elemento > botão direito > Copy > Copy Selector
        let ano = new Date().getFullYear();
        let espaço = " ";
        elemento.innerHTML = prefix + espaço + ano + espaço + sufix + espaço + cnpj + espaço + email + espaço + endereço + espaço + desenvolvedor;

</script>

```
