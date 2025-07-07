<!-- # Correções -->
# <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Hammer%20and%20Wrench.png" alt="Hotfixes" width="45px"> Correções
[Retornar para a pasta Meu GitHub](../)

| **Hotfix** | **Explicação** | **Correção** |
|:-------:|:--------------:|:------------:|
| Imagens renderizadas gigantes nos READMEs dos cursos | Em 06/07/25, o GitHub gerou um bug ao renderizar meus READMEs. As imagens usadas como logos estavam com a marcação `<img src="..." width="auto" height="25">`. O GitHub parou de interpretar corretamente o `width="auto" height="25"`, fazendo com que as imagens aparecessem em tamanho gigante e bagunçassem toda a estrutura. | A correção encontrada foi trocar `width="auto" height="25"` por `style="height:25px; width:auto;"`. No entanto, não foi necessário aplicar essa correção em todos os READMEs, pois dois dias depois o problema foi corrigido automaticamente pelo GitHub. O registro permanece para referência futura. |
