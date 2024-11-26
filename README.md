# Fonts

## Instalação (ubuntu)

Faça download desse repositório como um arquivo zip

### System wide

Faz a instalação das fontes para todos os usuários: 

```bash
sudo cp *.ttf /usr/share/fonts/truetype/
fc-cache -f -v
```

### User only

Instala apenas para o usuário:

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

