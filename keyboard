from tkinter import *
import time
import datetime
import pygame

pygame.init()
root = Tk()
root.geometry('1352x700')
root.configure(background = 'white')
root.title("music keys")
ABC = Frame(root, background = 'red', bd = 20, relief = RIDGE)
ABC.grid()

ABC1 = Frame(ABC, background = 'red', bd = 20, relief = RIDGE)
ABC1.grid()
ABC2 = Frame(ABC, background = 'red', relief = RIDGE)
ABC2.grid()
ABC3 = Frame(ABC, background = 'red', relief = RIDGE)
ABC3.grid()

str1 = StringVar()
str1.set("Just like music")
Dete1 = StringVar()
Time1 = StringVar()

Dete1.set(time.strftime('%d/%m/%Y'))
Time1.set(time.strftime('%d:%m:%S'))
# Label with title
Label(ABC1, text = "Musical Keys", font = ('arial',25,'bold'),padx = 8, pady = 8, bd = 4, bg = "red", fg = 'orange', justify = CENTER).grid(row = 0, column = 0,columnspan = 11)
# time, name, date
txtDate = Entry(ABC1, textvariable = Dete1, font = ('arial',18,'bold'), bd = 34, bg = "red", fg = 'orange', width= 28, justify = CENTER).grid(row = 1, column = 0,pady = 1)
txtDisplay = Entry(ABC1, textvariable = str1, font = ('arial',18,'bold'), bd = 34, bg = "red", fg = 'orange', width= 28, justify = CENTER).grid(row = 1, column = 1,pady = 1)
txtTime = Entry(ABC1, textvariable = Time1, font = ('arial',18,'bold'), bd = 34, bg = "red", fg = 'orange', width= 28, justify = CENTER).grid(row = 1, column = 2,pady = 1)
# black keys
# key press
def value_Cs():
    str1.set('C#')
    sound = pygame.mixer.Sound('C_s.wav')
    sound.play()

def value_Ds():
    str1.set('D#')
    sound = pygame.mixer.Sound('D_s.wav')
    sound.play()

def value_Fs():
    str1.set('F#')
    sound = pygame.mixer.Sound('F_s.wav')
    sound.play()

def value_Gs():
    str1.set('G#')
    sound = pygame.mixer.Sound('G_s.wav')
    sound.play()

btnCs = Button(ABC2,  height = 6, width= 6, text = "C#", font = ('arial',18,'bold'),command = value_Cs,bd = 4, bg = "black",fg = "white")
btnCs.grid(row = 0, column = 2,padx = 5, pady = 5)
btnDs = Button(ABC2,  height = 6, width= 6, text = "D#", font = ('arial',18,'bold'),bd = 4, bg = "black",fg = "white",command = value_Ds)
btnDs.grid(row = 0, column = 3,padx = 5, pady = 5)
btnFs = Button(ABC2,  height = 6, width= 6, text = "F#", font = ('arial',18,'bold'),bd = 4, bg = "black",fg = "white",command = value_Fs)
btnFs.grid(row = 0, column = 4,padx = 5, pady = 5)
btnGs = Button(ABC2,  height = 6, width= 6, text = "G#", font = ('arial',18,'bold'),bd = 4, bg = "black",fg = "white",command = value_Gs)
btnGs.grid(row = 0, column = 5,padx = 5, pady = 5)

# key press
def value_Bb():
    str1.set('Bb')
    sound = pygame.mixer.Sound('Bb.wav')
    sound.play()

def value_Cs1():
    str1.set('C#1')
    sound = pygame.mixer.Sound('C_s1.wav')
    sound.play()

def value_Ds1():
    str1.set('D#1')
    sound = pygame.mixer.Sound('D_s1.wav')
    sound.play()

btnBb = Button(ABC2,  height = 6, width= 6, text = "Bb", font = ('arial',18,'bold'),bd = 4, bg = "black",fg = "white",command = value_Bb)
btnBb.grid(row = 0, column = 6,padx = 5, pady = 5)
btnCs1 = Button(ABC2,  height = 6, width= 6, text = "C#1", font = ('arial',18,'bold'),bd = 4, bg = "black",fg = "white",command = value_Cs1)
btnCs1.grid(row = 0, column = 7,padx = 5, pady = 5)
btnDs1 = Button(ABC2,  height = 6, width= 6, text = "D#1", font = ('arial',18,'bold'),bd = 4, bg = "black",fg = "white",command = value_Ds1)
btnDs1.grid(row = 0, column = 8,padx = 5, pady = 5)
# white keys
# key press
def value_C():
    str1.set('C')
    sound = pygame.mixer.Sound('C.wav')
    sound.play()

