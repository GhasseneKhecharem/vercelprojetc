# vercelprojetc
4. vercel -v
5. vercel init
   j'ai choisi angular
6. cd angular 
   vercel
7. vercel list
8. vercel logs project1-raw5kb3nq.vercel.app
9. vercel inspect project1-raw5kb3nq.vercel.app
Cette commande nous fournit des informations sur le deploiement 
10. Elles permettent de stocker des variables (emplacements, mots de passes,tokens...) pour les utiliser
 ultérieurement sans avoir besoin de les écrire dans le code pour des raisons de sécurité.
11.vercel env add plain var1
12.vercel env ls
13. C'est un type particulier de variables d'environnements utilisés pour les mots de passe et les tokens, elles vont être encryptées et stockées.
15.vercel secret add secretvar2 azerty12345
16. Les 3 environnements proposés sont : Production, Preview et Development 
Dans un projet il est conseillé de mettre en place différents environnements, un environnement Development si le projet est en cours 
de dévelopement et là c'est la phase où on peut encore modifier quoi que ce soit, un environnement Preview pour la phase de testing, et enfin
un environnement Production pour la phase de production où le projet est déjà fonctionnelle et entrain d'être exploité.
17.
18.https://vercel.com/ghassenekhecharem/vercelprojetc
19.Quand un collaborateur effectue des changements sur sa propre branche et qu'il veut les intègrer sur la branche master il effectue un 
pull request, donc c'est une sorte de demande d'affecter des modifications sur la branche master
