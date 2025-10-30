# Exercice : Programmation de la logique interne d'un jeu de simulation de ferme.

**Commencez par** [lire le sujet](http://wwwperso.insa-toulouse.fr/~lebotlan/Y/Ada-S2/exo-ferme.html)

Cliquez ensuite sur "RUN".
Vérifiez que vous obtenez le bon résultat (tech.io vous dira toujours "success", même si le résultat est incorrect).

@[Programme à compléter]({"stubs": ["mission1.adb"], "command": "./adabuild mission1.adb"})
with GAda.Text_IO ;

procedure Mission1 is

   package Txt renames GAda.Text_IO ;

   procedure Afficher (Arg : Integer) is
   begin

      -- Compléter ici.
      
txt.put_line(aff=>"la valeur de la variable X est"&Arg'image);
   end Afficher ;

   X : Integer ;

begin

   X := 10 ;


   -- Compléter ici.
Afficher(x);
end Mission1 ;
