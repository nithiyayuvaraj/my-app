{\rtf1\ansi\ansicpg1252\deff0\nouicompat\deflang1053{\fonttbl{\f0\fnil\fcharset0 Calibri;}}
{\*\generator Riched20 10.0.17134}\viewkind4\uc1 
\pard\sa200\sl276\slmult1\f0\fs22\lang29 pipeline \{\par
    agent any \par
    stages \{\par
        stage('Clean') \{ \par
            steps \{\par
                bat "mvn clean "\par
            \}\par
        \}\par
        stage('Test') \{ \par
            steps \{\par
                bat "mvn test"\par
            \}\par
        \}\par
        stage('Deploy') \{ \par
            steps \{\par
                bat "mvn package" \par
            \}\par
        \}\par
    \}\par
\}\par
}
 