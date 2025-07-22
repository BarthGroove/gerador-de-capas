Gerador de Capas para YouTube
Este é um projeto de uma ferramenta web front-end, criada em HTML, CSS (com Tailwind CSS) e JavaScript puro, para facilitar a criação de thumbnails (capas) personalizadas para vídeos do YouTube.

A aplicação permite a manipulação de imagens e textos em tempo real diretamente no navegador, oferecendo uma alternativa rápida e gratuita a softwares de edição de imagem mais complexos.

✨ Funcionalidades Principais
Busca de Imagens via API: Integre sua chave da API do Pexels para buscar e usar milhões de fotos de alta qualidade como imagem de fundo sem sair da ferramenta.

Upload Local: Envie imagens do seu próprio computador para usar como fundo ou como um elemento destacado (foreground).

Controle Total de Textos:

Adicione um texto principal e um secundário.

Ajuste a fonte, cor, tamanho e posição (horizontal e vertical) de cada texto de forma independente.

Manipulação de Imagem Destacada:

Controle o tamanho (escala) da imagem sobreposta.

Posicione a imagem livremente no canvas.

Filtros de Imagem de Fundo:

Ajuste o brilho, contraste e saturação da imagem de fundo para garantir que seus textos tenham o máximo de destaque.

Download Instantâneo: Baixe sua capa finalizada como um arquivo .png de alta resolução (1280x720), pronto para ser usado no YouTube.

🚀 Como Usar a Ferramenta
A ferramenta é um único arquivo HTML auto-contido. Para usá-la, siga os passos:

Salve o Código: Copie todo o código do arquivo gerador_de_capas.html.

Crie o Arquivo: Cole o código em um editor de texto (como Bloco de Notas, VS Code, etc.) e salve o arquivo com a extensão .html (ex: gerador.html).

Abra no Navegador: Dê um duplo-clique no arquivo salvo. Ele será aberto no seu navegador padrão.

Para usar a busca de imagens:
Obtenha uma API Key: Crie uma conta gratuita no site Pexels e obtenha sua chave da API.

Cole a Chave: No painel de controle da ferramenta, cole a chave no campo "Sua Chave da API (Pexels)".

Busque e Clique: Digite o que deseja procurar, clique em "Buscar" e, em seguida, clique na imagem desejada para defini-la como fundo.

⚠️ Limitações Conhecidas
Sem Salvamento de Projetos: A ferramenta não armazena seu trabalho. Se a página for fechada ou atualizada, o progresso será perdido.

Remoção de Fundo: A funcionalidade de remover o fundo de imagens está temporariamente desativada devido a restrições de segurança dos navegadores (CORS) que impedem a conexão direta com as APIs.

Fontes Pré-definidas: Apenas as fontes carregadas do Google Fonts no código estão disponíveis.

Este projeto foi desenvolvido com o objetivo de ser uma ferramenta prática e poderosa para criadores de conteúdo. Sinta-se à vontade para usá-lo e modificá-lo conforme suas necessidades!