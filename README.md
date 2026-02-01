Написала для работы, может ко-то еще сочтет нужным. Простейший код, который пробегается по файлу .docx и форматирует его содержимое следующим образом перед тем как вывести отдельным .txt файлом:

Удаляет все ссылки из текста
В начале каждого абзаца ставить тег
, а в конце соответственно

Любые списки преобразует в списки html т.е. обособляет весь список тегом
а эл-ты списка тегами
(важно, чтобы списки были оформлены именно как docx списки иначе не сработает)
Если есть абзац начинающийся с "фото" добавляет его тегу
style="font-size: 12px"
Все функции в коде помечены и прокомментированы на русском, поэтому не составит труда удалить ненужные пункты или добавить свои, если нужно.

I wrote this code for my job, so if you find it useful, feel free to use it.
It’s a simple script that processes a .docx file and formats it before exporting it as a .txt file:
Deletes all links in the file
Adds the tag at the beginning of each paragraph and at the end
Restores all lists as HTML lists (IMPORTANT: the lists must already exist as proper DOCX lists in the file, otherwise the script won’t work)
If a paragraph starts with the word "фото", its style is changed to style="font-size: 12px"
