#1 way too long words
'''
num = int(input('Enter:'))
arr=[]
for i in range(num):
    word = input('Enter:')
    arr.append(word)

for a in arr:
    if len(a)<=10:
        print(a)
    else:
        print(a[0]+str(len(a)-2)+a[-1])'''

#2 Next round
'''nums = input('enter:')
arr=[]
for i in range(int(nums.split()[0])):
    num = int(input('enter:'))
    arr.append(num)

def getNumberOfRounds(k, arr):
    count=0
    for i in range(len(arr)):
        if arr[i]>=arr[k-1] and arr[i]>0:
            count+=1
    return count

print(getNumberOfRounds(int(nums.split()[1]), arr))'''
#3 Domino piling
'''size = input('enter:')
print(int((int(size.split()[0])*int(size.split()[1])/2)))'''
#4 Bit++
'''
oper_num = int(input('enter'))
arr=[]
for i in range(oper_num):
    oper = input('enter operation:')
    arr.append(oper)

def giveAnswer(arr):
    num=0
    for j in range(len(arr)):
        if len(arr)==1 or j==len(arr)-1:
            if arr[j]=='X++' or arr[j]=='X--':
                pass
            elif arr[j]=='++X':
                num+=1
            elif arr[j]=="--X":
                num-=1
        else:
            if arr[j]=='X++' or arr[j]=='++X':
                num+=1
            elif arr[j]=='X--' or arr[j]=="--X":
                num-=1
    return num

print(giveAnswer(arr))'''
#5 Beautiful Matrix
'''arr=[]
for i in range(5):
    col = input('Enter column:')
    arr.append([int(i) for i in col.split()])
    # print(arr)

def findNumber(arr):
    num=0
    for j in range(1,len(arr)):
        for k in range(1,len(arr[j])):
            if arr[j][k]==1:
                if k==2 and j==2:
                   num=0
                else:
                    num=abs(k-2)+abs(j-2)
    return num
print(findNumber(arr))'''
#6 Petya and Strings
'''arr = []
for i in range(2):
    line = input('Enter: ')
    arr.append([i.lower() for i in line.split()])

def compareStrings(arr):
    result=0
    for i in range(len(arr[0])):
        if arr[0][i]==arr[1][i]:
            result=0
        elif arr[0][i]>arr[1][i]:
            result=1
        else:
            result=-1
    return result
print(compareStrings(arr))'''
#7 Helpful Math
'''
num = input('Enter: ')
arr=[int(i) for i in num.split('+')]
arr.sort()
line=''
for j in range(0,(len(arr)-1)):
    line += str(arr[j])+'+'

print(line + str(arr[len(arr)-1]))'''
#8 Word Capitilization
'''word = input('Enter:')
print(word[0].upper()+word[1:])'''

#9 Boy or Girl
'''name = input("Enter name:") 
s = set(name)
if (len(s)//2==1):
    print("IGNORE HIM!")
else:
    print("CHAT WITH HER!")'''

#10 Bear and Big Brother
'''limak = int(input('Enter:'))
bob = int(input('Enter:'))
def findYear(l,b):
    year=0
    while(l<=b):
        l*=3
        b*=2
        year+=1
    return year
print(findYear(limak, bob))'''
#11 Soldier and Bananas
'''first_banana = int(input('Enter first banana cost:'))
soldier_money = int(input("Enter soldier's money:"))
num_banana = int(input('Enter number of banana:'))
def borrowMoney(k,n,w):
    total=0
    for i in range(1,w+1):
        total+=i*k
    return (total-n)
print(borrowMoney(first_banana, soldier_money, num_banana))'''
#12 Elephant
'''coor = int(input('Enter:'))

def findSteps(coor):
    step=0
    
    for i in range(1,200000):
        if coor-i*5==1 or coor-i*5==2 or coor-i*5==3 or coor-i*5==4:
            step+=i+1
            return step

        elif coor-i*5==0 or coor-i*4==0 or coor-i*3==0 or coor-i*2==0:
            step=i
            return step

        elif coor-1==0:
            step=i
            return step
        
        else:
            i+=1

print(findSteps(coor))'''

