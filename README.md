# M4_NBA

<h1>Script de Consulta</h1>

<li>Qual equipe que ganhou mais partidas na temporada 2020? </li>
<ul>SELECT * FROM vinte ORDER BY W ASC LIMIT 1;</ul>
<li>Qual equipe que perdeu mais partidas na temporada 2020? </li>
<ul>SELECT * FROM vinte ORDER BY L ASC LIMIT 1;</ul>
<li>Quais times fizeram menos pontos em 2020?</li>
<ul>SELECT * FROM `vinte` ORDER BY G DESC;</ul>
<li>Quais times fizeram mais pontos na temporada de 2020?</li>
<ul>SELECT * FROM `vinte` ORDER BY G ASC;</ul>
<li>Quantas partidas aconteceram na temporada de 2020?</li>
<ul>select count(SEASON_ID) from vinte;</ul>
<li>Quantas partidas o time Milwaukee fez em 2020? </li>
<ul>select count(SEASON_ID) from vinte where TEAM = 'Milwaukee';</ul>
