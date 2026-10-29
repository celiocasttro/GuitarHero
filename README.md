# Rock Hero

Jogo de ritmo original para iPhone, inspirado no estilo de jogos de notas musicais. Projeto independente do DRAMOVIX.

## Jogar
Abra `index.html` em um navegador moderno. No iPhone, use os cinco botões coloridos na tela.

## Gerar IPA
O GitHub Actions executa a compilação iOS em um runner macOS e publica um artefato `RockHero-unsigned-IPA` na aba **Actions** quando o workflow termina.

1. Abra **Actions** no repositório.
2. Selecione **Build iOS IPA** e abra a execução mais recente.
3. Baixe o artefato **RockHero-unsigned-IPA**.

O arquivo é um IPA **sem assinatura**. A instalação pode exigir assinatura no dispositivo com uma ferramenta compatível, como SideStore. O workflow não usa músicas, imagens ou outros assets proprietários do Guitar Hero.

## Observação
A primeira execução instala as dependências e cria o projeto nativo iOS. Se a compilação falhar, consulte o log do job em Actions para ver o erro exato.