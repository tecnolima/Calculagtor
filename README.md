# Calculator
from tkinter import TK, Entry, Button, StringVar
lass calculator:
def_init_(self,master):
master.title("calculator")
master.geometry('357x420+0+0)
master.resizable(False, False)
self equation=StringVar()
self.entry_value=''
Entry(width=17,bg='#fff', font=('Arial Bold,'28)textvariable=self.equation).place(x=0,y=0))
Button(width=11,height=4,text='(', relief='flat',bg='white',command=lamda;self show('(')).place(x=0,y=50)
Button(width=11,height=4,text=')', relief='flat',bg='white',command=lamda;self show(')')).place(x=90,y=50)
Button(width=11,height=4,text='%', relief='flat',bg='white',command=lamda;self show('%')).place(x=180,y=50)
Button(width=11,height=4,text='1', relief='flat',bg='white',command=lamda;self show('1')).place(x=0,y=125)
Button(width=11,height=4,text='2', relief='flat',bg='white',command=lamda;self show('2')).place(x=90,y=125)
Button(width=11,height=4,text='3', relief='flat',bg='white',command=lamda;self show('3')).place(x=180,y=125)
Button(width=11,height=4,text='4', relief='flat',bg='white',command=lamda;self show('4')).place(x=0,y=200)
Button(width=11,height=4,text='5', relief='flat',bg='white',command=lamda;self show('5')).place(x=90,y=200)
Button(width=11,height=4,text='6', relief='flat',bg='white',command=lamda;self show('6')).place(x=180,y=200)
Button(width=11,height=4,text=7', relief='flat',bg='white',command=lamda;self show('7')).place(x=0,y=275)
Button(width=11,height=4,text='8', relief='flat',bg='white',command=lamda;self show('8')).place(x=180,y=275)
Button(width=11,height=4,text='9', relief='flat',bg='white',command=lamda;self show('9')).place(x=90,y=275)
Button(width=11,height=4,text='0', relief='flat',bg='white',command=lamda;self show('0')).place(x=90,y=350)
Button(width=11,height=4,text='-', relief='flat',bg='white',command=lamda;self show('-')).place(x=180,y=350)
Button(width=11,height=4,text='+', relief='flat',bg='white',command=lamda;self show('+')).place(x=270,y=275)
Button(width=11,height=4,text='_', relief='flat',bg='white',command=lamda;self show('_')).place(x=270,y=200)
Button(width=11,height=4,text='/', relief='flat',bg='white',command=lamda;self show('/')).place(x=270,y=50)
Button(width=11,height=4,text='*', relief='flat',bg='white',command=lamda;self show('*')).place(x=270,y=125)
Button(width=11,height=4,text='=', relief='flat',bg='lightblue',command=self.solve..place(x=270,y=125)
Button(width=11,height=4,text='c', relief='flat', command.clear).place(x=0,y=0)
def show(self,value)
self.entry-vakue+=str(value)
self.equation.set(self.entry-value)
def clear(self):
Self.entry_value
self.equation.set(self.entry-value)
def solve(self):
result=eval(self.entry_value)
self.equation.set(result)
root =TK()
root.mainloop()
