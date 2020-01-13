# calcpythonoop
Calc oop em python com erro 
------------------------------------ main calc------------------------------------------------------------
from cadastro import Cal
from matematica import Matematica
from menos import menos
from multiplica import multiplica
from divisoria import divisoria



calc = Cal()


menos = menos(input('digite'),
              input('digite:')
              )
multiplica = multiplica(input('digite:'),
                        input('digite:')
                        )
divisoria = divisoria(input('digite:'),
                      input('digite:')
                      )
matematica = Matematica(input('Digite:'),
                  input('Digite')
                  )



print("resultado:",calc.Mat(matematica
        )
      )

print("resultado",calc.Subt(menos)
      )
print("resultado",calc.Mult(multiplica)
      )
print("resultado",calc.Divisao(divisoria)
      )
      --------------------------------class math----------------------------------------------------------------------
      
      class Matematica:
    numero: int
    numero2: int


    def __init__(self, numero, numero2):
        self.numero  = numero
        self.numero2 = numero2
        
        -------------------------------------class subt-------------------------------------
        class menos:
    def __init__(self,numero,numero2):
        self.numero = numero
        self.numero = numero2
        
        
        -------------------------------------class mult------------------------------------     
        class multiplica:
    def __init__(self,numero,numero2):
        self.numero = numero
        self.numero2 = numero2

-----------------------------------class div------------------------------
class divisoria:
    def __init__(self,numero,numero2):
        self.numero = numero
        self.numero2 = numero2

-----------------------------------------------------------------
print("resultado",calc.Subt(numero,numero2))
print("resultado",calc.Mult(numero,numero2))
print("resultado",calc.Divisao(numero,numero2))
        
