# Crimson Wanderer — revisão 2

Protótipo estilizado com superfícies arredondadas, detalhes faciais, dedos e caminhada procedural inspirada em referência humana. Ainda não é um personagem realista: a anatomia e as articulações continuam simplificadas, sem escultura, texturas de pele ou simulação de tecido.

- `CrimsonWanderer_v2.blend`: Blender 4.3.2, cena de estúdio e animação. Abra e pressione Espaço para reproduzir os quadros 1–37.
- `CrimsonWanderer_v2.glb`: modelo, materiais, esqueleto e animação `Walk` para Godot. A cena de estúdio não é exportada.
- `CrimsonWanderer_v2.png`: prévia renderizada.

A caminhada é no lugar; o deslocamento no jogo deve ser feito pelo controlador do personagem. Habilite repetição da animação na importação do Godot para caminhada contínua. O sobretudo acompanha as pernas, sem física de tecido. A animação foi criada proceduralmente; não é captura de movimento extraída do vídeo.

Validação: importação via GLTFDocument no Godot 4.6.3 e reprodução de `Walk`, com 13 trilhas. Integração com o projeto VeuSombrioGodot ainda não realizada.
