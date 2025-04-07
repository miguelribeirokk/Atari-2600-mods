# 🕹️ Atari 2600 Mods

> Um repositório com modificações feitas em jogos clássicos do Atari 2600 — na base da ASM bruta.

## 🎯 Objetivo

Este projeto tem como foco a experimentação com **Assembly do Atari 2600**, modificando jogos como o clássico **Combat** para estudar:

- Hack de ROMs
- Alterações de comportamento nos jogos
- Inserção de novos sprites, sons ou lógica
- E, claro, se divertir quebrando um pouco o sistema 😄

---

## 📁 Estrutura

```bash
Atari-2600-mods/
├── C∞mbat.asm         # Mod com alterações de gameplay
├── DANICombat.asm     # Mod dedicado ao Daniel, com ajustes customizados
├── TIKTOKombat.asm    # Edição "moderna" com mudanças criativas como velocidade e colisões
├── combat.asm         # Versão base ou levemente editada do Combat
````

## 🔧 Como rodar os mods
Para compilar e rodar os mods, você precisará de:

### 🧰 Ferramentas recomendadas
- Assembler: DASM (cross-platform)
- Emulador: Stella (recomendado)

### ⚙️ Compilando um mod
Exemplo com o DASM:

```bash
dasm C∞mbat.asm -f3 -o C∞mbat.bin
```
Isso vai gerar uma ROM .bin que pode ser executada no emulador.

### ▶️ Rodando no Stella

```bash
stella C∞mbat.bin
```
Ou simplesmente abra a ROM no emulador usando a interface gráfica.

## ✏️ Sobre os mods
- Verifique a documentação em .pdf

## 📜 Licença
- Distribuído sob a licença MIT.
- Você pode modificar, distribuir, estudar e hackear à vontade.


