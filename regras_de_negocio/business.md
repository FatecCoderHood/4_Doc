# Regras de Negócios para o Projeto de Gestão de Fazendas

Descrição
Este projeto visa desenvolver um sistema de gestão de áreas georreferenciadas, possibilitando a captura, edição e análise de dados geoespaciais para otimizar o controle de propriedades agrícolas e seu desempenho.



## Como um administrador, eu quero cadastrar novos usuários no sistema, informando dados como nome, e-mail e tipo de acesso, para que eu possa garantir que apenas pessoas autorizadas possam utilizá-lo.

Critérios de aceitação:

O sistema deve permitir o cadastro de novos usuários com nome, e-mail e tipo de acesso.

O tipo de acesso deve ser restrito a funções específicas (administrador, consultor, analista).

## Como um administrador, eu quero editar informações de usuários, permitindo a atualização de dados cadastrais e permissões, para que eu possa manter o controle correto dos acessos.

Critérios de aceitação:

O sistema deve permitir a edição de informações como nome, e-mail e permissões de acesso.

O sistema deve refletir as alterações imediatamente após a atualização.

## Como um administrador, eu quero excluir usuários do sistema, removendo seu acesso permanentemente, para que eu possa garantir a segurança e evitar acessos indevidos.

Critérios de aceitação:

O sistema deve permitir a exclusão de usuários de forma irreversível.

O sistema deve gerar um log de auditoria quando a exclusão ocorrer.

## Como um administrador, eu quero definir diferentes níveis de permissão para cada tipo de usuário, para que eu possa atribuir funções específicas e restringir acessos, garantindo a segurança e organização do sistema.

Critérios de aceitação:

O sistema deve permitir a atribuição de permissões específicas por tipo de usuário.

As permissões devem ser claramente definidas para diferentes funcionalidades no sistema (visualização, edição, etc.).

## Como um administrador, eu quero visualizar um painel de métricas contendo estatísticas de acesso e uso do sistema, para que eu possa monitorar e tomar decisões informadas.

Critérios de aceitação:

O sistema deve exibir métricas como número de usuários ativos, funcionalidades mais utilizadas e eventos críticos.

As métricas devem ser atualizadas em tempo real e disponibilizadas de forma gráfica e intuitiva.

## Como um consultor, eu quero cadastrar novas áreas no sistema, informando atributos como nome, localização, tamanho, cultura plantada e produtividade esperada, para que eu possa manter o banco de dados atualizado.

Critérios de aceitação:

O sistema deve permitir o cadastro das áreas com os atributos mencionados.

Eu devo poder editar ou excluir as áreas cadastradas.

## Como um consultor, eu quero importar arquivos no formato .geojson contendo informações geográficas das áreas, para que eu possa automatizar o cadastro de áreas georreferenciadas, tornando o processo mais rápido e preciso.

Critérios de aceitação:

O sistema deve permitir o upload de arquivos .geojson.

O sistema deve processar as informações contidas no arquivo e registrar os dados corretamente.

## Como um consultor, eu quero visualizar gráficos e métricas detalhadas sobre as áreas cadastradas, para que eu possa acompanhar a produtividade ao longo do tempo e tomar decisões estratégicas.

Critérios de aceitação:

O sistema deve exibir gráficos sobre a produtividade, variações climáticas e outros dados relevantes.

Eu devo poder filtrar as métricas por tipo de cultura, período e outros critérios.

## Como um analista, eu quero visualizar áreas cadastradas como uma lista de fotogrametria e "dar assign", para que eu possa organizar as áreas de acordo com os dados geoespaciais e realizar as análises adequadas.

Critérios de aceitação:

O sistema deve exibir uma lista de áreas georreferenciadas no formato de fotogrametria.

Eu devo poder atribuir cada área a uma análise ou tarefa específica.

## Como um analista, eu quero aprovar ou rejeitar áreas cadastradas no sistema, para que eu possa garantir que apenas dados validados sejam utilizados nas análises.

Critérios de aceitação:

O sistema deve permitir a aprovação ou rejeição das áreas com base na revisão dos dados cadastrados.

O histórico de aprovação deve ser registrado.

## Como um analista, eu quero visualizar no mapa os talhões agrícolas cadastrados, com informações sobre limites, área total, cultura plantada e status de produção, para que eu possa compreender melhor sua distribuição espacial e facilitar a análise territorial.

Critérios de aceitação:

O sistema deve exibir os talhões no mapa com os atributos necessários (limites, área, cultura, status).

Eu devo poder aplicar filtros e realizar zoom no mapa.

## Como um analista, eu quero modificar informações das áreas, como tipo de cultura, produtividade estimada e características do solo, para que eu possa manter os dados atualizados e garantir maior precisão nas análises agrícolas.

Critérios de aceitação:

O sistema deve permitir a edição dos dados das áreas conforme necessário.

As edições devem ser registradas no histórico da área.

## Como um analista, eu quero editar e ajustar os polígonos das áreas no mapa, para que eu possa corrigir sobreposições, modificar vértices e redefinir limites, garantindo a precisão dos dados geoespaciais.

Critérios de aceitação:

O sistema deve permitir a edição das geometrias diretamente no mapa.

As alterações devem ser salvas de forma permanente e registradas no histórico.

## Como um analista, eu quero visualizar camadas de dados sobre os talhões no mapa, como tipo de solo, índices climáticos e produtividade histórica, para que eu possa realizar uma análise mais completa das áreas agrícolas.

Critérios de aceitação:

O sistema deve permitir a sobreposição de diferentes camadas de dados no mapa.

Eu devo poder visualizar essas camadas de forma clara e interativa.

## Como um analista, eu quero acessar um histórico de edições realizadas nas áreas cadastradas, para que eu possa entender as mudanças ao longo do tempo e manter um controle de auditoria das informações.

Critérios de aceitação:

O sistema deve registrar e exibir um histórico detalhado de todas as edições realizadas nas áreas.

Eu devo poder consultar e filtrar as edições por data, tipo de modificação e usuário responsável.