#13 Stones on the Table
'''strings = input('Enter:')
def countColors(strs):
    num=0
    for i in range(len(strs)-1):
        if strs[i]==strs[i+1]:
            num+=1
        else:
            pass
    return num
print(countColors(strings))'''
#14 Word
'''word = input('Enter:')
def replaceLetters(word):
    upper_num=0
    for i in range(len(word)):
        if word[i].isupper():
            upper_num+=1
    low_num = len(word)-upper_num
    if low_num>=upper_num:
        return word.lower()
    else:
        return word.upper()
print(replaceLetters(word))'''
#15 Wrong Subtraction
'''n,k=[int(x) for x in input('Enter n and k :').split()]
def wrongSubtraction(n,k):
    for i in range(k):
        if n%10==0:
            n/=10
            
        else:
            n-=1
    return n
print(wrongSubtraction(n,k))'''
#16 Tram
'''stops = int(input('Enter:'))
arr=[]
for i in range(stops):
    people = [int(x) for x in input('Enter exiting and entering passengers:').split()]
    arr.append(people)
def calculateCapacity(arr):
    total=0
    cap_arr=[]
    for i in range(len(arr)):
        total=total-arr[i][0]+arr[i][1]
        cap_arr.append(total)
    cap_arr.sort(reverse=True)
    return cap_arr[0]
print(calculateCapacity(arr))'''
#17 Nearly Lucky Number
'''num = input('Enter:')
def findLuckyNumber(num):
    length = len(num)
    four_num = num.count('4')
    seven_num = num.count('7')
    if length-(four_num+seven_num)==0:
        return 'YES'
    else:
        return 'NO'
print(findLuckyNumber(num))'''