def value_D():
    str1.set('D')
    sound = pygame.mixer.Sound('D.wav')
    sound.play()

def value_E():
    str1.set('E')
    sound = pygame.mixer.Sound('E.wav')
    sound.play()

def value_F():
    str1.set('F')
    sound = pygame.mixer.Sound('F.wav')
    sound.play()

def value_G():
    str1.set('G')
    sound = pygame.mixer.Sound('G.wav')
    sound.play()

def value_A():
    str1.set('A')
    sound = pygame.mixer.Sound('A.wav')
    sound.play()

def value_B():
    str1.set('B')
    sound = pygame.mixer.Sound('B.wav')
    sound.play()

btnC = Button(ABC2,  height = 6, width= 6, text = "C", font = ('arial',18,'bold'),bd = 4, bg = "white",fg = "black",command = value_C)
btnC.grid(row = 1, column = 0,padx = 5, pady = 5)
btnD = Button(ABC2,  height = 6, width= 6, text = "D", font = ('arial',18,'bold'),bd = 4, bg = "white",fg = "black",command = value_D)
btnD.grid(row = 1, column = 1,padx = 5, pady = 5)
btnE = Button(ABC2,  height = 6, width= 6, text = "E", font = ('arial',18,'bold'),bd = 4, bg = "white",fg = "black",command = value_E)
btnE.grid(row = 1, column = 2,padx = 5, pady = 5)
btnF = Button(ABC2,  height = 6, width= 6, text = "F", font = ('arial',18,'bold'),bd = 4, bg = "white",fg = "black",command = value_F)
btnF.grid(row = 1, column = 3,padx = 5, pady = 5)
btnG = Button(ABC2,  height = 6, width= 6, text = "G", font = ('arial',18,'bold'),bd = 4, bg = "white",fg = "black",command = value_G)
btnG.grid(row = 1, column = 4,padx = 5, pady = 5)
btnA = Button(ABC2,  height = 6, width= 6, text = "A", font = ('arial',18,'bold'),bd = 4, bg = "white",fg = "black",command = value_A)
btnA.grid(row = 1, column = 5,padx = 5, pady = 5)
btnB = Button(ABC2,  height = 6, width= 6, text = "B", font = ('arial',18,'bold'),bd = 4, bg = "white",fg = "black",command = value_B)
btnB.grid(row = 1, column = 6,padx = 5, pady = 5)

# key press
def value_C1():
    str1.set('C1')
    sound = pygame.mixer.Sound('C1.wav')
    sound.play()

def value_D1():
    str1.set('D1')
    sound = pygame.mixer.Sound('D1.wav')
    sound.play()

def value_E1():
    str1.set('E1')
    sound = pygame.mixer.Sound('E1.wav')
    sound.play()

def value_F1():
    str1.set('F1')
    sound = pygame.mixer.Sound('F1.wav')
    sound.play()

btnC1 = Button(ABC2,  height = 6, width= 6, text = "C1", font = ('arial',18,'bold'),bd = 4, bg = "white",fg = "black",command = value_C1)
btnC1.grid(row = 1, column = 7,padx = 5, pady = 5)
btnD1 = Button(ABC2,  height = 6, width= 6, text = "D1", font = ('arial',18,'bold'),bd = 4, bg = "white",fg = "black",command = value_D1)
btnD1.grid(row = 1, column = 8,padx = 5, pady = 5)
btnE1 = Button(ABC2,  height = 6, width= 6, text = "E1", font = ('arial',18,'bold'),bd = 4, bg = "white",fg = "black",command = value_E1)
btnE1.grid(row = 1, column = 9,padx = 5, pady = 5)
btnF1 = Button(ABC2,  height = 6, width= 6, text = "F1", font = ('arial',18,'bold'),bd = 4, bg = "white",fg = "black",command = value_F1)
btnF1.grid(row = 1, column = 10,padx = 5, pady = 5)
root.mainloop()
