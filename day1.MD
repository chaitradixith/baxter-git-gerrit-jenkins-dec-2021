 - - 1109  git branch
 - - 11- 12  git diff home-page-branch..main
 - - 11- 13  git branch --merged
 - - 1114  git checkout seo-works
 - 1115  git checkout main 
 - 1116  git merge seo-works
 - 1117  git branch
 - 1118  git status
 - 1119  git add .
 - 1- 120  git commit -m "merged from seo work having meta chars"
 - 1- 121  git staus
 - 1- 122  clear
 - 1- 123  git status
 - 1- 124  gir branch 
 - 1- 125  git branch 
 - 1- 126  git branch --merged
 - 1- 127  clear
 - 1- 128  git log
 - 1- 129  clear
 - 1- 130  git log --oneline
 - 1- 131  git log --oneline --graph --all --decorate
 - 1- 132  clear
 - 1- 133  git branch 
 - 1- 134  git checkout --help
 - 1- 135  git checkout -b article-content main
 - 1- 136  git branch
 - 1- 137  git status
 - 1- 138  git add . 
 - 1- 139  git commit -m "added aside tag to index file"
 - 1140  git status
 - 1141  git checkout main 
 - 1142  git branch --no-merged
 - 1143  git diff article-content..main
 - 1144  git diff article-content..main^
 - 1145  clear
 - 1146  git branch 
 - 1147  git merge article-content
 - 1148  git branch --no-merged
 - 1149  git branch 
 - 1150  git branch -m seo-works baxter-seo-works
 - 1151  git branch
 - 1152  git branch -d article-content
 - 1153  git branch 
 - 1154  clear
 - 1155  git log --oneline 
 - 1156  git log --oneline -3
 - 1157  git log main --oneline
 - 1158  git log home-page-branch --oneline
 - 1159  clear
 - 1160  git log --help
 - 1161  git log --oneline 
 - 1162  git log --oneline --grep="meta tag""
 - 1163  git log --oneline --grep="meta tag"
 - 1164  git log home-page-branch --oneline
 - 1165  git checkout -b update-meta fcf6666
 - 1166  git branch 
 - 1167  git status
 - 1168  git add . 
 - 1169  git commit -m "updated view port for multiple device compatibility"
 - 1170  clear
 - 1171  git checkout main 
 - 1172  git branch --no-merged
 - 1173  git merge update-meta
 - 1174  git log --oneline --graph --all --decorate
 - 1175  git show --color-words
 - 1176  clear
 - 1177  git reset --help
 - 1178  clear
 - 1179  git branch 
 - 1180  git checkout -b reset-works main 
 - 1181  git branch 
 - 1182  git status
 - 1183  git -am "added a footer note to home page"
 - 1184  git -a -m "added a footer note to home page"
 - 1185  clear
 - 1186  git add . 
 - 1187  git commit -m "added copyright to home page"
 - 1188  git lot --oneline -5
 - 1189  git log --oneline -5
 - 1190  git add . 
 - 1191  git commit -m "add footer for baxter india"
 - 1192  git status
 - 1193  git log --oneline -5
 - 1194  clear
 - 1195  git status
 - 1196  git log --oneline -4
 - 1197  git reset --soft HEAD^
 - 1198  git status
 - 1199  git commit -m "update the comments for copyright"
 - 1200  git status
 - 1201  git log --oneline -5
 - 1202  clear
 - 1203  git status
 - 1204  git log --oneline -4
 - 1205  git reset HEAD^
 - 1206  git status
 - 1207  git add . 
 - 1208  git commit -m "showing default reset for baxter india footer"
 - 1209  git status
 - 1210  clear
 - 12- 11  git log --oneline -5
 - 12- 12  git reset --hard HEAD^
 - 12- 13  git status
 - 1214  clear
 - 1215  git status
 - 1216  git add . 
 - 1217  git commit -m "added contact information"
 - 1218  git status 
 - 1219  git log --oneline --5
 - 1220  git log --oneline -5
 - 1221  git reset --hard HEAD^
 - 1222  git log --oneline -5
 - 1223  git status
 - 1224  clear
 - 1225  git log --oneline
 - 1226  ls
 - 1227  pwd
 - 1228  ls -la
 - 1229  cd .git
 - 1230  ls
 - 1231  cd ..
 - 1232  clear
 - 1233  history
 - 1234  history -80
 - 1235  clear
 - 1236  git status
 - 1237  ls
 - 1238  git branch 
 - 1239  git status
 - 1240  git restore index.html
 - 1241  git status
 - 1242  clear
 - 1243  git status
 - 1244  git branch 
 - 1245  git checkout main
 - 1246  git status
 - 1247  clear
 - 1248  git checkout -b new-branch main 
 - 1249  git branch 
 - 1250  git stash list
 - 1251  git add . 
 - 1252  git commit -m "added h3 tag to show stash"
 - 1253  git status
 - 1254  git stash --help
 - 1255  git stash first-stash "testing h3 stash"
 - 1256  git stash save "testing h3 stash"
 - 1257  git stash list
 - 1258  clear
 - 1259  git status
 - 1260  git stash save "h3 for stash created"
 - 1261  git status
 - 1262  git stash save "second aside working inside article"
 - 1263  git status
 - 1264  git stash list
 - 1265  git stash show stash@{0}
 - 1266  git stash apply stash@{0}
 - 1267  git status
 - 1268  git status
 - 1269  clear
 - 1270  git branch 
 - 1271  git checkout main 
 - 1272  git add . 
 - 1273  git commit -m "updated h3 tag"
 - 1274  git checkout main 
 - 1275  git new-branch 
 - 1276  git checkout new-branch 
 - 1277  git stash list
 - 1278  git stash apply stash@{1}
 - 1279  git stash drop stash@{0}
 - 1280  git stash list
 - 1281  git status 
 - 1282  git add . 
 - 1283  git ci -m "updated with stash"
 - 1284  git status
 - 1285  clear
 - 1286  git branch 
 - 1287  git stash list
 - 1288  git co main 
 - 1289  git co new-branch 
 - 1290  git stash list
 - 1291  git stash pop
 - 1292  git stash list
 - 1293  clear
 - 1294  git --help
 - 1295  clear
 - 1296  pwd
 - 1297  git status
 - 1298  git branch 
 - 1299  git co main 
 - 1300  git push origin main 
 - 1301  git push origin home-page-branch
 - 1302  git add . 
 - 1303  git st
 - 1304  clear
 - 1305  git ci -m "updated readme file"
 - 1306  git branch 
 - 1307  git push origin main 
 - 1308  history -150