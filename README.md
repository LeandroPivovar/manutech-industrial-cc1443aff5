# Manutech Industrial

Site estático com arquivos públicos em `dist/`, sem dependências, banco ou etapa de build. Servir essa pasta em um servidor estático. Imagens e Switzer estão locais; a hero utiliza Georgia como fonte de sistema.

## Conteúdo e direção

Hero baseada no print Elegance fornecido: fotografia de fundo integral, cabeçalho sobreposto, título serifado com destaque itálico laranja, dois contatos de navegação e painel inferior com informações reais. Sem copiar marca, fotografia, textos ou números da empresa de referência. Corpo com sobre, serviços, galeria filtrável, orientação para consulta, contato, FAQ e mapa.

Dados fornecidos: Manutech Industrial; manutenção e automação industrial; Balneário Piçarras/SC; posicionamento “Sua empresa, nosso compromisso”. WhatsApp confirmado pelo usuário: (47) 99218-5521. Horário 08–18 no print sem dias confirmados não foi generalizado. Sem endereço comercial: mapa da cidade como referência de atendimento, sem apontar sede.

Não foram inventados anos, clientes, avaliações, preços, certificações, especialidades adicionais ou garantias de prazo. Nome apresentado de forma tipográfica até haver logotipo original. Fotografias são ilustrativas de contexto técnico; fontes, autores e licenças em [créditos](dist/assets/credits.md).

## Funcionalidade e validação

Menu acessível por teclado/Escape; filtros de galeria; cinco FAQs; seleção de assunto a partir dos dois serviços; formulário prepara mensagem para revisão e envio pelo visitante no WhatsApp, sem armazenar os dados ou enviar automaticamente.

Testado no navegador em 360, 390, 768 e 1440 px: sem overflow horizontal, imagens/fontes/âncoras carregadas, títulos com até duas linhas, controles e destinos corretos. Doze recursos HTTP200, zero erros de console; preferência de redução de movimento aplicada. WhatsApp visível e sem colisão com textos/controles nos 82 pontos de rolagem verificados. Mapa renderiza Balneário Piçarras.

Taste: direção borrowed-category, seed 1592188606, sem novo sorteio; composição da hero e tipografia determinadas pelo print explícito. Revisão visual final 7,4/10: execução coesa da referência, ainda beneficiada por acervo e logotipo próprios. Inspector final: zero FAIL e dois WARN (escala com tamanhos responsivos e ausência de vídeo; busca retornou microscopia de papel, inadequada ao serviço). Fotos utilizadas: Yetkin Ağaç (fábrica) e Bulat843 (manutenção, painel e equipamento), licença Pexels. Nenhuma foto sorteada genérica usada.

## GitHub e hospedagem

Entrega por commit e push no repositório próprio. Configuração estática compatível com Vercel; deploy Git desativado e nenhum deploy executado nesta tarefa, seguindo a preferência expressa anteriormente. Metadados CRM e de revisão, arquivos de ambiente e credenciais ficam ignorados no Git e fora de `dist/`.
