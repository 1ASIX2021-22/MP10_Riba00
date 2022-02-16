1- Comprovem si tenim la carpeta Code, en cas contrari, la creeem.

![Selecció_352](https://user-images.githubusercontent.com/91245889/144205559-a90a2656-ab17-42a7-9fc4-fdff48ad49ad.png)

2- Obrir navegador amb la següent comanda

![Selecció_353](https://user-images.githubusercontent.com/91245889/144205919-0796456c-0b8e-4871-857b-b75fb9bc9d1e.png)

3- Anem al compte de GitHub > Your Organizations > 1ASIX21-22 > PlantillaLaravelMysql i li donem a Use this template.

![Selecció_354](https://user-images.githubusercontent.com/91245889/144207780-6e57b4ab-9366-46ef-ae68-d588079fb2fe.png)

4- Fem una copia al nostre repositori amb el nom que nosaltres vulguem i li donem a Create repository from template.

![Selecció_355](https://user-images.githubusercontent.com/91245889/144208107-8e1b0775-1886-4c88-aa40-ebf0ff50e66f.png)

5- Instalarem el Github CLI per a poder executar la comanda.
curl -fsSL https://cli.github.com/packages/githubcli-archive-keyring.gpg | sudo dd of=/usr/share/keyrings/githubcli-archive-keyring.gpg

![Selecció_358](https://user-images.githubusercontent.com/91245889/144210560-ba4799c5-fcd2-4673-b4d2-344a1e7d3ef9.png)

echo "deb [arch=$(dpkg --print-architecture) signed-by=/usr/share/keyrings/githubcli-archive-keyring.gpg] https://cli.github.com/packages stable main" | sudo tee /etc/apt/sources.list.d/github-cli.list > /dev/null

![Selecció_359](https://user-images.githubusercontent.com/91245889/144210738-50a68f9a-4331-4a7c-a5d1-c758974b4086.png)

sudo apt update

sudo apt install gh

![Selecció_360](https://user-images.githubusercontent.com/91245889/144210852-f67e158c-fbd0-49f6-914d-6a17e8661488.png)


6- Un cop instalat el GithubCLI, el primer que farem és un ls a la carpeta Code i veurem que hi ha una carpeta amb el nostre ID de Github i entrem.

![Selecció_357](https://user-images.githubusercontent.com/91245889/144208906-812f8d88-cf38-436f-89a8-b6d09c0069b9.png)

7- Peguem la direcció Github CLI a la terminal i executem la comanda. 

![Selecció_361](https://user-images.githubusercontent.com/91245889/144211650-52b6f84b-91ea-45ca-99c3-acaefb26c099.png)

8- Ens surt que ens hem de fer un login. Anem seguint els passos tal i com es veu a la captura fins que fem el logib.

![Selecció_362](https://user-images.githubusercontent.com/91245889/144219189-33c390a3-0595-4ffe-8b96-ba8b0a098441.png)

9- Ara, ja ens podrem descarregar el codi.

![Selecció_363](https://user-images.githubusercontent.com/91245889/144219629-19b1037a-e98a-4353-9bba-d4d181547726.png)

10- Un cop descarregat entrem a la carpeta

![Selecció_365](https://user-images.githubusercontent.com/91245889/144230897-a4502ca6-742b-45e2-9fbb-4834a840f0d0.png)

11- Hem de tenir el PHPStorm i hem de poder obrir el projecte al PHPStorm.

![Selecció_367](https://user-images.githubusercontent.com/91245889/144232522-a40cf5c1-0550-4aa6-9773-c7f3cb9c2fcf.png)

12- També és recomanable instal·lar el valet, executem la comanda de la captura i fem clic amb Ctrl a la direcció que ens apareix. 

![Selecció_369](https://user-images.githubusercontent.com/91245889/144233118-b9e8314e-b4d5-456a-a942-77b82d3e02df.png)

Ara el que farem és arreglar l'error SQL. Hem de generar les dades necessàries per a que l'aplicació funcioni. Per fer-ho, fem clic dret a la carpeta del projecte > Find in Files > Escrivim "MYSQL". Ens troba a tots els llocs on es troba MYSQL fins que trobem la connexió on ens diu el port, el host, el user...

![Selecció_499](https://user-images.githubusercontent.com/91245889/154261200-8e2a66d8-e495-4233-9987-01a0cd65b52d.png)







