# ChonOS for WSL

||
|:--:|
|ChonOS to Windows Subsytem for Linux|


## How to import WSL image with chonOS?

<details>
<summary> Instructions to import a WSL chonOS image </summary>

1. Salve into DOWNLOADS folder the WSL image available at [ChonOS SourceForge Repo](https://sourceforge.net/projects/chonos/files/rc1/)
   
![image](https://github.com/chon-group/dpkg-chonos-wsl-installer/assets/32855001/7ce3dd4a-8437-4ca6-b2f0-df4947968a8f)


2. In the powershell run the commands below:

```sh
wsl --import chonOS $env:USERPROFILE\chonOS $env:USERPROFILE\Downloads\chonOS-rc1-WSL.tar.gz
wsl --distribution chonOS
```


![01](https://github.com/chon-group/dpkg-chonos-wsl-installer/assets/32855001/b33cf072-c137-4375-8a63-dfd6be6f4491)


3. Acess the WebConsole using the default credentiais 

- user = root
- passwd = root
  
![02](https://github.com/chon-group/dpkg-chonos-wsl-installer/assets/32855001/054171e1-6ab2-40f5-8b23-7141ec63a701)


</details>

## How to install a new WSL distribution with chonOS?
<details>
<summary> Instructions to create a LXC Container using terminal command </summary>

![101](https://github.com/chon-group/dpkg-chonos-wsl-installer/assets/32855001/f3631f2f-bc7c-4a04-b682-f47691465262)


![image](https://github.com/chon-group/dpkg-chonos-wsl-installer/assets/32855001/978f8bde-3882-4e98-9abd-336de1dcd6bb)


![106](https://github.com/chon-group/dpkg-chonos-wsl-installer/assets/32855001/d88e0cf8-60eb-4da2-9e1f-ff2737eaf649)



</details>

## COPYRIGHT
<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />The ChonOS for WSL is part of the [_Cognitive Hardware on Networks Operating
System (chonOS)_](http://os.chon.group/) and is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>. The licensor cannot revoke these freedoms as long as you follow the license terms:

* __Attribution__ — You must give __appropriate credit__ like below:

LAZARIN, Nilson Mori; PANTOJA, Carlos Eduardo; VITERBO, José. Towards a Toolkit for Teaching AI Supported by Robotic-agents: Proposal and First Impressions. In: WORKSHOP SOBRE EDUCAÇÃO EM COMPUTAÇÃO (WEI), 31. , 2023, João Pessoa/PB. Anais [...]. Porto Alegre: Sociedade Brasileira de Computação, 2023 . p. 20-29. ISSN 2595-6175. DOI: https://doi.org/10.5753/wei.2023.229753.


<details>
<summary> Bibtex citation format</summary>

```
@inproceedings{chonOS,
 author = {Nilson Lazarin and Carlos Pantoja and José Viterbo},
 title = { Towards a Toolkit for Teaching AI Supported by Robotic-agents: Proposal and First Impressions},
 booktitle = {Anais do XXXI Workshop sobre Educação em Computação},
 location = {João Pessoa/PB},
 year = {2023},
 issn = {2595-6175},
 pages = {20--29},
 publisher = {SBC},
 address = {Porto Alegre, RS, Brasil},
 doi = {10.5753/wei.2023.229753},
 url = {https://sol.sbc.org.br/index.php/wei/article/view/24887}
}

```
</details>