#18 Translation
'''word1,word2 = input().split()
def reverseWord(word1,word2):
    rev_word = ''
    for i in range(len(word1)):
        rev_word+=word1[len(word1)-1-i]
    if word2==rev_word:
        return 'YES'
    else:
        return 'NO'
print(reverseWord(word1,word2))'''
#19 Anton and Danik
'''line = input()
def countLine(l):
    a_num = l.count('A')
    d_num = l.count('D')
    if a_num>d_num:
        return 'Anton'
    elif a_num<d_num:
        return 'Danik'
    else:
        return 'Friendship'
print(countLine(line))'''
#20 Beautiful year
'''year=int(input())
def findDistincYear(y):
    for i in range(y+1,9000):
        a = i // 1000
        b = i//100%10
        c = i//10%10
        d = i % 10
        if (a != b and a != c and a != d and b != c and b != d and c != d):
            return i
print(findDistincYear(year))'''
#21 George and accommodation
'''num_room = int(input())
def findRoom(n_r):
    arr=[]
    for i in range(n_r):
        p = [int(x) for x in input().split()]
        arr.append(p)
    free =0
    for j in range(len(arr)):
        if arr[j][1]-arr[j][0]>=2:
            free+=1
    return free
print(findRoom(num_room))'''
#22 Vanya and Fence
'''friends,fence = [int(x) for x in input().split()]
def findMinimumWidth(f,fen):
    height_fri=[]
    for i in range(f):
        height_fri.append(int(input()))
    count=0
    for k in height_fri:
        if k-fen>0:
            count+=2
        else:
            count+=1
    return count
print(findMinimumWidth(friends,fence))'''
#23 In search of an easy problem
'''num = int(input())
def easyOrhard(num):
    dec=[]
    for i in range(num):
        dec.append(int(input()))
    if dec.__contains__(1):
        return 'HARD'
    else:
        return 'EASY'
print(easyOrhard(num))'''
#24 Magnets
'''num = int(input())
def findGroup(n):
    groups =[]
    for i in range(n):
        groups.append(int(input()))
    count=1
    l= len(groups)
    for j in range(l-2):
        if groups[j]!=groups[j+1]:
            count+=1
    return count
print(findGroup(num))'''
#25 Calculating function
'''num = int(input())
def calculatingFunc(num):
    total=0
    for i in range(1,num+1):
        if i%2==0:
            total+=i
        else:
            total-=i
    return total
print(calculatingFunc(num))'''
#26 Ultra-fast mathematician
'''n1 = input()
n2 = input()
def sumNumbers(n1,n2):
    sum=''
    for i in range(len(n1)):
        if n1[i]==n2[i]:
            sum+='0'
        else:
            sum+='1'
    return sum
print(sumNumbers(n1,n2))'''
#27 Drinks
'''num_juice = int(input())
def findVolume(n):
    volume=[]
    for i in range(n):
        volume.append(int(input()))
    total_volume=0
    for j in range(n):
        total_volume+=volume[j]/100
    return (total_volume/n)*100
print(findVolume(num_juice))'''
#28 Hulk
'''n = int(input())
def showFeel(n):
    if n%3==1:
        return 'I hate it'
    elif n%3==2:
        return 'I hate that I love it'
    elif n%3==0:
        return 'I hate that I love that I hate it'
print(showFeel(n))'''
#29 I wanna be guy
'''n = int(input())
p = [int(x) for x in input().split()]
q = [int(x) for x in input().split()]
def passOrNot(n,q,p):
    num = [x for x in range(1,n+1)]
    n1  = [num.remove(p1) for p1 in p if num.__contains__(p1) ]
    n2  = [num.remove(q1) for q1 in q if num.__contains__(q1) ]
    if num ==[]:
        return 'I become the guy'
    else:
        return 'Oh, my keyboard!'
print(passOrNot(n,q,p))'''
#30 Arrival of the General
'''n = int(input())
heights = []
heights
for i in range(n):
    heights.append(int(input()))
def correctArrival(h):
    l=min(h)
    b=max(h)
    l_ind=h.index(l)
    b_ind=h.index(b)
    if h.count(l)>1 :
        l_indexes=[]
        for i in range(len(h)):
            if h[i]==l:
                l_indexes.append(i)
        l_ind=max(l_indexes)
    if h.count(b)>1 :
        l_indexes=[]
        for i in range(len(h)):
            if h[i]==l:
                l_indexes.append(i)
        l_ind=min(l_indexes)
    if l_ind<b_ind:
        seconds=len(h)+b_ind-l_ind-2
    else:
        seconds=len(h)+b_ind-l_ind-1
    return seconds
print(correctArrival(heights))'''
#31 Divisibility Problem
'''n=int(input())
arr =[]
for i in range(n):
    arr.append([int(x) for x in input().split()])
def minMoves(a):
    total=[]
    for i in range(len(a)):
        for j in range(1000):
            if a[i][1]*j>a[i][0]:
                a1= a[i][1]*j
                a2 =a[i][0]
                total.append(a1-a2)
                
                break
    return total
    # return a1,a2
print(minMoves(arr))'''
#32 Anton and letters
'''letters = input().replace(',','').replace('{','').replace('}','')
letters = [x for x in letters.split()]
def countDistinct(l):
    uniq_letters=[]
    for i in l:
        if i not in uniq_letters:
            uniq_letters.append(i)
        
    return len(uniq_letters)
print(countDistinct(letters))'''
#33 Pangram
'''sentence = input()
def pangram(sentence):
    b=True
    for i in range(ord('a'),ord('z')+1):
        if sentence.find(chr(i))==-1:
            b=False
        else:
            b=True
    if b==False:
        return 'NO'
    else:
        return 'YES'
print(pangram(sentence))'''
#34 Games
'''n = int(input())
uniforms = []
for i in range(n):
    uniforms.append([int(x) for x in input().split()])
def findColors(uni):
    count=0
    for i in range(len(uni)):
        for j in range(i,len(uni)):
            if uni[i][0]==uni[j][1]:
                count+=1
    for i in range(len(uni)):
        for j in range(i,len(uni)):
            if uni[i][1]==uni[j][0]:
                count+=1
    return count
print(findColors(uniforms))'''

