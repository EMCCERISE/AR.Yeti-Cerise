# Cerise 
## Teste dos pacotes LightShip para Realidade Aumentada

- Teste com geolocalização;
- Implementação de detecção de objetos e oclusão;
- Demarcação de pontos de referência visuais (VPS);


# Instalação:
Siga o passo a passo da instalação do pacote da Lightship para XR. Como o pacote é constantemente atualizado, é recomendado que siga à risca as instruções de instalação do pacote, incluindo a versão do Unity.
```https://lightship.dev/docs/ardk/setup/```

Além do pacote ARDK, é necessário criar uma cena padrão no Unity, seguindo as instruções também da Lightship:
```https://lightship.dev/docs/ardk/setup/#setting-up-a-basic-ar-scene```

E por fim, é necessário seguir as instruções de criar um ambiente com VPS no Unity:
```https://lightship.dev/docs/ardk/how-to/vps/real_world_location_ar/```
Nesta etapa você pode baixar o conteúdo deste github em uma pasta e importar a cena no Unity (arraste os arquivos para o projeto do Unity).

Nesta última etapa, será necessário 
1) Criar uma conta da Lightship em:
   ```https://lightship.dev/account```
2) Criar um projeto na Lightship na dashboard da sua conta.
   Vá na sua dashboard da Lightship e crie um projeto.
3) Escanear um ambiente teste e enviar para o Lightship.
   Baixe o aplicativo Niantic Wayfarer, seguindo as instruções: ```https://lightship.dev/docs/ardk/how-to/vps/tooling/install_and_use_niantic_wayfarer/```
   As instruções incluem como criar um Test Scan.
4) Baixar o ambiente
   Criado o TestScan, ele aparecerá na sua dashboard do projeto da sua conta da Lightship. Terá um botão para baixar o arquivo zip com a malha.

Aplique esta malha conforma instruções em ```https://lightship.dev/docs/ardk/how-to/vps/real_world_location_ar/```. 

Feito isso, basta compilar o código em Android e instalar o APK no dispositivo. Se o escaneamento estiver com uma boa qualidade, ao abrir o aplicativo ele detectará o ambiente e posicionará os objetos em AR.
   
