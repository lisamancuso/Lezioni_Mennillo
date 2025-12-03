# Esercizio 1
  110  pwd
  111  cd ..
  112  cd

# Esercizio 2

  113  mkdir lab_linux
  114  cd lab_linux/
  115  mkdir progetti; mkdir documenti; mkdir backup
  116  mkdir progetti/app_a; mkdir progetti/app_b
  117  tree
  118  touch progetti/app_a/main.py
  119  touch progetti/app_b/note.txt
  120  touch documenti/report.doc

# Esercizio 3.1
  121  cd progetti/app_a
  122  cd ../..
  123  cd documenti/
  124  cd /home/lisa/lab_linux/

# Esercizo 3.2
  125  cd progetti/app_b
  126  cd ../../documenti/
  127  cd -

# Esercizio 4
  128  cp ../app_a/main.py ../../backup/
  129  cp ../../documenti/report.doc ../../backup/report_backup.doc
  130  cp ../../progetti/app_a ../../progetti/app_a_backup
  131  cp -r ../../progetti/app_a ../../progetti/app_a_backup

# Esercizio 5
  132  mv note.txt appunti.txt
  133  mv ../../documenti/report.doc ../../backup/
  134  cp -r ../app_b ../app_beta
  135  tree
  136  cd ..
  137  ls
  138  ls app_beta/
  139  rm app_beta/
  140  rm -r app_beta/
  141  mv app_b app_beta
  142  ls app_beta/

# Esercizio 6
  143  cd
  144  mkdir progetto_web
  145  mkdir progetto_web/frontend; mkdir progetto_web/backend; mkdir progetto_web/docs
  146  mkdir progetto_web/frontend/css
  147  touch progetto_web/frontend/css/style.css
  148  touch progetto_web/frontend/index.html
  149  touch progetto_web/backend/server.py
  150  touch progetto_web/docs/README.md
  151  cp progetto_web/backend/server.py lab_linux/backup/
  152  mv -r progetto_web lab_linux/backup/
  153  mv progetto_web lab_linux/backup/
  154  mv lab_linux/backup/ lab_linux/backup_finale

