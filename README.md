# M4_NBA

<h1>Script de Consulta</h1>
<li>
<ul>Qual equipe que ganhou mais partidas na temporada 2020? </ul>
<p>SELECT * FROM vinte ORDER BY W ASC LIMIT 1;</p>
<ul>Qual equipe que perdeu mais partidas na temporada 2020? </ul>
<p>SELECT * FROM vinte ORDER BY L ASC LIMIT 1;</p>
<ul>Quais times fizeram menos pontos em 2020?</ul>
<p>SELECT * FROM `vinte` ORDER BY G DESC;</p>
<ul>Quais times fizeram mais pontos na temporada de 2020?</ul>
<p>SELECT * FROM `vinte` ORDER BY G ASC;</p>
<ul>Quantas partidas aconteceram na temporada de 2020?</ul>
<p>select count(SEASON_ID) from vinte;</p>
<ul>Quantas partidas o time Milwaukee fez em 2020? </ul>
<p>select count(SEASON_ID) from vinte where TEAM = 'Milwaukee';</p>
</li>
