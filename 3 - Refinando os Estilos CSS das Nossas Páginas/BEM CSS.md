[B] Bloco
[E] Elemento
[M] Modificador

*"BEM faz alusãoa Programação Orientada a Objetos (POO), uma
maneira de descrever a realidade no código, com uma variedade de
padrões e uma maneira de pensar nas entidades do programa"*
> - Varga Stepanova, desenvolvedores front-end do projeto.

- Bloco (Block):
    - Entidade independente (bloco de construção)
    - Elemento pai
    - [BLOCO] (.btn)

- Elemento (Elements)
    - Elemento filho
    - Não independente
    - Vinculado a um bloco
    - [BLOCO]__[ELEMENTO] (.btn_price)

- Modificador (Modifier)
    - Modifica um bloco ou elemento
    - Variante para alterar a aparência
        - Variar uma propriedade
        - Atribuir um estado
    - [BLOCO]__[ELEMENTO]--[MODIFICADOR]
        .menu--dark
        .bnt--orange
        .menu__link--disabled
