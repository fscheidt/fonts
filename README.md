# Fonts

## Instalação

### ubuntu

fazer o download do repositório como arquivo zip:

```bash
wget https://github.com/fscheidt/fonts/releases/download/v1/fonts.zip
```

#### System wide

Instalar as fontes para todos os usuários: 

```bash
sudo cp *.ttf /usr/share/fonts/truetype/
fc-cache -f -v
```

#### User only

Instalar apenas para o usuário:

```bash
mkdir ~/.fonts
cp *.ttf ~/.fonts
fc-cache -f -v
```

## Verificação 

Lista as fontes instaladas:

```bash
fc-list : family | sort | uniq
```

