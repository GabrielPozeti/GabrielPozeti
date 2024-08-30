## Olá, me chamo Gabriel Pozeti

<div>
  <a href="https://github.com/GabrielPozeti">
    <a href="https://github.com/anuraghazra/github-readme-stats">
      <img height=200 align="center" src="https://github-readme-stats.vercel.app/api?username=GabrielPozeti&theme=transparent" />
    </a>
    <a href="https://github.com/anuraghazra/convoychat">
      <img height=200 align="center" src="https://github-readme-stats.vercel.app/api/top-langs?username=GabrielPozeti&layout=compact&langs_count=8&card_width=320&theme=transparent" />
    </a>  
</div>
    
<div style="display: inline_block"><br>
  <img align="center" alt="Gabriel-Java" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-plain.svg">
  <img align="center" alt="Gabriel-HTML" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg">
  <img align="center" alt="Gabriel-CSS" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg">
  <img align="center" alt="Gabriel-C" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/c/c-original.svg">
</div>

##
    
<div> 
  <a href="https://www.instagram.com/gahpf/" target="_blank"><img src="https://img.shields.io/badge/-Instagram-%23E4405F?style=for-the-badge&logo=instagram&logoColor=white" target="_blank"></a>
  <a href = "mailto:gabrielpozeti@gmail.com" target="_blank"><img src="https://img.shields.io/badge/-Gmail-%23333?style=for-the-badge&logo=gmail&logoColor=white" target="_blank"></a>
  <a href="https://www.linkedin.com/in/gabriel-henrique-pozeti-de-faria-860129312/ target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a> 
</div>

- uses: Platane/snk@v3
  with:
    # github user name to read the contribution graph from (**required**)
    # using action context var `github.repository_owner` or specified user
    github_user_name: ${{ GabrielPozeti }}

    # list of files to generate.
    # one file per line. Each output can be customized with options as query string.
    #
    #  supported options:
    #  - palette:     A preset of color, one of [github, github-dark, github-light]
    #  - color_snake: Color of the snake
    #  - color_dots:  Coma separated list of dots color.
    #                 The first one is 0 contribution, then it goes from the low contribution to the highest.
    #                 Exactly 5 colors are expected.
    outputs: |
      dist/github-snake.svg
      dist/github-snake-dark.svg?palette=github-dark
      dist/ocean.gif?color_snake=orange&color_dots=#bfd6f6,#8dbdff,#64a1f4,#4b91f1,#3c7dd9
