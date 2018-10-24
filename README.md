## Exercice du MOOCademy

Exercice réalisé dans le cadre de la semaine Rails / Back end (THP), par notre belle équipe :
- [Ysaline Macé](https://github.com/Ysalien)
- [Nikita Vasilev](https://github.com/nikitavasilev)
- [Arthur Mansuy](https://github.com/tutus06) 
- [Thomas Charvet](https://github.com/TomacTh) 
- [Nathaniel Debache](https://github.com/Natdenice).

## Database

MOOCademy est une base de données, réalisée à partir de rails, permettant d'accéder à des cours. Ces cours sont définis par un titre et une description et contiennent plusieurs leçons. Les leçons contiennent un titre et un body.
On retrouve alors deux model Course (table courses) et Lesson (table lessons). Leur index est lié sur Lesson.

##### NB
Les models se trouvent dans le sous-fichier model, dans app
Les tables se trouvent dans le fichier migrate, contenu dans db
