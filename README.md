 ### Olá eu me chamo Sara Tascheck

- 🎓Estudo : Analise e Desenvolvimento de SoftWear
- ✨Pronomes: Ela/Dela

[Me chamo Sara tenho 19 anos e estudo Analise e Desenvolvimento na Unisociesc]

<div style="display: inline_block"><br>
 <img align="center" alt="Rafa-Js" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-plain.svg">
 <img align="center" alt="Rafa-Python" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg">
</div>

 ##

<div>
 <a href="https://www.instagram.com/sara_tascheck/" target="_blank"><img src="https://img.shields.io/badge/-Instagram-%23E4405F?style=for-the-badge&logo=instagram&logoColor=white" target="_blank"></a>
 <a href="https://www.linkedin.com/in/sara-tascheck-708aa722a/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a> 
</div>

##

Nome: General Data 

em: 
 cronograma: # executar a cada 12 horas
   - cron : " * */12 * * * "
 workflow_dispatch :

trabalhos : 
 construir : 
  nome : Jobs para atualizar dados
  run-on : ubuntu-latest
  passos : 
   # Animação de Cobra
   - usa : Platane/snk@master
    id : cobra-gif
    com:
      github_user_name : SaraTaschcek
      svg_out_path : dist/github-contribution-grid-snake.svg

   - usa : crazy-max/ghaction-github-page@v2.1.3
     com :
      target_brach : saída
      build_dir : dist
     ambiente :
      GITHUB_TOKEN : $ {{ segredos.GITHUB_TOKEN }}











       


