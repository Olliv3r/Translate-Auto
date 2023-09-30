# Translate-Auto
Traduz arquivos de legenda .srt
![main](https://github.com/Olliv3r/Translate-Auto/blob/main/media/main.gif)

> [!IMPORTANT]
> Instalação dos requisitos
```
apt update && apt install git python python-pip -y
git clone https://github.com/Olliv3r/Translate-Auto
cd Translate-Auto && pip install -r requirements.txt
```

Exemplos:
Traduz a legenda de um arquivo específico:
```
./translateAuto.py --source=en --target=pt --file subtitle/subtitle.srt
```
Traduz a legenda de múltiplos arquivos do diretório padrão `subtitle`:
```
./translateAuto --source=en -target=pt --all
```

> [!NOTE]
> Caso queira traduzir vários arquivos de legenda `.srt` você precisa copiá-los para dentro do diretório `subtitle` o qual o programa usa para traduzir mais de um arquivo de legenda `.srt`. Se for apenas um arquivo não há necessidade de fazer esta etapa.

Nos exemplos acima a tradução foi realizada somente do idioma `english` para o `portuguese`, é possível traduzir o arquivo para qualquer idioma disponível. Todos os idiomas podem ser acessados usando a opção `--languages`:
```
./translateAuto.py --languages
```

### Recurso:

- [x] Tradução de arquivos de legendas
- [ ] Outros

© Copyright [Olliver](https://github.com/Olliv3r/).
