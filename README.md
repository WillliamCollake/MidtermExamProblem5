# MidtermExamProblem5
Problem 5 Midterm

def dict_invert(d)
'''
d: dict
returns an inverted dictionary according to the instructions above
'''
inverse = {}
for elm in d.keys();
  if d[elm] in inverse:
    inverse[d[elm]].append(elm)
  else:
     invese[d[elm]] = [elm]
  for val in inverse.values():
      val.sort()
  return inverse
