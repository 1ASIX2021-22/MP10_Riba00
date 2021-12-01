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

Ens surt que ens hem de fer un login









