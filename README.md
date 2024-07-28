# Fonts

## Instalação (ubuntu)
Faça download desse repositório como um arquivo zip

### System wide

Instala as fontes para todos os usuários: 

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

Verifica se as fontes foram devidamente instaladas no sistema:

```bash
fc-list : family | sort | uniq
```
