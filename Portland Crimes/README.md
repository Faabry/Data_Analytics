<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
<<<<<<< HEAD
  <H1 align="center"> Data Analysis </H1>
  <h2> Ciclo de Vida Ciência de Dados </h2>
  <ul>
      <li><img src="https://user-images.githubusercontent.com/110841289/213749996-ee7a4a6c-9fbc-4c29-86ba-b758ead5f0f9.jpeg" align="right" width=300 heigth=300></li>
    <li> Entender o Problema </li>
    <li> Coletar os Dados </li>
    <li> Processar os Dados </li>
    <li> Exploração dos Dados </li>
    <li> Comunicar os Resultados </li>
    <li> Feedback </li>
  </ul>
  <br>
  <br>
  <br>
  <h2> Tipos de Dados </h2>
  <ol>
    <li> Em relação aos tipos de armazenamentos os dados podem ser <strong>numéricos ou categóricos</strong></li>
    <br>
      <ul>
          <li> <b>Dados Qualitativos</b> </li>
          <ul>
              <li>Nominal: Profissão, Sexo, Religião</li>
              <li>Ordinal: Dados que tem uma hierarquia como por exemplo escolaridade.</li>
          </ul>
          <li> <b>Dados Quantitativos</b> </li>
          <ul>
              <li>Discreta: Dados numéricos de valores <i>inteiros</i> como por exemplo nº de filhos</li>
              <li>Contínua: Dados numéricos de valores <i>decimais</i> como por exemplo altura, peso etc.</li>
          </ul>
      </ul>
      <br>
    <li> Em relação à fonte de dados eles podem ser <strong>primários ou secundários</strong></li>
    <br>
      <ul>
          <li> <b>Dados Primários</b> </li>
            <ul>
                <li>São dados próprios, geralmente são gerados dentro da própria empresa, podem facilmente ser manipulados pelo analista de dados.</li>
            </ul>
          <li> <b>Dados Secundários</b> </li>
          <ul>
              <li>Não são dados próprios, geralmente são fornecidos por terceiros ou em alguns casos alguma parceria de troca de informações, esse tipo de dado não é de domínio público</li>
          </ul>
          <li> <b>Dados Terciários </b> </li>
              <ul>
                  <li> Assim como os dados secundários, os dados terciário são fornecidos por terceiros, a única diferença é que eles são de domínio público.</li>
          </ul>
      </ul>
      <br>
    <li> Em relação à linguagem de programação eles podem ser <strong>primitivos ou não primitivos</strong></li>
      <br>
      <ul>
          <li> <b>Dados Primitivos</b> </li>
            <ul>
                <li>Dados do tipo <i>int, str, float, booelan</i> </li>
            </ul>
          <li> <b>Dados não Primitivos</b> </li>
            <ul>
                <li>Dados do tipo <i>list, tuple, dict</i> </li>
             </ul>
      </ul>
      <br>
    <li> Independente dos itens anteriores os dados podem ser <strong>estruturados, semi estruturados ou não estruturados</strong></li>
    <br>
      <ul>
          <li> <b>Dados Estruturados</b> </li>
          <ul>
              <li>São dados que seguem uma classificação e lógica formal, geralmente são dados em formatos tabulares como em bancos de dados relacionais ou planilhas do Excel. </li>
          </ul>
          <li> <b>Dados Semi Estruturados</b> </li>
          <ul>
              <li>São dados sem uma devida organização, no entanto já estão classificados de alguma forma, portanto a compreensão de como os dados estão separados é mais fácil, mas ainda sim algum trabalho de estruturação será necessária. Alguns exemplos de dados semi estruturados são arquivos no formato XML, JSON.</li>
          </ul>
          <li> <b>Dados Não Estruturados</b> </li>
          <ul>
              <li>Dados não estruturados são informações que não possuem um formato fixo ou organização pré-definida, tornando-se mais difíceis de serem processados e analisados de maneira convencional.</li>
          </ul>
      </ul>
  </ol>
  <br>
