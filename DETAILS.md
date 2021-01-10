Em este arquivo irei descrfever todos os detalhes do projeto que consiste em a criação de Buttons Perdonalizados.
Em a pasta res/values/themes  dos arquivos themes.xml e night/themes.xml na linha 3 de cada arquivo, é trocado o a linha:
 <style name="Theme.CustomButtons" parent=Theme.MaterialComponents.DayNight.DarkActionBar>,  para
 <style name="Theme.CustomButtons" parent=Theme.MaterialComponents.DayNight.NoActionBar>
É deletado o componente textView contendo o "Hello World" e é adicionado um button no centro da tela 
