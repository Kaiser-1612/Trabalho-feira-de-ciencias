<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
        <h1>Cadastro de função</h1>
<form>
<p><label for="iTitulodafuncao" >Titulo da função:</label>
    <input type="text" id="iTitulodafuncao" name="Titulodafuncao">  </p>
<p><label for="iCBO" >CBO (Classificação Brasileira de Ocupações):</label>
    <input type="text" id="iCBO" name="CBO"> </p>
<p><label for="iTrabalhoqueregeaprofissão"> Trabalho que rege a profissão:</label>
    <input type="text" id="iTrabalhoqueregeaprofissão" name="Trabalhoqueregeaprofissão"> </p>
<p><label for="iDepartamento/Setor" >Departamento/Setor:</label>
    <input type="text" id="iDepartamento/Setor" name="Departamento/Setor"> </p>
<p><label for="iFormaçãoacadêmica" >Formação acadêmica:</label>
    <input type="text" id="iFormaçãoacadêmica" name="Formaçãoacadêmica"> </p>
<p><label for="iExperiênciaprévia" >Experiência prévia:</label>
    <input type="text" id="iExperiênciaprévia" name="Experiênciaprévia"> </p>    
<p><label for="iCompetênciastécnicas" >Competências técnicas (Hard Skills):</label>
    <input type="text" id="iCompetênciastécnicas" name="Competênciastécnicas"> </p>   
<p><label for="iCompetênciascomportamentais" >Competências comportamentais (Soft Skills)
    <input type="text" id="iCompetênciascomportamentais" name="Competênciascomportamentais"> </p></label>
<p><label for="iJornadadetrabalho" >Jornada de trabalho:</label>
    <input type="text" id="iJornadadetrabalho" name="Jornadadetrabalho"> </p>
  
    <p><input type="submit" value="Enviar"></p>
    
    <script>
    url = "<script>
    url = "https://script.google.com/macros/s/AKfycbwul7BTzOSrvIXCPOBpAN1QuV8OzcHNVWMNcGyiHnxCA5gU8WDdGCCu3nuf-zgLHj-0/exec"; 

    document.getElementById('meuFormulario').addEventListener('submit', function(e) {
      e.preventDefault();

      fetch(URL_WEB_APP, {
        method: 'POST',
        body: new FormData(this)
      })
      .then(() => {
        alert('Enviado!');
        this.reset(); 
      });
    });

    
  </script>


</body>
</html>