=======
  <h1 align="center">Portland Crimes Analysis</h1>
    <img src="img/crime.jpeg" height=400px width=900px>
  <h1>Column Info:</h1>
  <ul>
    <li><b>Address:</b> Address of reported incident at the 100 block level (e.g.: 1111 SW 2nd Ave would be 1100 Block SW 2nd Ave).</li>
    <br>
    <li><b>Case Number:</b> The case year and number for the reported incident (YY-######).</li>
    <br>
    <li><b>Crime Against:</b> Crime against category (Person, Property, or Society).</li>
    <br>
    <li><b>Neighborhood: </b>Neighborhood where incident occurred. If the neighborhood name is missing, the incident occurred outside of the boundaries of the Portland neighborhoods or at a location that could not be assigned to a specific address in the system. (e.g., Portland, near Washington Park, on the streetcar, etc.).</li>
    <br>
    <li><b>Occur Date: </b>Date the incident occurred. The exact occur date is sometimes unknown. In most situations, the first possible date the crime could have occurred is used as the occur date. (For example, victims return home from a week-long vacation to find their home burglarized. The burglary could have occurred at any point during the week. The first date of their vacation would be listed as the occur date.)
</li>
      <br>
    <li><b>Occur Time: </b>Time the incident occurred. The exact occur time is sometimes unknown. In most situations, the first possible time the crime could have occurred is used as the occur time. The time is reported in the 24-hour clock format, with the first two digits representing hour (ranges from 00 to 23) and the second two digits representing minutes (ranges from 00 to 59).
</li>
    <br>
    <li><b>Offense Category: </b>Category of offense (for example, Assault Offenses).</li>
    <br>
    <li><b>Offense Type: </b>Type of offense (for example, Aggravated Assault).
Note: The statistic for Homicide Offenses has been updated in the Group A Crimes report to align with the 2019 FBI NIBRS definitions. The statistic for Homicide Offenses includes (09A) Murder & Non-negligent Manslaughter and (09B) Negligent Manslaughter. As of January 1, 2019, the FBI expanded the definition of negligent manslaughter to include traffic fatalities that result in an arrest for driving under the influence, distracted driving, or reckless driving. The change in definition impacts the 2019 homicide offenses statistic and the comparability of 2019 homicide statistics to prior year.
</li>
    <br>
    <li><b>Open Data Lat/Lon: </b>Generalized Latitude / Longitude of the reported incident. For offenses that occurred at a specific address, the point is mapped to the block's midpoint. Offenses that occurred at an intersection is mapped to the intersection centroid.
</li>
      <br>
      <li><b>Open Data X/Y: </b>Generalized XY point of the reported incident. For offenses that occurred at a specific address, the point is mapped to the block's midpoint. Offenses that occurred at an intersection is mapped to the intersection centroid. To protect the identity of victims and other privacy concerns, the points of certain case types are not released. XY points use the Oregon State Plane North (3601), NAD83 HARN, US International Feet coordinate system.
</li>
    <br>
    <li><b>Offense Count: </b>Number of offenses per incident. Offenses (i.e. this field) are summed for counting purposes.</li>  
</ul>
>>>>>>> ca98e587d9e8a12e54438051ee3bf0c5658079a0
  <h3> OBS: </h3>
    <ul>
        <li> <b>Não existe análise de Dados Não Estruturados</b>, os dados devem ser pré processados para que se tornem esruturados antes de qualquer análise.</li>
    </ul>
  <h1> Sobre mim: </h1>
  <a href="https://www.linkedin.com/in/airton-f-225784255/">
  <img src="https://user-images.githubusercontent.com/110841289/224358942-846f52a8-6945-49ca-8aa7-6719b2f1c603.png">
  </a>
  <a href="https://www.instagram.com/faa_bry/">
  <img src="https://user-images.githubusercontent.com/110841289/224359564-da97e372-92b5-4229-9d73-eee2779e16c4.png">
  </a>
</body>
</html>




