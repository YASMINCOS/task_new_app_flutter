# Primeiro app com flutter

A new Flutter project.

## Pontos abordados

1. **Widgets - A Base do Flutter**:
   - Widgets são os blocos de construção fundamentais no Flutter.
   - Tudo no Flutter é um widget, desde o layout até os elementos visuais.
   - Existem widgets para layout (como `Container`, `Column`, `Row`, etc.), widgets para texto (como `Text`), widgets para interação (como `Button`) e muito mais.

2. **Peças de Lego**:
   - No Flutter, os widgets são frequentemente comparados a peças de Lego que podem ser combinadas para construir interfaces de usuário complexas.
   - Cada widget tem sua própria funcionalidade e pode ser combinado com outros widgets para criar interfaces de usuário ricas e dinâmicas.

3. **Containers e Stacks**:
   - `Container`: Um widget que permite personalizar a aparência, o layout e outros atributos de seu filho. É frequentemente usado para agrupar outros widgets.
   - `Stack`: Um layout que empilha seus filhos em cima uns dos outros. É útil quando você precisa posicionar widgets uns sobre os outros.

4. **Column**:
   - `Column`: Um layout que organiza seus filhos verticalmente em uma única coluna.
   - Exemplo:
     ```dart
     Column(
       children: <Widget>[
         Container(color: Colors.red, height: 100),
         Container(color: Colors.blue, height: 100),
         Container(color: Colors.green, height: 100),
       ],
     )
     ```

5. **Text e ElevatedButton**:
   - `Text`: Um widget usado para exibir texto na interface do usuário.
   - `ElevatedButton`: Um botão material elevado que reage ao toque.
   - Exemplo:
     ```dart
     ElevatedButton(
       onPressed: () {
         // Ação a ser executada quando o botão é pressionado
       },
       child: Text('Pressione-me'),
     )
     ```

6. **Overflow e Árvores de Widgets**:
   - `Overflow`: Refere-se à situação em que o conteúdo de um widget excede seu espaço disponível.
   - O Flutter usa uma árvore de widgets para construir interfaces de usuário, onde cada widget tem filhos que são widgets aninhados dentro dele.

7. **Material vs. Cupertino**:
   - Material: Um conjunto de widgets e diretrizes de design que implementam o Material Design, uma linguagem de design desenvolvida pelo Google. É amplamente utilizado no Android.
   - Cupertino: Um conjunto de widgets e diretrizes de design que implementam o estilo de design do iOS. É usado para criar aplicativos com uma aparência nativa do iOS.


8. **Stateless vs. Stateful Widgets**:
   - **Stateless Widget**: Um widget que não mantém estado interno. Sua renderização é determinada apenas pelos valores fornecidos em seu construtor. Exemplos comuns incluem ícones, textos e botões.
   - **Stateful Widget**: Um widget que pode manter estado interno. Ele pode reconstruir sua árvore de widgets quando o estado muda, geralmente em resposta a eventos como toques ou atualizações de dados. Usa o método `setState()` para notificar o framework quando o estado é alterado.

9. **ListView**:
   - Um widget que exibe uma lista rolável de widgets filhos. É útil para exibir grandes quantidades de dados ou uma coleção de itens. Você pode criar listas verticais ou horizontais, e os itens podem ser personalizados conforme necessário.

10. **AnimatedOpacity**:
   - Um widget que anima a opacidade de seu filho de forma suave e gradual. É útil para criar transições suaves entre diferentes estados de visibilidade de um widget. Você pode ajustar a opacidade e a duração da animação conforme necessário.

11. **Image**:
   - Um widget usado para exibir imagens em um aplicativo Flutter. Pode exibir imagens de diferentes fontes, como a rede, o sistema de arquivos local ou a memória. Você pode definir a largura, a altura, o ajuste, a escala e outros atributos da imagem conforme necessário.

12. **Arquivo .yaml** (pubspec.yaml):
   - Um arquivo de manifesto YAML usado para configurar e gerenciar um projeto Flutter. Nele, você especifica dependências do pacote, ativos (como imagens e fontes), informações do aplicativo (como nome, descrição e versão) e outras configurações específicas do projeto.


This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.
