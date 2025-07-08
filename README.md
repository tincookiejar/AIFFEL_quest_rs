mkdir -p AIFFEL_quest_cr/MainQuest/Quest{01..08}
mkdir -p AIFFEL_quest_cr/Exploration/Ex{01..07}

# 각 Quest와 Ex 폴더에 빈 파일 생성
for i in {01..08}; do
  touch AIFFEL_quest_cr/MainQuest/Quest$i/{notebook.ipynb,README.md}
done

for i in {01..07}; do
  touch AIFFEL_quest_cr/Exploration/Ex$i/{notebook.ipynb,README.md}
done
