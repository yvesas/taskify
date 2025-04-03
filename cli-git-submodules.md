# Comandos para Gerenciar Submódulos Git

Para trabalhar com submodules vai precisar destes comandos essenciais:

## 1. Clonar o repositório principal COM os submódulos

```
git clone --recursive https://github.com/seu-usuario/HiDoctor.git
```

O parâmetro `--recursive` já baixa automaticamente os submódulos (frontend e backend).

## 2. Se já clonou sem os submódulos

Execute dentro da pasta do projeto:

```
git submodule update --init --recursive
```

## 3. Comandos úteis para submódulos

- **Atualizar todos os submódulos para o commit mais recente** :

```
  git submodule update --remote --recursive
```

- **Ver o status dos submódulos** :

```
  git submodule status
```

- **Adicionar um novo submódulo** (caso precise):

  ```
  git submodule add https://github.com/seu-usuario/repositorio.git pasta-destino
  ```

## 4. Quando fazer alterações nos submódulos

1. Entre na pasta do submódulo:

   ```
   cd frontend  # ou cd backend
   ```

2. Faça suas alterações e commits (como em um repositório normal)
3. Volte para o repositório principal e atualize a referência:

   ```
   cd ..
   git add frontend  # ou backend
   git commit -m "Atualiza submódulo frontend para nova versão"
   git push
   ```

## 5. Se alguém atualizou os submódulos

Para sincronizar:

```
git pull
git submodule update --recursive
```
