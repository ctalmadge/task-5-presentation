% Task 5: Final Presentation 
% Charles Talmadge
% 25 July, 2017

pandoc -t revealjs --template=template-index.html -s --variable theme="black" --variable transition="slide" --variable revealjs-url="./" present.md -o present.html

