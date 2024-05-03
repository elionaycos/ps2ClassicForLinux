---

# ps2classic

O **ps2classic** é uma ferramenta que permite manipular arquivos do Memory Card Virtual (VME) do PlayStation 2. Esta versão foi compilada do zero com algumas melhorias e otimizações em relação à versão original.

## Funcionalidades

- **Decriptação de arquivos VME**: Permite decriptar arquivos VME do PlayStation 2 para que possam ser editados ou transferidos para outros dispositivos.
- **Edição de saves do PlayStation 2**: Facilita a edição de saves de jogos do PS2 para adicionar trapaças, transferir dados entre saves, etc.
- **Compatibilidade aprimorada**: Esta versão do ps2classic foi desenvolvida com foco em melhorar a compatibilidade com uma variedade de sistemas e ambientes de execução.

## Requisitos

- Sistema operacional Linux (ou compatível com Wine no Windows)
- Compilador C e ferramentas de desenvolvimento padrão (para compilar a partir do código-fonte)
- Conhecimento básico de linha de comando

## Compilação

Para compilar o ps2classic a partir do código-fonte, siga estas etapas:

1. Clone este repositório:

```bash
git clone https://github.com/elionaycos/ps2ClassicForLinux
```

2. Navegue até o diretório do repositório:

```bash
cd ps2classic
```

3. Compile o código-fonte:

```bash
make
```

Isso irá gerar o executável `ps2classic`.

## Uso

Para usar o ps2classic, você pode executar o comando apropriado no terminal, conforme necessário. Aqui está um exemplo de uso para decriptar um arquivo VME:

```bash
./ps2classic vd cex ecc INPUT_FILE_VME OUTPUT_FILE_VME 
```

Consulte a seção de ajuda (`./ps2classic`) para obter mais informações sobre as opções disponíveis.

## Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir problemas (issues) ou enviar solicitações de recebimento (pull requests) para melhorar este projeto.


## Fonte
https://github.com/tszentendrei/ps2classic
---
