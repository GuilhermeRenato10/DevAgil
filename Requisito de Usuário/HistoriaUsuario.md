# 1. História de Usuário

A Tabela 3 a seguir contém as Histórias de Usuárias elicitadas. 

<table>
    <thead>
        <tr style="background-color: purple; color: white" >
            <th style="border-style:solid;border-width:1px;text-align:center">ID</th>
            <th style="border-style:solid;border-width:1px;text-align:center">História de Usuário</th>
            <th style="border-style:solid;border-width:1px;text-align:center">Critérios de aceitação</th>
            <th style="border-style:solid;border-width:1px;text-align:center">Prioridade</th>
            <th style="border-style:solid;border-width:1px;text-align:center">RF/RNF relacionado</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <span id="ustory-01"></span>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">US01</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Como usuario, quero poder criar uma conta no sistema com meu nome, e-mail e senha, para que eu possa acessar o sistema</td>
              <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1"><ol><li>O usuário deve preencher os campos de Nome, E-mail e Senha.</li><li> O sistema deve validar se o e-mail informado já está registrado.</li><li>O sistema deve confirmar a criação da conta com uma mensagem de sucesso.</li></ol></td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Alta</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RF01</td>
        </tr>
        <tr>
            <span id="ustory-01"></span>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">US02</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Como usuario, quero poder fazer login no sistema com meu e-mail e senha, para que eu possa acessar meu time fictício</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1"><ol><li>O sistema deve permitir login com e-mail e senha.</li><li>O sistema deve exibir uma mensagem de erro caso os dados estejam incorretos.</li><li>O sistema deve redirecionar o usuário para a página principal após login bem-sucedido.</li></ol></td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle"> Alta </td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RF02</td>
        </tr>
        <tr>
            <span id="ustory-01"></span>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">US03</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Como usuario, quero poder criar um time fictício com jogadores reais, para que eu possa gerenciar meu time e competir com outros usuários</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1"><ol><li>O usuário deve selecionar jogadores de uma lista com base em jogadores reais.</li><li>O sistema deve permitir ao usuário salvar e nomear o time fictício.</li><li>O sistema deve exibir a lista de jogadores disponíveis e informações básicas sobre eles (nome, posição, time real, etc.).</li></ol></td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Alta</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RF03</td>
        </tr>
        <tr>
            <span id="ustory-01"></span>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">US04</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Como usuario, quero poder selecionar 11 jogadores para o time titular e para o banco de reservas, para que meu time esteja pronto para participar das ligas e competições</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1"><ol><li>O sistema deve permitir a seleção de 11 jogadores para o time titular e 5 para o banco de reservas.</li><li>O sistema deve validar se o número de jogadores não excede os limites estabelecidos.</li><li>O sistema deve permitir a alteração da formação a qualquer momento, dentro das regras do sistema.</li><li>O usuário deve poder visualizar os jogadores já selecionados e suas posições.</li></ol></td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Alta</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RF04</td>
        </tr>
        <tr>
            <span id="ustory-01"></span>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">US05</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Como usuario, quero poder criar ou participar de uma liga, para que eu posso competir com outros usuários e comparar o desempenho do meu time</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1"><ol><li>O sistema deve permitir a criação de uma liga privada ou pública.</li><li>O sistema deve permitir que o usuário se inscreva em ligas existentes.</li><li>O sistema deve exibir a lista de ligas disponíveis para participação.</li></ol></td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Alta</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RF05</td>
        </tr>
        <tr>
            <span id="ustory-01"></span>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">US06</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Como usuario, quero que o sistema calcule automaticamente a pontuação do meu time com base no desempenho dos jogadores, para que eu possa acompanhar o desempenho do meu time de acordo com os jogos reais.</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1"><ol><li>O sistema deve calcular a pontuação do time com base no desempenho dos jogadores em jogos reais.</li><li>A pontuação deve refletir as ações do jogador (gols, assistências, cartões, etc.) com base nas regras do sistema.</li></ol></td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Alta</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RF06</td>
        </tr>
        <tr>
            <span id="ustory-01"></span>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">US07</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Como usuário, quero visualizar a pontuação total do meu time e um ranking atualizado após cada rodada, para que eu possa acompanhar o desempenho do meu time e competir com outros usuários.</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1"><ol><li>O sistema deve exibir a pontuação total do time na página principal do usuário.</li><li>O sistema deve exibir um ranking geral das ligas e competições, com a posição do time do usuário.</li<li></ol></td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Média</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RF07</td>
        </tr>
</table>

<div style="text-align: center">
<p>Tabela 3: História de Usuário</p>
</div>
