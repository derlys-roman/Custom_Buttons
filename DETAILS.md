Em este arquivo irei descrfever todos os detalhes do projeto que consiste em a criação de Buttons Perdonalizados.
Em a pasta res/values/themes  dos arquivos themes.xml e night/themes.xml na linha 3 de cada arquivo, é trocado o a linha:
 <style name="Theme.CustomButtons" parent=Theme.MaterialComponents.DayNight.DarkActionBar>,  para
 <style name="Theme.CustomButtons" parent=Theme.MaterialComponents.DayNight.NoActionBar>.
 É deletado o componente textView contendo o "Hello World" e é adicionado um button no centro da tela.
 É adicionado um button com as segintes caracteristicas: 
 <Button
        android:id="@+id/button"
        <!--Para definir o limite diagonal ou seja deitado-->
        android:layout_width="250dp"
        <!--definindo a altura do button-->
        android:layout_height="60dp"
        android:layout_marginStart="8dp"
        android:layout_marginLeft="8dp"
        android:layout_marginTop="8dp"
        android:layout_marginEnd="8dp"
        android:layout_marginRight="8dp"
        android:layout_marginBottom="8dp"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        android:text="Button"
        android:textAllCaps="false"
        />
        
        
        
        