#35 AmusingJoke
'''word1=input()
word2=input()
word3=input()
def trueName(w1,w2,w3):
    wrd1,wrd2,wrd3=[],[],[]
    [wrd1.append(i) for i in w1]
    [wrd2.append(j) for j in w2]
    [wrd3.append(k) for k in w3]
    
    for x in wrd1:
        if x in wrd3:
            wrd3.remove(x)
            print(wrd3,'after wrd1')
            for k in wrd2:
                if k in wrd3:
                    wrd3.remove(k)
                    print(wrd2,'after wrd1')
                    if wrd3==[]:
                        return 'YES'
                    else:
                        return 'NO'
                else:
                    return 'NO'
        else:
            return 'NO'
    return wrd1,wrd2,wrd3
    
print(trueName(word1,word2,word3))'''
#36 Anton and Polyhedrons
'''n = int(input())
hedrons = []
for i in range(n):
    hedrons.append(input())
def countFaces(h):
    total=0
    if 'Tetrahedron' in h:
       total+= h.count('Tetrahedron')*4
    if 'Cube' in h:
       total+= h.count('Cube')*6
    if 'Octahedron' in h:
       total+= h.count('Octahedron')*8
    if 'Dodecahedron' in h:
       total+= h.count('Dodecahedron')*12
    if 'Icosahedron' in h:
       total+= h.count('Icosahedron')*20
    return total
print(countFaces(hedrons))'''
#37 Candies and two sisters
'''n=int(input())
tests = [7, 1, 2, 3, 2000000000, 763243547]
for i in range(n):
    tests.append(int(input()))
def findWays(t):
    answers=[]
    for i in t:
        if i==1 and i==2:
            answers.append(0)
            print(answers)
        elif i%2==0:
            answers.append(((i/2)-1))
            print(answers)
        else:
            answers.append((i//2))
    return answers
print(findWays(tests))'''
#38 Fox and snake
'''n,m=[int(x) for x in input().split()]
line=''
for i in range(n):
    if i%2==0:
        for j in range(m):
            line+='#'
        line+='\n'
    else:
        if i%4==1:
            for j in range(m):
                if j!=m-1:
                    line+='.'
                else:
                    line+='#'
            line+='\n'
        else:
            for j in range(m):
                if j!=0:
                    line+='.'
                else:
                    line+='#'
            line+='\n'
print(line)'''
#39 I_love_%username%
'''n = int(input())
points =[]
for i in range(n):
    points.append(int(input()))

def findAmazingPerf(p):
    count=0
    for i in range(1, len(p)):
        if p[i]<=p[i-1]/2 or p[i]>=p[i-1]/2+p[i-1] or p[i]>=p[i-1]+1000 :
            count+=1
    # for i in range(1, len(p)-1):
    #     if p[i]>=p[i-1]*2 or p[i]>=p[i+1]*2:
    #         count+=1
    return count
print(findAmazingPerf(points))'''

#40 New Year and Hurry
'''n, k = [int(x) for x in input().split()]
def numOfProb(n, k):
    count=0
    total=240-k
    for i in range(1, n+1):
        total-=i*5    
        if not total<0:
            print(i, total)
            count+=1
    return count
print(numOfProb(n, k))'''

#41 Vasya the Hipster
'''r, b = [int(x) for x in input().split()]
def call(r,b):
    pair=0
    same_pair=0
    if r>=b:
        pair=b
        if (r-b)==1:
            same_pair=0
        else:
            same_pair=int((r-b)/2)
    else:
        pair=r
        if (b-r)==1:
            same_pair=0
        else:
            same_pair=int((b-r)/2)
    return pair, same_pair
print(call(r,b))'''

#42 Remove smallest
'''n = int(input())
arr = []
for i in range(n):
    arr2 =[]
    n2 = int(input())
    for j in range(n2):
        arr2.append(int(input()))
    arr.append(arr2)
def removeSmall(a):
    f=0
    ans=[]
    for i in range(len(a)):
        a[i].sort()
        for j in range(1, len(a[i])):
            if a[i][j]-a[i][j-1]>1:
                f=1
                ans.append('NO')
            else:
                ans.append('YES')
        if len(a[i])==1:
            ans.append('YES')
    return ans
print(removeSmall(arr))'''
