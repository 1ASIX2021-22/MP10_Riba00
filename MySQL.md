Instalacio mysql per a php i laravel




<b>1- </b>Primer que tot, instal·lar el servidor mysql, amb la següent comanda.


![Selecció_556](https://user-images.githubusercontent.com/91245889/162403647-c48cdc15-975a-4ab1-b83b-12bf4eb88c52.png)

<b>2- </b>Ens dona error de permisos i anem a solucionar-ho.


![Selecció_557](https://user-images.githubusercontent.com/91245889/162404259-1173bf20-52b3-4a0c-96a5-0d54ebda3d39.png)


<b>3- </b>El fitxer debian.conf ens mostra un usuari i una contrasenya per defecte.


![Selecció_558](https://user-images.githubusercontent.com/91245889/162404264-1c7741f4-168c-4413-bf57-72f71b476141.png)

<b>4- </b>Introduim l'usuari i la contrasenya per a veure si tenim permisos i ja estariem dintre.

![Selecció_559](https://user-images.githubusercontent.com/91245889/162404280-6a20dda6-e581-4c94-a7df-ab1594c9c615.png)


<b>5- </b>Un cop dintre, creem una base de dades.

![Selecció_560](https://user-images.githubusercontent.com/91245889/162404308-116a015c-ec02-4f45-b85c-d241a2ef429f.png)


<b>6- </b>Comprovem que s'ha creat correctament.


![Selecció_561](https://user-images.githubusercontent.com/91245889/162404326-1f31c0f1-77c2-4a1e-935c-97bb7b02fbbe.png)

<b>7- </b>Seleccionem la base de dades creada.


![Selecció_562](https://user-images.githubusercontent.com/91245889/162404344-8e071ed5-7e83-4bd1-9e72-eb2b0adb5af0.png)

<b>8- </b> Per a crear una taula hem d'introduir el nom i entre parèntesis els camps amb el seu corresponent tipus.

![Selecció_563](https://user-images.githubusercontent.com/91245889/162404382-7ab574c4-1602-49a8-a0c8-6e84747d3957.png)

<b>9- </b>Ja tindriem creada la taula.


![Selecció_564](https://user-images.githubusercontent.com/91245889/162404406-76f447a4-82f1-431d-bf87-f6bb8af514c5.png)

<b>10- </b>El pas següent és descarregar el mysql Workbench.

![Selecció_565](https://user-images.githubusercontent.com/91245889/163164029-7453ad51-f6db-4c95-9b35-6342c6e826ee.png)


<b>11- </b>Per a poder instalar-lo necessitem aquests dos fitxers.

![Selecció_566](https://user-images.githubusercontent.com/91245889/163164240-99ea1f6e-b47b-4442-aa5d-e03b7a814d9e.png)




<b>12- </b>Comprovem que s'han baixat correctament.

![Selecció_567](https://user-images.githubusercontent.com/91245889/162404491-7640c694-5eca-478d-9759-a56a09a0ecfa.png)


<b>13- </b>Instalem el primer paquet.

![Selecció_568](https://user-images.githubusercontent.com/91245889/162404526-bab34070-447b-4c5b-80a1-fd576c03a60c.png)


<b>14- </b>Després el segon paquet.

![Selecció_569](https://user-images.githubusercontent.com/91245889/162404535-f3fa5644-3444-4df6-b284-c8ab7a9dbbcf.png)


<b>15- </b>Podem comprovar que el MySQL Workbech s'ha instal·lat correctament, però no inicia ja que li falten dependències.

![Selecció_570](https://user-images.githubusercontent.com/91245889/162404547-fee4f15c-87d1-4944-bd91-0df87a63d2f2.png)

<b>16- </b>Amb la següent comanda podem veure els paquets de dependències que falten.


![Selecció_571](https://user-images.githubusercontent.com/91245889/162404566-6b91209c-ee7d-47b0-9702-f01cc2f0edd8.png)

<b>17- </b>Les instalem per al correcte funcionament del MySQL Workbench.


![Selecció_572](https://user-images.githubusercontent.com/91245889/162404574-bf883cfc-962d-47d2-9844-a34d6ca9570f.png)

<b>18- </b> També realitzarem aquest acomanda per a corregir temes de dependències.


![Selecció_573](https://user-images.githubusercontent.com/91245889/162404584-d4de4363-fa31-4081-b3dc-e44eff002881.png)

<b>19- </b>Un cop realitzats tots els passos anteriors i haver corregit els errors, ja hauriem de poder accedir al MySQL Workbench.

![Selecció_575](https://user-images.githubusercontent.com/91245889/162404626-758a74b6-85a2-4d24-b1a9-cfd467cea0c5.png)


<b>20- </b>Dintre del MySQL Workbench, de moment no tenim accés ja que hem de posar l'usuari i la contrasenya que hem vist anteriorment.

![Selecció_576](https://user-images.githubusercontent.com/91245889/162404642-d433b58b-e083-4a78-943e-c9e227b38089.png)


<b>22- </b>

![Selecció_577](https://user-images.githubusercontent.com/91245889/162404667-31c17f0d-cd37-4255-a314-75c474a5199b.png)


<b>23- </b>


![Selecció_578](https://user-images.githubusercontent.com/91245889/162404676-d98c0760-0ad4-4fbe-9631-18f15d19d888.png)

<b>24- </b>

![Selecció_579](https://user-images.githubusercontent.com/91245889/162404692-b84b3022-0dc7-4952-b6ef-3be9556e34d1.png)


<b>25- </b>

![Selecció_580](https://user-images.githubusercontent.com/91245889/162404764-d98bc84e-f3e8-4ea0-a83c-d914f7f12ae2.png)


<b>26- </b>

![Selecció_581](https://user-images.githubusercontent.com/91245889/162404783-952578c5-c15a-411a-8596-7047686f5fe8.png)


<b>27- </b>

![Selecció_582](https://user-images.githubusercontent.com/91245889/162404821-f4ede74b-51ce-4f44-8ea9-718d570e1534.png)


<b>28- </b>


![Selecció_583](https://user-images.githubusercontent.com/91245889/162404829-a45890f1-3de8-46c2-a25d-ec432c39418f.png)

<b>29- </b>

![Selecció_584](https://user-images.githubusercontent.com/91245889/162404875-f4ea4f54-c266-43d8-b3fc-f562ad219425.png)


<b>30- </b>

![Selecció_585](https://user-images.githubusercontent.com/91245889/162404891-0f3b3fbe-21ec-4256-9b5f-7f206b31413e.png)


<b>31- </b>

![Selecció_720](https://user-images.githubusercontent.com/91245889/162404925-cb4cfb4d-073e-4ecb-80aa-eed02a3deb15.png)


<b>32- </b>


![Selecció_721](https://user-images.githubusercontent.com/91245889/162404936-21687201-cb41-4ea3-9a54-71791553b674.png)

<b>33- </b>

![Selecció_722](https://user-images.githubusercontent.com/91245889/162404968-2c064f62-4a5b-408c-99d3-b9e9d3f736b1.png)


<b>34- </b>


![Selecció_723](https://user-images.githubusercontent.com/91245889/162404976-b517923f-f161-41fc-812f-5e358b69bf90.png)

<b>35- </b>

![Selecció_724](https://user-images.githubusercontent.com/91245889/162404997-0b191c70-33b6-43a4-91dd-ff67bb28710e.png)


<b>36- </b>
![Selecció_725](https://user-images.githubusercontent.com/91245889/162405017-25f4ff4e-7ba4-4e60-8623-708ab6265f60.png)

<b>37- </b>

![Selecció_726](https://user-images.githubusercontent.com/91245889/162405070-72566ff2-4325-40e5-8548-5b3c529bdcc1.png)


<b>38- </b>

![Selecció_727](https://user-images.githubusercontent.com/91245889/162405091-650215ff-e8f6-4580-a954-ce606c1dad2f.png)


<b>39- </b>


![Selecció_728](https://user-images.githubusercontent.com/91245889/162405105-d93cfbe7-facb-47a7-945a-e51f423a83dd.png)

<b>40- </b>

![Selecció_729](https://user-images.githubusercontent.com/91245889/162405115-4a5aeca1-4a2f-47d6-a38b-884decb86d1d.png)


<b>41- </b>


![Selecció_730](https://user-images.githubusercontent.com/91245889/162405127-ff1ccd5a-076e-40ac-9679-9d5e2218fd52.png)

<b>42- </b>

![Selecció_731](https://user-images.githubusercontent.com/91245889/162405134-a2559395-543d-4006-92ea-963f3efe90b0.png)


<b>43- </b>

![Selecció_732](https://user-images.githubusercontent.com/91245889/162405147-e152382b-dff6-475d-8b0b-63f6b7e633df.png)


<b>44- </b>

![Selecció_733](https://user-images.githubusercontent.com/91245889/162405181-f79dd88a-5aa9-4ed3-8540-cac6151a28c1.png)



<b>45- </b>

![Selecció_734](https://user-images.githubusercontent.com/91245889/162405217-8ccc1f21-cc3d-4de4-b84a-24383ffaf674.png)


<b>46- </b>

![Selecció_735](https://user-images.githubusercontent.com/91245889/162405228-2747b445-f167-467f-834e-62876bf03a3f.png)


<b>47- </b>

![Selecció_736](https://user-images.githubusercontent.com/91245889/162405240-91b32fe8-e798-470c-989c-c0e3fd4f43f5.png)


<b>48- </b>

![Selecció_737](https://user-images.githubusercontent.com/91245889/162405278-491ff3f6-0f01-4e2a-b20d-76b411a64bd6.png)


<b>49- </b>


![Selecció_738](https://user-images.githubusercontent.com/91245889/162405316-24d806f0-c0db-4dad-bb25-2835db4a6df3.png)



<b>50- </b>

![Selecció_739](https://user-images.githubusercontent.com/91245889/162405326-1cc2c5a9-567b-432b-8e86-fed4787d472a.png)


<b>51- </b>

![Selecció_740](https://user-images.githubusercontent.com/91245889/162405336-2040a2ed-e920-4504-82d9-32f305a6aef8.png)


<b>52- </b>

![Selecció_741](https://user-images.githubusercontent.com/91245889/162405345-abdec36d-a59d-4748-be34-67ae0a3411ff.png)
