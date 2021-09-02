# Novo conteúdo
Passo a passo geral:
- Abre o Github
- No github usa `Repository -> Open in External Editor`
- Vai abrir o vscode
- No VScode abre um terminal em `Terminal -> New Terminal` (ou usa um já aberto)
- Pra adicionar um novo post, usa no terminal:
```
.\hugo new timeline/<post_name>.md
```
ps: troca o `<post_name>` pelo nome que você quiser
- Vai criar um documento novo na pasta `content/timeline`
- Abre esse documento e edita ele colocando o que você quiser
- Não esquece de mudar o título (`title`) e se você quer publicar ou não usando o `draft`
  - `draft: false` -> aparece no site
  - `draft: true` -> não aparece no site
- Precisa colocar uma imagem?
  - move ela pra a pasta `static/img`
  - usa um dos métodos de inserir imagem colocando o caminho pra ela usando `/img/<nomedoarquivo>.<extensao>`
- Terminou de fazer o que tava fazendo e quer colocar na núvem?
- Vai pra a janela do Github
- Ele deve atualizar com as suas mudanças mostrando em vermelho o que tinha e verde o que você mudou
- Antes de tudo aperta o "Fetch origin" ali em cima pra pegar as mudanças da nuvem
- Revisa tudo, garante que tudo que você fez tá lá mesmo (as vezes vc pode ter esquecido de salvar)
- Revisado, aperta o botão azul "Commit to master" (as vezes vc pode ter que colocar um "Summary")
- Vai aparecer o botão "Push origin" pra você subir as suas coisas na nuvem
- Em uns 2 min deve estar live no site automagicamente