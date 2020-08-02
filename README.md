The representation of a frieze is based on a coding with numbers in the range 0 …15, each such number n being
associated with a particular point p such that
• if the rightmost digit of the representation of n in base 2 is equal to 1 then p is to be connected to its
northern neighbour:
• if the second rightmost digit of the representation of n in base 2 is equal to 1 then p is to be connected
to its north-eastern neighbour:
• if the third rightmost digit of the representation of n in base 2 is equal to 1 then p is to be connected
to its eastern neighbour:
• if the fourth rightmost digit of the representation of n in base 2 is equal to 1 then p is to be connected
to its south-eastern neighbour:
思路为选取每个图案片段，提取其中的线段，对不同几何类型都进行相应变换，例如平移则需要把所有的线段平移之后判断是否和原始的相同，
若需要提供详细的咨询指导，可联系V信codingtutor
