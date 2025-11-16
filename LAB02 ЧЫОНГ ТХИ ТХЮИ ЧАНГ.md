cd /c/Users/Admin/student/truongthithuytrang
cp truongthithuytrang.info.md info.temp.md
ln info.temp.md info.hard.md
ln -s info.temp.md info.soft.md
cat info.hard.md
head -n 2 info.hard.md
tail -n 2 info.hard.md

cat info.soft.md
head -n 2 info.soft.md
tail -n 2 info.soft.md

cat truongthithuytrang.info.md
head -n 2 truongthithuytrang.info.md
tail -n 2 truongthithuytrang.info.md
nano info.temp.md
cat info.hard.md
head -n 2 info.hard.md
tail -n 2 info.hard.md

cat info.soft.md
head -n 2 info.soft.md
tail -n 2 info.soft.md

cat truongthithuytrang.info.md
head -n 2 truongthithuytrang.info.md
tail -n 2 truongthithuytrang.info.md
rm info.temp.md
cat info.hard.md # Содержимое будет отображаться, так как это жёсткая ссылка
cat info.soft.md # Будет ошибка, так как файл, на который указывает ссылка, удалён
sed 's/старый текст/новый текст/g' truongthithuytrang.info.md
sed -i 's/старый текст/новый текст/g' truongthithuytrang.info.md
head -n 1 truongthithuytrang.info.md
tail -n 2 truongthithuytrang.info.md
more truongthithuytrang.info.md
less truongthithuytrang.info.md
grep "Ваше Имя" truongthithuytrang.info.md
history | grep "команда"
> empty.md
cat truongthithuytrang.info.md > info_copy.md
cat *.md
grep -E "a.*b" *.md
