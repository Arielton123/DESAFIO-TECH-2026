# EcoPonto --- Plataforma de Reciclagem e Descarte Consciente

## Objetivo

Criar uma plataforma web que ajude as pessoas a encontrar locais
adequados para entregar materiais recicláveis e descartar resíduos
corretamente. O projeto busca incentivar hábitos sustentáveis e
facilitar o acesso a informações sobre reciclagem.

## Tecnologias utilizadas

* **HTML5:** estrutura das páginas.
* **CSS3:** identidade visual, organização do conteúdo e adaptação
para celulares e computadores.
* **JavaScript:** interações, filtros e funcionalidades da plataforma.
* **Supabase:** autenticação e armazenamento dos dados, caso o projeto
utilize cadastro de usuários e registros compartilhados.
* **Leaflet:** exibição de mapas interativos.
* **OpenStreetMap:** dados cartográficos utilizados no mapa.
* **Git e GitHub:** controle de versão e hospedagem do código-fonte.

## Funcionalidades previstas

* **Página inicial:** apresentação do projeto e acesso às principais
áreas.
* **Mapa de pontos de coleta:** visualização dos locais cadastrados
para entrega de materiais.
* **Busca e filtros:** pesquisa por endereço, bairro ou tipo de
material aceito.
* **Detalhes dos locais:** endereço, materiais recebidos, horários e
orientações de descarte.
* **Cadastro de pontos:** inclusão de novos locais por usuários
autorizados.
* **Sugestão de correções:** envio de informações sobre dados
incorretos ou locais desativados.
* **Área informativa:** orientações sobre separação de resíduos e
descarte consciente.

## Descrição da solução

O EcoPonto será uma plataforma web que reúne informações sobre locais de
coleta seletiva e descarte adequado de resíduos. A pessoa poderá
consultar um mapa, pesquisar pontos próximos de uma região informada e
verificar quais materiais cada local recebe.

Cada ponto de coleta terá uma página ou ficha com informações como
endereço, tipos de materiais aceitos, horários de funcionamento e
instruções importantes. A plataforma também poderá permitir que usuários
enviem sugestões de novos locais ou informem possíveis alterações nos
dados existentes.

A proposta é tornar a busca por pontos de reciclagem mais simples e
contribuir para a conscientização ambiental. As informações exibidas
deverão ser verificadas antes de serem tratadas como confirmadas,
evitando orientar os usuários para locais inexistentes ou que não
recebam determinado material.

## Etapas de desenvolvimento e commits

A sequência abaixo apresenta uma sugestão de evolução do projeto.
Execute cada commit depois de concluir a etapa correspondente.

### 1\. Estrutura inicial

Criação dos arquivos principais e organização das pastas.

``` bash
git add .
git commit -m "chore: cria estrutura inicial do EcoPonto"
```

### 2\. Interface da plataforma

Desenvolvimento da página inicial, navegação e layout responsivo.

``` bash
git add .
git commit -m "feat: cria interface inicial e navegacao"
```

### 3\. Mapa e pesquisa

Adição do mapa interativo e dos filtros para localizar pontos de coleta.

``` bash
git add .
git commit -m "feat: adiciona mapa e busca de pontos de coleta"
```

### 4\. Informações e documentação

Inclusão das fichas dos locais, orientações de descarte e documentação
do projeto.

``` bash
git add .
git commit -m "docs: documenta funcionalidades e objetivo do projeto"
```

> \*\*Importante:\*\* esses comandos são exemplos de mensagens para commits
> futuros. Eles não registram alterações automaticamente. Para criar
> pelo menos três commits reais, conclua e salve uma etapa, execute
> `git add` e `git commit`, e só então passe à etapa seguinte.

## Observação

O mapa pode utilizar dados do OpenStreetMap por meio do Leaflet. Os
pontos de coleta precisam ser cadastrados e verificados pelo projeto; a
biblioteca de mapas, por si só, não fornece uma lista garantida de
locais de reciclagem.

